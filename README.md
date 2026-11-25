
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Explore to Discover | Philippines</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav class="navbar">
        <a href="#home" class="logo">Explore<span>PH.</span></a>

        <ul class="nav-links">
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#destinations">Destinations</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>

        <button id="themeBtn" class="theme-btn">🌙</button>
    </nav>
</header>

<section id="home" class="hero">
    <div class="hero-content">
        <p class="subtitle">DISCOVER THE BEAUTY OF THE PHILIPPINES</p>
        <h1>Explore to <span>Discover.</span></h1>
        <p>
            Discover beautiful places, experience different cultures,
            and create unforgettable memories in the Philippines.
        </p>
        <a href="#destinations" class="btn">Explore Destinations</a>
    </div>
</section>

<section id="about" class="about section">
    <div class="about-image">
        <img src="https://images.unsplash.com/photo-1518509562904-e7ef99cdcc86?w=900"
             alt="Beautiful tropical island in the Philippines">
    </div>

    <div class="about-content">
        <p class="subtitle">ABOUT US</p>
        <h2>Discover the Beauty of the Philippines</h2>
        <p>
            The Philippines is a beautiful country known for its
            stunning beaches, clear waters, green mountains, and
            rich culture. It is home to many amazing destinations
            waiting to be explored.
        </p>
        <p>
            ExplorePH helps travelers discover beautiful places
            and find inspiration for their next adventure.
        </p>
        <a href="#destinations" class="btn">Discover More</a>
    </div>
</section>

<section id="destinations" class="destinations section">
    <div class="section-heading">
        <p class="subtitle">TRAVEL AND EXPLORE</p>
        <h2>Popular Destinations</h2>
        <p>Explore some of the most beautiful places in the Philippines.</p>
    </div>

    <div class="destination-grid">

        <div class="destination-card">
            <img src="https://images.unsplash.com/photo-1518509562904-e7ef99cdcc86?w=700"
                 alt="Palawan">
            <div class="card-content">
                <h3>Palawan</h3>
                <p>Explore crystal-clear waters, beautiful lagoons,
                   and breathtaking island views.</p>
                <span>📍 MIMAROPA, Philippines</span>
            </div>
        </div>

        <div class="destination-card">
            <img src="https://images.unsplash.com/photo-1510414842594-a61c69b5ae57?w=700"
                 alt="Boracay">
            <div class="card-content">
                <h3>Boracay</h3>
                <p>Enjoy white sand beaches, exciting activities,
                   and unforgettable sunsets.</p>
                <span>📍 Aklan, Philippines</span>
            </div>
        </div>

        <div class="destination-card">
            <img src="https://images.unsplash.com/photo-1544551763-46a013bb70d5?w=700"
                 alt="Bohol">
            <div class="card-content">
                <h3>Bohol</h3>
                <p>Discover the famous Chocolate Hills,
                   beautiful beaches, and nature attractions.</p>
                <span>📍 Central Visayas, Philippines</span>
            </div>
        </div>

        <div class="destination-card">
            <img src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21?w=700"
                 alt="Siargao">
            <div class="card-content">
                <h3>Siargao</h3>
                <p>Experience surfing, island hopping,
                   and the relaxing tropical atmosphere.</p>
                <span>📍 Surigao del Norte, Philippines</span>
            </div>
        </div>

        <div class="destination-card">
            <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470?w=700"
                 alt="Baguio">
            <div class="card-content">
                <h3>Baguio</h3>
                <p>Enjoy cool weather, pine trees,
                   and beautiful mountain scenery.</p>
                <span>📍 Benguet, Philippines</span>
            </div>
        </div>

        <div class="destination-card">
            <img src="https://images.unsplash.com/photo-1470770841072-f978cf4d019e?w=700"
                 alt="Cebu">
            <div class="card-content">
                <h3>Cebu</h3>
                <p>Discover waterfalls, historical places,
                   and beautiful island adventures.</p>
                <span>📍 Central Visayas, Philippines</span>
            </div>
        </div>

    </div>
</section>

<section class="quote-section">
    <h2>"Travel is the only thing you buy that makes you richer."</h2>
    <p>Explore new places. Create unforgettable memories.</p>
</section>

<section id="contact" class="contact section">
    <div class="section-heading">
        <p class="subtitle">GET IN TOUCH</p>
        <h2>Contact Us</h2>
        <p>Have questions or suggestions? Send us a message!</p>
    </div>

    <form id="contactForm">
        <input type="text" id="name" placeholder="Your Name" required>
        <input type="email" id="email" placeholder="Your Email" required>
        <textarea id="message" placeholder="Your Message" rows="5" required></textarea>
        <button type="submit" class="btn">Send Message</button>
    </form>
</section>

<footer>
    <h2>Explore<span>PH.</span></h2>
    <p>Discover places. Create memories.</p>
    <p class="copyright">
        © 2026 ExplorePH. All Rights Reserved.
    </p>
</footer>

<script src="app.js"></script>
</body>
</html>
