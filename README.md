
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hier klicken</title>

  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      font-family: Arial, sans-serif;
      background: white;
    }

    button {
      font-size: 40px;
      padding: 20px 40px;
      cursor: pointer;
    }
  </style>
</head>

<body>

  <button onclick="rickroll()">Hier klicken</button>

  <script>
    function rickroll() {
      window.location.href = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";
    }
  </script>

</body>
</html>
