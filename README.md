# Salen.nadim.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ALA RASI - Street Wear for Men and Women</title>
    <meta name="description" content="Discover bold street wear from ALA RASI. Urban fashion for men and women – hoodies, tees, and more.">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <style>
        body { font-family: 'Arial Black', sans-serif; background-color: #111; color: #fff; }
        .hero { background: url('street-hero.jpg') no-repeat center center; background-size: cover; height: 500px; display: flex; align-items: center; justify-content: center; text-shadow: 2px 2px 4px rgba(0,0,0,0.8); }
        .product { margin: 20px; background: #222; padding: 15px; border-radius: 10px; }
        .navbar { background-color: #000; }
        .btn-primary { background-color: #ff0000; border: none; }
        .btn-secondary { background-color: #333; }
    </style>
</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark">
        <a class="navbar-brand" href="#">ALA RASI</a>
        <div class="collapse navbar-collapse">
            <ul class="navbar-nav ml-auto">
                <li class="nav-item"><a class="nav-link" href="#home">Home</a></li>
                <li class="nav-item"><a class="nav-link" href="#mens">Men's</a></li>
                <li class="nav-item"><a class="nav-link" href="#womens">Women's</a></li>
                <li class="nav-item"><a class="nav-link" href="#about">About</a></li>
                <li class="nav-item"><a class="nav-link" href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <section id="home" class="hero">
        <div class="text-center">
            <h1>ALA RASI Street Wear</h1>
            <p>Urban vibes for the streets. Bold fashion for men and women.</p>
            <a href="#mens" class="btn btn-primary">Shop Men's</a>
            <a href="#womens" class="btn btn-secondary">Shop Women's</a>
        </div>
    </section>

    <section id="mens" class="container my-5">
        <h2>Men's Street Wear</h2>
        <div class="row">
            <div class="col-md-4 product">
                <img src="mens-hoodie.jpg" alt="Men's Hoodie" class="img-fluid">
                <h3>Graffiti Hoodie</h3>
                <p>$45 – Street-ready comfort.</p>
                <button class="btn btn-secondary">Add to Cart</button>
            </div>
            <div class="col-md-4 product">
                <img src="mens-tee.jpg" alt="Men's T-Shirt" class="img-fluid">
                <h3>Urban Tee</h3>
                <p>$25 – Edgy designs.</p>
                <button class="btn btn-secondary">Add to Cart</button>
            </div>
            <!-- Add more men's products -->
        </div>
    </section>

    <section id="womens" class="container my-5">
        <h2>Women's Street Wear</h2>
        <div class="row">
            <div class="col-md-4 product">
                <img src="womens-jacket.jpg" alt="Women's Jacket" class="img-fluid">
                <h3>Street Jacket</h3>
                <p>$60 – Bold and versatile.</p>
                <button class="btn btn-secondary">Add to Cart</button>
            </div>
            <div class="col-md-4 product">
                <img src="womens-sneakers.jpg" alt="Women's Sneakers" class="img-fluid">
                <h3>Urban Sneakers</h3>
                <p>$80 – Step up your game.</p>
                <button class="btn btn-secondary">Add to Cart</button>
            </div>
            <!-- Add more women's products -->
        </div>
    </section>

    <section id="about" class="bg-light py-5 text-dark">
        <div class="container">
            <h2>About ALA RASI</h2>
            <p>ALA RASI is your go-to for authentic street wear. Inspired by urban culture, we create gear for men and women who live for the streets – from hoodies to sneakers, all with that edgy, rebellious vibe.</p>
        </div>
    </section>

    <section id="contact" class="container my-5">
        <h2>Contact Us</h2>
        <form>
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" class="form-control" id="name">
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" class="form-control" id="email">
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea class="form-control" id="message" rows="3"></textarea>
            </div>
            <button type="submit" class="btn btn-primary">Send</button>
        </form>
    </section>

    <footer class="bg-dark text-white text-center py-3">
        <p>&copy; 2023 ALA RASI. All rights reserved. Follow us on Instagram: @alarasi_streetwear</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
