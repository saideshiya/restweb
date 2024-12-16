# Ex.07 Restaurant Website
## Date:

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurant Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('c:\Users\admin\OneDrive\Desktop\marble.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
            color: #0e0a0a;
        }
        header {
            background-color: rgba(212, 183, 88, 0.7);
            padding: 20px 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        nav {
            background-color: rgba(146, 161, 100, 0.8);
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 40px;
            background-color: rgba(220, 152, 74, 0.6);
            border-radius: 10px;
            margin: 20px auto;
            max-width: 1200px;
        }
        h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .menu-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .menu-item {
            background-color: rgba(255, 255, 255, 0.1);
            padding: 15px;
            text-align: center;
            border-radius: 10px;
            width: 220px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
        }
        .menu-item img {
            width: 100%;
            height: 140px;
            object-fit: cover;
            border-radius: 10px;
        }
        footer {
            background-color: rgba(0, 0, 0, 0.8);
            text-align: center;
            color: #fff;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        form {
            max-width: 600px;
            margin: 0 auto;
        }
        .form-group {
            margin: 15px 0;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input, select, textarea {
            width: 100%;
            padding: 10px;
            border-radius: 5px;
            border: none;
        }
        button {
            display: block;
            width: 100%;
            background-color: #ff5722;
            color: #fff;
            border: none;
            padding: 10px;
            border-radius: 5px;
            font-size: 1em;
            cursor: pointer;
        }
        button:hover {
            background-color: #e64a19;
        }
    </style>
</head>
<body bgcolor="black">

<header>
    <h1 style="font-family: Georgia, 'Times New Roman', Times, serif;" color="black"> 🙏WELCOME TO SPICY SPOT 🌶️</h1>
</header>

<nav>
    <a href="c:\Users\admin\OneDrive\Desktop\menu.jpg">Menu</a>
    <a href="">Order Online</a>
    <a href="#booking">Table Booking</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact</a>
</nav>

<section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-container">
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Flavorful Grilled Chicken Meals.jpeg" alt="Dish 1">
            <h3 color="black">Grilled Chicken</h3>
            <p>Price: ₹350</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\World Food Day _ Indian Dish _ Veg Biryani _ Food Photography.jpeg" alt="Dish 2">
            <h3>Vegetable Biryani</h3>
            <p>Price: ₹200</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Classic Margherita Pizza.jpeg" alt="Dish 3">
            <h3>Margherita Pizza</h3>
            <p>Price: ₹699</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Creamy Chicken Alfredo Fettuccine_ The Ultimate Comfort Food Recipe You'll Crave!.jpeg" alt="Dish 4">
            <h3>Pasta Alfredo</h3>
            <p>Price: ₹999</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Chicken Recipes.jpeg" alt="Dish 5">
            <h3>Caesar Salad</h3>
            <p>Price: ₹259</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Saveurs Secretes · Photography.jpeg" alt="Dish 6">
            <h3>Butter Naan</h3>
            <p>Price: ₹200</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Restaurant-Style Paneer Tikka - Sanjana_Feasts - Paneer Recipes.jpeg" alt="Dish 7">
            <h3>Tandoori Paneer</h3>
            <p>Price: ₹350</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Homemade Chicken Tikka Kabab Recipe - khaddoroshik.jpeg" alt="Dish 8">
            <h3>Chicken Tikka</h3>
            <p>Price: ₹299</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Peanut Butter Brownies [90 Minutes].jpeg" alt="Dish 9">
            <h3>Chocolate Brownie</h3>
            <p>Price: ₹199</p>
        </div>
        <div class="menu-item">
            <img src="c:\Users\admin\Downloads\Mango Smoothie (Quick and Easy Recipe).jpeg" alt="Dish 10">
            <h3>Mango Smoothie</h3>
            <p>Price: ₹200</p>
        </div>
    </div>
</section>

<section id="order">
    <h2>Order Online</h2>
    <form action="/order" method="post">
        <div class="form-group">
            <label for="dish">Select Dish:</label>
            <select id="dish" name="dish">
                <option>Grilled Chicken</option>
                <option>Vegetable Biryani</option>
                <option>Margherita Pizza</option>
                <option>Pasta Alfredo</option>
                <option>Caesar Salad</option>
                <option>Butter Naan</option>
                <option>Tandoori Paneer</option>
                <option>Chicken Tikka</option>
                <option>Chocolate Brownie</option>
                <option>Mango Smoothie</option>
            </select>
        </div>
        <div class="form-group">
            <label for="quantity">Quantity:</label>
            <input type="number" id="quantity" name="quantity" min="1" value="1">
        </div>
        <div class="form-group">
            <label for="address">Delivery Address:</label>
            <textarea id="address" name="address" rows="3"></textarea>
        </div>
        <button type="submit"><a href="c:\Users\admin\OneDrive\Desktop\done.jpeg">Place Order</a></button>
    </form>
</section>

<section id="booking">
    <h2>Table Booking</h2>
    <form action="/book-table" method="post">
        <div class="form-group">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
        </div>
        <div class="form-group">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
        </div>
        <div class="form-group">
            <label for="date">Date:</label>
            <input type="date" id="date" name="date" required>
        </div>
        <div class="form-group">
            <label for="time">Time:</label>
            <input type="time" id="time" name="time" required>
        </div>
        <div class="form-group">
            <label for="guests">Number of Guests:</label>
            <input type="number" id="guests" name="guests" min="1" required>
        </div>
        <button type="submit">Book Table</button>
    </form>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>Welcome to SPICY SPOT , where we offer delicious dishes made with fresh ingredients and served with love. Enjoy an amazing dining experience with us! find your tast buds on our shop ! hurry hurry~~</p>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Address: 123 Food Street, Gourmet City</p>
    <p>Phone: +123 456 789</p>
    <p>Email: contact@spicy_spot.com</p>
</section>

<footer bgcolor="white">
    <p>&copy; 2024 spicy spicy_spot. All Rights Reserved.</p>
</footer>

</body>
</html>
```
           
            
## OUTPUT:


![Screenshot (109)](https://github.com/user-attachments/assets/0f0c006f-bbff-4df1-84bf-56c00461c209)

![Screenshot (110)](https://github.com/user-attachments/assets/bcc7b156-859e-4698-a154-e47e47aede6b)

![Screenshot (111)](https://github.com/user-attachments/assets/86f3cc41-72c9-4ab5-9982-ce8cdf85ea0b)

![Screenshot (112)](https://github.com/user-attachments/assets/ca358405-8b13-420b-b76d-fff68f76ae6e)

![Screenshot (113)](https://github.com/user-attachments/assets/90fd124f-8f2b-4d8f-aa7d-eeb2b5aeb966)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
