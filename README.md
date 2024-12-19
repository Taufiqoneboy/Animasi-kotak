<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Animasi Kotak</title>
  <style>
    /* Animasi dengan CSS */
    @keyframes gerak {
      0% { transform: translateX(0); }
      50% { transform: translateX(200px); }
      100% { transform: translateX(0); }
    }

    .kotak {
      width: 50px;
      height: 50px;
      background-color: red;
      animation: gerak 2s infinite; /* Durasi animasi 2 detik, berulang */
    }

    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f0f0f0;
    }
  </style>
</head>
<body>
  <div class="kotak"></div>
</body>
</html>
