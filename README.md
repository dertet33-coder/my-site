
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Мой первый сайт</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #05051c, #123c70);
            color: white;
            text-align: center;
        }
        header {
            padding: 60px 15px;
        }
        h1 {
            font-size: 36px;
            color: #42caff;
        }
        .card {
            background: #172b50;
            margin: 20px;
            padding: 25px;
            border-radius: 20px;
        }
        button {
            padding: 14px 25px;
            border: none;
            border-radius: 12px;
            background: #168cff;
            color: white;
            font-size: 17px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать!</h1>
        <p>Это мой первый сайт на GitHub</p>
    </header>

    <div class="card">
        <h2>Мой проект</h2>
        <p>Здесь будет размещена информация о моём проекте.</p>
        <button onclick="alert('Привет!')">
            Нажми сюда
        </button>
    </div>
</body>
</html>
