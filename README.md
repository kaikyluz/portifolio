<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portfólio Kaiky Luz</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="style.css" />
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css" />
</head>
<body>
  <header>
    <div class="container">
      <h1>Kaiky Luz</h1>
      <p class="title">Desenvolvedor Web | Automação de Processos</p>
      <p class="contato">
        <a href="https://wa.me/5511934912215" target="_blank">
          <i class="fab fa-whatsapp"></i> (11) 93491-2215
        </a>
      </p>
    </div>
  </header>

  <section class="about">
    <div class="container">
      <h2>Sobre Mim</h2>
      <p>
        Sou <strong>estudante de Análise e Desenvolvimento de Sistemas</strong> com foco em <strong>desenvolvimento web</strong> e <strong>automações</strong>.
        Busco oportunidades para aplicar meus conhecimentos em projetos reais, entregando <strong>soluções simples, úteis e funcionais</strong> para pequenos negócios e autônomos.
      </p>
    </div>
  </section>

  <section class="services">
    <div class="container">
      <h2>Serviços</h2>
      <div class="service-list">
        <div class="service-item">
          <h3>Criação de Sites</h3>
          <p>Landing pages, portfólios, sites institucionais.</p>
        </div>
        <div class="service-item">
          <h3>Sistemas Web Simples</h3>
          <p>Cadastros de clientes, controle de estoque, agendamentos.</p>
        </div>
        <div class="service-item">
          <h3>Automatizações</h3>
          <p>Automatização de tarefas repetitivas, integração com planilhas.</p>
        </div>
      </div>
    </div>
  </section>

  <section class="technologies">
    <div class="container">
      <h2>Tecnologias que Utilizo</h2>
      <ul>
        <li><i class="fab fa-html5"></i> HTML, CSS, JavaScript</li>
        <li><i class="fas fa-database"></i> MySQL (básico)</li>
        <li><i class="fas fa-graduation-cap"></i> Em constante aprendizado</li>
      </ul>
    </div>
  </section>

  <section class="contact">
    <div class="container">
      <h2>Contato</h2>
      <p>Entre em contato através do meu <a href="https://www.linkedin.com/in/kaiky-luz-bb16a5326" target="_blank">LinkedIn</a> ou envie uma mensagem no WhatsApp:</p>
      <a class="botao-whatsapp" href="https://wa.me/5511934912215" target="_blank">
        <i class="fab fa-whatsapp"></i> Falar comigo no WhatsApp
      </a>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Kaiky Luz | Todos os direitos reservados.</p>
    </div>
  </footer>
</body>
</html>


{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  html {
    scroll-behavior: smooth;
  }
  
  body {
    font-family: 'Roboto', sans-serif;
    background-color: #f7f7f7;
    color: #333;
    line-height: 1.6;
  }
  
  .container {
    width: 90%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 30px 0;
  }
  
  header {
    background-color: #007acc;
    color: white;
    text-align: center;
    padding: 50px 0;
  }
  
  header h1 {
    font-size: 42px;
    font-weight: 500;
  }
  
  header .title {
    font-size: 20px;
    margin-bottom: 15px;
    color: #f0f0f0;
  }
  
  .contato {
    font-size: 18px;
    margin-top: 10px;
  }
  
  .contato a {
    color: #25D366;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s;
  }
  
  .contato a:hover {
    color: #128C7E;
  }
  
  section {
    padding: 50px 0;
  }
  
  h2 {
    font-size: 28px;
    margin-bottom: 20px;
    color: #007acc;
  }
  
  .service-list {
    display: flex;
    gap: 20px;
    justify-content: space-between;
    flex-wrap: wrap;
  }
  
  .service-item {
    background-color: #fff;
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    flex: 1;
    text-align: center;
    min-height: 180px;
  }
  
  .service-item h3 {
    font-size: 22px;
    color: #007acc;
    margin-bottom: 15px;
  }
  
  ul {
    list-style-type: none;
    padding-left: 0;
  }
  
  ul li {
    margin: 8px 0;
    font-size: 16px;
  }
  
  ul li i {
    margin-right: 8px;
    color: #007acc;
  }
  
  .contact a {
    color: #007acc;
    text-decoration: none;
    font-weight: bold;
  }
  
  .contact a:hover {
    text-decoration: underline;
  }
  
  .botao-whatsapp {
    display: inline-block;
    background-color: #25D366;
    color: white;
    padding: 12px 20px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
    margin-top: 15px;
    transition: background-color 0.3s;
  }
  
  .botao-whatsapp:hover {
    background-color: #128C7E;
  }
  
  footer {
    background-color: #333;
    color: white;
    padding: 20px 0;
    text-align: center;
  }
  
  footer p {
    font-size: 13px;
    opacity: 0.8;
  }
  
  @media (max-width: 768px) {
    .service-list {
      flex-direction: column;
      gap: 15px;
    }
  
    .service-item {
      flex: none;
      width: 100%;
    }
  }
