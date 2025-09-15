<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>For My Love 💜</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background-color: #2e004f;
      color: white;
      text-align: center;
      padding: 50px;
    }
    .btn {
      background-color: purple;
      color: white;
      border: none;
      padding: 15px 30px;
      margin: 15px;
      border-radius: 12px;
      font-size: 18px;
      cursor: pointer;
      transition: 0.3s;
    }
    .btn:hover {
      background-color: #b300ff;
      transform: scale(1.1);
    }
    .message {
      margin-top: 25px;
      font-size: 20px;
      display: none;
      animation: fadeIn 1s forwards;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .final {
      font-size: 26px;
      font-weight: bold;
      color: #ff69b4;
      display: none;
      animation: fadeIn 2s forwards;
    }
  </style>
</head>
<body>
  <h1>Hey Hope 💜</h1>
  <p>I made something special just for you 😘</p>

  <button class="btn" onclick="showMessage('msg1')">Click Me 1</button>
  <button class="btn" onclick="showMessage('msg2')">Click Me 2</button>
  <button class="btn" onclick="showMessage('msg3')">Click Me 3</button>
  <button class="btn" onclick="showFinal()">Final Surprise 💌</button>

  <div id="msg1" class="message">Your cute chubby cheeks make me melt 😍</div>
  <div id="msg2" class="message">That sweet smile is my sunshine ☀️</div>
  <div id="msg3" class="message">Your dangerous laughter is my favorite sound 😂💖</div>

  <div id="final" class="final">The Best Girlfriend Ever 💗</div>

  <script>
    function showMessage(id) {
      document.getElementById(id).style.display = "block";
    }
    function showFinal() {
      document.getElementById('final').style.display = "block";
    }
  </script>
</body>
</html>
