<template>
    <div class="rules-page">
      <h1 class="page-title">Rules of the game</h1>
      <p class="players">4 players or more</p>
      
    <ul>
      <li>1 detective <img class="loupe2" src="../assets/loupe.png"></li>
      <li>3 players <img class="group" src="../assets/groupe.png"></li>
      <p class="cards">2 with the same cards and 1 exception with a different cards.</p>
      <p class="red-group"><span>The aim</span></p>
      </ul>
    </div>
  </template>
  
  <script>
  export default {
    name: 'RulesPage',
  }
  </script>
  
  <style scoped>

  .loupe2 {
    width: 40px;
    height: 40px;
  }

  .group {
    width: 40px;
    height: 40px;
  }

  .players {
    background-color: #54bec7;
    border-radius : 5px;
    width: 130px;
  }

  .rules-page {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: white;
    border: 2px solid white; 
    border-radius: 10px;
    text-align: left;
    color: black;
  }
  
  .page-title {
    font-size: 28px;
    margin-bottom: 20px;
    color: black;
    text-align: center;
  }
  
  h2 {
    font-size: 24px;
    margin-top: 20px;
    color: black;
  }
  
  p {
    font-size: 16px;
    margin-bottom: 20px;
    line-height: 1.5;
    color: black;
  }
  
  ul {
    list-style-type: disc;
    margin-left: 20px;
    margin-bottom: 20px;
    color: black;
  }
  
  li {
    font-size: 16px;
  }
  
  </style>
  