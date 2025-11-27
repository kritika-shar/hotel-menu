<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QuickBite - Online Food Delivery</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav>
        <div class="logo">QuickBite</div>
        <ul class="nav-links">
            <li><a href="#restaurants">Restaurants</a></li>
            <li><a href="#menu">Menu</a></li>
            <li><a href="#cart">Cart</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <button id="login-btn">Login</button>
    </nav>

    <header>
        <h1>Delicious food delivered at your doorstep!</h1>
        <p>Choose from your favorite restaurants, browse their menu, and get hot food delivered fast!</p>
        <a href="#restaurants" class="cta-btn">Order Now</a>
    </header>

    <section id="restaurants">
        <h2>Featured Restaurants</h2>
        <div class="restaurants-container">
            <div class="restaurant-card">
                <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=400&q=80" alt="Italiano">
                <h3>Italiano</h3>
                <p>Pasta, Pizza, Risotto</p>
            </div>
            <div class="restaurant-card">
                <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=400&q=80" alt="Spicy Hut">
                <h3>Spicy Hut</h3>
                <p>Indian, Tandoori, Curry</p>
            </div>
            <div class="restaurant-card">
                <img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=400&q=80" alt="Burger Queen">
                <h3>Burger Queen</h3>
                <p>Burgers, Fries, Shakes</p>
            </div>
        </div>
    </section>

    <section id="menu">
        <h2>Popular Dishes</h2>
        <div class="menu-container">
            <!-- Sample menu items -->
            <div class="menu-item">
                <img src="https://images.unsplash.com/photo-1519864600265-abb23843b6b4?auto=format&fit=crop&w=400&q=80" alt="Margherita Pizza">
                <div>
                    <h4>Margherita Pizza</h4>
                    <p>Italiano</p>
                    <span>₹399</span>
                    <button onclick="addToCart('Margherita Pizza',399)">Add to Cart</button>
                </div>
            </div>
            <div class="menu-item">
                <img src="https://images.unsplash.com/photo-1499028344343-cd173ffc68a9?auto=format&fit=crop&w=400&q=80" alt="Butter Chicken">
                <div>
                    <h4>Butter Chicken</h4>
                    <p>Spicy Hut</p>
                    <span>₹299</span>
                    <button onclick="addToCart('Butter Chicken',299)">Add to Cart</button>
                </div>
            </div>
            <div class="menu-item">
                <img src="https://images.unsplash.com/photo-1519864600265-abb23843b6b4?auto=format&fit=crop&w=400&q=80" alt="Cheese Burger">
                <div>
                    <h4>Cheese Burger</h4>
                    <p>Burger Queen</p>
                    <span>₹199</span>
                    <button onclick="addToCart('Cheese Burger',199)">Add to Cart</button>
                </div>
            </div>
        </div>
    </section>

    <section id="cart">
        <h2>Your Cart</h2>
        <div id="cart-items"></div>
        <div id="cart-total"></div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form id="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Email" required>
            <textarea rows="4" placeholder="Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 QuickBite Food Delivery. All rights reserved.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
