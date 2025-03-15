=<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>אור של טובה - טיפולים הוליסטיים</title>
    <style>
        /* סגנון כללי */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
            overflow-x: hidden;
            transition: background-color 0.3s ease;
        }

        /* כותרת ראשית */
        header {
            background: linear-gradient(45deg, #FF7F50, #FFDD00);
            padding: 100px 20px;
            color: white;
            text-align: center;
            animation: fadeIn 2s ease-in-out;
            position: relative;
        }

        header h1 {
            margin: 0;
            font-size: 3.5em;
            font-weight: bold;
            letter-spacing: 2px;
            text-shadow: 3px 3px 6px rgba(0, 0, 0, 0.2);
        }

        header p {
            font-size: 1.5em;
            margin-top: 10px;
            font-weight: lighter;
        }

        /* אנימציות */
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        /* כותרות סעיפים */
        h2 {
            color: #FF7F50;
            font-size: 2.5em;
            margin-bottom: 15px;
            font-weight: bold;
            animation: slideUp 1.5s ease-out;
        }

        @keyframes slideUp {
            0% { opacity: 0; transform: translateY(30px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        /* עיצוב הסקשנים */
        section {
            padding: 40px;
            margin: 30px auto;
            background-color: white;
            border-radius: 15px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            animation: slideUp 2s ease-out;
            max-width: 1000px;
            text-align: center;
        }

        section:hover {
            transform: scale(1.05);
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
        }

        section p {
            font-size: 1.3em;
            line-height: 1.8;
            margin-bottom: 20px;
            color: #555;
        }

        /* שירותים כרטיסים */
        .service-card {
            background-color: #f9f9f9;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            margin: 20px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .service-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
        }

        .service-card h3 {
            font-size: 1.8em;
            color: #FF7F50;
        }

        .service-card p {
            font-size: 1.2em;
            color: #333;
        }

        /* כפתורים */
        a {
            color: #ffffff;
            text-decoration: none;
            font-weight: bold;
            padding: 15px 30px;
            background-color: #FF7F50;
            border-radius: 25px;
            transition: background-color 0.3s ease, color 0.3s ease;
            display: inline-block;
            margin-top: 20px;
        }

        a:hover {
            background-color: #FFDD00;
            color: #333;
        }

        /* עיצוב תמונות */
        img {
            width: 100%;
            border-radius: 12px;
            margin-top: 20px;
            transition: transform 0.3s ease;
        }

        img:hover {
            transform: scale(1.05);
        }

        /* פוטר */
        footer {
            background-color: #FF7F50;
            padding: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
            color: white;
            text-align: center;
            font-size: 1.2em;
        }

        footer p {
            margin: 0;
        }

        /* עיצוב רספונסיבי */
        @media screen and (max-width: 768px) {
            header h1 {
                font-size: 2.2em;
            }

            section {
                margin: 10px;
                padding: 20px;
            }

            h2 {
                font-size: 1.8em;
            }

            p {
                font-size: 1.1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>אור של טובה - טיפולים הוליסטיים גוף ונפש</h1>
        <p>המסע שלך לרוגע, שלמות ושלווה</p>
    </header>

    <section id="about">
        <h2>על טובה</h2>
        <p>טובה מומחית בתחום טיפולים הוליסטיים, מטפלת בטראומות, חרדות, חוסר נחת, ושלום בית.</p>
        <p>עם ניסיון רחב בעבודה עם מגוון בעיות, היא כאן כדי להחזיר לך את השלווה והאיזון בחיים.</p>
        <img src="https://images.unsplash.com/photo-1531308581242-42916e0b6355?crop=entropy&cs=tinysrgb&fit=max&ixid=MnwzNjA0OXwwfDF8c2VhcmNofDJ8fG9yaWVuZ3xlbnwwfDB8fHwyfHw%3D&ixlib=rb-1.2.1&q=80&w=1080" alt="טיפול הוליסטי">
    </section>

    <section id="services">
        <h2>השירותים שלנו</h2>
        <div class="service-card">
            <h3>טיפולי גוף ונפש</h3>
            <p>החזרת האיזון בין גוף לנפש. טיפולים מותאמים אישית לכל אדם.</p>
        </div>
        <div class="service-card">
            <h3>טיפול בטראומות וחרדות</h3>
            <p>עבודה עם טראומות וחרדות באמצעות טכניקות הוליסטיות מרגיעות.</p>
        </div>
        <div class="service-card">
            <h3>הכוונה לטיפול בבעיות זוגיות ושלום בית</h3>
            <p>הכוונה ותמיכה לזוגות לשיפור התקשורת והחיים המשותפים.</p>
        </div>
        <a href="#contact">צרו קשר עכשיו</a>
    </section>

    <section id="testimonials">
        <h2>עדויות מלקוחות</h2>
        <p>"טיפול מצוין, החזיר לי את השלווה והביטחון!" - יעל</p>
        <p>"תודה טובה, אני מרגיש הרבה יותר טוב!" - אבי</p>
        <img src="https://images.unsplash.com/photo-1605397152460-c31a4761d8a9?crop=entropy&cs=tinysrgb&fit=max&ixid=MXwyMDg3fHwyfDF8c2VhcmNofDd8fGZlZWFsJTIwbGVpc3VyZXxlbnwwfDB8fHwyfHw%3D&ixlib=rb-1.2.1&q=80&w=1080" alt="עדויות מלקוחות">
    </section>

    <section id="contact">
        <h2>יצירת קשר</h2>
        <p>צרו קשר עם טובה דרך ווטסאפ או טלפון:</p>
        <ul>
            <li><a href="https://wa.me/1234567890" target="_blank">צור קשר בוואטסאפ</a></li>
            <li><a href="tel:+1234567890">שיחת טלפון</a></li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2025 אור של טובה - טיפולים הוליסטיים</p>
    </footer>
</body>
</html>
