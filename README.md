<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AutoDiagnost - Умная диагностика вашего авто</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700&family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #4361ee;
            --primary-dark: #3a56d4;
            --secondary: #3f37c9;
            --accent: #f72585;
            --dark: #1a1a2e;
            --light: #f8f9fa;
            --white: #ffffff;
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
        }
        
        .container {
            width: 100%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Шапка */
        header {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.1);
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 0;
        }
        
        .logo {
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .logo-icon {
            width: 40px;
            height: 40px;
            background: var(--primary);
            color: white;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 20px;
        }
        
        .logo-text h1 {
            font-family: 'Montserrat', sans-serif;
            font-size: 22px;
            color: var(--dark);
        }
        
        .logo-text h1 span {
            color: var(--primary);
        }
        
        .logo-text p {
            font-size: 12px;
            color: #666;
        }
        
        /* Герой секция */
        .hero {
            padding: 180px 0 100px;
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            color: white;
            position: relative;
            overflow: hidden;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiPjxkZWZzPjxwYXR0ZXJuIGlkPSJwYXR0ZXJuIiB3aWR0aD0iNDAiIGhlaWdodD0iNDAiIHBhdHRlcm5Vbml0cz0idXNlclNwYWNlT25Vc2UiIHBhdHRlcm5UcmFuc2Zvcm09InJvdGF0ZSg0NSkiPjxyZWN0IHdpZHRoPSIyMCIgaGVpZ2h0PSIyMCIgZmlsbD0icmdiYSgyNTUsMjU1LDI1NSwwLjA1KSIvPjwvcGF0dGVybj48L2RlZnM+PHJlY3QgZmlsbD0idXJsKCNwYXR0ZXJuKSIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIvPjwvc3ZnPg==');
            opacity: 0.3;
        }
        
        .hero-content {
            position: relative;
            z-index: 2;
            max-width: 600px;
        }
        
        .hero-badge {
            display: inline-block;
            background: rgba(255, 255, 255, 0.2);
            padding: 6px 15px;
            border-radius: 20px;
            font-size: 14px;
            font-weight: 500;
            margin-bottom: 20px;
        }
        
        .hero h2 {
            font-family: 'Montserrat', sans-serif;
            font-size: 42px;
            line-height: 1.2;
            margin-bottom: 20px;
        }
        
        .hero p {
            font-size: 18px;
            margin-bottom: 30px;
            opacity: 0.9;
        }
        
        .btn {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            padding: 12px 28px;
            border-radius: 30px;
            font-weight: 500;
            font-size: 16px;
            cursor: pointer;
            transition: all 0.3s ease;
            text-decoration: none;
        }
        
        .btn-primary {
            background: var(--white);
            color: var(--primary);
        }
        
        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        
        .btn-outline {
            background: transparent;
            color: var(--white);
            border: 2px solid var(--white);
        }
        
        .btn-outline:hover {
            background: var(--white);
            color: var(--primary);
        }
        
        /* Возможности */
        .features {
            padding: 100px 0;
        }
        
        .section-header {
            text-align: center;
            max-width: 700px;
            margin: 0 auto 60px;
        }
        
        .section-subtitle {
            display: inline-block;
            color: var(--primary);
            font-weight: 600;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 1px;
            margin-bottom: 15px;
        }
        
        .section-title {
            font-family: 'Montserrat', sans-serif;
            font-size: 36px;
            margin-bottom: 20px;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .feature-card {
            background: white;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
            transition: all 0.3s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }
        
        .feature-icon {
            width: 60px;
            height: 60px;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            color: white;
            border-radius: 12px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 24px;
            margin-bottom: 20px;
        }
        
        .feature-card h3 {
            font-family: 'Montserrat', sans-serif;
            font-size: 20px;
            margin-bottom: 15px;
        }
        
        /* Мобильное приложение */
        .app-section {
            padding: 100px 0;
            background: var(--white);
        }
        
        .app-container {
            display: flex;
            align-items: center;
            gap: 60px;
        }
        
        .app-content {
            flex: 1;
        }
        
        .app-image {
            flex: 1;
            position: relative;
        }
        
        .app-mockup {
            width: 100%;
            max-width: 300px;
            margin: 0 auto;
            position: relative;
            z-index: 2;
        }
        
        .app-bg-circle {
            position: absolute;
            width: 400px;
            height: 400px;
            background: linear-gradient(45deg, rgba(67, 97, 238, 0.1), rgba(63, 55, 201, 0.1));
            border-radius: 50%;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 1;
        }
        
        .download-buttons {
            display: flex;
            gap: 15px;
            margin-top: 30px;
        }
        
        /* Подвал */
        footer {
            background: var(--dark);
            color: white;
            padding: 80px 0 30px;
        }
        
        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 40px;
            margin-bottom: 60px;
        }
        
        .footer-col h4 {
            font-family: 'Montserrat', sans-serif;
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
            background: var(--primary);
        }
        
        .footer-col ul li {
            margin-bottom: 12px;
        }
        
        .footer-col ul li a {
            color: #ccc;
            transition: all 0.3s ease;
        }
        
        .footer-col ul li a:hover {
            color: white;
            padding-left: 5px;
        }
        
        .copyright {
            text-align: center;
            padding-top: 30px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            color: #999;
            font-size: 14px;
        }
        
        /* Адаптивность */
        @media (max-width: 768px) {
            .hero h2 {
                font-size: 32px;
            }
            
            .app-container {
                flex-direction: column;
            }
            
            .section-title {
                font-size: 28px;
            }
        }
    </style>
</head>
<body>
    <!-- Шапка -->
    <header>
        <div class="container header-container">
            <div class="logo">
                <div class="logo-icon">
                    <i class="fas fa-car"></i>
                </div>
                <div class="logo-text">
                    <h1>Auto<span>Diagnost</span></h1>
                    <p>Профессиональная диагностика</p>
                </div>
            </div>
            <nav>
                <a href="#" class="btn btn-outline">Демо-доступ</a>
            </nav>
        </div>
    </header>

    <!-- Герой секция -->
    <section class="hero">
        <div class="container">
            <div class="hero-content">
                <span class="hero-badge">Новое поколение диагностики</span>
                <h2>Удаленный контроль состояния вашего автомобиля</h2>
                <p>Получайте точные данные о работе всех систем автомобиля и профессиональные рекомендации прямо в вашем смартфоне</p>
                <div class="hero-buttons">
                    <a href="#" class="btn btn-primary">
                        <i class="fas fa-play"></i> Видеообзор
                    </a>
                    <a href="#" class="btn btn-outline">
                        <i class="fas fa-mobile-alt"></i> Скачать приложение
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Возможности -->
    <section class="features">
        <div class="container">
            <div class="section-header">
                <span class="section-subtitle">Возможности</span>
                <h2 class="section-title">Комплексный мониторинг всех систем</h2>
                <p>Наш сервис предоставляет полную информацию о состоянии вашего автомобиля в режиме реального времени</p>
            </div>
            <div class="features-grid">
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-engine"></i>
                    </div>
                    <h3>Диагностика двигателя</h3>
                    <p>Мониторинг параметров работы двигателя, расхода топлива и температуры в реальном времени</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-bolt"></i>
                    </div>
                    <h3>Электронные системы</h3>
                    <p>Контроль состояния электрооборудования и аккумуляторной батареи</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-car-crash"></i>
                    </div>
                    <h3>Безопасность</h3>
                    <p>Диагностика систем безопасности: ABS, ESP, подушек безопасности</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <h3>Анализ данных</h3>
                    <p>Подробные отчеты и аналитика по всем параметрам работы автомобиля</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-bell"></i>
                    </div>
                    <h3>Уведомления</h3>
                    <p>Своевременные оповещения о неисправностях и необходимости ТО</p>
                </div>
                <div class="feature-card">
                    <div class="feature-icon">
                        <i class="fas fa-file-pdf"></i>
                    </div>
                    <h3>Отчеты</h3>
                    <p>Формирование профессиональных отчетов для сервисных центров</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Мобильное приложение -->
    <section class="app-section">
        <div class="container">
            <div class="app-container">
                <div class="app-content">
                    <span class="section-subtitle">Мобильное приложение</span>
                    <h2 class="section-title">Всегда под рукой</h2>
                    <p>Наше приложение доступно для iOS и Android и предоставляет полный функционал удаленной диагностики</p>
                    
                    <div class="app-features">
                        <p><i class="fas fa-check-circle" style="color: var(--primary);"></i> Удобный интерфейс с наглядной визуализацией данных</p>
                        <p><i class="fas fa-check-circle" style="color: var(--primary);"></i> История всех диагностик и поездок</p>
                        <p><i class="fas fa-check-circle" style="color: var(--primary);"></i> Рекомендации по обслуживанию</p>
                        <p><i class="fas fa-check-circle" style="color: var(--primary);"></i> Напоминания о ТО</p>
                    </div>
                    
                    <div class="download-buttons">
                        <a href="#" class="btn btn-primary">
                            <i class="fab fa-apple"></i> App Store
                        </a>
                        <a href="#" class="btn btn-primary">
                            <i class="fab fa-google-play"></i> Google Play
                        </a>
                    </div>
                </div>
                <div class="app-image">
                    <img src="https://via.placeholder.com/300x600" alt="Мобильное приложение AutoDiagnost" class="app-mockup">
                    <div class="app-bg-circle"></div>
                </div>
            </div>
        </div>
    </section>

    <!-- Подвал -->
    <footer>
        <div class="container">
            <div class="footer-grid">
                <div class="footer-col">
                    <div class="logo">
                        <div class="logo-icon">
                            <i class="fas fa-car"></i>
                        </div>
                        <div class="logo-text">
                            <h1>Auto<span>Diagnost</span></h1>
                        </div>
                    </div>
                    <p>Инновационный сервис удаленной диагностики автомобилей</p>
                </div>
                <div class="footer-col">
                    <h4>Сервис</h4>
                    <ul>
                        <li><a href="#">Главная</a></li>
                        <li><a href="#">Возможности</a></li>
                        <li><a href="#">Тарифы</a></li>
                        <li><a href="#">Приложение</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Поддержка</h4>
                    <ul>
                        <li><a href="#">FAQ</a></li>
                        <li><a href="#">Документация</a></li>
                        <li><a href="#">Контакты</a></li>
                    </ul>
                </div>
                <div class="footer-col">
                    <h4>Контакты</h4>
                    <ul>
                        <li><i class="fas fa-phone"></i> +7 (495) 123-45-67</li>
                        <li><i class="fas fa-envelope"></i> info@autodiagnost.ru</li>
                        <li><i class="fas fa-map-marker-alt"></i> Москва, ул. Автодиагностики, 15</li>
                    </ul>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2023 AutoDiagnost. Все права защищены.</p>
            </div>
        </div>
    </footer>

    <script>
        // Простая анимация при скролле
        document.addEventListener('DOMContentLoaded', function() {
            const animateOnScroll = function() {
                const elements = document.querySelectorAll('.feature-card, .app-content');
                
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
        });
    </script>
</body>
</html>
