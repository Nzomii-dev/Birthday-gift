<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Happy Birthday!</title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Quicksand&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Quicksand', sans-serif;
      background: linear-gradient(135deg, #ffe0ec, #f7f0ff);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      text-align: center;
    }
    h1 {
      font-family: 'Pacifico', cursive;
      color: #ff66a6;
      font-size: 3em;
      margin-bottom: 0.3em;
    }
    p {
      font-size: 1.2em;
      max-width: 600px;
      margin: 0 auto 2em;
      color: #5c5c5c;
    }
    .photo {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      object-fit: cover;
      border: 5px solid #ffb3d9;
      margin-bottom: 1.5em;
    }
    .footer {
      margin-top: 2em;
      font-size: 0.9em;
      color: #999;
    }
    .heart {
      color: #ff66a6;
      animation: pulse 1.2s infinite;
    }
    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }
  </style>
</head>
<body>
  <h1>Happy Birthday, Haruto! <span class="heart">❤</span></h1>
  <img src="https://i.imgur.com/3ZQ3Z7L.jpg" alt="Cute Couple" class="photo">
  <p>
    On this special day, I just want to remind you how loved and appreciated you are.
    Your smile, your kindness, and your quiet strength light up my world every single day.
    I hope your birthday is filled with as much joy as you've given me—because you deserve all of it and more.
    Here's to more memories, more laughter, and more love.
    Happy birthday, my favorite person! 💕
  </p>
  <div class="footer">
    Made with love by Nozomi 💌
  </div>
  <audio autoplay loop>
    <source src="https://www.bensound.com/bensound-music/bensound-love.mp3" type="audio/mp3">
    Your browser does not support the audio element.
  </audio>
</body>
</html>
