# FrameScape
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="FrameScape: Your go-to store for custom framing and scenic photography.">
    <title>FrameScape | Custom Framing and Scenic Photos</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Welcome to FrameScape</h1>
        <p>Your one-stop shop for custom framing and beautiful scenic photography.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Custom Framing</li>
            <li>Scenic Photography Prints</li>
            <li>Personalized Framing Solutions</li>
        </ul>
    </section>

    <section id="gallery">
        <h2>Scenic Photo Gallery</h2>
        <div class="gallery-grid">
            <img src="image1.jpg" alt="Scenic Photo 1">
            <img src="image2.jpg" alt="Scenic Photo 2">
            <img src="image3.jpg" alt="Scenic Photo 3">
            <!-- Add more images as needed -->
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: contact@framescape.com</p>
        <p>Phone: +123 456 7890</p>
    </section>

    <footer>
        <p>&copy; 2024 FrameScape. All Rights Reserved.</p>
    </footer>
</body>
</html>
CSS style:
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: #333;
    color: white;
    padding: 1em 0;
}

header nav ul {
    list-style: none;
    text-align: center;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

section {
    padding: 2em;
    text-align: center;
}

#gallery .gallery-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
}

#gallery .gallery-grid img {
    width: 100%;
    height: auto;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
    margin-top: 2em;
}
