<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>رزومه آنلاین | مریم رضایی</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <h1>مریم رضایی</h1>
        <p>توسعه‌دهنده فرانت‌اند</p>
    </header>

    <main>
        <section class="about">
            <h2>درباره من</h2>
            <p>علاقه‌مند به توسعه وب و یادگیری فناوری‌های جدید. این صفحه نمونه‌ای از توانایی‌های من در HTML/CSS و Git است.</p>
        </section>

        <section class="skills">
            <h2>مهارت‌ها</h2>
            <ul>
                <li>HTML5, CSS3</li>
                <li>JavaScript (مقدماتی)</li>
                <li>Git & GitHub</li>
            </ul>
        </section>
    </main>

    <footer class="footer">
        <a href="https://github.com/marygit2022" target="_blank">پروفایل GitHub من</a>
    </footer>
</body>
</html>
/* Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    background-color: #f9f9f9;
    color: #333;
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    text-align: center;
}

.header {
    margin-bottom: 2rem;
    padding-bottom: 1rem;
    border-bottom: 2px solid #3498db;
}

h1 {
    color: #2c3e50;
    font-size: 2.5rem;
}

h2 {
    color: #3498db;
    margin: 1.5rem 0;
}

ul {
    list-style: none;
}

ul li {
    background: #ecf0f1;
    margin: 0.5rem 0;
    padding: 0.5rem;
    border-radius: 5px;
}

.footer {
    margin-top: 2rem;
    padding-top: 1rem;
    border-top: 1px solid #ddd;
}

.footer a {
    color: #3498db;
    text-decoration: none;
}

.footer a:hover {
    text-decoration: underline;
}@media (max-width: 600px) {
    body {
        padding: 10px;
    }
    h1 {
        font-size: 2rem;
    }
}<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
<ul>
    <li><i class="fab fa-html5"></i> HTML5</li>
    <li><i class="fab fa-css3-alt"></i> CSS3</li>
    <li><i class="fab fa-js"></i> JavaScript</li>
    <li><i class="fab fa-git"></i> Git</li>
</ul>
