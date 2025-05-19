# Ex.07 Restaurant Website
## Date:19.05.2025

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Thanuja's Restaurant - Home</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>

  <nav class="navbar">
    <div class="container">
      <h1 class="logo">Thanuja's Restaurant</h1>
      <ul class="nav-links">
        <li><a href="index.html" class="active">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </div>
  </nav>

  <!-- Hero Section -->
  <section style="background: url('images/restaurant-hero.jpg') center/cover no-repeat; color: white; text-align: center; padding: 5rem 2rem;">
    <div class="container">
      <h2 style="font-size: 3rem; margin-bottom: 1rem;">Welcome to Thanuja’s Restaurant</h2>
      <p style="font-size: 1.4rem; color: orange; font-weight: bold; text-shadow: 1px 1px #fff;">Taste Meets Tradition</p>

      <a href="menu.html" style="display: inline-block; margin-top: 2rem; background-color: #ff6f00; color: white; padding: 0.8rem 1.5rem; border-radius: 8px; text-decoration: none; font-weight: bold;">Explore Menu</a>
    </div>
  </section>

  <!-- Offer Section -->
  <section class="menu-section">
    <div class="container">
      <h2>🔥 Today's Special Offers 🔥</h2>
      <div class="menu-grid">
        <div class="menu-card">
          <img src="Chicken Biriyani.jpg" alt="Chicken Biryani">
          <h3>Chicken Biryani</h3>
          <p style="color: green; font-weight: bold;">20% OFF</p>
        </div>
        <div class="menu-card">
          <img src="Chicken Shawarma.jpg" alt="Shawarma">
          <h3>Shawarma Combo</h3>
          <p style="color: green; font-weight: bold;">Buy 1 Get 1 Free</p>
        </div>
        <div class="menu-card">
          <img src="Smoothie.jpeg" alt="Smoothie">
          <h3>Fruit Smoothie</h3>
          <p style="color: green; font-weight: bold;">Free with any meal!</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Thanuja's Restaurant. All Rights Reserved.</p>
  </footer>

</body>
</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Thanuja's Menu</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>

  <nav class="navbar">
    <div class="container">
      <h1 class="logo">Thanuja's Restaurant</h1>
      <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html" class="active">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </div>
  </nav>

  <section class="menu-section">
    <div class="container">
      <h2>Our Signature Dishes</h2>
      <div class="menu-grid">
        <div class="menu-card"><img src="Mutton-Biryani.jpg" alt="Mutton Biryani"><h3>Mutton Biryani</h3></div>
        <div class="menu-card"><img src="Chicken Biriyani.jpg" alt="Chicken Biryani"><h3>Chicken Biryani</h3></div>
        <div class="menu-card"><img src="Chicken Lollipop.jpg" alt="Chicken Lollipop"><h3>Chicken Lollipop</h3></div>
        <div class="menu-card"><img src="Chicken Grilled.jpg" alt="Grilled Chicken"><h3>Grilled Chicken</h3></div>
        <div class="menu-card"><img src="Chicken Shawarma.jpg" alt="Shawarma"><h3>Shawarma</h3></div>
        <div class="menu-card"><img src="Prawn Fry.jpg" alt="Prawn Fry"><h3>Prawn Fry</h3></div>
        <div class="menu-card"><img src="Smoothie.jpeg" alt="Smoothie"><h3>Fruit Smoothie</h3></div>
      </div>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Thanuja's Restaurant.</p>
    </div>
  </footer>

</body>
</html>
```
adminsitration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Administration</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>

  <nav class="navbar">
    <div class="container">
      <h1 class="logo">Thanuja's Restaurant</h1>
      <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html" class="active">Administration</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </div>
  </nav>

  <section class="admin">
    <div class="container">
      <h2>Our Journey</h2>
      <p>Thanuja's Restaurant was founded by a passionate chef with a dream — to serve soul-satisfying food. Our management focuses on quality, customer delight, and global expansion.</p>
      <p>We now operate in over 80 locations, and our leadership team ensures that every outlet delivers excellence.</p>
    </div>
  </section>
  <section class="chefs">
  <div class="container">
    <h2>Meet Our Master Chefs</h2>
    <div class="chef-grid">
      <div class="chef-card">
        <img src="chef1.jpg" alt="Chef Rajesh">
        <h3>Chef Rajesh Kumar</h3>
        <p>Head Chef – Biryani Master</p>
      </div>
      <div class="chef-card">
        <img src="chef2.jpg" alt="Chef Meera">
        <h3>Chef Meera Joshi</h3>
        <p>Pastry Chef – Dessert Queen</p>
      </div>
      <div class="chef-card">
        <img src="chef3.jpg" alt="Chef Arjun">
        <h3>Chef Arjun Das</h3>
        <p>Grill Specialist – Flavour Wizard</p>
      </div>
    </div>
  </div>
</section>


  <footer>
    <div class="container">
      <p>&copy; 2025 Thanuja's Restaurant.</p>
    </div>
  </footer>

</body>
</html>
```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact Us</title>
  <link rel="stylesheet" href="styles.css"/>
</head>
<body>

  <nav class="navbar">
    <div class="container">
      <h1 class="logo">Thanuja's Restaurant</h1>
      <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html" class="active">Contact</a></li>
      </ul>
    </div>
  </nav>

  <section class="contact">
    <div class="container">
      <h2>Contact Us</h2>
      <p><strong>Email:</strong> thanujasrestaurant@gmail.com</p>
      <p><strong>Phone:</strong> 9876543210</p>
      <p><strong>Address:</strong> 14/8 Shanmuga Sundaram 1st Street, Chennai - 600008</p>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Thanuja's Restaurant.</p>
    </div>
  </footer>

</body>
</html>
```


## OUTPUT:

![alt text](<Screenshot 2025-05-19 195116.png>)

![alt text](<Screenshot 2025-05-19 194525.png>)

![alt text](<Screenshot 2025-05-19 194511.png>)

![alt text](<Screenshot 2025-05-19 194408.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
