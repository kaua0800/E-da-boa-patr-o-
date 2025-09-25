<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chama no ZAP</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #1e1e2f; /* Fundo sólido */
      color: #fff;
      text-align: center;
      padding: 50px 20px;
      overflow-x: hidden;
    }

    .container {
      background: rgba(0, 0, 0, 0.6);
      padding: 30px;
      border-radius: 15px;
      max-width: 400px;
      margin: auto;
      animation: slideDown 1s ease-out;
    }

    h1 {
      font-size: 28px;
      margin-bottom: 30px;
      animation: fadeIn 2s ease-in-out;
    }

    .btn {
      display: block;
      margin: 15px auto;
      padding: 15px 20px;
      font-size: 20px;
      font-weight: bold;
      color: #fff;
      background: #25d366; /* Verde estilo WhatsApp */
      border: none;
      border-radius: 12px;
      text-decoration: none;
      width: 200px;
      transition: 0.3s;
      animation: fadeInUp 1.5s ease-in-out;
    }

    .btn:hover {
      background: #1ebe57;
      transform: scale(1.05);
    }

    /* Animações */
    @keyframes slideDown {
      from { transform: translateY(-50px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes fadeInUp {
      from { transform: translateY(30px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Chama no ZAP que é da boa</h1>
    <!-- Botões com link direto pro WhatsApp -->
    <a href="https://wa.me/5581997839240?text=quero%20um%20corre%2020" class="btn">De 20</a>
    <a href="https://wa.me/5581997839240?text=quero%20um%20corre%20de%2050" class="btn">De 50</a>
  </div>
</body>
</html>
