📄 Страница `index.html`

Структура:

```html
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <title>Профиль - Иван Иванов</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <h1>Иван Иванов</h1>
    <img src="https://via.placeholder.com/150" alt="Фото профиля" class="profile-img">
    
    <p class="description">Привет! Я начинающий веб-разработчик. Учусь создавать сайты с нуля.</p>
    
    <div class="contacts">
      <p><strong>Email:</strong> ivan@example.com</p>
      <p><strong>Телефон:</strong> +7 777 123 45 67</p>
    </div>

    <button id="toggleButton">Показать больше</button>
    
    <div class="more-info" id="moreInfo">
      <h2>Обо мне</h2>
      <p>Я люблю программировать, играть в шахматы и гулять на природе.</p>
      <p>Навыки: HTML, CSS, немного JavaScript</p>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
```