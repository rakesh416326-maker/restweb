# Ex.07 Restaurant Website
## Date:14/12/2025
## ref no:25018957

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
~~~
home.html

<!DOCTYPE html>
<html>
<head>
    <title>Thalapakkatti Restaurant</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Thalapakkatti Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <img src="Screenshot 2025-10-08 132427.png" alt="Restaurant Banner" style="width:80%; max-width:900px; border-radius:10px;">
    <h2>Welcome to Thalapakkatti</h2>
    <p>Authentic flavors, fresh ingredients, and a cozy dining experience.</p>
</section>

<footer>
    © Designed by Rakesh s.
</footer>
</body>
</html>
menu.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Thalapakkatti - Menu</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Thalapakkatti Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Our Menu</h2>
    <div class="menu-grid">
        <div class="card"><img src="Screenshot 2025-10-08 133021.png"><p>Grilled Chicken -₹660</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 133311.png"><p>Mushroom Pasta - ₹360</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 133521.png"><p>chicken Tikka - ₹320</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 133809.png"><p>chicken  Pizza - ₹250</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 134039.png"><p>chicken Noodles - ₹200</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 134506.png"><p>fruit Salad - ₹90</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 134856.png"><p>Chicken Curry - ₹320</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 135158.png"><p>Prawn Fry - ₹350</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 135342.png"><p>chicken Biriyani - ₹170</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 135710.png"><p>Club Sandwich - ₹140</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 135905.png"><p>Fresh Juice - ₹100</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 140113.png"><p>Coffee - ₹70</p></div>
    </div>
</section>

<footer>
    © Designed by Rakesh s.
</footer>
</body>
</html>
admin.html

<!DOCTYPE html>
<html>
<head>
    <title>Thalapakkatti - Administration</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Thalapakkatti Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Meet Our Team</h2>
    <div class="team-grid">
        <div class="card"><img src="Screenshot 2025-10-08 171505.png" ><p>Person 1 - Head Chef</p></div>
        <div class="card"><img src="Screenshot 2025-10-08 171723.png"><p>Person 2 - Manager</p></div>
    </div>
</section>

<footer>
    © Designed by rakesh s.
</footer>
</body>
</html>
contact.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Thalapakkatti - Contact Us</title>
    <link rel="stylesheet" href="index.css">
    
        
        
</head>
<body>

<header>
    <h1>Thalapakkatti Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <div class="contact-container">
        <h2>Contact Us</h2>
        <p><b>Address:</b> No. 83, Anna Salai,Mount Road, Chennai,Tamil Nadu 600002</p>
        <p><b>Phone:</b> +91 9345819747</p>
        <p><b>Email:</b> contact@lamesa.com</p>
        <p><b>Opening Hours:</b> Mon-Sun: 10:00 AM - 10:00 PM</p>
    </div>
</section>

<footer>
    © Designed by rakesh s.
</footer>

</body>
</html>
index.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #fff7f5;
    color: #333;
}
header {
    background-color: #b33a3a; /* Primary color */
    color: white;
    padding: 20px;
    text-align: center;
}
nav {
    background-color: #333;
    text-align: center;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    padding: 8px;
    display: inline-block;
}
nav a:hover {
    background-color: #f2c57c; /* Accent color */
    color: #333;
}
section {
    padding: 40px;
    text-align: center;
}
h2 {
    color: #b33a3a;
    font-style:oblique;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.menu-grid, .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    max-width: 1000px;
    margin: 20px auto;
    text-align: center;
}
.card {
    background-color: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    font-style: italic;
    color:#b33a3a;
    text-shadow:#f2c57c;
}
.card img {
    width: 80px;
    height: 100px;
    object-fit: cover;
    border-radius: 25px;
    align-items: center;
    border: #f2c57c;
    
}
footer {
    background-color:#333;
    color: white;
    
    text-align: center;
    padding: 15px;
}
contact-container {
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
            padding: 20px;
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .contact-container h2 {
            text-align: center;
            color: #b33a3a;
        }
        .contact-container p {
            font-size: 18px;
            margin: 10px 0;
        }
        .contact-container b {
            color: #b33a3a;
        }
~~~

## OUTPUT:
<img width="1897" height="913" alt="a" src="https://github.com/user-attachments/assets/9f1033f0-d0b1-4424-8253-270548e0a8f1" />
<img width="1887" height="900" alt="b" src="https://github.com/user-attachments/assets/4d71aeda-7c34-4090-a896-1af4aacae808" />
<img width="1860" height="868" alt="c" src="https://github.com/user-attachments/assets/4e09f84a-108a-4df4-86ce-9271be6ab88e" />
<img width="1867" height="901" alt="d" src="https://github.com/user-attachments/assets/9a569d32-56de-4db7-87ae-64476cb70e8b" />



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
