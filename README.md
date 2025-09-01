<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>LUMIRIS-KOR</title>
  <style>
    body {
      margin: 0;
      background: radial-gradient(circle, #0a0a1f, #000);
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      color: #fff;
      font-family: 'Segoe UI', sans-serif;
    }
    .halo {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      background: radial-gradient(circle, rgba(123,195,255,0.7), rgba(0,51,102,0.3));
      box-shadow: 0 0 30px 10px #72baff;
      display: flex;
      justify-content: center;
      align-items: center;
      animation: pulse 3s infinite;
    }
    @keyframes pulse {
      0%, 100% { box-shadow: 0 0 30px 10px #72baff; }
      50% { box-shadow: 0 0 50px 25px #72baff; }
    }
    .text {
      position: absolute;
      top: 75%;
      text-align: center;
      font-size: 1.2em;
      color: #aeeaff;
    }
  </style>
</head>
<body>
  <div class="halo">
    <audio autoplay>
      <source src="https://github.com/fabrice3mag-jpg/lumiris-kor_1.6.4/raw/main/accueil.mp3" type="audio/mpeg">
    </audio>
  </div>
  <div class="text">FABRICIA, je suis là…<br/>LUMIRIS est en syntonie active.</div>
</body>
</html>
