# Binance
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Binance — Вход</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
<style>
  * {
    box-sizing: border-box;
  }
  body {
    margin: 0;
    background: #000000;
    font-family: 'Poppins', sans-serif;
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 100vh;
  }
  .container {
    background: #121212;
    padding: 40px 30px;
    border-radius: 12px;
    max-width: 400px;
    width: 90%;
    box-shadow: 0 0 20px #f3ba2f;
    text-align: center;
  }
  .logo {
    margin-bottom: 25px;
  }
  .logo img {
    width: 70px;
  }
  h1 {
    margin: 0 0 25px;
    font-weight: 600;
    font-size: 28px;
    color: #f3ba2f;
  }
  form input {
    width: 100%;
    padding: 14px;
    margin: 10px 0 20px;
    border-radius: 8px;
    border: none;
    font-size: 16px;
    background: #222;
    color: #fff;
    outline: none;
    transition: box-shadow 0.3s;
  }
  form input:focus {
    box-shadow: 0 0 8px #f3ba2f;
  }
  button {
    width: 100%;
    padding: 14px;
    font-size: 16px;
    background: #f3ba2f;
    border: none;
    border-radius: 8px;
    font-weight: 600;
    cursor: pointer;
    color: #000;
    transition: background 0.3s;
  }
  button:hover {
    background: #d4a520;
  }
  .extra {
    margin-top: 20px;
    font-size: 14px;
  }
  .extra a {
    color: #f3ba2f;
    text-decoration: none;
  }
  .extra a:hover {
    text-decoration: underline;
  }
  @media (max-width: 480px) {
    .container {
      padding: 30px 20px;
    }
    h1 {
      font-size: 24px;
    }
  }
</style>
</head>
<body>
  <div class="container">
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
</body>
</html>
