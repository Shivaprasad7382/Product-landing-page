<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Product Landing Page</title>
</head>
<body>
    <header>
        <h1> Amazon </h1>
        <p>Amazing products for you!</p>
    </header>
    
    <section id="features">
        <div class="feature">
            <img src="product1.jpg" alt="Feature 1">
            <h2>Feature 1</h2>
            <p>Description of Feature 1.</p>
        </div>
        <div class="feature">
            <img src="feature2.jpg" alt="Feature 2">
            <h2>Feature 2</h2>
            <p>Description of Feature 2.</p>
        </div>
        <!-- Add more features as needed -->
    </section>
    
    <section id="cta">
        <h2>Ready to get started?</h2>
        <p>Order now and experience the difference!</p>
        <a href="#" class="button">Order Now</a>
    </section>
    
    <footer>
        <p>&copy; 2024 Your Company. All rights reserved.</p>
    </footer>
</body>
</html>
//css
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    text-align: center;
    background-color: #f4f4f4;
    padding: 20px;
}

section {
    padding: 40px;
}

#features {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.feature {
    flex: 1 0 300px;
    text-align: center;
    margin: 20px;
}

img {
    max-width: 100%;
    height: auto;
}

#cta {
    background-color: #e0e0e0;
    text-align: center;
}

.button {
    display: inline-block;
    padding: 10px 20px;
    margin-top: 20px;
    background-color: #3498db;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 10px;
    background-color: #333;
    color: #fff;
}
