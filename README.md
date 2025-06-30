<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Binance – Вход</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
<style>
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    background: #000;
    font-family: 'Poppins', sans-serif;
    color: #fff;
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 20px;
  }
  .login-wrapper {
    background: #121212;
    border-radius: 16px;
    padding: 40px 35px 50px;
    max-width: 400px;
    width: 100%;
    box-shadow: 0 0 30px #f3ba2f;
    text-align: center;
  }
  .logo {
    margin-bottom: 30px;
  }
  .logo img {
    width: 70px;
  }
  h1 {
    font-weight: 700;
    font-size: 28px;
    margin-bottom: 30px;
    color: #f3ba2f;
  }
  form {
    display: flex;
    flex-direction: column;
  }
  input {
    background: #222;
    border: none;
    border-radius: 8px;
    padding: 14px 16px;
    margin-bottom: 20px;
    color: #fff;
    font-size: 16px;
    outline: none;
    transition: box-shadow 0.3s ease;
  }
  input:focus {
    box-shadow: 0 0 8px #f3ba2f;
  }
  button {
    background: #f3ba2f;
    border: none;
    border-radius: 8px;
    padding: 14px;
    font-weight: 700;
    font-size: 16px;
    color: #000;
    cursor: pointer;
    transition: background 0.3s ease;
  }
  button:hover {
    background: #d4a520;
  }
  .extra {
    margin-top: 25px;
    font-size: 14px;
  }
  .extra a {
    color: #f3ba2f;
    text-decoration: none;
  }
  .extra a:hover {
    text-decoration: underline;
  }

  /* Footer */
  footer {
    margin-top: 40px;
    font-size: 12px;
    color: #888;
    text-align: center;
  }

  footer a {
    color: #f3ba2f;
    text-decoration: none;
    margin: 0 5px;
  }
  footer a:hover {
    text-decoration: underline;
  }

  /* Responsive */
  @media (max-width: 480px) {
    .login-wrapper {
      padding: 30px 20px 40px;
    }
    h1 {
      font-size: 24px;
      margin-bottom: 25px;
    }
    input {
      font-size: 14px;
      padding: 12px 14px;
    }
    button {
      font-size: 14px;
      padding: 12px;
    }
  }
</style>
</head>
<body>
  <div class="login-wrapper">
    <div class="logo">
      <img src="https://cryptologos.cc/logos/binance-coin-bnb-logo.svg?v=024" alt="Binance Logo" />
    </div>
    <h1>Войти в аккаунт</h1>
    <form>
      <input type="text" placeholder="Email или номер телефона" required />
      <input type="password" placeholder="Пароль" required />
      <button type="submit">Войти</button>
    </form>
    <div class="extra">
      Нет аккаунта? <a href="#">Зарегистрироваться</a>
    </div>
  </div>

  <footer>
    © 2017–2025 Binance. Все права защищены. &nbsp;|&nbsp; <a href="#">Условия использования</a> &nbsp;|&nbsp; <a href="#">Политика конфиденциальности</a>
  </footer>
</body>
</html>
