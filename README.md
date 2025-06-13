<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AutoScan - Премиальная диагностика автомобилей</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">
</head>
<body>
    <header class="glass-header">
        <div class="container">
            <div class="logo">
                <div class="logo-icon">
                    <i class="fas fa-car-side"></i>
                </div>
                <div>
                    <h1>Auto<span>Scan</span></h1>
                    <p>Профессиональная диагностика</p>
                </div>
            </div>
            <nav>
                <ul>
                    <li><a href="index.html" class="active">Главная</a></li>
                    <li><a href="about.html">О сервисе</a></li>
                    <li><a href="features.html">Возможности</a></li>
                    <li><a href="pricing.html">Тарифы</a></li>
                    <li><a href="mobile-app.html">Приложение</a></li>
                    <li><a href="contact.html" class="contact-btn">Контакты</a></li>
                </ul>
            </nav>
            <div class="mobile-menu">
                <i class="fas fa-bars"></i>
            </div>
        </div>
    </header>

    <section class="hero">
        <div class="hero-overlay"></div>
        <div class="container">
            <div class="hero-content">
                <span class="hero-badge">Новое поколение диагностики</span>
                <h2>Умный контроль состояния вашего автомобиля</h2>
                <p>Получайте точные данные и профессиональные рекомендации прямо в вашем смартфоне</p>
                <div class="hero-buttons">
                    <a href="#" class="btn btn-primary">
                        <i class="fas fa-play"></i> Демо-версия
                    </a>
                    <a href="#" class="btn btn-secondary">
                        <i class="fas fa-mobile-alt"></i> Скачать приложение
                    </a>
                </div>
            </div>
            <div class="hero-image">
                <img src="images/app-3d.png" alt="Мобильное приложение AutoScan" class="app-3d">
                <div class="circle-decor circle-1"></div>
                <div class="circle-decor circle-2"></div>
            </div>
        </div>
    </section>

    <section class="partners">
        <div class="container">
            <p>Доверяют ведущие автопроизводители</p>
            <div class="partners-grid">
                <img src="images/brands/audi.svg" alt="Audi">
                <img src="images/brands/bmw.svg" alt="BMW">
                <img src="images/brands/mercedes.svg" alt="Mercedes">
                <img src="images/brands/toyota.svg" alt="Toyota">
                <img src="images/brands/ford.svg" alt="Ford">
            </div>
        </div>
    </section>

    <section class="how-it-works">
        <div class="container">
            <div class="section-header">
                <span class="section-subtitle">Как это работает</span>
                <h2>Простое подключение — профессиональный результат</h2>
            </div>
            <div class="steps">
                <div class="step">
                    <div class="step-icon">
                        <div class="step-number">1</div>
                        <i class="fas fa-plug"></i>
                    </div>
                    <h3>Подключение</h3>
                    <p>Подсоедините сканер к диагностическому разъёму OBD2 вашего автомобиля</p>
                </div>
                <div class="step">
                    <div class="step-icon">
                        <div class="step-number">2</div>
                        <i class="fas fa-mobile-alt"></i>
                    </div>
                    <h3>Синхронизация</h3>
                    <p>Запустите приложение и подключитесь к сканеру через Bluetooth</p>
                </div>
                <div class="step">
                    <div class="step-icon">
                        <div class="step-number">3</div>
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3>Анализ</h3>
                    <p>Получайте данные в реальном времени и подробные отчёты</p>
                </div>
            </div>
        </div>
    </section>

    <section class="features">
        <div class="container">
            <div class="section-header center">
                <span class="section-subtitle">Возможности</span>
                <h2>Комплексный мониторинг всех систем</h2>
            </div>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon gradient-1">
                        <i class="fas fa-engine"></i>
                    </div>
                    <h3>Двигатель</h3>
                    <p>Мониторинг параметров работы двигателя, расхода топлива и температуры</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon gradient-2">
                        <i class="fas fa-car-battery"></i>
                    </div>
                    <h3>Электроника</h3>
                    <p>Диагностика электронных систем и состояния аккумулятора</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon gradient-3">
                        <i class="fas fa-tire"></i>
                    </div>
                    <h3>Ходовая часть</h3>
                    <p>Контроль состояния подвески, тормозной системы и давления в шинах</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon gradient-4">
                        <i class="fas fa-exclamation-triangle"></i>
                    </div>
                    <h3>Диагностика ошибок</h3>
                    <p>Расшифровка кодов ошибок с рекомендациями по устранению</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon gradient-5">
                        <i class="fas fa-file-invoice"></i>
                    </div>
                    <h3>Отчёты</h3>
                    <p>Профессиональные отчёты для сервисных центров в PDF формате</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon gradient-6">
                        <i class="fas fa-bell"></i>
                    </div>
                    <h3>Уведомления</h3>
                    <p>Своевременные оповещения о неисправностях и необходимости ТО</p>
                </div>
            </div>
        </div>
    </section>

    <section class="app-showcase">
        <div class="container">
            <div class="app-content">
                <div class="section-header">
                    <span class="section-subtitle">Мобильное приложение</span>
                    <h2>Интуитивно понятный интерфейс</h2>
                    <p>Наше приложение сочетает мощный функционал с простым и удобным интерфейсом, доступным каждому автовладельцу</p>
                </div>
                <div class="app-features">
                    <div class="app-feature">
                        <i class="fas fa-check-circle"></i>
                        <span>Реальное время работы всех систем</span>
                    </div>
                    <div class="app-feature">
                        <i class="fas fa-check-circle"></i>
                        <span>История всех поездок и диагностик</span>
                    </div>
                    <div class="app-feature">
                        <i class="fas fa-check-circle"></i>
                        <span>Рекомендации по обслуживанию</span>
                    </div>
                </div>
                <div class="download-buttons">
                    <a href="#" class="download-btn">
                        <i class="fab fa-apple"></i>
                        <div>
                            <span>Download on the</span>
                            <strong>App Store</strong>
                        </div>
                    </a>
                    <a href="#" class="download-btn">
                        <i class="fab fa-google-play"></i>
                        <div>
                            <span>Get it on</span>
                            <strong>Google Play</strong>
                        </div>
                    </a>
                </div>
            </div>
            <div class="app-screenshots">
                <div class="phone-mockup">
                    <img src="images/phone-mockup.png" alt="AutoScan App">
                    <div class="screen-slider">
                        <img src="images/app-screen-1.jpg" class="active" alt="App Screen 1">
                        <img src="images/app-screen-2.jpg" alt="App Screen 2">
                        <img src="images/app-screen-3.jpg" alt="App Screen 3">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="testimonials">
        <div class="container">
            <div class="section-header center">
                <span class="section-subtitle">Отзывы</span>
                <h2>Что говорят наши клиенты</h2>
            </div>
            <div class="testimonials-grid">
                <div class="testimonial-card">
                    <div class="rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <p class="quote">"Сервис помог обнаружить проблему с датчиком кислорода до того, как это привело к серьёзным поломкам. Экономия денег и времени!"</p>
                    <div class="author">
                        <img src="images/testimonials/user1.jpg" alt="Иван Петров">
                        <div>
                            <h4>Иван Петров</h4>
                            <span>Toyota Camry</span>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <p class="quote">"Очень удобное приложение. Теперь всегда знаю, когда нужно менять масло или фильтры. Отчёты понятные и информативные."</p>
                    <div class="author">
                        <img src="images/testimonials/user2.jpg" alt="Елена Смирнова">
                        <div>
                            <h4>Елена Смирнова</h4>
                            <span>Volkswagen Golf</span>
                        </div>
                    </div>
                </div>
                <div class="testimonial-card">
                    <div class="rating">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <p class="quote">"Использую в своём автосервисе. Клиенты довольны подробными отчётами, а я экономлю время на диагностике."</p>
                    <div class="author">
                        <img src="images/testimonials/user3.jpg" alt="Алексей Ковалёв">
                        <div>
                            <h4>Алексей Ковалёв</h4>
                            <span>Владелец СТО</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section class="cta">
        <div class="container">
            <div class="cta-card">
                <div class="cta-content">
                    <h2>Готовы попробовать?</h2>
                    <p>Начните использовать AutoScan сегодня и получите первую диагностику бесплатно</p>
                </div>
                <div class="cta-buttons">
                    <a href="#" class="btn btn-light">
                        <i class="fas fa-envelope"></i> Оставить заявку
                    </a>
                    <a href="#" class="btn btn-outline-light">
                        <i class="fas fa-question-circle"></i> Задать вопрос
                    </a>
                </div>
            </div>
        </div>
    </section>

    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <div class="logo">
                        <div class="logo-icon">
                            <i class="fas fa-car-side"></i>
                        </div>
                        <div>
                            <h3>Auto<span>Scan</span></h3>
                            <p>Инновационная диагностика</p>
                        </div>
                    </div>
                    <p class="footer-about">AutoScan — это современный сервис удалённой диагностики автомобилей, помогающий владельцам и сервисным центрам контролировать состояние транспортных средств.</p>
                    <div class="social-links">
                        <a href="#"><i class="fab fa-vk"></i></a>
                        <a href="#"><i class="fab fa-telegram"></i></a>
                        <a href="#"><i class="fab fa-youtube"></i></a>
                        <a href="#"><i class="fab fa-instagram"></i></a>
                    </div>
                </div>
                <div class="footer-col">
                    <h4>Сервис</h4>
                    <ul>
                        <li><a href="#">Главная</a></li>
                        <li><a href="#">Возможности</a></li>
                        <li><a href="#">Тарифы</a></li>
                        <li><a href="#">Приложение</a></li>
                        <li><a href="#">Блог</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Поддержка</h4>
                    <ul>
                        <li><a href="#">FAQ</a></li>
                        <li><a href="#">Документация</a></li>
                        <li><a href="#">Сообщество</a></li>
                        <li><a href="#">Контакты</a></li>
                        <li><a href="#">Политика конфиденциальности</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Контакты</h4>
                    <ul class="contact-info">
                        <li><i class="fas fa-map-marker-alt"></i> Москва, ул. Автодиагностики, 15</li>
                        <li><i class="fas fa-phone"></i> +7 (495) 123-45-67</li>
                        <li><i class="fas fa-envelope"></i> support@autoscan.ru</li>
                        <li><i class="fas fa-clock"></i> Пн-Пт: 9:00 - 18:00</li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2023 AutoScan. Все права защищены.</p>
                <div class="payment-methods">
                    <i class="fab fa-cc-visa"></i>
                    <i class="fab fa-cc-mastercard"></i>
                    <i class="fab fa-cc-paypal"></i>
                    <i class="fab fa-cc-apple-pay"></i>
                </div>
            </div>
        </div>
    </footer>

    <script src="js/main.js"></script>
</body>
</html>/* Общие стили */
:root {
    --primary: #4361ee;
    --primary-dark: #3a56d4;
    --secondary: #3f37c9;
    --accent: #f72585;
    --dark: #1a1a2e;
    --dark-light: #16213e;
    --gray: #e2e8f0;
    --light: #f8f9fa;
    --white: #ffffff;
    --success: #4cc9f0;
    --warning: #f8961e;
    --danger: #ef233c;
    
    --shadow-sm: 0 1px 3px rgba(0,0,0,0.12);
    --shadow-md: 0 4px 6px rgba(0,0,0,0.1);
    --shadow-lg: 0 10px 25px rgba(0,0,0,0.1);
    --shadow-xl: 0 20px 50px rgba(0,0,0,0.15);
    
    --radius-sm: 4px;
    --radius-md: 8px;
    --radius-lg: 12px;
    --radius-xl: 16px;
    --radius-full: 9999px;
    
    --transition: all 0.3s ease;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    line-height: 1.6;
    color: var(--dark);
    background-color: var(--light);
    overflow-x: hidden;
}

h1, h2, h3, h4, h5, h6 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 700;
    line-height: 1.2;
}

a {
    text-decoration: none;
    color: inherit;
}

ul {
    list-style: none;
}

img {
    max-width: 100%;
    height: auto;
}

.container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

/* Кнопки */
.btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    padding: 12px 24px;
    border-radius: var(--radius-lg);
    font-weight: 500;
    font-size: 16px;
    cursor: pointer;
    transition: var(--transition);
    border: none;
    outline: none;
}

.btn-primary {
    background-color: var(--primary);
    color: var(--white);
}

.btn-primary:hover {
    background-color: var(--primary-dark);
    transform: translateY(-2px);
    box-shadow: var(--shadow-md);
}

.btn-secondary {
    background-color: var(--white);
    color: var(--primary);
    border: 1px solid var(--primary);
}

.btn-secondary:hover {
    background-color: var(--primary);
    color: var(--white);
    transform: translateY(-2px);
    box-shadow: var(--shadow-md);
}

.btn-light {
    background-color: var(--white);
    color: var(--primary);
}

.btn-light:hover {
    background-color: var(--gray);
    transform: translateY(-2px);
    box-shadow: var(--shadow-md);
}

.btn-outline-light {
    background-color: transparent;
    color: var(--white);
    border: 1px solid var(--white);
}

.btn-outline-light:hover {
    background-color: var(--white);
    color: var(--primary);
    transform: translateY(-2px);
    box-shadow: var(--shadow-md);
}

/* Шапка */
.glass-header {
    background: rgba(255, 255, 255, 0.9);
    backdrop-filter: blur(10px);
    -webkit-backdrop-filter: blur(10px);
    box-shadow: var(--shadow-sm);
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
    transition: var(--transition);
}

.glass-header.scroll-down {
    transform: translateY(-100%);
}

.glass-header.scroll-up {
    transform: translateY(0);
    box-shadow: var(--shadow-md);
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 0;
}

.logo {
    display: flex;
    align-items: center;
    gap: 12px;
}

.logo-icon {
    width: 40px;
    height: 40px;
    background-color: var(--primary);
    color: var(--white);
    border-radius: var(--radius-md);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 18px;
}

.logo h1 {
    font-size: 22px;
    margin-bottom: 2px;
}

.logo h1 span {
    color: var(--primary);
}

.logo p {
    font-size: 12px;
    color: var(--dark-light);
    opacity: 0.8;
}

nav ul {
    display: flex;
    gap: 20px;
}

nav ul li a {
    font-weight: 500;
    font-size: 15px;
    transition: var(--transition);
    padding: 8px 12px;
    border-radius: var(--radius-sm);
}

nav ul li a:hover, nav ul li a.active {
    color: var(--primary);
}

.contact-btn {
    background-color: var(--primary);
    color: var(--white) !important;
    padding: 8px 16px !important;
    border-radius: var(--radius-lg) !important;
}

.contact-btn:hover {
    background-color: var(--primary-dark) !important;
}

.mobile-menu {
    display: none;
    font-size: 24px;
    cursor: pointer;
}

/* Герой секция */
.hero {
    position: relative;
    padding: 180px 0 100px;
    background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
    color: var(--white);
    overflow: hidden;
}

.hero-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: url('images/dots-pattern.png') center/cover;
    opacity: 0.1;
}

.hero .container {
    position: relative;
    display: flex;
    align-items: center;
    gap: 40px;
    z-index: 1;
}

.hero-content {
    flex: 1;
}

.hero-badge {
    display: inline-block;
    background-color: rgba(255, 255, 255, 0.2);
    padding: 6px 12px;
    border-radius: var(--radius-full);
    font-size: 14px;
    font-weight: 500;
    margin-bottom: 20px;
}

.hero h2 {
    font-size: 48px;
    margin-bottom: 20px;
    line-height: 1.2;
}

.hero p {
    font-size: 18px;
    margin-bottom: 30px;
    opacity: 0.9;
    max-width: 500px;
}

.hero-buttons {
    display: flex;
    gap: 16px;
    margin-top: 30px;
}

.hero-image {
    flex: 1;
    position: relative;
}

.app-3d {
    position: relative;
    z-index: 2;
    max-width: 100%;
    height: auto;
    filter: drop-shadow(var(--shadow-xl));
    animation: float 6s ease-in-out infinite;
}

.circle-decor {
    position: absolute;
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.1);
    z-index: 1;
}

.circle-1 {
    width: 300px;
    height: 300px;
    top: -50px;
    right: -50px;
}

.circle-2 {
    width: 200px;
    height: 200px;
    bottom: -30px;
    left: -30px;
}

@keyframes float {
    0% { transform: translateY(0px); }
    50% { transform: translateY(-20px); }
    100% { transform: translateY(0px); }
}

/* Партнеры */
.partners {
    padding: 60px 0;
    background-color: var(--white);
}

.partners p {
    text-align: center;
    margin-bottom: 30px;
    font-size: 14px;
    color: var(--dark-light);
    opacity: 0.7;
}

.partners-grid {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
    gap: 40px;
}

.partners-grid img {
    height: 30px;
    opacity: 0.6;
    filter: grayscale(100%);
    transition: var(--transition);
}

.partners-grid img:hover {
    opacity: 1;
    filter: grayscale(0%);
}

/* Как это работает */
.how-it-works {
    padding: 100px 0;
    background-color: var(--light);
}

.section-header {
    margin-bottom: 60px;
    max-width: 600px;
}

.section-header.center {
    text-align: center;
    margin-left: auto;
    margin-right: auto;
}

.section-subtitle {
    display: inline-block;
    color: var(--primary);
    font-weight: 600;
    font-size: 14px;
    text-transform: uppercase;
    letter-spacing: 1px;
    margin-bottom: 12px;
}

.section-header h2 {
    font-size: 36px;
    margin-bottom: 16px;
}

.section-header p {
    color: var(--dark-light);
    font-size: 16px;
}

.steps {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.step {
    background-color: var(--white);
    padding: 40px 30px;
    border-radius: var(--radius-xl);
    box-shadow: var(--shadow-sm);
    transition: var(--transition);
    text-align: center;
}

.step:hover {
    transform: translateY(-10px);
    box-shadow: var(--shadow-lg);
}

.step-icon {
    position: relative;
    width: 80px;
    height: 80px;
    margin: 0 auto 25px;
}

.step-number {
    position: absolute;
    top: -10px;
    right: -10px;
    width: 36px;
    height: 36px;
    background-color: var(--accent);
    color: var(--white);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    font-size: 14px;
}

.step-icon i {
    width: 100%;
    height: 100%;
    background-color: var(--primary);
    color: var(--white);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 32px;
}

.step h3 {
    font-size: 20px;
    margin-bottom: 15px;
}

.step p {
    color: var(--dark-light);
    font-size: 15px;
}

/* Возможности */
.features {
    padding: 100px 0;
    background-color: var(--white);
}

.features-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.feature-card {
    background-color: var(--light);
    padding: 30px;
    border-radius: var(--radius-xl);
    transition: var(--transition);
}

.feature-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-md);
}

.feature-icon {
    width: 60px;
    height: 60px;
    border-radius: var(--radius-lg);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 24px;
    margin-bottom: 20px;
    color: var(--white);
}

.gradient-1 {
    background: linear-gradient(45deg, #4361ee, #4cc9f0);
}
.gradient-2 {
    background: linear-gradient(45deg, #7209b7, #b5179e);
}
.gradient-3 {
    background: linear-gradient(45deg, #f8961e, #f94144);
}
.gradient-4 {
    background: linear-gradient(45deg, #43aa8b, #90be6d);
}
.gradient-5 {
    background: linear-gradient(45deg, #577590, #277da1);
}
.gradient-6 {
    background: linear-gradient(45deg, #9d4edd, #c77dff);
}

.feature-card h3 {
    font-size: 18px;
    margin-bottom: 12px;
}

.feature-card p {
    color: var(--dark-light);
    font-size: 15px;
    line-height: 1.6;
}

/* Показ приложения */
.app-showcase {
    padding: 100px 0;
    background-color: var(--light);
}

.app-showcase .container {
    display: flex;
    align-items: center;
    gap: 60px;
}

.app-content {
    flex: 1;
}

.app-features {
    margin: 30px 0;
}

.app-feature {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 15px;
}

.app-feature i {
    color: var(--primary);
    font-size: 18px;
}

.app-feature span {
    font-size: 16px;
}

.download-buttons {
    display: flex;
    gap: 15px;
    margin-top: 40px;
}

.download-btn {
    display: flex;
    align-items: center;
    gap: 10px;
    padding: 12px 20px;
    background-color: var(--dark);
    color: var(--white);
    border-radius: var(--radius-lg);
    transition: var(--transition);
}

.download-btn:hover {
    background-color: var(--dark-light);
    transform: translateY(-2px);
    box-shadow: var(--shadow-md);
}

.download-btn i {
    font-size: 24px;
}

.download-btn div {
    display: flex;
    flex-direction: column;
}

.download-btn div span {
    font-size: 10px;
}

.download-btn div strong {
    font-size: 16px;
    font-weight: 600;
}

.app-screenshots {
    flex: 1;
    position: relative;
}

.phone-mockup {
    position: relative;
    width: 300px;
    margin: 0 auto;
}

.phone-mockup img {
    position: relative;
    z-index: 2;
}

.screen-slider {
    position: absolute;
    top: 12px;
    left: 12px;
    right: 12px;
    bottom: 12px;
    border-radius: 25px;
    overflow: hidden;
}

.screen-slider img {
    position: absolute;
    width: 100%;
    height: 100%;
    object-fit: cover;
    opacity: 0;
    transition: opacity 1s ease;
}

.screen-slider img.active {
    opacity: 1;
}

/* Отзывы */
.testimonials {
    padding: 100px 0;
    background-color: var(--white);
}

.testimonials-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 30px;
}

.testimonial-card {
    background-color: var(--light);
    padding: 30px;
    border-radius: var(--radius-xl);
    box-shadow: var(--shadow-sm);
    transition: var(--transition);
}

.testimonial-card:hover {
    transform: translateY(-5px);
    box-shadow: var(--shadow-md);
}

.rating {
    color: var(--warning);
    margin-bottom: 20px;
}

.quote {
    font-style: italic;
    margin-bottom: 25px;
    position: relative;
}

.quote::before {
    content: '"';
    font-size: 60px;
    color: var(--primary);
    opacity: 0.2;
    position: absolute;
    top: -20px;
    left: -10px;
    font-family: serif;
}

.author {
    display: flex;
    align-items: center;
    gap: 15px;
}

.author img {
    width: 50px;
    height: 50px;
    border-radius: 50%;
    object-fit: cover;
}

.author h4 {
    font-size: 16px;
    margin-bottom: 4px;
}

.author span {
    font-size: 14px;
    color: var(--dark-light);
}

/* Призыв к действию */
.cta {
    padding: 80px 0;
    background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
    color: var(--white);
}

.cta-card {
    background-color: var(--white);
    padding: 60px;
    border-radius: var(--radius-xl);
    box-shadow: var(--shadow-xl);
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: url('images/cta-pattern.png') center/cover;
}

.cta-content h2 {
    font-size: 32px;
    margin-bottom: 12px;
    color: var(--white);
}

.cta-content p {
    font-size: 18px;
    opacity: 0.9;
}

.cta-buttons {
    display: flex;
    gap: 15px;
}

/* Подвал */
footer {
    background-color: var(--dark);
    color: var(--gray);
    padding: 80px 0 0;
}

.footer-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 40px;
    margin-bottom: 60px;
}

.footer-col h4 {
    color: var(--white);
    font-size: 18px;
    margin-bottom: 25px;
    position: relative;
    padding-bottom: 10px;
}

.footer-col h4::after {
    content: '';
    position: absolute;
    bottom: 0;
    left: 0;
    width: 40px;
    height: 2px;
    background-color: var(--primary);
}

.footer-about {
    font-size: 14px;
    line-height: 1.7;
    margin: 20px 0;
}

.social-links {
    display: flex;
    gap: 15px;
}

.social-links a {
    width: 36px;
    height: 36px;
    background-color: rgba(255, 255, 255, 0.1);
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: var(--transition);
}

.social-links a:hover {
    background-color: var(--primary);
    color: var(--white);
}

.footer-col ul li {
    margin-bottom: 12px;
}

.footer-col ul li a {
    font-size: 15px;
    transition: var(--transition);
}

.footer-col ul li a:hover {
    color: var(--white);
    padding-left: 5px;
}

.contact-info li {
    display: flex;
    align-items: center;
    gap: 10px;
    margin-bottom: 15px;
    font-size: 14px;
}

.contact-info i {
    color: var(--primary);
    width: 20px;
    text-align: center;
}

.footer-bottom {
    border-top: 1px solid rgba(255, 255, 255, 0.1);
    padding: 20px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 14px;
}

.payment-methods {
    display: flex;
    gap: 15px;
    font-size: 24px;
}

.payment-methods i {
    opacity: 0.7;
    transition: var(--transition);
}

.payment-methods i:hover {
    opacity: 1;
}

/* Адаптивность */
@media (max-width: 1024px) {
    .hero h2 {
        font-size: 40px;
    }
    
    .app-showcase .container {
        flex-direction: column;
    }
    
    .app-content {
        text-align: center;
    }
    
    .download-buttons {
        justify-content: center;
    }
    
    .app-feature {
        justify-content: center;
    }
}

@media (max-width: 768px) {
    nav {
        display: none;
    }
    
    .mobile-menu {
        display: block;
    }
    
    .hero .container {
        flex-direction: column;
        text-align: center;
    }
    
    .hero-buttons {
        justify-content: center;
    }
    
    .hero h2 {
        font-size: 32px;
    }
    
    .hero p {
        margin-left: auto;
        margin-right: auto;
    }
    
    .cta-card {
        flex-direction: column;
        text-align: center;
        gap: 30px;
    }
    
    .cta-buttons {
        justify-content: center;
    }
}

@media (max-width: 480px) {
    .hero h2 {
        font-size: 28px;
    }
    
    .hero-buttons {
        flex-direction: column;
    }
    
    .download-buttons {
        flex-direction: column;
    }
    
    .section-header h2 {
        font-size: 28px;
    }
}
document.addEventListener('DOMContentLoaded', function() {
    // Мобильное меню
    const mobileMenuBtn = document.querySelector('.mobile-menu');
    const nav = document.querySelector('nav ul');
    
    mobileMenuBtn.addEventListener('click', function() {
        nav.style.display = nav.style.display === 'flex' ? 'none' : 'flex';
    });
    
    // Закрытие меню при клике на пункт
    const navItems = document.querySelectorAll('nav ul li a');
    navItems.forEach(item => {
        item.addEventListener('click', function() {
            if (window.innerWidth <= 768) {
                nav.style.display = 'none';
            }
        });
    });
    
    // Плавная прокрутка
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener('click', function(e) {
            e.preventDefault();
            
            const targetId = this.getAttribute('href');
            if (targetId === '#') return;
            
            const targetElement = document.querySelector(targetId);
            if (targetElement) {
                window.scrollTo({
                    top: targetElement.offsetTop - 100,
                    behavior: 'smooth'
                });
            }
        });
    });
    
    // Фиксация шапки при скролле
    const header = document.querySelector('.glass-header');
    let lastScroll = 0;
    
    window.addEventListener('scroll', function() {
        const currentScroll = window.pageYOffset;
        
        if (currentScroll <= 100) {
            header.classList.remove('scroll-up');
            return;
        }
        
        if (currentScroll > lastScroll && !header.classList.contains('scroll-down')) {
            header.classList.remove('scroll-up');
            header.classList.add('scroll-down');
        }
        
        if (currentScroll < lastScroll && header.classList.contains('scroll-down')) {
            header.classList.remove('scroll-down');
            header.classList.add('scroll-up');
        }
        
        lastScroll = currentScroll;
    });
    
    // Слайдер скриншотов приложения
    const appScreens = document.querySelectorAll('.screen-slider img');
    let currentScreen = 0;
    
    if (appScreens.length > 1) {
        function showNextScreen() {
            appScreens[currentScreen].classList.remove('active');
            currentScreen = (currentScreen + 1) % appScreens.length;
            appScreens[currentScreen].classList.add('active');
        }
        
        setInterval(showNextScreen, 3000);
    }
    
    // Анимация при скролле
    const animateOnScroll = function() {
        const elements = document.querySelectorAll('.step, .feature-card, .testimonial-card');
        
        elements.forEach(element => {
            const elementPosition = element.getBoundingClientRect().top;
            const screenPosition = window.innerHeight / 1.2;
            
            if (elementPosition < screenPosition) {
                element.style.opacity = '1';
                element.style.transform = 'translateY(0)';
            }
        });
    };
    
    // Инициализация анимации
    window.addEventListener('scroll', animateOnScroll);
    animateOnScroll();
    
    // Добавление класса активного пункта меню при скролле
    const sections = document.querySelectorAll('section');
    const navLinks = document.querySelectorAll('nav ul li a');
    
    window.addEventListener('scroll', function() {
        let current = '';
        
        sections.forEach(section => {
            const sectionTop = section.offsetTop;
            const sectionHeight = section.clientHeight;
            
            if (pageYOffset >= (sectionTop - 150)) {
                current = section.getAttribute('id');
            }
        });
        
        navLinks.forEach(link => {
            link.classList.remove('active');
            if (link.getAttribute('href') === `#${current}`) {
                link.classList.add('active');
            }
        });
    });
    
    // Параллакс эффект для герой секции
    const hero = document.querySelector('.hero');
    if (hero) {
        window.addEventListener('scroll', function() {
            const scrollPosition = window.pageYOffset;
            hero.style.backgroundPositionY = scrollPosition * 0.5 + 'px';
        });
    }
});
