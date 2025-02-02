# Kebap
Kebap is a project for managing kebap recipes and ingredients.
git add README.md
git commit -m "Update README with project description"
git push origin main
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kebaputuzexu - Kebab & Pizza Shop</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="container">
            <h1>Welcome to Kebaputuzexu</h1>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#recipes">Recipes</a></li>
                    <li><a href="#delivery">Delivery</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="container">
            <h2>Delicious Kebabs & Pizzas in Pilsen!</h2>
            <p>Experience the best of Turkish and Italian cuisine right here in Pilsen.</p>
            <a href="#menu" class="btn">View Our Menu</a>
        </div>
    </section>

    <!-- Menu Section -->
    <section id="menu" class="menu">
        <div class="container">
            <h2>Our Menu</h2>
            <div class="menu-items">
                <!-- Kebab Item -->
                <div class="menu-item">
                    <img src="images/kebab.jpg" alt="Kebab">
                    <h3>Classic Kebab</h3>
                    <p>Tender meat, fresh vegetables, and our special sauce.</p>
                    <p>Price: 99 CZK</p>
                </div>

                <!-- Pizza Item -->
                <div class="menu-item">
                    <img src="images/pizza.jpg" alt="Pizza">
                    <h3>Margherita Pizza</h3>
                    <p>Fresh tomatoes, mozzarella, and basil on a crispy crust.</p>
                    <p>Price: 129 CZK</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Recipes Section -->
    <section id="recipes" class="recipes">
        <div class="container">
            <h2>Our Signature Recipes</h2>
            <div class="recipe-items">
                <!-- Recipe 1 -->
                <div class="recipe-item">
                    <h3>How to Make a Perfect Kebab</h3>
                    <p>Step 1: Marinate the meat with spices...</p>
                    <a href="#" class="btn">Read More</a>
                </div>

                <!-- Recipe 2 -->
                <div class="recipe-item">
                    <h3>The Secret to Crispy Pizza Dough</h3>
                    <p>Step 1: Mix flour, water, yeast, and salt...</p>
                    <a href="#" class="btn">Read More</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Delivery Section -->
    <section id="delivery" class="delivery">
        <div class="container">
            <h2>Order Delivery</h2>
            <form action="#" method="POST">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="address">Address:</label>
                <input type="text" id="address" name="address" required>

                <label for="phone">Phone Number:</label>
                <input type="tel" id="phone" name="phone" required>

                <label for="order">Select Your Order:</label>
                <select id="order" name="order" required>
                    <option value="classic-kebab">Classic Kebab (99 CZK)</option>
                    <option value="margherita-pizza">Margherita Pizza (129 CZK)</option>
                </select>

                <button type="submit" class="btn">Place Order</button>
            </form>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>Visit us at: Kebaputuzexu, Main Street, Pilsen</p>
            <p>Call us at: +420 123 456 789</p>
            <p>Email us at: info@kebaputuzexu.cz</p>
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <div class="container">
            <p>&copy; 2023 Kebaputuzexu. All rights reserved.</p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
// Placeholder for future functionality
document.addEventListener('DOMContentLoaded', () => {
    console.log('Website Loaded!');
});
kebaputuzexu/
│
├── index.html          // Main HTML file
├── styles.css          // CSS file for styling
├── script.js           // JavaScript file for interactivity
└── images/             // Folder for images
    ├── kebab.jpg       // Image of kebab
    ├── pizza.jpg       // Image of pizza
    └── hero.jpg        // Background image for hero section
