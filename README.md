<style>
    :root {
        --primary-color: #3498db;
        --dark-color: #2c3e50;
        --light-color: #ecf0f1;
    }
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        line-height: 1.6;
        max-width: 800px;
        margin: 0 auto;
        padding: 20px;
        color: #333;
    }
    header {
        text-align: center;
        margin-bottom: 30px;
        border-bottom: 2px solid var(--primary-color);
        padding-bottom: 20px;
    }
    h1 {
        color: var(--dark-color);
        font-size: 2.5em;
    }
    h2 {
        color: var(--primary-color);
        border-left: 4px solid var(--primary-color);
        padding-left: 10px;
    }
    a {
        color: var(--primary-color);
        text-decoration: none;
    }
    a:hover {
        text-decoration: underline;
    }
    ul {
        list-style-type: square;
    }
    .section {
        margin-bottom: 30px;
    }
    @media (max-width: 600px) {
        body { padding: 10px; }
        h1 { font-size: 2em; }
    }
</style>
