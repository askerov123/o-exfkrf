<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Обучение HTML и CSS</title>
    <link rel="stylesheet" href="style.css">
</head>
<body><!DOCTYPE html>
<html lang="ru">
<head>
 <h1>Добро пожаловать в мир HTML и CSS!</h1>
         <что-бы было легче используйте нейросети по жиланию>
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Галерея изображений</title>
    <style>
        /* Общие стили */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f9;
        }
        h1 {
            text-align: center;
            color: #333;
        }

        /* Стили галереи */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .gallery-item {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            background: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }

        .gallery-item:hover {
            transform: scale(1.03);
        }

        .gallery-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            display: block;
        }

        .gallery-item p {
            padding: 10px;
            text-align: center;
            margin: 0;
            font-size: 14px;
            color: #555;
        }

        /* Подвал */
        footer {
            text-align: center;
            margin-top: 30px;
            padding: 10px;
            color: #666;
        }
    </style>
</head>
<body>
    <h1>Галерея изображений</h1>
    
    <div class="gallery">
        <!-- Изображение 1 -->
        <div class="gallery-item">
            <a href="https://as2.ftcdn.net/v2/jpg/01/04/97/89/1000_F_104978944_wdnZR5EZY1hpHtS6BXWdGTMWQURS09Cn.jpg" target="_blank">
                 <img src="https://as2.ftcdn.net/v2/jpg/01/04/97/89/1000_F_104978944_wdnZR5EZY1hpHtS6BXWdGTMWQURS09Cn.jpg" alt="Пример">
            </a>
            <p>Горный пейзаж</p>
        </div>

        <!-- Изображение 2 -->
        <div class="gallery-item">
            <a href="https://as2.ftcdn.net/v2/jpg/01/04/97/89/1000_F_104978944_wdnZR5EZY1hpHtS6BXWdGTMWQURS09Cn.jpg">
                 <img src="https://as2.ftcdn.net/v2/jpg/01/04/97/89/1000_F_104978944_wdnZR5EZY1hpHtS6BXWdGTMWQURS09Cn.jpg" alt="Пример">
            </a>
            <p>Морской закат</p>
        </div>

            <p>Зеленый лес</p>
        </div>

        <!-- Изображение 4 -->
        <div class="gallery-item">
            <a href="https://as2.ftcdn.net/v2/jpg/01/04/97/89/1000_F_104978944_wdnZR5EZY1hpHtS6BXWdGTMWQURS09Cn.jpg" target="_blank">
                <img src="https://as2.ftcdn.net/v2/jpg/01/04/97/89/1000_F_104978944_wdnZR5EZY1hpHtS6BXWdGTMWQURS09Cn.jpg" alt="Пример">
            </a>

<a href="https://example.com/full-size.jpg">
  <img src="https://as2.ftcdn.net/v2/jpg/01/04/97/89/1000_F_104978944_wdnZR5EZY1hpHtS6BXWdGTMWQURS09Cn.jpg" alt="Пример">
</a>

            <p>Ночной город</p>
        </div>
    </div>

    <footer>
        © 2024 Галерея изображений. Нажмите на фото для просмотра в полном размере.
    </footer>
</body>
</html>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Пример HTML-таблицы</title>
    <style>
        /* Стили для таблицы */
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table {
            width: 80%;
            border-collapse: collapse;
            margin: 20px auto;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #0066cc;
            color: white;
        }
        tr:nth-child(even) {
            background-color: #f2f2f2;
        }
        tr:hover {
            background-color: #ddd;
        }
        caption {
            font-weight: bold;
            font-size: 1.2em;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <h1>Пример HTML-таблицы</h1>
    
    <table>
        <caption>Список студентов</caption>
        <thead>
            <tr>
                <th>№</th>
                <th>Имя</th>
                <th>Фамилия</th>
                <th>Курс</th>
                <th>Оценка</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1</td>
                <td>Иван</td>
                <td>Петров</td>
                <td>HTML/CSS</td>
                <td>5</td>
            </tr>
            <tr>
                <td>2</td>
                <td>Мария</td>
                <td>Сидорова</td>
                <td>JavaScript</td>
                <td>4</td>
            </tr>
            <tr>
                <td>3</td>
                <td>Алексей</td>
                <td>Иванов</td>
                <td>Python</td>
                <td>5</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <td colspan="4">Средняя оценка:</td>
                <td>4.67</td>
            </tr>
        </tfoot>
    </table>

    <h2>Ключевые теги для таблиц:</h2>
    <ul>
        <li><code>&lt;table&gt;</code> — контейнер таблицы.</li>
        <li><code>&lt;caption&gt;</code> — заголовок таблицы.</li>
        <li><code>&lt;thead&gt;</code> — шапка таблицы (заголовки столбцов).</li>
        <li><code>&lt;tbody&gt;</code> — основное тело таблицы.</li>
        <li><code>&lt;tfoot&gt;</code> — подвал таблицы (итоги, примечания).</li>
        <li><code>&lt;tr&gt;</code> — строка таблицы.</li>
        <li><code>&lt;th&gt;</code> — ячейка-заголовок (жирный текст).</li>
        <li><code>&lt;td&gt;</code> — обычная ячейка.</li>
        <li><code>colspan</code> — объединение ячеек по горизонтали.</li>
        <li><code>rowspan</code> — объединение ячеек по вертикали.</li>
    </ul>
</body>
</html>
    <header>
       
        <nav>
            <ul>
                <li><a href="#html">HTML</a></li>
                <li><a href="#css">CSS</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="html">
            <h2>Основы HTML</h2>
            <p>HTML (HyperText Markup Language) — это язык разметки для создания веб-страниц.</p>
            
<pre>

<code>&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
    &lt;title&gt;Моя страница&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
    &lt;h1&gt;Привет, мир!&lt;/h1&gt;
&lt;/body&gt;
&lt;/html&gt;</code>
</pre>
        </section>

        <section id="css">
            <h2>Основы CSS</h2>
            <p>CSS (Cascading Style Sheets) — язык стилей для оформления HTML-документов.</p>
            <pre><code>
</code></pre>
        </section>

        <section id="contact">
               
        </section>
    </main>

    <footer>
        <p>© 2024 Обучение HTML и CSS. Все права защищены.</p>
    </footer>
</body>
</html>
