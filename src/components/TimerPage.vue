<template>
    <div class="timer-page">
      <div class="timer-container">
        <div class="timer">
          <div class="timer-display">
            <p class="timer-text">{{ formatTime }}</p>
          </div>
        </div>
      </div>
      <div class="button-container">
  <button @click="startTimer" class="start-button" :disabled="timerRunning">{{ timerRunning ? 'In progress...' : 'Start' }}</button>
  <button @click="stopTimer" class="stop-button" :disabled="!timerRunning">Stop</button>
  <button @click="resetTimer" class="reset-button" :disabled="timerRunning">Reset</button>
</div>
      <div class="duration-options">
        <label class="duration_title" for="duration">Choose the duration (in seconds) :</label>
        <input type="number" id="duration" v-model="totalTime" :disabled="timerRunning" />
      </div>
    </div>
  </template>
  
  
  <script>
  export default {
    name: 'TimerPage',
    data() {
      return {
        totalTime: 40,
        timerInterval: null,
        timerRunning: false,
      };
    },
    computed: {
      formatTime() {
        const minutes = Math.floor(this.totalTime / 80);
        const seconds = this.totalTime % 80;
        return `${minutes.toString().padStart(2, '0')}:${seconds.toString().padStart(2, '0')}`;
      },
    },
    methods: {
      startTimer() {
        if (!this.timerRunning) {
          this.timerInterval = setInterval(() => {
            if (this.totalTime > 0) {
              this.totalTime--;
            } else {
              clearInterval(this.timerInterval);
              
            }
          }, 1000);
          this.timerRunning = true;
        }
      },
      stopTimer() {
        clearInterval(this.timerInterval);
        this.timerRunning = false;
      },
      resetTimer() {
        clearInterval(this.timerInterval);
        this.timerRunning = false;
        this.totalTime = 80; 
      },
    },
  };
  </script>
  
  
  <style scoped>
  .timer-page {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    min-height: 100vh;
    background-color: transparent;
    color: white;
  }
  
  .timer-container {
    width: 200px;
    height: 200px;
    border-radius: 50%;
    background-color: transparent;
    border: 5px solid white;
    display: flex;
    justify-content: center;
    align-items: center;
    box-shadow: 0 0 20px rgba(255, 255, 255, 0.3);
  }
  
  .timer {
    width: 100%;
    height: 100%;
    border-radius: 50%;
    background-color: transparent;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .timer-display {
    font-size: 32px;
    font-weight: bold;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
  }
  
  .timer-text {
    margin: 0;
  }
  
  .start-button,
  .stop-button,
  .reset-button {
    margin-top: 20px;
    padding: 10px 20px;
    font-size: 16px;
    border-radius: 5px;
    cursor: pointer;
    transition: background-color 0.3s ease;
    display: flex;
    flex-direction: row;
  }
  
  .start-button {
    background-color: #007bff;
    color: white;
    border: none;
  }
  
  .start-button:disabled {
    background-color: #ccc;
    cursor: not-allowed;
  }
  
  .start-button:hover {
    background-color: #ffffff;
    color: rgb(0, 0, 0);
  }
  
  .stop-button {
    background-color: #ff3333;
    color: white;
    border: none;
  }
  
  .stop-button:disabled {
    background-color: #ccc;
    cursor: not-allowed;
  }
  
  .stop-button:hover {
    background-color: #ff6666;
    color: white;
  }
  
  .reset-button {
    background-color: #33cc33;
    color: white;
    border: none;
  }
  
  .reset-button:disabled {
    background-color: #ccc;
    cursor: not-allowed;
  }
  
  .reset-button:hover {
    background-color: #66ff66;
    color: white;
  }
  
  .duration-options {
    margin-top: 20px;
    align-content: center;
    display: flex;
    flex-direction: row;
    align-items: center;
  }
  
  .duration_title{
    display: flex;
    align-content: center;
    color: black;
  }
  label {
    font-size: 16px;
    margin-bottom: 5px;
  }
  
  input {
    padding: 5px;
    font-size: 16px;
    text-align: center;
    width: 80px;
  }
  .button-container {
  display: flex;
  gap:20px;
 
}
  </style>
  