# Ex.07 Restaurant Website
## Date:18/12/25
# ref no :25008762

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
home.html

<!DOCTYPE html>
<html>
<head>
    <title>Crimson Fork</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header>
    <h1>Crimson Fork – Non-Veg Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <img src="rest.png" alt="Restaurant Banner" class="banner">
    <h2>Welcome to Crimson Fork</h2>
    <p>Bold flavors, premium non-veg dishes, and a royal dining experience.</p>
</section>

</body>
</html>

menu.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Crimson Fork - Menu</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header>
    <h1>Crimson Fork – Non-Veg Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Our Non-Veg Special Menu</h2>

    <div class="menu-grid">
        <div class="card"><img src="chicken.png"><p>Butter Chicken – ₹320</p></div>
        <div class="card"><img src="mutton.png"><p>Mutton Rogan Josh – ₹380</p></div>
        <div class="card"><img src="fish.png"><p>Fish Fry – ₹280</p></div>
        <div class="card"><img src="biriyani.png"><p>Chicken Biryani – ₹250</p></div>
        <div class="card"><img src="tandoori.png"><p>Tandoori Chicken – ₹340</p></div>
        <div class="card"><img src="prawn.png"><p>Prawn Masala – ₹360</p></div>
    </div>
</section>

</body>
</html>

admin.html

<!DOCTYPE html>
<html>
<head>
    <title>Crimson Fork - Administration</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header>
    <h1>Crimson Fork</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Our Management Team</h2>

    <div class="team-grid">
        <div class="card"><img src="chef.png"><p> Jack  Head Chef</p></div>
        <div class="card"><img src="manager.png"><p>Rose Restaurant Manager</p></div>
    </div>
</section>

</body>
</html>

contact.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Crimson Fork - Contact Us</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>

<header>
    <h1>Crimson Fork – Non-Veg Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <div class="contact-container">
        <h2>Contact Us</h2>
        <p><b>Address:</b> 45 Royal Street, Food Plaza, Chennai</p>
        <p><b>Phone:</b> +91 9123456780</p>
        <p><b>Email:</b> support@crimsonfork.com</p>
        <p><b>Timing:</b> 11:00 AM – 11:30 PM</p>
    </div>
</section>

</body>
</html>

index.css

body {
    font-family: 'Segoe UI', sans-serif;
    margin: 0;

    /* Background image */
    background-image: url("bground.png"); /* put your image name here */
    background-size: cover;        /* makes image cover full screen */
    background-position: center;   /* centers the image */
    background-repeat: no-repeat;  /* prevents repeating */
    background-attachment: fixed;  /* nice scrolling effect */

    color: #3b0a0a;
}

/* Header */
header {
    background: linear-gradient(90deg, #5a0f0f, #8b0000, #c21807);
    color: white;
    padding: 24px;
    text-align: center;
}

/* Navigation */
nav {
    background-color: #2b0606;
    text-align: center;
}

nav a {
    color: #ffd700;
    text-decoration: none;
    margin: 0 16px;
    padding: 10px;
    display: inline-block;
    font-weight: bold;
}

nav a:hover {
    background-color: #ffd700;
    color: #2b0606;
    border-radius: 6px;
}

/* Section */
section {
    padding: 40px;
    text-align: center;
}

/* Banner */
.banner {
    width: 80%;
    max-width: 420px;
    border-radius: 12px;
}

/* Headings */
h2 {
    color: #2b0606;
    letter-spacing: 1px;
}

/* Grid */
.menu-grid, .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
    max-width: 1000px;
    margin: auto;
}

/* Cards */
.card {
    background-color: #fff;
    padding: 18px;
    border-radius: 14px;
    box-shadow: 0 8px 16px rgba(0,0,0,0.15);
    border: 3px solid #8b0000;
}

.card img {
    width: 95px;
    height: 110px;
    border-radius: 12px;
}

/* Contact */
.contact-container {
    background-color: #fff;
    padding: 25px;
    border-radius: 14px;
    max-width: 750px;
    margin: auto;
    box-shadow: 0 6px 15px rgba(0,0,0,0.15);
}

```

## OUTPUT:
<img width="1912" height="959" alt="image" src="https://github.com/user-attachments/assets/b008e1a2-caa8-4d64-a57a-826ac0ce6172" />
<img width="1917" height="905" alt="image" src="https://github.com/user-attachments/assets/a616acf2-a0bf-4be4-a24b-559838d36fca" />
<img width="1909" height="910" alt="image" src="https://github.com/user-attachments/assets/c101fdb7-f256-47a4-be32-79a9c06a2854" />
<img width="1919" height="952" alt="image" src="https://github.com/user-attachments/assets/dae9725e-acb7-492d-9eff-c6da062f6466" />



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
