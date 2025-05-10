<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Selamat Ulang Tahun!</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(to right, #ff9a9e, #fad0c4);
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }

    h1 {
      font-size: 4em;
      color: #fff;
      animation: bounce 2s infinite;
      margin: 0;
    }

    p {
      font-size: 1.5em;
      color: #fff;
      max-width: 600px;
      text-align: center;
      margin-top: 20px;
      animation: fadeIn 4s ease-in-out;
    }

    .balloon {
      width: 50px;
      height: 70px;
      background-color: #ff4d6d;
      border-radius: 50% 50% 50% 50% / 60% 60% 40% 40%;
      position: absolute;
      bottom: -100px;
      animation: floatUp 6s ease-in-out infinite;
    }

    .balloon:nth-child(1) { left: 20%; animation-delay: 0s; }
    .balloon:nth-child(2) { left: 40%; animation-delay: 1s; background: #ffafcc; }
    .balloon:nth-child(3) { left: 60%; animation-delay: 2s; background: #cdb4db; }
    .balloon:nth-child(4) { left: 80%; animation-delay: 3s; background: #a2d2ff; }

    @keyframes floatUp {
      0% { transform: translateY(0); }
      100% { transform: translateY(-110vh); }
    }

    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>
</head>
<body>

  <div class="balloon"></div>
  <div class="balloon"></div>
  <div class="balloon"></div>
  <div class="balloon"></div>

  <h1>Happy Birthday!</h1>
  <p>
    Semoga hari ulang tahunmu dipenuhi dengan kebahagiaan, tawa, dan cinta.  
    Semoga setiap langkahmu ke depan membawa keberkahan dan kesuksesan yang luar biasa.  
    Selamat bertambah usia, tetap jadi pribadi yang menginspirasi!
  </p>

</body>
</html>
