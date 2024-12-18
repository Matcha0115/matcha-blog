<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Matcha的部落格</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        nav {
            background: #444;
            padding: 0.5rem 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 1rem;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            max-width: 800px;
            margin: 2rem auto;
            padding: 1rem;
            background: #fff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .post {
            margin-bottom: 2rem;
        }
        .post h2 {
            margin-top: 0;
        }
        footer {
            text-align: center;
            padding: 1rem 0;
            background: #333;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Blog</h1>
    </header>
    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>
    <div class="container">
        <div class="post">
            <h2>Post Title 1</h2>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque vitae turpis ut lorem vehicula dapibus.</p>
            <a href="#">Read more...</a>
        </div>
        <div class="post">
            <h2>Post Title 2</h2>
            <p>Curabitur ac lacus at nisi vulputate vehicula. Praesent nec eros ut nulla faucibus tincidunt.</p>
            <a href="#">Read more...</a>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 My Blog. All rights reserved.</p>
    </footer>
</body>
</html>
