<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Matematik Oyunu</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div id="game-container">
    <h1>Matematik Oyunu</h1>
    <div id="question-box">
      <p id="question">Hazır mısınız? Başlamak için tıklayın!</p>
    </div>
    <input type="number" id="answer" placeholder="Cevabınızı yazın">
    <button id="submit-answer">Cevabı Gönder</button>
    <p id="feedback"></p>
    <p>Puanınız: <span id="score">0</span></p>
    <button id="start-game">Oyunu Başlat</button>
  </div>
  <script src="script.js"></script>
</body>
</html>
