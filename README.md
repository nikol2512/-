<html lang="he">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>אור של טובה - טיפולים הוליסטיים</title>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&family=Roboto:wght@300;400;700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Roboto', sans-serif;
            background: #f2f2f2;
            color: #333;
            overflow-x: hidden;
        }

        /* כותרת ראשית */
        header {
            position: relative;
            height: 100vh;
            background: url('https://images.unsplash.com/photo-1506748686212-e5a5c07583c7?crop=entropy&cs=tinysrgb&fit=max&ixid=MXwyMDg3fHwyfDF8c2VhcmNofDJ8fG9yaWVuZ3xlbnwwfDB8fHwyfHw%3D&ixlib=rb-1.2.1&q=80&w=1080') center center no-repeat;
            background-size: cover;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 0 20px;
        }

        header h1 {
            font-size: 4em;
            margin: 0;
            letter-spacing: 2px;
            text-transform: uppercase;
            font-weight: 700;
            animation: fadeIn 1.5s ease-out;
        }

        header p {
            font-size: 1.5em;
            margin-top: 10px;
            font-weight: 300;
            animation: fadeIn 2s ease-out;
        }

        /* אנימציה */
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(-50px); }
            100% { opacity: 1; transform: translateY(0); }
        }

        /* כרטיסי שירותים */
        .service-card {
        
