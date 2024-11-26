# Web-Technologies-Assignment-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="A simple car webpage  for demonstration purposes.">
    <title>Rides Webpage </title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header {
            background: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
        }
        section {
            padding: 20px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        img {
            max-width: 100%;
            height: auto;
        }
        @media (max-width: 600px) {
            nav {
                display: flex;
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to My Webpage</h1>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <article>
        <h2>About This Page</h2>
        <p>This is a car webpage created for demonstration purposes featuring a Ford mustang, BMW X4 CSL.</p>
    </article>
</section>

<section id="gallery">
    <article>
        <h2>Image Gallery</h2>
        <p>Here are some images:</p>
        <ul>
            <li><img src="pbcswb.jpg" alt="Ford Mustang "></li>
            <li><img src="20241106_094641.jpg" alt="Mercedes AMG "></li>
            <li><img src="maxresdefault(1).jpg" alt="BMW X4"></li>
        </ul>
    </article>
</section>

<section id="contact">
    <article>
        <h2>Contact Me</h2>
        <p>If you'd like to get in touch, please <a href="systemstopboy@gmail.com">email me</a>.</p>
    </article>
</section>

<footer>
    <p>&copy; 2024 My Car Webpage</p>
</footer>

</body>
</html>
