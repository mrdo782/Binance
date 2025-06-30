# Binance
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Вход в Binance</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <link rel="icon" href="https://cryptologos.cc/logos/binance-coin-bnb-logo.svg" type="image/svg+xml">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(to right, #0f2027, #203a43, #2c5364);
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      color: #fff;
    }

    .login-container {
      background: #1c1c1e;
      padding: 40px 30px;
      border-radius: 16px;
      box-shadow: 0 0 30px rgba(0, 0, 0, 0.5);
      width: 100%;
      max-width: 400px;
      animation: fadeIn 1.2s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .logo {
      display: flex;
      justify-content: center;
      margin-bottom: 25px;
    }

    .logo img {
      width: 60px;
    }

    h2 {
      text-align: center;
      font-weight: 600;
      margin-bottom: 25px;
      color: #fcd535;
    }

    input {
      width: 100%;
      padding: 14px;
      margin: 10px 0 18px;
      font-size: 15px;
      border-radius: 10px;
      border: 1px solid #444;
      background: #2c2c2e;
      color: white;
      transition: 0.3s;
    }

    input:focus {
      border-color: #fcd535;
      outline: none;
    }

    button {
      width: 100%;
      padding: 14px;
      font-size: 15px;
      font-weight: 600;
      color: #111;
      background: #fcd535;
      border: none;
      border-radius: 10px;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    button:hover {
      background: #e6bf2c;
    }

    .google-btn {
      background: #fff;
      color: #111;
      margin-top: 10px;
      border: 1px solid #ccc;
    }

    .google-btn:hover {
      background: #e4e4e4;
    }

    .register {
      margin-top: 25px;
      text-align: center;
      font-size: 14px;
      color: #aaa;
    }

    .register a {
      color: #fcd535;
      text-decoration: none;
    }

    .register a:hover {
      text-decoration: underline;
    }

    @media (max-width: 480px) {
      .login-container {
        padding: 30px 20px;
      }
    }
  </style>
</head>
<body>
  <div class="login-container">
    <div class="logo">
      <img src="https://cryptologos.cc/logos/binance-coin-bnb-logo.svg" alt="Binance Logo" />
    </div>
    <h2>Вход в Binance</h2>
    <form id="login-form">
      <input type="text" placeholder="Email или номер телефона" required />
      <input type="password" placeholder="Пароль" required />
      <button type="submit">Войти</button>
    </form>
    <button class="google-btn">Войти через Google</button>
    <div class="register">
      Нет аккаунта? <a href="#">Зарегистрироваться</a>
    </div>
  </div>
</body>
</html>
