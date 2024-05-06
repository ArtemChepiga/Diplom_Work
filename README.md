<!DOCTYPE html>
<html lang="en">
<style>
        /* Стилі для навігаційного меню */
        nav {
            background-color: #1E1E1E;
            overflow: hidden;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        nav ul li {
            float: left;
            margin-right: 20px;
        }
        nav ul li a {
            display: block;
            color: #FFFFFF;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
            font-size: 16px;
            font-weight: bold;
        }
        nav ul li a:hover {
            background-color: #FFFFFF;
            color: #1E1E1E;
            border-radius: 5px;
        }
        /* Стилі для основного контенту */
        .content {
            padding: 20px;
            text-align: center;
            color: #1E1E1E;
            font-family: Arial, sans-serif;
        }
        /* Стилі для підвалу */
        footer {
            background-color: #1E1E1E;
            color: #FFFFFF;
            padding: 10px;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
            font-size: 14px;
        }
        h1 {
            color: #1E1E1E;
        }
    </style>
</head>
<body>
    <nav>
        <ul>
            <li><a href="index (2).html">Головна</a></li>
            <!-- Показувати посилання на реєстрацію та вхід тільки якщо користувач не авторизований -->
    
            <li><a href="index (3).html">Регестрація</a></li>
            <li><a href="index (1).html">Увійти</a></li>
            {% endif %}
            <!-- Показувати посилання на вихід тільки якщо користувач авторизований -->
            <li><a href="/logout">Створити напрямок</a></li>
            {% endif %}
            <!-- Додайте інші посилання на ваш вміст тут -->
        </ul>
    </nav>
<body>

<div class="container">
    <h2>Login</h2>
    <form action="/login" method="POST">
        <label for="username">Username:</label><br>
        <input type="text" id="username" name="username" required><br>
        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" required><br>
        <input type="submit" value="Login">
        <!-- Доданий блок для відображення повідомлення про помилку -->
    
    </form>
</div>

</body>
</html>
