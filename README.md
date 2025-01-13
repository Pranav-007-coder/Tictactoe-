# Tictactoe-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tic-Tac-Toe</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="game-container">
    <h1>Tic-Tac-Toe</h1>
    
    <!-- Game Mode Selection -->
    <div id="mode-selection">
      <button id="single-player">Single Player</button>
      <button id="two-player">Two Player</button>
    </div>

    <!-- Game Board -->
    <div id="board-container" style="display: none;">
      <div id="board" class="board">
        <button class="cell" id="cell-0"></button>
        <button class="cell" id="cell-1"></button>
        <button class="cell" id="cell-2"></button>
        <button class="cell" id="cell-3"></button>
        <button class="cell" id="cell-4"></button>
        <button class="cell" id="cell-5"></button>
        <button class="cell" id="cell-6"></button>
        <button class="cell" id="cell-7"></button>
        <button class="cell" id="cell-8"></button>
      </div>
      <button id="reset">Reset</button>
    </div>

    <!-- Congratulations Screen -->
    <div id="congratulations-screen" style="display: none;">
      <h2 id="winner-message"></h2>
      <button id="play-again">Play Again</button>
    </div>
  </div>

  <audio id="win-sound" src="win-sound.mp3"></audio>
  <script src="script.js"></script>
</body>
</html>