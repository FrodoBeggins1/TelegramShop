<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Магазин</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f9f9f9;
        }
        header {
            background-color: #0078d7;
            color: white;
            padding: 20px 0;
        }
        .container {
            padding: 20px;
        }
        .product {
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 15px;
            margin: 10px auto;
            max-width: 300px;
            background-color: white;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            margin-top: 15px;
            background-color: #0078d7;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        .button:hover {
            background-color: #005bb5;
        }
    </style>
</head>
<body>
    <header>
        <h1>Добро пожаловать в наш магазин!</h1>
    </header>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Товар 1">
            <h2>Товар 1</h2>
            <p>Цена: 1000 грн</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Товар 2">
            <h2>Товар 2</h2>
            <p>Цена: 2000 грн</p>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Товар 3">
            <h2>Товар 3</h2>
            <p>Цена: 3000 грн</p>
        </div>
        <a class="button" href="https://t.me/ВашЛогинМенеджера">Связаться с менеджером</a>
    </div>
</body>
</html>
