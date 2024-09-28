<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>شركة بدر الجيعان للمحاماة</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background-color: #f9f9f9;
            color: #333;
            overflow-x: hidden;
        }

        header {
            background-color: #222;
            color: #fff;
            padding: 0; /* إزالة الحواف العلوية والسفلية */
            text-align: center;
        }

        header img {
            width: 100%;
            height: auto;
            display: block;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
            padding: 15px 0;
        }

        nav a {
            color: #fff;
            padding: 15px 30px;
            text-decoration: none;
            font-size: 1.2em;
        }

        nav a:hover {
            background-color: #555;
        }

        .hero {
            background-color: #f5f5f5;
            text-align: center;
            padding: 100px 20px;
        }

        .hero h2 {
            font-size: 2.5em;
            color: #000;
        }

        .hero p {
            font-size: 1.2em;
            color: #666;
            margin-top: 20px;
        }

        .hero button {
            padding: 15px 30px;
            background-color: #222;
            color: #fff;
            border: none;
            font-size: 1.2em;
            margin-top: 30px;
            cursor: pointer;
        }

        .services {
            display: flex;
            justify-content: center;
            padding: 50px 20px;
            background-color: #fff;
        }

        .service {
            flex: 1;
            max-width: 300px;
            text-align: center;
            margin: 10px;
        }

        .service h3 {
            font-size: 1.8em;
            margin-bottom: 15px;
        }

        .service p {
            font-size: 1.1em;
            color: #666;
        }

        .about {
            padding: 50px 20px;
            background-color: #f9f9f9;
            text-align: center;
        }

        .about h2 {
            font-size: 2.2em;
            margin-bottom: 20px;
        }

        .about p {
            font-size: 1.1em;
            line-height: 1.8;
            color: #555;
            max-width: 800px;
            margin: 0 auto;
        }

        .gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            padding: 50px 20px;
            background-color: #fff;
        }

        .gallery img {
            max-width: 45%;
            margin: 10px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        footer {
            background-color: #222;
            color: #fff;
            padding: 30px 0;
            text-align: center;
        }

        footer p {
            margin: 0;
            font-size: 1.1em;
        }

        .contact {
            text-align: center;
            margin: 20px 0;
        }

        .contact h3 {
            font-size: 30px;
        }

        .whatsapp-icon {
            position: absolute; /* تغيير إلى absolute */
            bottom: 20px; /* مسافة عن الأسفل */
            right: 20px; /* مسافة عن اليمين */
            width: 60px;
            transition: transform 0.3s;
        }

        .whatsapp-icon img {
            width: 100%;
        }

        /* Animation for slide */
        @keyframes slide {
            0% {
                transform: translateY(0);
            }
            100% {
                transform: translateY(-10px);
            }
        }

        .whatsapp-icon:hover {
            animation: slide 0.5s forwards;
        }

        @media (max-width: 768px) {
            .hero h2 {
                font-size: 2em;
            }

            .services {
                flex-direction: column;
            }

            .service {
                max-width: 100%;
                margin: 20px 0;
            }

            .gallery img {
                max-width: 90%;
            }
        }
    </style>
</head>
<body>

    <header>
        <img src="https://madray20060.github.io/Madray2006.github.io/IMG_3433.png" alt="Logo">
    </header>

    <nav>
        <a href="#services">الخدمات</a>
        <a href="#about">من نحن</a>
        <a href="#contact">تواصل معنا</a>
    </nav>

    <section class="hero">
        <h2>نحن هنا لحمايتك قانونيًا</h2>
        <p>شركة بدرالجيعان للمحاماة تقدم حلولًا قانونية شاملة للأفراد والشركات مع فريق محترف من المحامين المتخصصين في مختلف المجالات القانونية.</p>
        <button>احجز استشارة الآن</button>
    </section>

    <section class="services" id="services">
        <div class="service">
            <h3>استشارات قانونية</h3>
            <p>نحن نقدم استشارات قانونية شاملة تغطي مختلف القضايا القانونية، بما في ذلك العقود والشؤون التجارية والقضايا الجنائية والمدنية.</p>
        </div>
        <div class="service">
            <h3>الدفاع في القضايا</h3>
            <p>فريقنا من المحامين المتخصصين مستعد للدفاع عن حقوقك في جميع أنواع القضايا أمام المحاكم.</p>
        </div>
        <div class="service">
            <h3>إدارة العقود</h3>
            <p>نقدم خدمات متخصصة في إعداد ومراجعة العقود القانونية لضمان حماية حقوق عملائنا في كل مرحلة من مراحل العقود.</p>
        </div>
    </section>

    <section class="about" id="about">
        <h2>من نحن</h2>
        <p>شركة بدرالجيعان للمحاماة هي شركة قانونية رائدة تقدم خدمات قانونية متكاملة للأفراد والشركات. نحن نعمل بتفانٍ لتقديم أفضل الحلول القانونية لكل عميل، مع التركيز على النزاهة والشفافية في كل خطوة. فريقنا من المحامين ذوي الخبرة يتفهمون التعقيدات القانونية ويمكنهم مساعدتك في مواجهة أي تحدي قانوني.</p>
    </section>

    <!-- قسم الصور -->
    <section class="gallery">
        <img src="https://madray20060.github.io/Madray2006.github.io/IMG_3436.jpeg" alt="صورة 1">
        <div class="whatsapp-icon">
            <a href="https://api.whatsapp.com/send?phone=966533630037&text=السلام%20عليكم%20ورحمة%20الله%20وبركاته" target="_blank">
                <img src="https://madray20060.github.io/Madray2006.github.io/IMG_3435.png" alt="WhatsApp Icon">
            </a>
        </div>
    </section>

    <section class="contact" id="contact">
        <h3>اتصل بنا</h3>
    </section>

    <footer>
        <p>  شركة بدر الجيعان للمحاماة.</p> 
        <p> 0533630037 </p> 
    </footer>

</body>
</html>
