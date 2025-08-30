# Pizzaria-Bauducco
Cardápio digital da Pizzaria Bauducco
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cardápio Digital</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background-color: #f8f8f8;
      color: #333;
      padding: 20px;
      max-width: 800px;
      margin: auto;
    }
    header {
      text-align: center;
      border-bottom: 2px solid #d40000;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }
    h1 {
      color: #d40000;
    }
    .categoria {
      background-color: #fff;
      padding: 15px;
      margin-bottom: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .item {
      margin-bottom: 10px;
    }
    .item strong {
      color: #222;
    }
    footer {
      text-align: center;
      margin-top: 30px;
      color: #666;
      font-size: 0.9em;
    }
  </style>
</head>
<body>

  <header>
    <h1>Pizzaria Boa</h1>
    <p>🍕 Desde 2020 fazendo a melhor pizza da cidade</p>
  </header>

  <div class="categoria">
    <h2>🍕 Pizzas Salgadas</h2>
    <div class="item">
      <strong>Margherita</strong> - R$ 45,00<br>
      <small>Molho de tomate, mussarela, manjericão fresco</small>
    </div>
    <div class="item">
      <strong>Calabresa</strong> - R$ 48,00<br>
      <small>Molho, mussarela, calabresa, cebola</small>
    </div>
  </div>

  <div class="categoria">
    <h2>🥤 Bebidas</h2>
    <div class="item">
      <strong>Refrigerante 350ml</strong> - R$ 8,00
    </div>
    <div class="item">
      <strong>Água 500ml</strong> - R$ 5,00
    </div>
  </div>

  <footer>
    📞 Peça pelo WhatsApp: (61) 9999244244<br>
    📍 Qms 18 Rua Casa 21 - Sobradinho DF
  </footer>

</body>
</html>
