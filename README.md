<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Animation</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #000;
    }
    .circle {
      width: 50px;
      height: 50px;
      background-color: #00f;
      border-radius: 50%;
      animation: bounce 2s infinite ease-in-out;
    }
    @keyframes bounce {
      0%, 100% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-100px);
      }
    }
  </style>
</head>
<body>
  <div class="circle"></div>
</body>
</html>
