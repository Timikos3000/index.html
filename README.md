<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой Сайт</title>
    <!-- Метатег для подтверждения Google -->
    <meta name="google-site-verification" content="iVernEiSUhlHJMyvH_6RkhgBj9ZbQJk6KrEuW6ANEQc" />
    <style>
        /* Основные стили */
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; color: #333; background-color: #f4f4f4; }
        header { background-color: #333; color: #fff; padding: 1em 0; text-align: center; }
        nav { text-align: center; margin-top: 10px; }
        nav a { color: #333; text-decoration: none; margin: 0 15px; font-weight: bold; }
        nav a:hover { color: #007bff; }
        .container { max-width: 800px; margin: auto; padding: 20px; }
        h1 { color: #333; }
        p { line-height: 1.6; }
        footer { background-color: #333; color: #fff; text-align: center; padding: 10px 0; margin-top: 20px; }
        .image { width: 100%; height: auto; max-width: 500px; margin: 20px auto; display: block; }
    </style>
</head>
<body>

<!-- Шапка сайта -->
<header>
    <h1>Добро пожаловать на мой сайт</h1>
    <nav>
        <a href="#about">Обо мне</a>
        <a href="#portfolio">Портфолио</a>
        <a href="#contact">Контакты</a>
    </nav>
</header>

<!-- Основной контент -->
<div class="container">
    <!-- Раздел "Обо мне" -->
    <section id="about">
        <h2>Обо мне</h2>
        <p>Привет! Меня зовут [Ваше имя]. Я веб-разработчик, занимаюсь созданием и разработкой сайтов. У меня есть опыт работы с различными языками программирования и фреймворками.</p>
        <img src="https://via.placeholder.com/500" alt="Фото обо мне" class="image">
    </section>

    <!-- Раздел "Портфолио" -->
    <section id="portfolio">
        <h2>Портфолио</h2>
        <p>Здесь вы можете увидеть мои проекты:</p>
        <ul>
            <li>Проект 1: <a href="#">Ссылка на проект</a></li>
            <li>Проект 2: <a href="#">Ссылка на проект</a></li>
            <li>Проект 3: <a href="#">Ссылка на проект</a></li>
        </ul>
    </section>

    <!-- Раздел "Контакты" -->
    <section id="contact">
        <h2>Контакты</h2>
        <p>Свяжитесь со мной:</p>
        <ul>
            <li>Email: <a href="mailto:example@example.com">example@example.com</a></li>
            <li>Телефон: +7 (123) 456-78-90</li>
            <li>Социальные сети:
                <a href="#">ВКонтакте</a>, <a href="#">Facebook</a>, <a href="#">Instagram</a>
            </li>
        </ul>
    </section>
</div>

<!-- Футер сайта -->
<footer>
    <p>&copy; 2024 [Ваше имя]. Все права защищены.</p>
</footer>

</body>
</html>
