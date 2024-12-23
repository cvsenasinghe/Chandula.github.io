<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Meme Lords</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(270deg, #ff7e5f, #feb47b, #6a11cb, #2575fc);
            background-size: 800% 800%;
            animation: moveGradient 10s ease infinite;
            color: #333;
        }
        @keyframes moveGradient {
            0% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
            100% {
                background-position: 0% 50%;
            }
        }
        header {
            background: linear-gradient(270deg, #ff7e5f, #feb47b, #6a11cb, #2575fc);
            background-size: 800% 800%;
            animation: moveGradient 10s ease infinite;
            color: white;
            padding: 20px;
            text-align: center;
            border-radius: 0 0 25px 25px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        nav {
            background: linear-gradient(270deg, #ff7e5f, #feb47b, #6a11cb, #2575fc);
            background-size: 800% 800%;
            animation: moveGradient 10s ease infinite;
            overflow: hidden;
            border-radius: 25px;
            margin: 20px auto;
            max-width: 90%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            border-radius: 25px;
            transition: all 0.3s;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .content {
            padding: 20px;
            text-align: center;
            max-width: 90%;
            margin: 20px auto;
            border-radius: 25px;
            background-color: rgba(255, 255, 255, 0.9);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .meme {
            margin: 20px auto;
            border: 2px solid #ddd;
            border-radius: 15px;
            padding: 10px;
            background-color: white;
            max-width: 500px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s;
        }
        .meme:hover {
            transform: scale(1.05);
        }
        .meme img {
            max-width: 100%;
            border-radius: 10px;
        }
        footer {
            background: linear-gradient(270deg, #ff7e5f, #feb47b, #6a11cb, #2575fc);
            background-size: 800% 800%;
            animation: moveGradient 10s ease infinite;
            text-align: center;
            padding: 10px;
            color: white;
            border-radius: 25px 25px 0 0;
            position: fixed;
            bottom: 0;
            width: 100%;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.2);
        }
        h2 {
            color: #444;
        }
    </style>
</head>
<body>

<header>
    <h1>The Meme Lords</h1>
    <p>Your daily dose of fun and memes!</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#memes">Memes</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
</nav>

<div class="content">
    <section id="memes">
        <h2>Featured Memes</h2>
        <div class="meme">
            <img src="https://i.imgflip.com/5xk28v.jpg" alt="Funny Meme">
            <p>"When you realize it's Monday tomorrow..."</p>
        </div>
        <div class="meme">
            <img src="https://i.imgflip.com/5xk2a2.jpg" alt="Cat Meme">
            <p>"The face you make when food arrives."</p>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Welcome to The Meme Lords! We're dedicated to sharing the funniest memes on the internet. Join us for laughs and good vibes.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email us at <a href="mailto:contact@memelords.com">contact@memelords.com</a> or follow us on social media.</p>
    </section>
</div>

<footer>
    <p>&copy; 2024 The Meme Lords. All Rights Reserved.</p>
</footer>

</body>
</html>
