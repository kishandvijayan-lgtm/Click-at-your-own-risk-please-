<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Be My Valentine 💖</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #ff9a9e, #fad0c4);
      font-family: 'Arial', sans-serif;
    }

    .card {
      background: white;
      padding: 40px;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 10px 25px rgba(0,0,0,0.2);
    }

    h1 {
      color: #e63946;
      margin-bottom: 30px;
    }

    button {
      font-size: 18px;
      padding: 12px 30px;
      margin: 10px;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      background-color: #e63946;
      color: white;
      transition: transform 0.2s, background-color 0.2s;
    }

    button:hover {
      background-color: #d62828;
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Mary, will you be my Valentine? 💘</h1>
    <button onclick="yesClicked()">Yes</button>
    <button onclick="yesClicked()">Yes</button>
  </div>

  <script>
    function yesClicked() {
      alert("YAY 💖 I knew you'd say yes!");
    }
  </script>
</body>
</html>
