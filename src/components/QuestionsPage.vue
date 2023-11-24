    <template>
    <div class="questions-page">
      <img class="pas" src="../assets/pas.png">
      <h1 class="page-title"><img class ="detectiv-left" src="../assets/detectiv_title.png">Questions <span>for</span> detective<img class="detectiv-right" src="../assets/detectiv_title_droite.png"></h1>
        <ul>
          <li>What country does this brand come from? </li>
          <li>Give me just one color of the logo</li>
          <li>What year was it created?</li>
          <li>What is this brand's speciality? </li>
          <li>Who is the creator? </li>
          <li>What's the brief history of the logo? </li>
          <li>Do the colors in the logo mean anything?</li>
          <li>Is there a particular meaning behind the logo's elements? </li>
          <li>Who is the target audience fot the logo and brand? </li>
          <li>Have there been any specific events or <img class="loupe" src="../assets/loupe.png">campaigns linked to the logo? </li>
          <li>Are there any variations in the way the logo is used? </li>
          <li>Are elements of the logo featured prominently in advertising for specific products? </li>
        </ul>
      </div>
  </template>
  <script>
    export default {
    name: 'QuestionsPage',
  }
  </script>

 <style scoped>

  .detectiv-left {
    margin-right : 5px;
  }

  .detectiv-right {
    margin-left : 5px;
  }
  .pas {
    width: 60px;
    height: 200px;
    float: right;
    margin-right: 60px;
    rotate: 30deg;
  }
 .loupe {
  width: 60px;
  height: 60px;
  margin-top: 15px;
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
    margin-left: 10px;
    margin-bottom: 20px;
    margin-right: 100px;
    color: black;
  }
  
  li {
    font-size: 25px;
    font-weight: bold;
  }
  
  @media screen and (max-width: 480px) {
      
      
      .pas {
        margin-left : 50px;
      }

      h1 span {
        display: flex;
        align-content: center;
        justify-content: center;
        margin-top: 5px;
      }

      h1 {
        text-align: center;
        margin-left: 15px;
        margin-top: 15px;
      }

      .detectiv-right {
        margin-left: 60px;
      }

      li {
        width: 300px;
      }
    }
  </style>
  
