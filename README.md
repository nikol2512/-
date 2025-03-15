<!DOCTYPE html>
<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>אור של טובה - טיפולים הוליסטיים</title>
    <style>
        /* סגנון כללי */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f0f8ff;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
            overflow-x: hidden;
        }

        /* כותרת ראשית */
        header {
            background: linear-gradient(45deg, #6a5acd, #4682b4);
            padding: 50px;
            color: white;
            text-align: center;
            border-bottom: 5px solid #333;
            animation: fadeIn 2s ease-in-out;
        }

        header h1 {
            margin: 0;
            font-size: 3.5em;
            font-weight: bold;
        }

        header p {
            font-size: 1.3em;
            margin-top: 10px;
            font-weight: lighter;
        }

        /* אנימציות */
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideUp {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        /* כותרות סעיפים */
        h2 {
            color: #4b8b3b;
            font-size: 2.5em;
            margin-bottom: 15px;
            font-weight: bold;
            animation: slideUp 1.5s ease-out;
        }

        /* עיצוב הסקשנים */
        section {
            padding: 30px;
            margin: 20px;
            background-color: #ffffff;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
            animation: slideUp 2s ease-out;
        }

        section:hover {
            transform: scale(1.02);
        }

        section p {
            font-size: 1.2em;
            line-height: 1.8;
            margin-bottom: 20px;
        }

        /* תמונות */
        img {
            width: 100%;
            border-radius: 12px;
            margin-top: 20px;
            transition: transform 0.3s ease;
        }

        img:hover {
            transform: scale(1.05);
        }

        /* רשימות שירותים */
        ul {
            list-style: none;
            padding: 0;
            text-align: left;
            font-size: 1.2em;
        }

        ul li {
            margin: 12px 0;
        }

        /* קישורים */
        a {
            color: #4682b4;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        /* פוטר */
        footer {
            background-color: #6a5acd;
            padding: 15px;
            position: fixed;
            bottom: 0;
            width: 100%;
            color: #fff;
            text-align: center;
            font-size: 1.1em;
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
                font-size: 1em;
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
        <img src="https://via.placeholder.com/800x400/FFD700/000000?text=%D7%98%D7%99%D7%A4%D7%95%D7%9C+%D7%94%D7%95%D7%9C%D7%99%D7%A1%D7%98%D7%99" alt="טיפולים הוליסטיים">
    </section>

    <section id="services">
        <h2>השירותים שלנו</h2>
        <ul>
            <li>טיפולי גוף ונפש</li>
            <li>טיפול בטראומות וחרדות</li>
            <li>הכוונה לטיפול בבעיות זוגיות ושלום בית</li>
        </ul>
        <img src="https://via.placeholder.com/800x400/FFD700/000000?text=%D7%A9%D7%99%D7%A8%D7%95%D7%AA%D7%99%D7%9D+%D7%94%D7%95%D7%9C%D7%99%D7%A1%D7%98%D7%99%D7%99%D7%9D" alt="שירותים הוליסטיים">
    </section>

    <section id="testimonials">
        <h2>עדויות מלקוחות</h2>
        <p>"טיפול מצוין, החזיר לי את השלווה והביטחון!" - יעל</p>
        <p>"תודה טובה, אני מרגיש הרבה יותר טוב!" - אבי</p>
        <img src="https://via.placeholder.com/800x400/FFD700/000000?text=%D7%A2%D7%93%D7%95%D7%99%D7%95%D7%AA+%D7%9E%D7%9C%D7%90%D7%9B%D7%95%D7%AA" alt="עדויות מלקוחות">
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
