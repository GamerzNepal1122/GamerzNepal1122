- 👋 Hi, I’m @GamerzNepal1122
- 👀 I’m interested in making Games
- 🌱 I’m currently learning C and C# and CS
- 💞️ I’m looking to collaborate on Some Developer
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game Artist Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #333;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #0066cc 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header li {
            float: left;
            display: inline;
            padding: 0 20px 0 20px;
        }
        header #branding {
            float: left;
        }
        header #branding h1 {
            margin: 0;
        }
        header nav {
            float: right;
            margin-top: 10px;
        }
        header .highlight,
        header .current a {
            color: #e8491d;
            font-weight: bold;
        }
        header a:hover {
            color: #ffffff;
            font-weight: bold;
        }
        .showcase {
            min-height: 400px;
            background: url('banner-image.jpg') no-repeat 0 -400px;
            text-align: center;
            color: #ffffff;
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .showcase p {
            font-size: 20px;
        }
        .gallery {
            margin: 20px 0;
        }
        .gallery img {
            width: 23%;
            border-radius: 5px;
            margin: 1%;
            float: left;
            transition: opacity 0.3s ease; /* New transition effect */
        }
        .gallery img:hover {
            opacity: 0.7; /* Improved hover effect */
        }
        footer {
            background: #333;
            color: #ffffff;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div id="branding">
                <h1><span class="highlight">My</span> Game Art Portfolio</h1>
            </div>
            <nav>
                <ul>
                    <li class="current"><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#gallery">Gallery</a></li>
                    <li><a href="#contact">Contact</a></li> <!-- Added Contact link -->
                </ul>
            </nav>
        </div>
    </header>
    <div class="showcase">
        <h1>Welcome to My Portfolio</h1>
        <p>Showcasing my game art and creativity.</p>
    </div>
    <div class="gallery">
            <img src="Screenshot 2024-04-29 223209.png" alt="Artwork 1">
        <!-- Example: <img src="image1.jpg" alt="Artwork 1"> -->
    </div>
    <footer>
        © 2024 Shirsh Karn. All rights reserved.
    </footer>
</body>
</html>
