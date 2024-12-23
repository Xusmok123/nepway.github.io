<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Travel Nepway and Tours Pvt. Ltd.</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 15px 0;
        }

        header .logo {
            font-size: 24px;
            text-align: center;
        }

        nav {
            text-align: center;
            margin-top: 10px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 10px;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #555;
            border-radius: 5px;
        }

        .hero-section {
            background: url('your-hero-image.jpg') no-repeat center center/cover;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #fff;
            text-align: center;
        }

        .hero-section h1 {
            font-size: 48px;
            margin: 0;
        }

        .cta-button {
            background-color: #f29c11;
            padding: 10px 30px;
            color: white;
            font-size: 20px;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 20px;
        }

        .cta-button:hover {
            background-color: #c87a00;
        }

        .section {
            padding: 40px 10%;
            text-align: center;
        }

        .section h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .destinations, .ticketing, .reasons {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .destination, .reason {
            width: 30%;
            margin: 20px 0;
        }

        .destination img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        footer {
            background-color: #333;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        footer a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
        }

        footer a:hover {
            color: #f29c11;
        }
    </style>
</head>

<body>

    <!-- Header Section -->
    <header>
        <div class="logo">Travel Nepway and Tours Pvt. Ltd.</div>
        <nav>
            <a href="#">Home</a>
            <a href="#">Destinations</a>
            <a href="#">Tour Packages</a>
            <a href="#">Ticketing</a>
            <a href="#">About Us</a>
            <a href="#">Contact</a>
            <a href="#">Book Now</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero-section">
        <div>
            <h1>Travel Your Way with Travel Nepway</h1>
            <a href="#ticketing" class="cta-button">Book Your Flight Now</a>
        </div>
    </section>

    <!-- Introduction Section -->
    <section class="section" id="introduction">
        <h2>Welcome to Travel Nepway</h2>
        <p>At Travel Nepway, we specialize in providing seamless and affordable international and domestic flight tickets. Whether you're planning your dream vacation or a business trip, we offer the best deals to make your journey hassle-free. Book your tickets with us and travel your way!</p>
    </section>

    <!-- Featured Destinations Section -->
    <section class="section" id="destinations">
        <h2>Explore Popular Destinations</h2>
        <div class="destinations">
            <div class="destination">
                <img src="kathmandu.jpg" alt="Kathmandu">
                <h3>Kathmandu Valley</h3>
                <p>Explore the rich culture and history of Nepal’s capital city with ancient temples and UNESCO sites.</p>
            </div>
            <div class="destination">
                <img src="everest.jpg" alt="Everest Base Camp">
                <h3>Everest Base Camp</h3>
                <p>Embark on the thrilling trek to the Everest Base Camp and experience the beauty of the Himalayas.</p>
            </div>
            <div class="destination">
                <img src="pokhara.jpg" alt="Pokhara">
                <h3>Pokhara</h3>
                <p>Enjoy the serene lakes and adventure activities in the scenic city of Pokhara.</p>
            </div>
        </div>
    </section>

    <!-- Featured Ticketing Section -->
    <section class="section" id="ticketing">
        <h2>Book Your Tickets with Ease</h2>
        <p>Explore the world with affordable international flights. Whether you're heading to Asia, Europe, or the Americas, we provide the best flight options to suit your travel needs.</p>
        <p>Fly within Nepal effortlessly with our range of domestic flight options. From Kathmandu to Pokhara, Lukla, and beyond, we have you covered.</p>
        <a href="#contact" class="cta-button">Book Your Flight Now</a>
    </section>

    <!-- Why Choose Us Section -->
    <section class="section" id="why-us">
        <h2>Why Book Your Tickets with Us?</h2>
        <div class="reasons">
            <div class="reason">
                <h3>Best Price Guarantee</h3>
                <p>Get the best prices on both international and domestic flights.</p>
            </div>
            <div class="reason">
                <h3>Expert Travel Consultants</h3>
                <p>Our team will help you find the best flights for your travel needs.</p>
            </div>
            <div class="reason">
                <h3>Easy Booking Process</h3>
                <p>Quick and hassle-free online booking with flexible payment options.</p>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="section" id="testimonials">
        <h2>What Our Clients Say About Our Ticketing Service</h2>
        <p>"I booked my flight to Bangkok with Travel Nepway, and the process was smooth and easy. I got the best deal, and their customer service was excellent!" — John, USA</p>
        <p>"Travel Nepway made booking my domestic flight to Pokhara a breeze. I’ll definitely use them again for my next trip." — Anita, Nepal</p>
    </section>

    <!-- Call to Action Section -->
    <section class="section" id="cta">
        <h2>Ready to Book Your Next Flight?</h2>
        <a href="#contact" class="cta-button">Book Now</a>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Travel Nepway and Tours Pvt. Ltd.</p>
        <div>
            <a href="#">Home</a>
            <a href="#">Destinations</a>
            <a href="#">Tour Packages</a>
            <a href="#">Ticketing</a>
            <a href="#">About Us</a>
            <a href="#">Contact</a>
        </div>
    </footer>

</body>

</html>
