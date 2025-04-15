# Culto-do-vazio
Estudos sobre o culto do Deus dos universos(ANALOG HORROR)
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>OBSERVADOR</title>
  <style>
    body {
      background-color: black;
      color: white;
      font-family: monospace;
      margin: 0;
      padding: 0;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
    }
    .blinking {
      animation: blink 1.2s infinite;
    }
    @keyframes blink {
      0%, 100% { opacity: 1; }
      50% { opacity: 0; }
    }
    .link {
      color: #ff0000;
      text-decoration: none;
      margin-top: 20px;
    }
    .hidden {
      display: none;
    }
    .reveal {
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <h1 class="blinking">SE VOCÊ PODE VER, ELE TAMBÉM PODE.</h1><a class="link" href="#" onclick="revealSections()">ACESSAR ESTUDO</a>

  <div class="hidden reveal" id="content">
    <h2>/origem</h2>
    <p>Antes da forma, havia o vazio. O Deus não nasceu. Ele foi lembrado. Duas realidades brotaram de sua mente partida.</p><h2>/eco</h2>
<p>Áudio corrompido disponível. Dica: analise com espectrograma.</p>
<p><i>*Arquivo: eco_v1.wav*</i></p>

<h2>/oculo</h2>
<p>Teste de observação disponível. Não pisque.</p>
<p><i>*[Iniciar experimento]*</i></p>

<p style="margin-top: 40px; font-size: 0.8em;">01001000 01100101 00100000 01101001 01110011 00100000 01110111 01100001 01110100 01100011 01101000 01101001 01101110 01100111</p>

  </div>  <script>
    function revealSections() {
      document.getElementById("content").classList.remove("hidden");
    }
  </script></body>
</html>
