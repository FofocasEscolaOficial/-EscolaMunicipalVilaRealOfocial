<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Fofocas da 🏫 Vila Real</title>
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Open+Sans&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Open Sans', sans-serif;
      background: linear-gradient(135deg, #ffffff, #e6f2ff);
      color: #5a3e36;
      background-attachment: fixed;
    }

    .top-link {
      padding: 10px 20px;
      text-align: left;
      font-size: 20px;
    }

    .top-link a {
      color: #007bff;
      text-decoration: none;
      font-weight: bold;
    }

    .logo-area {
      background-color: #c6e6f7;
      text-align: center;
      padding: 20px;
      margin: 0 auto 20px;
      max-width: 300px;
      border-radius: 8px;
    }

    .logo-area img {
      width: 60px;
      display: block;
      margin: 0 auto 10px;
    }

    .logo-area span {
      font-family: 'Pacifico', cursive;
      font-size: 24px;
      display: block;
      color: #333;
    }

    .titulo-secundario {
      font-family: 'Pacifico', cursive;
      font-size: 28px;
      color: #444;
      text-align: center;
      margin-bottom: 40px;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
      padding: 0 20px;
    }

    .fofoca {
      background-color: #fff;
      border-left: 8px solid #add8e6;
      border-radius: 20px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      padding: 20px 30px;
      margin-bottom: 25px;
      font-size: 22px;
      line-height: 1.6;
      position: relative;
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      opacity: 0;
      transform: translateY(20px);
      animation: fadeIn 0.6s forwards;
    }

    .fofoca:hover {
      transform: translateY(-4px);
      box-shadow: 0 8px 16px rgba(0,0,0,0.15);
    }

    .fofoca::before {
      content: "💬";
      position: absolute;
      left: 10px;
      top: 10px;
      font-size: 28px;
    }

    footer {
      background-color: #add8e6;
      text-align: center;
      padding: 20px;
      font-size: 16px;
      color: #333;
      margin-top: 50px;
      border-top: 4px solid #87cefa;
      font-family: 'Pacifico', cursive;
    }

    @keyframes fadeIn {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .fofoca:nth-child(2) { animation-delay: 0.1s; }
    .fofoca:nth-child(3) { animation-delay: 0.2s; }
    .fofoca:nth-child(4) { animation-delay: 0.3s; }
    .fofoca:nth-child(5) { animation-delay: 0.4s; }
    .fofoca:nth-child(6) { animation-delay: 0.5s; }

    @media screen and (max-width: 600px) {
      .logo-area span {
        font-size: 20px;
      }

      .fofoca {
        font-size: 18px;
        padding: 15px 20px;
      }

      .fofoca::before {
        font-size: 24px;
      }
    }
  </style>
</head>
<body>
  <div class="top-link">
    <a href="#">EscolaMunicipalVilaRealOfocial</a>
  </div>

  <div class="logo-area">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQr7HIc6Evp3_fDSpXyOvreqMOSlKbN1esnpA&s" alt="Logo da escola">
    <span>Fofocas da 🏫 Vila Real</span>
  </div>

  <div class="container">
    <div class="titulo-secundario">As fofocas mais quentes do recreio:</div>
    <div class="fofoca">O site está em Construção 🚧</div>
    <div class="fofoca">O site está em Construção 🚧</div>
    <div class="fofoca">O site está em Construção 🚧</div>
    <div class="fofoca">O site está em Construção 🚧</div>
    <div class="fofoca">O site está em Construção 🚧</div>
  </div>

  <footer>
    © Criado pela turma do 5ºB.
  </footer>
</body>
</html>
