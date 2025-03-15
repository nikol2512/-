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
            transition: background-color 0.3s ease;
        }

        /* כותרת ראשית */
        header {
            background: linear-gradient(45deg, #FBB034, #FFDD00);
            padding: 80px 20px;
            color: white;
            text-align: center;
            position: relative;
            animation: fadeIn 2s ease-in-out;
        }

        header h1 {
            margin: 0;
            font-size: 3.5em;
            font-weight: bold;
            letter-spacing: 2px;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.3);
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
            color: #FBB034;
            font-size: 2.5em;
            margin-bottom: 15px;
            font-weight: bold;
            animation: slideUp 1.5s ease-out;
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
            font-size: 1.3em;
        }

        ul li {
            margin: 12px 0;
            padding-left: 25px;
            position: relative;
        }

        ul li:before {
            content: '✔';
            position: absolute;
            left: 0;
            color: #FBB034;
            font-size: 1.5em;
            top: 0;
        }

        /* קישורים */
        a {
            color: #FFDD00;
            text-decoration: none;
            font-weight: bold;
            padding: 8px 16px;
            border-radius: 25px;
            background-color: #4682b4;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        a:hover {
            background-color: #FFDD00;
            color: #333;
        }

        /* פוטר */
        footer {
            background-color: #6a5acd;
            padding: 20px;
            position: fixed;
            bottom: 0;
            width: 100%;
            color: #fff;
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
        <img src="https://images.unsplash.com/photo-1531308581242-42916e0b6355?crop=entropy&cs=tinysrgb&fit=max&ixid=MnwzNjA0OXwwfDF8c2VhcmNofDJ8fG9yaWVuZ3xlbnwwfDB8fHwyfHw%3D&ixlib=rb-1.2.1&q=80&w=1080" alt="טיפולים הוליסטיים">
    </section>

    <section id="services">
        <h2>השירותים שלנו</h2>
        <ul>
            <li>טיפולי גוף ונפש</li>
            <li>טיפול בטראומות וחרדות</li>
            <li>הכוונה לטיפול בבעיות זוגיות ושלום בית</li>
        </ul>
        <img src="https://images.unsplash.com/photo-1506514500612-bda68c052e6f?crop=entropy&cs=tinysrgb&fit=max&ixid=MXwyMDg3fHwyfDF8c2VhcmNofDd8fGZlZWFsJTIwbGVpc3VyZXxlbnwwfDB8fHwyfHw%3D&ixlib=rb-1.2.1&q=80&w=1080" alt="שירותים הוליסטיים">
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
