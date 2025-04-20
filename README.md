# 6numtem
Site de vendas 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>6num tem | Queima de Estoque</title>
  <style>
    :root {
      --laranja: #ff8800;
      --laranja-escuro: #cc6e00;
      --fundo: #fff8f0;
      --texto: #1e1e1e;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--fundo);
      color: var(--texto);
    }

    header {
      background-color: var(--laranja-escuro);
      color: white;
      padding: 20px;
      text-align: center;
    }

    header img {
      max-height: 100px;
      margin-bottom: 10px;
    }

    .hero {
      text-align: center;
      padding: 60px 20px;
      background-color: var(--laranja);
      color: white;
    }

    .hero h1 {
      font-size: 2.5em;
    }

    .hero p {
      font-size: 1.2em;
      margin-top: 10px;
    }

    .section {
      padding: 40px 20px;
      text-align: center;
    }

    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }

    .product-card {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 10px;
      width: 250px;
      padding: 20px;
      text-align: left;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
    }

    .product-card h3 {
      color: var(--laranja-escuro);
    }

    footer {
      background-color: var(--laranja-escuro);
      color: white;
      text-align: center;
      padding: 30px 20px;
      margin-top: 60px;
    }

    a {
      color: white;
      text-decoration: none;
    }

    .social {
      margin-top: 10px;
    }

    .social a {
      margin: 0 10px;
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="Logo 6num tem" />
    <h1>6num tem</h1>
    <p>Promoções direto do estoque</p>
  </header>

  <section class="hero">
    <h1>QUEIMA DE ESTOQUE!</h1>
    <p>Descontos incríveis em produtos selecionados. Aproveite antes que acabe!</p>
  </section>

  <section class="section">
    <h2>Ofertas do momento</h2>
    <div class="products">
      <div class="product-card">
        <h3>Produto 1</h3>
        <p>De R$ 100,00 por R$ 59,90</p>
      </div>
      <div class="product-card">
        <h3>Produto 2</h3>
        <p>De R$ 80,00 por R$ 39,90</p>
      </div>
      <div class="product-card">
        <h3>Produto 3</h3>
        <p>De R$ 120,00 por R$ 74,90</p>
      </div>
    </div>
  </section>

  <section class="section">
    <h2>Fale com a gente</h2>
    <p>Email: <a href="mailto:reislopeswallace@gmail.com">reislopeswallace@gmail.com</a></p>
    <div class="social">
      <a href="https://www.instagram.com/6nuntem?igsh=Z3dya25yYjV5aXo4" target="_blank">Instagram</a>
    </div>
  </section>

  <footer>
    <p>6num tem © 2025 — Todos os direitos reservados.</p>
    <p>Promoções imperdíveis direto do estoque. Garanta o seu antes que acabe!</p>
  </footer>

</body>
</html>
