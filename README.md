<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Car Dealership | Home</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Car Dealership</h1>
        <p>Find your dream car at unbeatable prices!</p>
        <nav>
            <a href="#home">Home</a>
            <a href="#cars">Cars</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Banner Section -->
    <section class="banner">
        <h2>Best Deals on Cars</h2>
    </section>

    <!-- Cars Section -->
    <section class="cars" id="cars">
        <h2>Available Cars</h2>
        <div class="car-list">
            <div class="car-card">
                <img src="https://www.motorshow.in.th/wp-content/uploads/2024/08/Toyota_GR_Corolla_MY_2025_2.jpg" alt="Toyota Corolla">
                <h3>Toyota Corolla</h3>
                <p>Reliable sedan for every family.</p>
                <p class="price">$20,000</p>
            </div>
            <div class="car-card">
                <img src="https://images.autofun.co.th/file1/b77104ccb8944a40933f5070236715d2_606x402.jpg" alt="Honda Civic">
                <h3>Honda Civic</h3>
                <p>Comfort and efficiency combined.</p>
                <p class="price">$22,000</p>
            </div>
            <div class="car-card">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQfPWXvxUXMhgkA8BUpmOJtDverSpWO69IVYQ&s" alt="Ford Mustang">
                <h3>Ford Mustang</h3>
                <p>A classic muscle car with modern touches.</p>
                <p class="price">$35,000</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Car Dealership. All Rights Reserved.</p>
    </footer>
</body>
</html>
