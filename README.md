# GranMarMemorialChop
GranMarMemorialChop
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GranMar Memorial Chop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #2c2c2c;
            color: white;
            padding: 20px 10%;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            background-color: #444;
            color: white;
            padding: 10px 10%;
            display: flex;
            justify-content: space-around;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background-color: #2c2c2c;
            border-radius: 5px;
        }
        section {
            padding: 20px 10%;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
        .gallery img {
            width: 100%;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        footer {
            background-color: #2c2c2c;
            color: white;
            text-align: center;
            padding: 20px 10%;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>GranMar Memorial Chop</h1>
        <p>Виготовлення пам'ятників з повагою до ваших традицій</p>
    </header>
    <nav>
        <a href="#about">Про нас</a>
        <a href="#services">Послуги</a>
        <a href="#gallery">Галерея</a>
        <a href="#contacts">Контакти</a>
    </nav>
    <section id="about">
        <h2>Про нас</h2>
        <p>GranMar Memorial Chop займається виготовленням високоякісних пам'ятників. Ми створюємо індивідуальні рішення, враховуючи всі побажання клієнтів, та дотримуємося найвищих стандартів якості.</p>
    </section>
    <section id="services">
        <h2>Послуги</h2>
        <ul>
            <li>Виготовлення пам'ятників із граніту та мармуру</li>
            <li>Гравірування текстів та зображень</li>
            <li>Фотографії за склом або на камені</li>
            <li>Установка пам'ятників</li>
        </ul>
    </section>
    <section id="gallery">
        <h2>Галерея робіт</h2>
        <div class="gallery">
            <img src="example1.jpg" alt="Приклад роботи 1">
            <img src="example2.jpg" alt="Приклад роботи 2">
            <img src="example3.jpg" alt="Приклад роботи 3">
            <img src="example4.jpg" alt="Приклад роботи 4">
        </div>
    </section>
    <section id="contacts">
        <h2>Контакти</h2>
        <p>Адреса: Вул. Тиха-Чендеш 8</p>
        <p>Телефон: +380635019117</p>
    </section>
    <footer>
        <p>&copy; 2025 GranMar Memorial Chop. Всі права захищено.</p>
    </footer>
</body>
</html>
