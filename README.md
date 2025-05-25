<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>А & А | Приглашение на свадьбу</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Montserrat:wght@300;400&display=swap" rel="stylesheet">
    <style>
        /* CSS стили */
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff9f5;
            color: #333;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3.5em;
            margin: 0;
            color: #d4a373;
        }
        .date {
            font-size: 1.5em;
            margin: 20px 0;
            letter-spacing: 3px;
        }
        .names {
            font-size: 4em;
            margin: 40px 0;
            font-weight: 700;
        }
        .btn {
            background: #d4a373;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 1.2em;
            cursor: pointer;
            margin: 20px;
            border-radius: 50px;
            transition: all 0.3s;
        }
        .btn:hover {
            background: #c08552;
        }
        .photo-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 40px 0;
        }
        .photo-gallery img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            margin: 10px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        footer {
            margin-top: 50px;
            padding: 20px;
            background: #f8edeb;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Мы женимся!</h1>
        <div class="date">15 СЕНТЯБРЯ 2024</div>
        <div class="names">А & А</div>
        
        <p>Дорогие друзья и родные,<br> 
        мы будем рады видеть вас в этот особенный день!</p>
        
        <button class="btn" onclick="alert('Подтверждение отправлено! ❤️')">Подтвердить присутствие</button>
        
        <div class="photo-gallery">
            <img src="https://via.placeholder.com/200" alt="Фото 1">
            <img src="https://via.placeholder.com/200" alt="Фото 2">
            <img src="https://via.placeholder.com/200" alt="Фото 3">
        </div>
        
        <div>
            <h2>Детали мероприятия</h2>
            <p><strong>Место:</strong> Ресторан «Лазурный», Москва</p>
            <p><strong>Время:</strong> 18:00</p>
            <p><strong>Дресс-код:</strong> Вечерний наряд</p>
        </div>
    </div>
    
    <footer>
        <p>С любовью,<br>Анна и Алексей</p>
    </footer>
</body>
</html>
