<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .content {
            padding: 20px;
        }
        .content section {
            margin-bottom: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="content">
        <section id="home">
            <h2>Home</h2>
            <p>This is the home section of the website.</p>
        </section>
        <section id="about">
            <h2>About</h2>
            <p>This is the about section of the website.</p>
        </section>
        <section id="services">
            <h2>Services</h2>
            <p>This is the services section of the website.</p>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>This is the contact section of the website.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 My Website</p>
    </footer>
</body>
</html>
