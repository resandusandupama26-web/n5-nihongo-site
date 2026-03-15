# n5-nihongo-site<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>N5 Nihongo Scholar</title>
    <style>
        /* This is CSS: It makes the page look pretty */
        body {
            font-family: 'Segoe UI', sans-serif;
            background-color: #f4f7f6;
            margin: 0;
            display: flex;
        }
        
        /* Sidebar Navigation */
        nav {
            width: 250px;
            background-color: #2c3e50;
            color: white;
            height: 100vh;
            padding: 20px;
        }

        nav h1 { font-size: 1.5rem; color: #e74c3c; }

        /* Main Content Area */
        main {
            flex-grow: 1;
            padding: 40px;
        }

        .card-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .kanji-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }

        .kanji-card:hover { transform: translateY(-5px); }

        .big-character { font-size: 3rem; color: #333; }
        
        .label { color: #7f8c8d; font-size: 0.9rem; }
    </style>
</head>
<body>

    <nav>
        <h1>N5 Master</h1>
        <ul>
            <li>Hiragana</li>
            <li>Katakana</li>
            <li><b>Kanji List</b></li>
            <li>Grammar</li>
        </ul>
    </nav>

    <main>
        <h2>Essential N5 Kanji</h2>
        <p>Click a card to see the reading and meaning.</p>

        <div class="card-container">
            <div class="kanji-card">
                <div class="big-character">日</div>
                <div class="label">Sun / Day</div>
                <div class="label"><i>ni / bi</i></div>
            </div>

            <div class="kanji-card">
                <div class="big-character">本</div>
                <div class="label">Book / Origin</div>
                <div class="label"><i>hon</i></div>
            </div>

            <div class="kanji-card">
                <div class="big-character">人</div>
                <div class="label">Person</div>
                <div class="label"><i>hito / jin</i></div>
            </div>
        </div>
    </main>

</body>
</html>
