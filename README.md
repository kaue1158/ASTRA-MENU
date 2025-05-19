<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Produto Incrível</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet" />
  <style>
    body {
      font-family: 'Inter', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      color: #333;
    }

    .container {
      max-width: 900px;
      margin: 50px auto;
      padding: 20px;
      background: #fff;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
      display: flex;
      flex-wrap: wrap;
    }

    .image {
      flex: 1 1 400px;
      text-align: center;
    }

    .image img {
      max-width: 100%;
      border-radius: 8px;
    }

    .details {
      flex: 1 1 400px;
      padding: 20px;
    }

    .details h1 {
      font-size: 28px;
      margin-bottom: 10px;
    }

    .price {
      font-size: 24px;
      color: #27ae60;
      margin: 10px 0;
    }

    .description {
      font-size: 16px;
      margin: 20px 0;
    }

    .buy-btn {
      display: inline-block;
      padding: 15px 30px;
      background: #2d89ef;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      border-radius: 6px;
      transition: background 0.3s ease;
    }

    .buy-btn:hover {
      background: #1b5fa7;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <div class="image">
      <img src="https://via.placeholder.com/450x450.png?text=Seu+Produto+Aqui" alt="Produto">
    </div>
    <div class="details">
      <h1>Produto Incrível</h1>
      <div class="price">R$ 149,90</div>
      <div class="description">
        Este é um produto incrível que vai mudar sua vida. Qualidade premium, entrega rápida e 100% de satisfação garantida.
      </div>
      <a href="#" class="buy-btn">Comprar Agora</a>
    </div>
  </div>

</body>
</html>
