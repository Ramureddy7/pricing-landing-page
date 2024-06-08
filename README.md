# pricing-landing-page
simple pricing landing page using HTML and CSS:  html
html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pricing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Our Pricing Plans</h1>
    </header>
    <main>
        <div class="pricing-card">
            <h2>Basic Plan</h2>
            <p class="price">$9.99</p>
            <ul>
                <li>Feature 1</li>
                <li>Feature 2</li>
                <li>Feature 3</li>
            </ul>
            <button>Select Plan</button>
        </div>
        <div class="pricing-card">
            <h2>Standard Plan</h2>
            <p class="price">$19.99</p>
            <ul>
                <li>Feature 1</li>
                <li>Feature 2</li>
                <li>Feature 3</li>
                <li>Feature 4</li>
            </ul>
            <button>Select Plan</button>
        </div>
        <div class="pricing-card">
            <h2>Premium Plan</h2>
            <p class="price">$29.99</p>
            <ul>
                <li>Feature 1</li>
                <li>Feature 2</li>
                <li>Feature 3</li>
                <li>Feature 4</li>
                <li>Feature 5</li>
            </ul>
            <button>Select Plan</button>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Company Name</p>
    </footer>
</body>
</html>
css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
}

main {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 50px;
}

.pricing-card {
    border: 1px solid #ccc;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    padding: 20px;
    text-align: center;
    margin: 0 20px;
}

.pricing-card h2 {
    color: #333;
}

.price {
    font-size: 24px;
    margin: 10px 0;
}

ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    margin: 10px 0;
}

button {
    background-color: #4CAF50;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    bottom: 0;
    width: 100%;
}
