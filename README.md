# Be my life partner
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Will You Be My Life Partner?</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background: linear-gradient(to right, #fceabb, #f8b500);
      color: #333;
    }
    h1 {
      font-size: 2.5rem;
      margin-bottom: 30px;
    }
    button {
      font-size: 1.2rem;
      padding: 10px 20px;
      margin: 10px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s ease;
    }
    .yes {
      background-color: #ff4081;
      color: white;
    }
    .yes:hover {
      background-color: #e91e63;
    }
    .no {
      background-color: #ccc;
      color: #333;
    }
    .no:hover {
      background-color: #999;
    }
    .response {
      margin-top: 30px;
      font-size: 1.5rem;
    }
  </style>
</head>
<body>
  <h1>Will You Be My Life Partner? 💍</h1>
  <div>
    <button class="yes" onclick="reply('Yes ❤️')">Yes</button>
    <button class="no" onclick="reply('No 💔')">No</button>
  </div>
  <div class="response" id="response"></div>

  <script>
    function reply(answer) {
      document.getElementById('response').innerText = `You answered: ${answer}`;
    }
  </script>
</body>
</html>


/life-partner-proposal/
