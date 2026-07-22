
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mirage & Magic Square Navigation</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(135deg, #0f0c20 0%, #1a103c 50%, #0d1b2a 100%);
      color: #ffffff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      padding: 20px;
    }

    .container {
      background: rgba(255, 255, 255, 0.05);
      backdrop-filter: blur(10px);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 16px;
      padding: 40px 30px;
      box-shadow: 0 15px 35px rgba(0, 0, 0, 0.5);
      text-align: center;
      max-width: 480px;
      width: 100%;
    }

    h1 {
      margin-bottom: 30px;
      font-size: 1.8rem;
      text-transform: uppercase;
      letter-spacing: 3px;
      color: #e0e6ed;
      text-shadow: 0 2px 10px rgba(0,0,0,0.5);
    }

    .nav-container {
      display: flex;
      flex-direction: column;
      gap: 20px;
      align-items: stretch;
    }

    .nav-link {
      display: block;
      color: #00f2fe;
      text-decoration: none;
      font-size: 1.2rem;
      font-weight: 700;
      letter-spacing: 1.5px;
      padding: 16px 24px;
      border: 2px solid #00f2fe;
      border-radius: 12px;
      background: rgba(0, 242, 254, 0.05);
      transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
      box-shadow: 0 4px 15px rgba(0, 242, 254, 0.1);
    }

    .nav-link:hover {
      background: #00f2fe;
      color: #0f0c20;
      box-shadow: 0 0 25px rgba(0, 242, 254, 0.6);
      transform: translateY(-3px);
    }

    .nav-link.secondary {
      color: #4facfe;
      border-color: #4facfe;
      background: rgba(79, 172, 254, 0.05);
      box-shadow: 0 4px 15px rgba(79, 172, 254, 0.1);
    }

    .nav-link.secondary:hover {
      background: #4facfe;
      color: #0f0c20;
      box-shadow: 0 0 25px rgba(79, 172, 254, 0.6);
    }

    .note {
      margin-top: 25px;
      font-size: 0.85rem;
      color: #8a99ad;
      line-height: 1.4;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Select Destination</h1>

    <div class="nav-container">
      <!-- Edit the href URL below to redirect where you want -->
      <a href="https://zoldick200-spec.github.io/33333/Mirage_Boss_Timer_v5%20(2).html" class="nav-link">MIRAGE WEEKLYBOSS</a>

      <!-- Edit the href URL below to redirect where you want -->
      <a href="https://zoldick200-spec.github.io/33333/ms11frenzy.html" class="nav-link secondary">MAGIC SQUARE FRENZY</a>
    </div>

    <p class="note">Click either button above to navigate to the respective page.</p>
  </div>

</body>
</html>

