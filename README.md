- 👋 Hi, I’m @harling123
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
harling123/harling123 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfection du Spray</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #f4f4f4;
            padding: 20px;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            text-decoration: none;
            color: #333;
            font-size: 18px;
        }

        .hero {
            background-image: url('kitchen-image.jpg'); /* Add the correct path to your kitchen image */
            background-size: cover;
            height: 500px;
            position: relative;
        }

        .hero h1 {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            color: white;
            font-size: 48px;
            text-transform: uppercase;
        }

        .services {
            display: flex;
            justify-content: space-around;
            padding: 50px 20px;
        }

        .service {
            text-align: center;
            width: 200px;
        }

        .service img {
            width: 100px;
            height: 100px;
        }

        .service h3 {
            font-size: 24px;
            margin: 10px 0;
        }

        .service p {
            font-size: 14px;
            color: #666;
        }

        footer {
            background-color: #f4f4f4;
            text-align: center;
            padding: 20px;
        }

        .cta-button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #d9534f;
            color: white;
            text-decoration: none;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Perfection du Spray</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section class="hero">
        <h1>Perfection du Spray</h1>
    </section>

    <section class="services" id="services">
        <div class="service">
            <img src="kitchen-icon.png" alt="Kitchen">
            <h3>Kitchen</h3>
            <p>Transform your kitchen with our professional spray-painting services.</p>
        </div>
        <div class="service">
            <img src="interior-icon.png" alt="Interior">
            <h3>Interior</h3>
            <p>Enhance the beauty of your interior spaces with precision painting.</p>
        </div>
        <div class="service">
            <img src="exterior-icon.png" alt="Exterior">
            <h3>Exterior</h3>
            <p>Exterior spray painting services to protect and beautify your home.</p>
        </div>
        <div class="service">
            <img src="commercial-icon.png" alt="Commercial">
            <h3>Commercial</h3>
            <p>Reliable commercial painting services for businesses of all sizes.</p>
        </div>
    </section>

    <footer>
        <a href="#contact" class="cta-button">Request a Quote</a>
        <p>&copy; 2024 Perfection du Spray. All Rights Reserved.</p>
    </footer>
</body>
</html>
