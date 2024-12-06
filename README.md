# Ex.07 Restaurant Website
# Date:4/11/2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Delicious Restaurant</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #575757;
        }
        .section {
            padding: 20px;
            text-align: center;
        }
        .menu-item {
            display: inline-block;
            width: 30%;
            padding: 10px;
            margin: 10px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .menu-item img {
            width: 100%;
            border-radius: 8px;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .reservation-form input, .reservation-form textarea {
            width: 80%;
            padding: 10px;
            margin: 10px;
            border-radius: 4px;
            border: 1px solid #ccc;
        }
        .reservation-form button {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }
        .reservation-form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

    <header>
        <h1>French Restaurant</h1>
        <p>Where every meal is a delight!</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#about">About Us</a>
        <a href="#contact">Contact</a>
        <a href="#reservation">Reservation</a>
    </nav>

    <section id="home" class="section">
        <h2>Welcome to French Restaurant</h2>
        <p>We offer an exquisite dining experience with the finest ingredients and a warm atmosphere.</p>
    </section>

    <section id="menu" class="section">
        <h2>Our Menu</h2>
        <div class="menu-item">
            <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-02 075845.png" alt="Dish 1">
            <h3>Cassoulet</h3>
            <p>A stew from Languedoc, southwest France, that combines white beans with meat</p>
            <p>$15.99</p>
        </div>
        <div class="menu-item">
            <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-02 075010.png" alt="Dish 2">
            <h3>Bouillabaisse</h3>
            <p>A traditional stew made by boiling various types of fish, often served with a sauce called rouille. </p>
            <p>$12.99</p>
        </div>
        <div class="menu-item">
            <img src="C:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-02 075030.png" alt="Dish 3">
            <h3>Gratin dauphinois</h3>
            <p>A regional dish made with potatoes and crème fraîche. </p>
            <p>$20.99</p>
        </div>
    </section>

    <section id="about" class="section">
        <h2>About Us</h2>
        <p>French Restaurant has been serving the finest cuisine for over 20 years. Our chefs specialize in fresh, local ingredients and bring a unique twist to classic dishes.</p>
    </section>

    <section id="contact" class="section">
        <h2>Contact Us</h2>
        <p>Email: contact@Frenchrestaurant.com</p>
        <p>Phone: +123 456 7890</p>
        <p>Address: 123 Flavor St, Food City</p>
    </section>

    <section id="reservation" class="section reservation-form">
        <h2>Make a Reservation</h2>
        <form action="#" method="POST">
            <input type="text" name="name" placeholder="Your Name" required><br>
            <input type="email" name="email" placeholder="Your Email" required><br>
            <input type="number" name="phone" placeholder="Your Phone Number" required><br>
            <input type="date" name="date" required><br>
            <textarea name="message" placeholder="Special Requests" rows="4"></textarea><br>
            <button type="submit">Book Now</button>
        </form>
    </section>

   

</body>
</html>
~~~

# OUTPUT:
![Screenshot 2024-12-06 111515](https://github.com/user-attachments/assets/90500a81-039b-4d67-b0ec-fc745ed75605)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
