<template>
    <div class="rules-page">
      <h1 class="page-title">Game rules</h1>
      
      <h2>Game objective:</h2>
      <p>The main goal of "Brand Hunt" is to enrich players' knowledge about brands in a fun and interactive way. By participating in this game, players learn to recognize and remember various brands through a series of enjoyable challenges. These challenges stimulate creativity, memory, and team spirit, while providing an educational opportunity to better understand the world of brands and advertising. The game is designed for 4 to 8 players, playing in teams of two.</p>
  
      <h2>Necessary materials:</h2>
      <ul>
        <li>A game board with colored squares, some marked with stars.</li>
        <li>A dice.</li>
        <li>Tokens for each team.</li>
        <li>Challenge cards corresponding to each color on the board.</li>
        <li>"Challenge" cards.</li>
        <li>Pens.</li>
        <li>Paper.</li>
      </ul>
  
      <h2>Determining the starting team:</h2>
      <p>Before starting, each team rolls the dice once. The team with the lowest number starts the game.</p>
  
      <h2>Setup:</h2>
<p>
    Before beginning the game, ensure that each team follows these setup steps:
</p>

<ol>
    <li>
        <strong>Place Tokens:</strong> Each team selects a token to represent their team on the game board. Place all the tokens on the "Start" square of the game board.
    </li>
    <br/>
    <li>
        <strong>Sort Challenge Cards:</strong> The game includes challenge cards corresponding to different categories (e.g., Yellow for guessing, Blue for miming, Green for drawing, etc.). Sort these challenge cards into their respective categories to prepare for the game.
    </li>
    <br/>
    <li>
        <strong>Prepare "Challenge" Cards:</strong> Keep a stack of "Challenge" cards ready. These cards will be used when teams land on starred squares during the game. Shuffle the "Challenge" cards to ensure randomness and place them face down within easy reach of all players.
    </li>
</ol>

<p>
    With these setup steps completed, the teams are ready to start playing "Brand Hunt." Enjoy the game and have fun learning about brands and advertising!
</p>

  
      <h2>Game play:</h2>
      <ul>
        <li><strong>Roll the dice:</strong> Teams take turns rolling the dice and move their token the indicated number of squares.</li>
        <br/>
        <li><strong>Type of challenge:</strong> Depending on the color of the square the team lands on, they must take on a different type of challenge:</li>
        
        <ul>
            
          <li>Yellow: Guess a brand with a post-it note on the forehead.</li>
          <li>Blue: Mime a brand or product.</li>
          <li>Green: Draw a brand or product.</li>
          <li>Orange: Guess a brand from its slogan.</li>
          <li>Purple: Identify a brand from an advertisement image.</li>
          <li>Pink: Guess a brand from the description of its products.</li>
        </ul>
        <li><strong>Starred squares and 'challenge' cards:</strong></li>
        <ul>
          <li>If a team lands on a starred square, they must draw a 'Challenge' card in addition to their 'color' card.</li>
          <li>The challenge can involve any aspect of the game and must be completed immediately.</li>
        </ul>
        <li><strong>Rules for challenges:</strong></li>
        <ul>
          <li>Each challenge must be completed in less than 60 seconds.</li>
          <li>Each team takes turns, regardless of whether they win or lose.</li>
        </ul>
        

<li>
    <strong>Additional Rules:</strong>
</li>
<ul>
    <li>No Explicit Words or Gestures: Players are not allowed to use words or gestures that explicitly form part of the brand name or product during challenges.</li>
    <li>Voting Rule for Disagreements: In case of disagreement over the validity of an answer, other teams will vote to decide. If the rules are not respected, the team must move back one space on the board.</li>
    <li><strong>Specific Rules for Each Category:</strong>
        <ul>
            <li>Mime (Blue): No talking is allowed during miming.</li>
            <li>Drawing (Green): The use of numbers and letters in drawings is prohibited.</li>
            <li>Post-it (Yellow): The person guessing can only respond with "yes" or "no".</li>
            <li>Product Description (Pink): The team can only use 5 words to describe the product, and these words must not belong to the same word family as the brand name.</li>
        </ul>
    </li>
</ul>
    <li><strong>End of the game and winner:</strong></li>
    <p>When a team reaches the end of the board, they face a challenge to validate their victory. The challenge is to correctly answer one question from each category within 3 minutes and 30 seconds. If the team answers incorrectly, they may redraw as long as it's within the time limit. In order to win, the team must draw one card from each category and answer them correctly within the time limit. If they don't succeed, they will have to redraw one card from each category and try again during their next turn, following the same rules.
</p>


      </ul>
  
      <h2>Difficulty levels:</h2>
      <ul>
        <li><strong>Beginner level:</strong> Each challenge must be completed in less than 1 minute.</li>
        <li><strong>Intermediate level:</strong> Each challenge must be completed in less than 45 seconds.</li>
        <li><strong>Expert level:</strong> Each challenge must be completed in less than 30 seconds.</li>
      </ul>
      <p>These varying time constraints for different skill levels allow players to choose a difficulty setting that matches their comfort and experience, making the game accessible and challenging for everyone.</p>
    </div>
  </template>
  
  <script>
  export default {
    name: 'RulesPage',
  }
  </script>
  
  <style scoped>

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
  