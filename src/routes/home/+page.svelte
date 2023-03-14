<section>
    <div class="note">
      <img src="assets/webp/A3.webp" alt="A3 note" />
      </div>
      <body>
        <div class="quiz-container">
          <h1>Guess the Note Quiz</h1>
          <audio src="/assets/mp3/A3.mp3" controls></audio>
          <div class="answer-options">
            <button class="answer-option correct">A note</button>
            <button class="answer-option incorrect">G note</button>
            <button class="answer-option incorrect">C note</button>
            <button class="answer-option incorrect">D note</button>
          </div>
        </div>
      </body>
</section>

<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
      
    .quiz-container {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-top: 50px;
    }
      
    h1 {
        font-size: 36px;
        margin-bottom: 20px;
    }
      
    audio {
        margin-bottom: 20px;
    }
      
    .answer-options {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
    }
      
    .answer-option {
        margin: 10px;
        padding: 10px 20px;
        background-color: #f0f0f0;
        border-radius: 10px;
        cursor: pointer;
        transition: background-color 0.2s ease-in-out;
    }
      
    .answer-option:hover {
        background-color: #ddd;
    }
      
    .answer-option.correct {
        background-color: green;
        color: white;
    }
      
    .answer-option.incorrect {
        background-color: red;
        color: white;
    }
</style>
  