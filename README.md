# rich-solutions
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rich Solutions | Virtual Wholesaling</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        .hero {
            background: #007BFF;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }
        .services, .about, .contact {
            padding: 50px 20px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px;
        }
    </style>
</head>
<body>
    <header class="hero">
        <h1>Welcome to Rich Solutions</h1>
        <p>Your Trusted Partner in Virtual Wholesaling</p>
        <a href="#services" class="btn btn-light">Explore Our Services</a>
    </header>

    <section id="services" class="services">
        <div class="container">
            <h2 class="text-center">Our Services</h2>
            <div class="row text-center">
                <div class="col-md-4">
                    <h3>Property Analysis</h3>
                    <p>Accurate and efficient property evaluation.</p>
                </div>
                <div class="col-md-4">
                    <h3>Deal Structuring</h3>
                    <p>Professional assistance in deal negotiations.</p>
                </div>
                <div class="col-md-4">
                    <h3>Virtual Closings</h3>
                    <p>End-to-end support for virtual real estate transactions.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2 class="text-center">About Us</h2>
            <p>
                Rich Solutions is a leading virtual wholesaling company specializing in connecting buyers and sellers in the real estate market.
                Our mission is to simplify real estate transactions through technology and expertise.
            </p>
        </div>
    </section>

    <section id="contact" class="contact bg-light">
        <div class="container">
            <h2 class="text-center">Contact Us</h2>
            <form>
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" placeholder="Your Name">
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" placeholder="Your Email">
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" rows="5" placeholder="Your Message"></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Rich Solutions. All rights reserved.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
