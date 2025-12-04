<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Puma Web</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #a3d5ff, #cce7ff, #e6f3ff);
      min-height: 100vh;
      padding: 20px;
    }

    h1 {
      font-family: "Comic Sans MS", cursive, sans-serif;
      font-size: 3rem;
      text-align: center;
      color: #003366;
      margin-bottom: 30px;
      text-shadow: 2px 2px #ffffff80;
    }

    .game-list {
      max-width: 800px;
      margin: auto;
    }

    .game-item {
      display: flex;
      align-items: center;
      background: #ffffffcc;
      padding: 15px;
      margin-bottom: 15px;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }

    .game-item img {
      width: 80px;
      height: 80px;
      border-radius: 10px;
      margin-right: 15px;
      object-fit: cover;
      background: #ddd;
    }

    .game-info h2 {
      margin: 0;
      font-size: 1.4rem;
      color: #003366;
    }

    .game-info p {
      margin: 3px 0 0;
      color: #003366;
    }
  </style>
</head>
<body>

  <h1>THE PUMA WEB</h1>

  <div class="game-list">

    <div class="game-item">
      <img src="https://via.placeholder.com/80" alt="Gioco 1">
      <div class="game-info">
        <h2>Click the Box</h2>
        <p>Clicca il quadrato e fai più punti possibile!</p>
      </div>
    </div>

    <div class="game-item">
      <img src="https://via.placeholder.com/80" alt="Gioco 2">
      <div class="game-info">
        <h2>Gioco 2</h2>
        <p>Descrizione del gioco numero 2.</p>
      </div>
    </div>

    <div class="game-item">
      <img src="https://via.placeholder.com/80" alt="Gioco 3">
      <div class="game-info">
        <h2>Gioco 3</h2>
        <p>Descrizione del gioco numero 3.</p>
      </div>
    </div>

  </div>

</body>
</html>
