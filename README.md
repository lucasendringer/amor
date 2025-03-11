<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Nossa História</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #e6dbb3; /* Bege mais escuro para fundo */
      margin: 0;
      padding: 0;
      color: #333;
      display: flex;
      justify-content: center;
      align-items: flex-start;
      min-height: 100vh;
      text-align: center;
    }

    .container {
      width: 90%;
      max-width: 800px;
      background-color: #f5f5dc; /* Bege mais claro para o quadro interno */
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
      text-align: center;
      margin-top: 30px;
    }

    h1 {
      color: #000; /* Preto */
      font-size: 2.3em; /* Tamanho da fonte */
      margin-bottom: 30px;
    }

    .event {
      margin-bottom: 40px;
      background-color: #f5f5dc; /* Bege mais claro para o quadro interno */
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }

    .event .date {
      font-weight: bold;
      font-size: 1.2em;
      color: #000; /* Preto para o título da foto */
      margin-bottom: 10px;
    }

    .event img {
      width: 40%; /* Tamanho da imagem */
      max-width: 600px;
      border-radius: 10px;
      margin-bottom: 20px;
    }

    .event .message {
      font-size: 1.0em;
      color: #000; /* Preto */
    }

    footer {
      margin-top: 40px;
      font-size: 1.0em;
      color: #777;
      text-align: left;
      margin-top: 50px;
    }

    /* Estilo da barra lateral */
    .side-bar {
      position: fixed;
      top: 0;
      left: 0;
      width: 200px;
      height: 100%;
      background-color: #f5f5dc; /* Bege claro */
      padding: 20px;
      box-shadow: 2px 0 15px rgba(0, 0, 0, 0.1);
    }

    .side-bar .title {
      font-weight: bold;
      font-size: 1.5em;
      color: #000;
      margin-bottom: 10px;
    }

    .side-bar .count {
      font-size: 1.0em;
      color: #000;
      margin-top: 10px;
    }
  </style>
</head>
<body>

  <!-- Barra lateral esquerda -->
  <div class="side-bar">
    <div class="title">Tempo Juntos:</div>
    <div class="count" id="tempo-juntos"></div>
  </div>

  <!-- Conteúdo principal -->
  <div class="container">
    <h1>Nossa História</h1>

    <!-- Evento 1 -->
    <div class="event">
      <div class="date">Nossa Primeira Foto</div>
      <img src="https://i.imgur.com/tr7Y5Lh.jpeg" alt="Nossa Primeira Foto">
      <div class="message">A partir desse dia eu já comecei a sentir que você iria ser a minha mulher. Tão tão tão linda</div>
    </div>

    <!-- Evento 2 -->
    <div class="event">
      <div class="date">Nossas idas ao terminal para você pegar seu Uber</div>
      <img src="https://i.imgur.com/OUD0FUH.jpeg" alt="Nossas idas ao terminal para você pegar seu Uber">
      <div class="message">Os momentos que eu fazia de tudo pra te levar, porque queria passar esse último tempinho do seu lado</div>
    </div>

    <!-- Evento 3 -->
    <div class="event">
      <div class="date">Nossa primeira "viagem" juntos</div>
      <img src="https://i.imgur.com/7v7wkMN.jpeg" alt="Nossa primeira 'viagem' juntos">
      <div class="message">Como eu amo essa foto nossa.. Você tão linda e eu já todo apaixonado por você... Essa viagem só foi boa por sua causa, desde que chegou você é minha melhor companhia</div>
    </div>

    <!-- Evento 4 -->
    <div class="event">
      <div class="date">Nossos idas atrasadas</div>
      <img src="https://i.imgur.com/6dqTsiq.jpeg" alt="Nossos idas atrasadas">
      <div class="message">Dia que tinhamos um aniversário mas chegamos no final kkkkk mas não importa, passamos um momento juntos pelo menos</div>
    </div>

    <!-- Evento 5 -->
    <div class="event">
      <div class="date">Eu e você</div>
      <img src="https://i.imgur.com/3KRtmkE.jpeg" alt="Eu e você">
      <div class="message">Como eu amo você, esse rostinho lindo</div>
    </div>

    <!-- Evento 6 -->
    <div class="event">
      <div class="date">A saga das vagas</div>
      <img src="https://i.imgur.com/p4BBrTD.jpeg" alt="A saga das vagas">
      <div class="message">Como é dificil encontrar vagas em um shopping sabado a noite...</div>
    </div>

    <!-- Evento 7 -->
    <div class="event">
      <div class="date">O pedido...</div>
      <img src="https://i.imgur.com/Ob9svec.jpeg" alt="O pedido...">
      <div class="message">Eu guardo esse dia bem guardado no meu coração... O dia que tomei minha melhor decisão. Pedir você em namoro... O amor da minha vidaaaaaaaaaaaaa</div>
    </div>

    <!-- Evento 8 -->
    <div class="event">
      <div class="date">Seu meio medvet</div>
      <img src="https://i.imgur.com/oaqKwQX.jpeg" alt="Seu meio medvet">
      <div class="message">Um dia muito importante pra você, que consequentemente se torna muito importante pra mim. Orgulho de ver a mulher que você é, tão inteligente e esforçada. Você é um mulherão do caralho</div>
    </div>

    <!-- Evento 9 -->
    <div class="event">
      <div class="date">Acordando</div>
      <img src="https://i.imgur.com/GUVPqHz.jpeg" alt="Acordando">
      <div class="message">Os momentos que você fala que está feia... Mas você não sabe que isso é impossível de acontecer, você é a mulher mais linda do mundo casa segundo do dia</div>
    </div>

    <!-- Evento 10 -->
    <div class="event">
      <div class="date">Ano novo...</div>
      <img src="https://i.imgur.com/oX7VUxW.jpeg" alt="Ano novo...">
      <div class="message">Nosso primeiro ano novo juntos... Que felicidade esse dia, saber que esse com certeza foi o primeiro de muitos, saber que estou com a mulher da minha vida... Eu amo esses momentos com você, amo cada momento nosso</div>
    </div>

    <!-- Evento 11 -->
    <div class="event">
      <div class="date">Um dia seu</div>
      <img src="https://i.imgur.com/rCAI1qf.jpeg" alt="Um dia seu">
      <div class="message">Um dia qualquer. Porém todos os dias são seus, todos os dias são dias de te fazer feliz, são dias de te surpreender e fazer você sorrir (o que eu mais gosto de fazer na vida)</div>
    </div>

    <!-- Evento 12 -->
    <div class="event">
      <div class="date">Você...</div>
      <img src="https://i.imgur.com/MFeW2I4.jpeg" alt="Você...">
      <div class="message">Essa aqui é só pra admirar a sua beleza... Como você é linda meu amor</div>
    </div>

    <!-- Evento 13 -->
    <div class="event">
      <div class="date">Minha preferida</div>
      <img src="https://i.imgur.com/q01HJcq.jpeg" alt="Minha preferida">
      <div class="message">Nosso rolê na praia, tão gostoso (só não mais gostosa que você).. Se tornou minha foto preferida, pois mostra exatemente o que eu queria fazer todo dia... Poder curtir um dia tranquilo, na brisa do mar, jogar conversa fora com você, te beijar e no final da noite dormir agarradinho</div>
    </div>

    <!-- Evento 14 -->
    <div class="event">
      <div class="date">Que soninho</div>
      <img src="https://i.imgur.com/i080Q3m.jpeg" alt="Que soninho">
      <div class="message">Linda até dormindo...</div>
    </div>

    <!-- Evento 15 -->
    <div class="event">
      <div class="date">Mais uma do carnaval</div>
      <img src="https://i.imgur.com/DLebNap.jpeg" alt="Mais uma do carnaval">
      <div class="message">Mais um dia que eu não queria que acabasse (afinal, nenhum dia ao seu lado deveria acabar). Que dia bom ao lado do amor da minha vida.</div>
    </div>

    <footer>
      5 meses juntos, namorando o amor da minha vida... Que coisa boa... Muito muito feliz.<br>
      Queria te dizer que esse tempo que estamos juntos estão sendo os melhores da minha vida, me sinto vivendo a melhor fase dela, sinto que estou realizado com você, até porque já encontrei o amor da minha vida, o amor que eu sempre quis.<br><br>

      Muito obrigado por estar me ensinando sobre o amor, por ser minha companheira e minha amada. Você é muito preciosa pra mim, chegou em um momento muito importante e acabou se tornando muito importante na minha vida! Obrigado meu amor.<br><br>

      Sinto que vamos viver muitas coisas boas juntos, vamos ser muito felizes e conquistar o mundo juntos. Você é quem eu quero passar o resto da vida ao lado.<br><br>

      Obrigado por todos os momentos juntos desde que nos conhecemos, você é e sempre será minha melhor escolha. <br><br>

      EU TE AMO MEU AMOR
    </footer>
  </div>

  <script>
    // Função para calcular e exibir o tempo juntos
    function updateTime() {
      const startDate = new Date('2024-10-26');
      const currentDate = new Date();

      const diff = currentDate - startDate;

      const months = Math.floor(diff / (1000 * 60 * 60 * 24 * 30));
      const days = Math.floor((diff % (1000 * 60 * 60 * 24 * 30)) / (1000 * 60 * 60 * 24));
      const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((diff % (1000 * 60)) / 1000);

      document.getElementById("tempo-juntos").innerHTML = `
        <div>${months} meses ${days} dias</div>
        <div>${hours}h ${minutes}min ${seconds}s</div>
      `;
    }

    // Atualizar o tempo ao carregar a página
    window.onload = updateTime;
  </script>
</body>
</html>
