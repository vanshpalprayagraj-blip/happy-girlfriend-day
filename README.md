# happy-girlfriend-day
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Girlfriend Day Manya</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #ffdce0;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .card {
      width: 90%;
      max-width: 400px;
      height: 500px;
      background: #fff0f5;
      border-radius: 20px;
      box-shadow: 0 0 20px pink;
      text-align: center;
      overflow: hidden;
      transition: transform 0.6s;
    }
    .front, .inside {
      padding: 20px;
    }
    .front {
      cursor: pointer;
    }
    .inside {
      display: none;
    }
    #cake {
      font-size: 50px;
      margin: 20px 0;
    }
    #celebration {
      display: none;
      font-size: 30px;
      animation: pop 1s infinite;
    }
    @keyframes pop {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
    button {
      background: hotpink;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 12px;
      font-size: 16px;
      margin-top: 15px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="front">
      <h1>💌 Happy Girlfriend Day, Manya!</h1>
      <p>Tap to open your surprise card 💖</p>
    </div>
    <div class="inside">
      <p>I love you and I loved you by my soul.</p>
      <p>I love you, Manya... not just with my heart, but with every part of my soul.<br>
      You've filled my life with laughter, light, and love I never knew was possible.<br>
      Happy Girlfriend Day, my love.<br>
      <i>This little surprise is just a glimpse of what your smile means to me.</i><br><br>
      — Yours, Vansh 💘</p>
      <button onclick="blowCandle()">🎂 Blow the Cake</button>
      <div id="cake">🎂🕯️</div>
      <div id="celebration">🎉💖🎉</div>
    </div>
  </div>

  <!-- Background Music -->
  <audio id="bg-music" autoplay loop>
    <source src="https://cdn.pixabay.com/audio/2022/10/26/audio_4568cc6d72.mp3" type="audio/mpeg">
  </audio>

  <!-- Blue – Young Kai (or similar) -->
  <audio id="kai-music">
    <source src="https://cdn.pixabay.com/audio/2022/03/15/audio_d5fd3dbf04.mp3" type="audio/mpeg">
  </audio>

  <script>
    document.querySelector(".front").addEventListener("click", function() {
      document.querySelector(".front").style.display = "none";
      document.querySelector(".inside").style.display = "block";
    });

    function blowCandle() {
      document.getElementById("cake").innerText = "🎂";
      document.getElementById("celebration").style.display = "block";
      document.getElementById("kai-music").play();
    }
  </script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Girlfriend Day Manya</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #ffdce0;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .card {
      width: 90%;
      max-width: 400px;
      height: 500px;
      background: #fff0f5;
      border-radius: 20px;
      box-shadow: 0 0 20px pink;
      text-align: center;
      overflow: hidden;
      transition: transform 0.6s;
    }
    .front, .inside {
      padding: 20px;
    }
    .front {
      cursor: pointer;
    }
    .inside {
      display: none;
    }
    #cake {
      font-size: 50px;
      margin: 20px 0;
    }
    #celebration {
      display: none;
      font-size: 30px;
      animation: pop 1s infinite;
    }
    @keyframes pop {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
    button {
      background: hotpink;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 12px;
      font-size: 16px;
      margin-top: 15px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="front">
      <h1>💌 Happy Girlfriend Day, Manya!</h1>
      <p>Tap to open your surprise card 💖</p>
    </div>
    <div class="inside">
      <p>I love you and I loved you by my soul.</p>
      <p>I love you, Manya... not just with my heart, but with every part of my soul.<br>
      You've filled my life with laughter, light, and love I never knew was possible.<br>
      Happy Girlfriend Day, my love.<br>
      <i>This little surprise is just a glimpse of what your smile means to me.</i><br><br>
      — Yours, Vansh 💘</p>
      <button onclick="blowCandle()">🎂 Blow the Cake</button>
      <div id="cake">🎂🕯️</div>
      <div id="celebration">🎉💖🎉</div>
    </div>
  </div>

  <!-- Background Music -->
  <audio id="bg-music" autoplay loop>
    <source src="https://cdn.pixabay.com/audio/2022/10/26/audio_4568cc6d72.mp3" type="audio/mpeg">
  </audio>

  <!-- Blue – Young Kai (or similar) -->
  <audio id="kai-music">
    <source src="https://cdn.pixabay.com/audio/2022/03/15/audio_d5fd3dbf04.mp3" type="audio/mpeg">
  </audio>

  <script>
    document.querySelector(".front").addEventListener("click", function() {
      document.querySelector(".front").style.display = "none";
      document.querySelector(".inside").style.display = "block";
    });

    function blowCandle() {
      document.getElementById("cake").innerText = "🎂";
      document.getElementById("celebration").style.display = "block";
      document.getElementById("kai-music").play();
    }
  </script>
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Happy Girlfriend Day Manya</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #ffdce0;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .card {
      width: 90%;
      max-width: 400px;
      height: 500px;
      background: #fff0f5;
      border-radius: 20px;
      box-shadow: 0 0 20px pink;
      text-align: center;
      overflow: hidden;
      transition: transform 0.6s;
    }
    .front, .inside {
      padding: 20px;
    }
    .front {
      cursor: pointer;
    }
    .inside {
      display: none;
    }
    #cake {
      font-size: 50px;
      margin: 20px 0;
    }
    #celebration {
      display: none;
      font-size: 30px;
      animation: pop 1s infinite;
    }
    @keyframes pop {
      0%, 100% { transform: scale(1); }
      50% { transform: scale(1.2); }
    }
    button {
      background: hotpink;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 12px;
      font-size: 16px;
      margin-top: 15px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="front">
      <h1>💌 Happy Girlfriend Day, Manya!</h1>
      <p>Tap to open your surprise card 💖</p>
    </div>
    <div class="inside">
      <p>I love you and I loved you by my soul.</p>
      <p>I love you, Manya... not just with my heart, but with every part of my soul.<br>
      You've filled my life with laughter, light, and love I never knew was possible.<br>
      Happy Girlfriend Day, my love.<br>
      <i>This little surprise is just a glimpse of what your smile means to me.</i><br><br>
      — Yours, Vansh 💘</p>
      <button onclick="blowCandle()">🎂 Blow the Cake</button>
      <div id="cake">🎂🕯️</div>
      <div id="celebration">🎉💖🎉</div>
    </div>
  </div>

  <!-- Background Music -->
  <audio id="bg-music" autoplay loop>
    <source src="https://cdn.pixabay.com/audio/2022/10/26/audio_4568cc6d72.mp3" type="audio/mpeg">
  </audio>

  <!-- Blue – Young Kai (or similar) -->
  <audio id="kai-music">
    <source src="https://cdn.pixabay.com/audio/2022/03/15/audio_d5fd3dbf04.mp3" type="audio/mpeg">
  </audio>

  <script>
    document.querySelector(".front").addEventListener("click", function() {
      document.querySelector(".front").style.display = "none";
      document.querySelector(".inside").style.display = "block";
    });

    function blowCandle() {
      document.getElementById("cake").innerText = "🎂";
      document.getElementById("celebration").style.display = "block";
      document.getElementById("kai-music").play();
    }
  </script>
</body>
</html>
