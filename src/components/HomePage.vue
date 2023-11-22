<template>
    <div class="home-container">
      <div class="logo-animation">
      
        <img src="@/assets/logo_brand.png" alt="Brand Hunt Logo" />
      </div>
      <div class="welcome-message">
        <h1>Welcome to Brand Hunt !</h1>
        <p>Dive into the exciting world of brands and advertising with our interactive game.</p>
      </div>
    </div>
  </template>
  
  <script>


  export default {
    name: 'HomePage',
    
  };
  </script>
  
  <style scoped>
  .home-container {
    background-color: #e5d5be;
    color: black;
    text-align: center;
  }
  
  .logo-animation img {
   
    animation: spinAndGrow 2s ease-in-out forwards;
    width:35%
  }
  
  @keyframes spinAndGrow {
    from {
      transform: scale(0.1) rotate(0deg);
      opacity: 0.1;
    }
    to {
      transform: scale(1) rotate(360deg);
      opacity: 1;
    }
  }
  
  .welcome-message h1 {
    margin-top: 20px;
  }
  
  .welcome-message p {
    margin-bottom: 20px;
  }
  </style>
  