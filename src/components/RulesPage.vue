<template>
    <div class="rules-page">
      <h1 class="page-title">The Exception rules </h1>
      <p class="players">4 players : 1 detective and 3 brand representatives</p>
      
      <h2>EQUIPMENT</h2>
      <p>1 die</p>
      <p>7 packs of cards with the history of brands (to play seven rounds) </p>
      <p>1 question sheet for the detective</p>

      <p class="attention">attention :</p>

      <p>Sort the pack of cards by the color code into different packs of three cards before starting to play.</p>
      <h2 class="setup">SETUP</h2>
      <p>The players roll the die, the player with the highest score will become the detective.
         The other 3 players, the brand representatives, will all receive a card from the first pack. The
         detective gets no card.</p>
      <p>Two of the cards are identical; containing information on the same main brand.
         The third card marked with a red dot, has a different brand on it; this player becomes “the
         Exception” for this round.</p>
      <p>The detective has to find out what the main brand is and who the Exception is.</p>

      <h2 class="first">FIRST ROUND</h2>
      <p>The three brand representatives are dealt one card of the same theme marked by the same
      color code.</p>
      <p>The detective doesn’t get a card. The brand representatives have 40 seconds to read and
      memorize as much information concerning the brand as possible. After 40 seconds, the 3
      players turn over the card and the game begins.</p>
      <p>Players take turns saying one word related to their logo on the card. At the end of the round,
      the detective asks a question of his choice from the question sheet provided. After two
      rounds, the detective can either ask another question or decide to denounce the
      exception/impostor.</p>
      <p>If the detective is right, he must identify the Exception’s brand to win.
      If the detective is wrong, it is the turn of the Exception to identify the brand of the other two
      brand representatives to win. </p>
      <br>
      <p>And so on for 7 rounds</p>

      <i>Have fun!</i>
    </div>
  </template>
  
  <script>
  export default {
    name: 'RulesPage',
  }
  </script>
  
  <style scoped>

  span {
    color : red;
  }

  .loupe2 {
    width: 40px;
    height: 40px;
  }

  .group {
    width: 40px;
    height: 40px;
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
    font-size: 36px;
    margin-bottom: 20px;
    color: #54bec7;
    text-align: center;
    font-family: Roboto;
  }
  
  h2 {
    font-size: 24px;
    margin-top: 20px;
    color: #54bec7;
    font-family: Roboto;
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
  