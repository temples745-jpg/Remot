<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ремонт и отделка в Гагаузии | Комрат, Чадыр-Лунга, Вулканешты</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --primary: #e67e22;
            --dark: #2c3e50;
            --light: #f4f7f6;
            --white: #ffffff;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            line-height: 1.6;
            color: var(--dark);
            background-color: var(--light);
        }

        header {
            background: var(--dark);
            color: var(--white);
            padding: 1rem 5%;
            position: fixed;
            width: 90%;
            top: 0;
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }

        .logo { font-size: 1.5rem; font-weight: bold; color: var(--primary); }

        .hero {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1581094794329-c8112a89af12?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');
            background-size: cover;
            background-position: center;
            height: 80vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: var(--white);
            padding: 0 20px;
            margin-top: 60px;
        }

        .hero h1 { font-size: 3rem; margin-bottom: 1rem; }
        .hero p { font-size: 1.2rem; max-width: 800px; }

        .btn {
            background: var(--primary);
            color: white;
            padding: 15px 30px;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            margin-top: 20px;
            display: inline-block;
            transition: 0.3s;
        }
        .btn:hover { background: #d35400; }

        .section { padding: 4rem 5%; }
        .section-title { text-align: center; margin-bottom: 3rem; }
        .section-title h2 { font-size: 2.5rem; color: var(--dark); }
        .section-title div { width: 80px; height: 4px; background: var(--primary); margin: 10px auto; }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .service-card {
            background: var(--white);
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            transition: 0.3s;
        }
        .service-card:hover { transform: translateY(-10px); }
        .service-card i { font-size: 2.5rem; color: var(--primary); margin-bottom: 1rem; }
        .service-card h3 { margin-bottom: 1rem; }

        .regions {
            background: var(--dark);
            color: white;
            text-align: center;
        }
        .region-list {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
            margin-top: 20px;
        }
        .region-item { background: rgba(255,255,255,0.1); padding: 10px 25px; border-radius: 20px; }

        footer { background: #1a252f; color: white; text-align: center; padding: 2rem; }

        @media (max-width: 768px) {
            .hero h1 { font-size: 2rem; }
            header { flex-direction: column; text-align: center; width: 100%; padding: 1rem 0; }
        }
    </style>
</head>
<body>

    <header>
        <div class="logo">МАСТЕР ГАГАУЗИИ</div>
        <div class="contact-info">📞 +373 (XX) XX-XX-XX</div>
    </header>

    <section class="hero">
        <h1>Ремонт и отделка под ключ</h1>
        <p>Профессиональные строительные услуги в Комрате, Чадыр-Лунге и Вулканештах. От демонтажа до фильтров для воды и септиков.</p>
        <a href="#contact" class="btn">Вызвать замерщика</a>
    </section>

    <section class="section" id="services">
        <div class="section-title">
            <h2>Наши услуги</h2>
            <div></div>
        </div>
        <div class="services-grid">
            <div class="service-card">
                <i class="fas fa-hammer"></i>
                <h3>Демонтаж и Гипсокартон</h3>
                <p>Снос старых конструкций, возведение стен, перегородок и потолков любой сложности.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-bolt"></i>
                <h3>Электрика</h3>
                <p>Полная замена проводки, установка щитков, розеток и освещения по стандартам безопасности.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-faucet"></i>
                <h3>Сантехника</h3>
                <p>Монтаж труб, установка ванн, унитазов, инсталляций и душевых кабин.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-border-all"></i>
                <h3>Плитка</h3>
                <p>Укладка плитки и керамогранита. Запил под 45°, работа с крупным форматом.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-water"></i>
                <h3>Септики и Дренаж</h3>
                <p>Обустройство автономной канализации и систем водоотведения для частных домов.</p>
            </div>
            <div class="service-card">
                <i class="fas fa-filter"></i>
                <h3>Фильтры для воды</h3>
                <p>Установка систем очистки и обратного осмоса для получения чистой питьевой воды.</p>
            </div>
        </div>
    </section>

    <section class="section regions">
        <h2>Работаем в 3-х районах</h2>
        <div class="region-list">
            <div class="region-item">📍 Комратский район</div>
            <div class="region-item">📍 Чадыр-Лунгский район</div>
            <div class="region-item">📍 Вулканештский район</div>
        </div>
    </section>

    <section class="section" id="contact" style="text-align: center;">
        <div class="section-title">
            <h2>Оставить заявку</h2>
            <div></div>
        </div>
        <p>Нужен качественный ремонт? Свяжитесь с нами прямо сейчас!</p>
        <div style="margin-top: 20px;">
            <p><strong>Телефон:</strong> +373 (номер)</p>
            <p><strong>Viber / WhatsApp:</strong> Доступны 24/7</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2026 Ремонт Гагаузия. Все права защищены.</p>
    </footer>

</body>
</html>
