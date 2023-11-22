<template>
    <div class="questions-page">
      <h1 class="page-title">Questions for detective</h1>
      <img class="pas" src="../assets/pas.png">
        <ul>
          <li>What Country does this brand come from ? </li>
          <li>Give me just one color of the logo ?</li>
          <li>What year was it created ?</li>
          <li>Who is the creator ? </li>
          <li>What's the brief history of the logo ? </li>
          <li>Do the colors in the logo mean anything ?</li>
          <li>Is there a particular meaning behind the logo's elements ? </li>
          <li>Who is the target audience fot the logo and brand ? </li>
          <li>Have there been any specific events or campaigns <img class="loupe" src="../assets/loupe.png"> linked to the logo ? </li>
          <li>Are there any variations in the way the logo is used ? </li>
          <li>Are elements of the logo featured prominently in advertising for specific products ? </li>
          <li>Has the logo been used in collaborations or partnerships with other brands or organizations ?</li>
        </ul>
      </div>
  </template>

  <script>
    export default {
    name: 'QuestionsPage',
  }
  </script>

 <style scoped>*
  .pas {
    width: 60px;
    height: 300px;
    float: right;
  }
 .loupe {
  width: 30px;
  height: 30px;
 }
  .questions-page {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    background-color: white;
    border: 2px solid white; 
    border-radius: 10px;
    text-align: justify;
    color: black;
  }
  
  .page-title {
    font-size: 40px;
    margin-bottom: 20px;
    color: #54bec7;
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
    margin-right: 100px;
    color: black;
  }
  
  li {
    font-size: 25px;
    font-weight: bold;
  }
  
  </style>
  
