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
Restaurent.html:
~~~
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to <i>French Restaurent</i></title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('back.jpg');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(4, 7, 49, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #373c6f;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #264653;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 180px;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1><i>Welcome to French Restaurent</i></h1>
        <p>Where taste meet excellency!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Main Content Section -->
    <div class="welcome-section">
        <h2>About Us</h2>
        <p>At FRENCH RESTAURENT, we are committed to serving delicious, fresh, and delightful meals to tantalize your taste buds. Join us for an unforgettable dining experience.</p>
    </div>

    <div class="features-section">
        <h2>Why Choose Us?</h2>
        <ul>
            <li>Authentic and fresh ingredients.</li>
            <li>Friendly and professional staff.</li>
            <li>A warm and inviting atmosphere.</li>
        </ul>
    </div>

    <!-- Food Images Section -->
    <div class="food-images">
        <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 174633.png" alt="Delicious Food 1">
        <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 174726.png" alt="Delicious Food 2">
        <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 174834.png" alt="Delicious Food 3">
    </div>
</body>
</html>
~~~
Menu.html:
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Our Specialties</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        h2 {
            background-color: #473b88;
            color: white;
            padding: 20px;
        }
        table {
            width: 100%;
            max-width: 800px;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }
        img {
            width: 100px;
            height: auto;
            border-radius: 8px;
        }
        caption {
            font-size: 1.5em;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h2>Our Specialties</h2>
    <table>
        <caption>Our Menu Items</caption>
        <tr>
            <td><img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 175846.png" alt="Food Item 1"></td>
            <td>
                <h3>1.Boeuf bourguignon</h3>
                <p>Boeuf bourguignon is a great example of budget cuts of meat being turned into stylish haute cuisine. For authenticity, be sure to use a Burgundian pinot noir for this recipe.</p>
            </td>
        </tr>
        <tr>
            <td><img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 174726.png" alt="Food Item 2"></td>
            <td>
                <h3>2.Chicken confit</h3>
                <p>In this classic confit, the chicken is salted and seasoned with herbs, then slowly cooked in olive oil to make it rich and tender.</p>
            </td>
        </tr>
        <tr>
            <td><img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 174834.png" alt="Food Item 3"></td>
            <td>
                <h3>3.French onion soup</h3>
                <p>See out the winter with this fragrant French onion soup. Don’t forget the cheesy croutons.</p>
            </td>
        </tr>
        <tr>
            <td><img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 175623.png" alt="Food Item 4"></td>
            <td>
                <h3>4.Bouillabaisse</h3>
                <p>This traditional French fish soup is infused with saffron, orange, thyme and chilli.</p>
            </td>
        </tr>
        <tr>
            <td><img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 180036.png" alt="Food Item 5"></td>
            <td>
                <h3>5.Croque monsieur</h3>
                <p>Only in France could the humble cheese and ham toastie be turned into a gourmet fare. Add a poached or fried egg on top to turn it into the equally stylish croque madame.</p>
            </td>
        </tr>
        <tr>
            <td><img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 180155.png" alt="Food Item 6"></td>
            <td>
                <h3>6.Quiche Lorraine</h3>
                <p>This quiche Lorraine is one of the most popular recipes on taste.com.au. Originally quiche Lorraine was an open custard pie with smoked bacon. It is only the more modern versions that add cheese to the mix.</p>
            </td>
        </tr>
        <tr>
            <td><img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 180400.png" alt="Food Item 4"></td>
            <td>
                <h3>7.Lamb shank navarin</h3>
                <p>Navarin is a French lamb ragout (or stew). The lamb is cooked low and slow until it melts in the mouth.</p>
            </td>
        </tr>
    </table>
</body>
</html>
```
Admin.html:
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - French Restaurent</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        .banner {
            background-color: #190a35;
            padding: 20px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #43478e;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
        }
        .nav-links a {
            display: inline-block;
            padding: 10px 15px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #2a9d8f;
        }
        .admin-section {
            padding: 20px;
        }
        .admin-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .admin-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        .admin-card h3 {
            font-size: 18px;
            margin: 10px 0;
        }
        .admin-card p {
            font-size: 14px;
            color: #555;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Meet Our Administration</h1>
        <p>The team behind French Restaurent's success</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="Restaurent.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Administration Section -->
    <div class="admin-section">
        <h2>Our Dedicated Team</h2>
        <div class="admin-grid">
            <div class="admin-card">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 183742.png" alt="Admin 1">
                <h3>VIJAY</h3>
                <p>C.E.O</p>
                <p>EMAIL:vijay@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 183841.png" alt="Admin 2">
                <h3>GORDON RAMSAY</h3>
                <p>Head Chef</p>
                <p>EMAIL:GR@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 183938.png" alt="Admin 3">
                <h3>TOM CRUISE</h3>
                <p>MENU CURATOR</p>
                <p>EMAIL:TOM@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 184054.png" alt="Admin 4">
                <h3>THOMAS SHELBY</h3>
                <p>MARKETING MANAGER</p>
                <p>TOMMYSHELBY@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 184424.png" alt="Admin 5">
                <h3>PEP GUARDIOLA</h3>
                <p>FINANCE MANAGER</p>
                <p>EMAIL:PEP@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-16 184646.png" alt="Admin 6">
                <h3>LIONEL MESSI</h3>
                <p>PUBLIC RELATIONS OFFICER</p>
                <p>EMAIL:LEO@gmail.com</p>
            </div>
        </div>
    </div>
</body>
</html>
```
Contact.html:
```
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - French Restaurant</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        .banner {
            background-color: #120a43;
            padding: 20px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #4b3d85;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
        }
        .nav-links a {
            display: inline-block;
            padding: 10px 15px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #2a9d8f;
        }
        .contact-section {
            padding: 20px;
        }
        .contact-details {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 500px;
            text-align: left;
        }
        .contact-details h2 {
            font-size: 20px;
            margin-bottom: 15px;
        }
        .contact-details p {
            font-size: 16px;
            margin: 5px 0;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Contact Us</h1>
        <p>We would love to hear from you!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="Restaurent.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Contact Section -->
    <div class="contact-section">
        <h2>Get in Touch</h2>
        <div class="contact-details">
            <h2>Our Address</h2>
            <p>3/2,st.Francisco</p>
            <p>Paris</p>

            <h2>Phone</h2>
            <p>9987345358</p>

            <h2>Email</h2>
            <p><a href="mailto:info@frenchrestaurent.com">info@Frenchrestaurent.com</a></p>
        </div>
    </div>
</body>
</html>
```

# OUTPUT:
Home Page:

![Screenshot 2024-12-16 185116](https://github.com/user-attachments/assets/1c9d567f-180f-44c6-98e6-cb21203b966a)

Menu Page:

![Screenshot 2024-12-16 185143](https://github.com/user-attachments/assets/f94c3d5c-f3af-47d0-9409-d714ce85217c)

Admin Page:

![Screenshot 2024-12-16 185202](https://github.com/user-attachments/assets/f8e4b160-940b-403e-bd20-516274900576)

Contact Page:

![Screenshot 2024-12-16 185219](https://github.com/user-attachments/assets/09f33a6e-4990-4bde-adfa-94c693d8c6ca)


# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
