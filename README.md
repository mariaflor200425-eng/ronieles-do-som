<!DOCTYPE html>
<html lang="pt-BR">
	<head>
		<meta charset="UTF-8">
        <META name="viewport" content="width=device-width,inicial-scale=1.0">
        <META name="viewport" content="width=device-width,inicial-scale=1.0">
        <META name="viewport" content="width=device-width,inicial-scale=1.0">
        <META name="viewport" content="width=device-width,inicial-scale=1.0">
		<color:red><p>RONIELES DO SOM</p></color:red>
	<link rel="stylesheet" href="styles.css">
</head>
<body><section class="inscricao-section">
    <h2>Inscreva-se e Receba Novidades do Som!</h2>

    <form action="/enviar-inscricao" method="POST">
        
        <div class="form-group">
            <label for="nome">Seu Nome:</label>
            <input type="text" id="nome" name="nome" required>
        </div>
        
        <div class="form-group">
            <label for="email">Seu Melhor E-mail:</label>
            <input type="email" id="email" name="email" required>
        </div>
        
        <div class="form-group">
            <label for="tipo-musica">Qual seu estilo musical favorito?</label>
            <select id="tipo-musica" name="estilo">
                <option value="eletronica">Eletrônica/DJ</option>
                <option value="hip-hop">Hip Hop/Rap</option>
                <option value="rock">Rock/Metal</option>
                <option value="outros">Outros</option>
            </select>
        </div>
        
        <button type="submit" class="btn-inscrever">
            QUERO ME INSCREVER
        </button>
        
    </form>
</section>
	<a href="https://www.ronieledossom.com">www.ronieledossom.com</a>
	<header><button onclick="alert('Olá!')">Clique aqui</button>

		Olá, <span style="color:rgb(0, 26, 255);">tudo bem?</span>


		<h1>Bem-vindo ao RONIELES DO SOM</h1>
	</header>
	<main>
		
		<section>
			<h2>seja bem vindo em nosso site</h2>
			<p>Somos uma empresa especializada em desenvolvimento de projetos de criaçao musical.</p>
			<p>instrumentos musicais são objetos criados para produzir música e são essenciais
				para a expressão artística e cultural em todo o mundo.</p>
			<img src="https://c.pxhere.com/images/dc/07/e3fba035261061b53803f88c83f8-1503233.jpg!d"
		srcset="https://c.pxhere.com/images/dc/07/e3fba035261061b53803f88c83f8-1503233.jpg!d" alt="música, musical, Instrumentos, eletrônicos, equipamento de audio, Disc jockey, Console de mixagem, tecnologia, Instrumento musical eletrônico, aparelho eletrônico, cdj, Instrumento eletrônico, reprodutor de mídia, Banco de imagens In PxHere"   >
		</section>
	</main>
	<footer>
		<p>&copy; 2025 RONIELES DO SOM. Todos os direitos reservados.</p>
	</footer>
</body>
</html><!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ronieles do Som</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #a8d8ff, #e3f2fd);
      color: #0a3d62;
      text-align: center;
    }

    header {
      background-color: #0a3d62;
      color: white;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    h1 {
      font-size: 2.5rem;
      letter-spacing: 2px;
    }

    p {
      font-size: 1.2rem;
    }

    .music-section {
      margin: 50px auto;
      max-width: 400px;
      background: white;
      border-radius: 20px;
      padding: 30px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    button {
      background-color: #0a3d62;
      color: white;
      border: none;
      padding: 15px 25px;
      border-radius: 30px;
      cursor: pointer;
      font-size: 1rem;
      transition: 0.3s;
    }

    button:hover {
      background-color: #1e90ff;
      transform: scale(1.05);
    }

    footer {
      margin-top: 80px;
      padding: 15px;
      background-color: #0a3d62;
      color: white;
      font-size: 0.9rem;
    }

    audio {
      margin-top: 20px;
      width: 100%;
      outline: none;
    }
  </style>
</head>
<body>

  <header>
    <h1>Ronieles do Som 🎶</h1>
    <p>O melhor do som automotivo e profissional</p>
  </header>

  <section class="music-section">
    <h2>Toque sua música</h2>
    <p>Escolha uma música do seu dispositivo e curta o som!</p>
    <input type="file" id="fileInput" accept="audio/*">
    <br><br>
    <audio id="audioPlayer" controls></audio>
    <br><br>
    <button onclick="playMusic()">▶️ Tocar Música</button>
    <button onclick="pauseMusic()">⏸️ Pausar</button>
  </section>

  <footer>
    © 2025 Ronieles do Som - Todos os direitos reservados
  </footer>

  <script>
    const audioPlayer = document.getElementById('audioPlayer');
    const fileInput = document.getElementById('fileInput'
<img src="https://c.pxhere.com/images/dc/07/e3fba035261061b53803f88c83f8-1503233.jpg!d"
		srcset="https://c.pxhere.com/images/dc/07/e3fba035261061b53803f88c83f8-1503233.jpg!d" alt="música, musical, Instrumentos, eletrônicos, equipamento de audio, Disc jockey, Console de mixagem, tecnologia, Instrumento musical eletrônico, aparelho eletrônico, cdj, Instrumento eletrônico, reprodutor de mídia, Banco de imagens In PxHere"   >);

	fileInput.addEventListener('change', function() {
	  const file = this.files[0];
	  if (file) {
		const fileURL = URL.createObjectURL(file);
		audioPlayer.src = fileURL;
	  }
	});

	function playMusic() {
	  audioPlayer.play();
	}

	function pauseMusic() {
	  audioPlayer.pause();
	}
  </script><!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ronieles do Som</title>
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #a8d8ff, #e3f2fd);
      color: #0a3d62;
      text-align: center;
    }

    header {
      background-color: #0a3d62;
      color: white;
      padding: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    h1 {
      font-size: 2.5rem;
      letter-spacing: 2px;
    }

    p {
      font-size: 1.2rem;
    }

    .music-section {
      margin: 50px auto;
      max-width: 400px;
      background: white;
      border-radius: 20px;
      padding: 30px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    button {
      background-color: #0a3d62;
      color: white;
      border: none;
      padding: 15px 25px;
      border-radius: 30px;
      cursor: pointer;
      font-size: 1rem;
      transition: 0.3s;
    }

    button:hover {
      background-color: #1e90ff;
      transform: scale(1.05);
    }

    footer {
      margin-top: 80px;
      padding: 15px;
      background-color: #0a3d62;
      color: white;
      font-size: 0.9rem;
    }

    audio {
      margin-top: 20px;
      width: 100%;
      outline: none;
    }

    .social-links {
      margin: 40px 0;
    }

    .social-links a {
      text-decoration: none;
      color: white;
      background-color: #1e90ff;
      padding: 12px 18px;
      border-radius: 30px;
      margin: 5px;
      display: inline-block;
      transition: 0.3s;
    }

    .social-links a:hover {
      background-color: #0a3d62;
      transform: translateY(-3px);
    }

    /* Estilo da seção de contato */
    .contact-section {
      margin: 60px auto;
      max-width: 400px;
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    input, textarea {
      width: 100%;
      margin: 10px 0;
      padding: 12px;
      border-radius: 10px;
      border: 1px solid #ccc;
      font-family: inherit;
      resize: none;
    }

    .send-btn {
      background-color: #1e90ff;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      font-size: 1rem;
      width: 100%;
      transition: 0.3s;
    }

    .send-btn:hover {
      background-color: #0a3d62;
    }
  </style>
</head>
<body>

  <header>
    <h1>Ronieles do Som 🎶</h1>
    <p>O melhor do som automotivo e profissional</p>
  </header>

  <section class="music-section">
    <h2>🎵 Toque sua música</h2>
    <p>Escolha uma música do seu dispositivo e curta o som!</p>
    <input type="file" id="fileInput" accept="audio/*">
    <br><br>
    <audio id="audioPlayer" controls></audio>
    <br><br>
    <button onclick="playMusic()">▶️ Tocar Música</button>
    <button onclick="pauseMusic()">⏸️ Pausar</button>
  </section>

  <section class="social-links">
    <h2>🌐 Siga o Ronieles do Som</h2>
    <a href="https://www.instagram.com/ronielesilva97/?__pwa=1#" target="_blank">Instagram</a>
    
    <a href="https://www.youtube.com/watch?v=uOrPUWSGUkg" target="_blank">YouTube</a>
  </section>

  <section class="contact-section">
    <h2>📩
 <p>Um instrumento musical é um objeto ou máquina criada para produzir sons organizados e agradáveis ao ouvido, que podem ser manipulados em parâmetros como timbre, altura, intensidade e duração. A história desses artefatos se confunde com a própria história da humanidade, sendo as flautas de osso os registros mais antigos já encontrados, datados de aproximadamente 42 mil anos. </p> instrumento musical é um objeto ou máquina criada para produzir sons organizados e agradáveis ao ouvido, que podem ser manipulados em parâmetros como timbre, altura, intensidade e duração. A história desses artefatos se confunde com a própria história da humanidade, sendo as flautas de osso os registros mais antigos já encontrados, datados de aproximadamente 42 mil anos. ></p><!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Robô Dançando</title>
</head>
<body>
  <h1>Olha o robô dançando! 🤖💃</h1>
  <img src="robo-dancando.gif" alt="Robô Dançando" width="300">
</body>
</html>
<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<title>Robô Dançando</title>
<style>
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #f0f0f0;
  }

  .robo {
    width: 100px;
    height: 150px;
    background: gray;
    border-radius: 10px;
    position: relative;
    animation: dançar 1s infinite alternate;
  }

  .robo::before {
    content: '';
    width: 40px;
    height: 40px;
    background: silver;
    border-radius: 50%;
    position: absolute;
    top: -40px;
    left: 30p
  }


  <!-- Barra de inscrição -->
  <div class="top-bar">
    <h2>Inscreva-se no nosso curso!</h2>
    <form>
      <input type="text" placeholder="Seu nome" required>
      <input type="email" placeholder="Seu e-mail" required>
      <button type="submit">Inscrever</button>
    </form>
  </div>

  <!-- Conteúdo central -->
  <div class="content">
    <h1>Bem-vindo ao meu site!</h1>
    <p>Aqui você pode colocar o robô dançando ou outras coisas legais 😎</p>
    <div class="robo"></div>
  </div>

</body>
</html>
