<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sipp Sipp Play</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff8a00, #e52e71);
      color: white;
      text-align: center;
      margin: 0;
      padding: 0;
    }

    .container {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 1rem;
      padding: 1rem;
      box-sizing: border-box;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    p {
      font-size: 1.2rem;
      max-width: 500px;
      margin-bottom: 2rem;
    }

    .btn {
      background: white;
      color: #e52e71;
      padding: 15px 30px;
      border-radius: 30px;
      text-decoration: none;
      font-size: 1.2rem;
      font-weight: bold;
      transition: 0.3s;
      display: inline-block;
      margin: 5px 0;
    }

    .btn:hover {
      background: #ff8a00;
      color: white;
    }

    /* Mobilanpassning */
    @media (max-width: 600px) {
      h1 {
        font-size: 2rem;
      }

      p {
        font-size: 1rem;
        max-width: 90%;
      }

      .btn {
        font-size: 1rem;
        padding: 12px 20px;
        width: 100%;
        max-width: 300px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Sipp Sipp Play</h1>
    <p>Välkommen till Sipp Sipp Play <br> En plats där du kan spela Sipp Sipp direkt i webbläsaren!</p>
    <a href="spelare-klunk.html" class="btn">Spela: Klunk</a>
    <a href="sippsipp-spelare.html" class="btn">Spela: Sipp Sipp</a>
  </div>
</body>
</html>
