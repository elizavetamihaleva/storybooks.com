<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Название вашего сайта</title>
    <meta name="description" content="Описание вашего сайта">
    
    <!-- Подключение CSS -->
    <link rel="stylesheet" href="styles.css">
    
    <!-- Иконка сайта (favicon) -->
    <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>
<body>
    <!-- Шапка сайта -->
    <header class="header">
        <div class="container">
            <div class="logo">
                <a href="/">Логотип</a>
            </div>
            
            <!-- Основная навигация -->
            <nav class="main-nav">
                <ul>
                    <li><a href="/">Главная</a></li>
                    <li><a href="/about">О нас</a></li>
                    <li><a href="/services">Услуги</a></li>
                    <li><a href="/portfolio">Портфолио</a></li>
                    <li><a href="/contacts">Контакты</a></li>
                </ul>
            </nav>
            
            <!-- Мобильное меню (бургер) -->
            <div class="mobile-menu">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </header>
    
    <!-- Основное содержимое -->
    <main class="main-content">
        <!-- Герой-секция (может быть слайдером) -->
        <section class="hero">
            <div class="container">
                <h1>Главный заголовок сайта</h1>
                <p>Краткое описание или призыв к действию</p>
                <button class="cta-button">Кнопка действия</button>
            </div>
        </section>
        
        <!-- Секция "О нас" -->
        <section class="about-section">
            <div class="container">
                <h2>О нас</h2>
                <p>Текст о вашей компании или проекте...</p>
            </div>
        </section>
        
        <!-- Секция услуг -->
        <section class="services-section">
            <div class="container">
                <h2>Наши услуги</h2>
                <div class="services-grid">
                    <div class="service-card">
                        <h3>Услуга 1</h3>
                        <p>Описание услуги</p>
                    </div>
                    <div class="service-card">
                        <h3>Услуга 2</h3>
                        <p>Описание услуги</p>
                    </div>
                    <div class="service-card">
                        <h3>Услуга 3</h3>
                        <p>Описание услуги</p>
                    </div>
                </div>
            </div>
        </section>
    </main>
    
    <!-- Подвал сайта -->
    <footer class="footer">
        <div class="container">
            <div class="footer-columns">
                <div class="footer-col">
                    <h3>О компании</h3>
                    <p>Краткая информация о компании</p>
                </div>
                <div class="footer-col">
                    <h3>Контакты</h3>
                    <address>
                        <p>Адрес: ул. Примерная, 123</p>
                        <p>Телефон: +7 (123) 456-78-90</p>
                        <p>Email: info@example.com</p>
                    </address>
                </div>
                <div class="footer-col">
                    <h3>Соцсети</h3>
                    <div class="social-links">
                        <a href="#">VK</a>
                        <a href="#">Telegram</a>
                        <a href="#">YouTube</a>
                    </div>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2023 Название компании. Все права защищены.</p>
            </div>
        </div>
    </footer>
