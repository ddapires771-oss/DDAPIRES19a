<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DDA Pire | Construção Civil</title>
  <style>
    /* Estilo geral */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: #f4f4f4;
      color: #222;
    }

    /* Cabeçalho */
    header {
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.5)), url('https://images.unsplash.com/photo-1503387762-592deb58ef4e') center/cover;
      color: #fff;
      text-align: center;
      padding: 120px 20px;
    }

    header h1 {
      font-size: 3.5em;
      text-transform: uppercase;
      letter-spacing: 3px;
      margin-bottom: 15px;
    }

    header p {
      font-size: 1.2em;
    }

    nav {
      background-color: #111;
      padding: 15px 0;
      text-align: center;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 20px;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #f4b400;
    }

    /* Seções */
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }

    .sobre, .servicos, .contato {
      margin-bottom: 60px;
    }

    .sobre h2, .servicos h2, .contato h2 {
      text-align: center;
      color: #333;
      margin-bottom: 25px;
      font-size: 2em;
      border-bottom: 3px solid #f4b400;
      display: inline-block;
      padding-bottom: 10px;
    }

    .sobre p {
      text-align: center;
      font-size: 1.1em;
      line-height: 1.6;
      max-width: 900px;
      margin: 20px auto;
    }

    .servicos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
    }

    .servico {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      padding: 30px;
      text-align: center;
      width: 300px;
      transition: transform 0.3s;
    }

    .servico:hover {
      transform: scale(1.05);
    }

    .servico h3 {
      margin-bottom: 15px;
      color: #f4b400;
    }

    .contato form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 500px;
      margin: 0 auto;
    }

    .contato input, .contato textarea {
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1em;
    }

    .contato button {
      background-color: #f4b400;
      border: none;
      color: #fff;
      padding: 15px;
      font-size: 1em;
      border-radius: 5px;
      cursor: pointer;
      transition: 0.3s;
    }

    .contato button:hover {
      background-color: #e09c00;
    }

    footer {
      background-color: #111;
      color: #fff;
      text-align: center;
      padding: 30px 20px;
      font-size: 0.9em;
    }

    footer a {
      color: #f4b400;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>DDA Pire</h1>
    <p>Excelência e confiança na construção civil</p>
  </header>

  <nav>
    <a href="#sobre">Sobre</a>
    <a href="#servicos">Serviços</a>
    <a href="#contato">Contato</a>
  </nav>

  <section id="sobre" class="sobre">
    <h2>Sobre Nós</h2>
    <p>
      A <strong>DDA Pire</strong> é uma empresa especializada em construção civil, dedicada a entregar
      qualidade, segurança e inovação em cada projeto. Com uma equipe experiente e apaixonada pelo que faz,
      transformamos sonhos em realidade com comprometimento e excelência.
    </p>
  </section>

  <section id="servicos" class="servicos">
    <h2>Serviços</h2>
    <div class="servico">
      <h3>Construções Residenciais</h3>
      <p>Projetos completos de casas e condomínios, com foco em durabilidade e design moderno.</p>
    </div>
    <div class="servico">
      <h3>Obras Comerciais</h3>
      <p>Execução de lojas, galpões e escritórios com alto padrão de qualidade e prazos garantidos.</p>
    </div>
    <div class="servico">
      <h3>Reformas e Manutenções</h3>
      <p>Renovação de ambientes, reparos e modernizações com atendimento personalizado.</p>
    </div>
  </section>
<form action="https://formsubmit.co/ddapires771@gmail.com" method="POST">
  <input type="text" name="name" placeholder="Seu name" required>
  <input type="email" name="email" placeholder="Seu e-mail" required>
  <textarea name="message" rows="5" placeholder="Mensagem" required></textarea>
  <button type="submit">Enviar Mensagem</button>

  <!-- Configurações extras -->
  <input type="hidden" name="_subject" value="Nova mensagem do site DDA Pires!">
  <input type="hidden" name="_captcha" value="false">
  <input type="hidden" name="_next" value="https://ddapires771-oss.github.io/DDAPIRES19a/sucesso.html">
</form>

  <footer>
    <p>&copy; 2025 DDA Pire - Todos os direitos reservados | Desenvolvido por <a href="#">DOUGLAS PIRES</a></p>
  </footer>
</body>
</html>

