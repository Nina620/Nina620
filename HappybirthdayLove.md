<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Happy Birthday</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      color: #333;
      text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.1);
    }

    .container {
      text-align: center;
      background: rgba(255, 255, 255, 0.8);
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
      max-width: 500px;
    }

    .card h1 {
      font-size: 2.5em;
      color: #ff6f61;
      margin-bottom: 15px;
    }

    .card p {
      font-size: 1.2em;
      margin: 10px 0;
    }

    .card .signature {
      margin-top: 20px;
      font-style: italic;
    }

    .button {
      background: #ff6f61;
      color: #fff;
      padding: 12px 25px;
      border: none;
      border-radius: 8px;
      font-size: 1em;
      cursor: pointer;
      transition: transform 0.2s ease, background-color 0.3s ease;
    }

    .button:hover {
      background: #ff3b2f;
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="card">
      <h1>🎉 Happy Birthday! 🎂</h1>
      <p>Dear Nugraha Pramukti Kusumah,</p>
      <p>Wishing you a day filled with love, joy, and happiness. May all your dreams come true!</p>
      <p class="signature">- From Ton amour</p>
      <button class="button" onclick="playMusic()">Play Birthday Song 🎶</button>
    </div>
  </div>

  <audio id="birthday-song" src="birthday-song.mp3"></audio>

  <script>
    function playMusic() {
      const song = document.getElementById('birthday-song');
      song.play();
    }
  </script>
</body>
</html>

<!---
Nina620/Nina620 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
