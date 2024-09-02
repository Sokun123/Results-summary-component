<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
</head>
<style>
    body {
    background-color: #f2f2f2;
    font-family: sans-serif;
  }
  
  .container {
    width: 500px;
    margin: 50px auto;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    border-radius: 10px;
    padding: 30px;
  }
  
  .result {
    background-color: #673AB7;
    color: #fff;
    padding: 30px;
    border-radius: 10px;
    text-align: center;
  }
  
  .result h2 {
    font-size: 48px;
    margin-bottom: 10px;
  }
  
  .result p {
    font-size: 16px;
    margin-bottom: 20px;
  }
  
  .summary {
    margin-top: 30px;
    background-color: #fff;
    border-radius: 10px;
    padding: 30px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
    text-align: center;
    font-size: 18px;
    line-height: 1.5;
  }
  
  .summary .item {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px;
    border-bottom: 1px solid #eee;
    font-size: 16px;
    
  }
  
  .summary .item:last-child {
    border-bottom: none;
  }
  
  .summary .item i {
    font-size: 20px;
    color: #673AB7;
  }
  
  .summary .item .score {
    font-weight: bold;
  }
  
  .continue {
    background-color: #673AB7;
    color: #fff;
    padding: 15px 30px;
    border-radius: 5px;
    text-decoration: none;
    display: block;
    margin-top: 30px;
    text-align: center;
    transition: background-color 0.3s ease;
  }
  
  .continue:hover {
    background-color: #512DA8;
  }
  </style>
<body>

<div class="container">
  <div class="result">
    <h1>Your Result</h1>
    <h2>76</h2>
    <p>of 100</p>
    <h3>Great</h3>
    <p>You scored higher than 65% of the people who have taken these tests.</p>
  </div>

  <div class="summary">
    <h1>Summary</h1>
    <div class="item">
      <img src="https://raw.githubusercontent.com/AhmeedSalama/Resultssummarycomponent/9c0b16edf158452e4213f5f5e6d6546ebbbc32eb/images/icon-reaction.svg" alt="icon">
      <span>Reaction</span>
      <span class="score">80 / 100</span>
    </div>
    <div class="item">
      <img src="https://raw.githubusercontent.com/AhmeedSalama/Resultssummarycomponent/9c0b16edf158452e4213f5f5e6d6546ebbbc32eb/images/icon-memory.svg" alt="icon">
      <span>Memory</span>
      <span class="score">92 / 100</span>
    </div>
    <div class="item">
      <img src="https://raw.githubusercontent.com/AhmeedSalama/Resultssummarycomponent/9c0b16edf158452e4213f5f5e6d6546ebbbc32eb/images/icon-verbal.svg" alt="icon">
      <span>Verbal</span>
      <span class="score">61 / 100</span>
    </div>
    <div class="item">
      <img src="https://raw.githubusercontent.com/AhmeedSalama/Resultssummarycomponent/9c0b16edf158452e4213f5f5e6d6546ebbbc32eb/images/icon-visual.svg" alt="icon">
      <span>Visual</span>
      <span class="score">72 / 100</span>
    </div>
  </div>

  <a href="#" class="continue">Continue</a>
</div>

</body>
</html>
