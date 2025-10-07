# Ex.07 Restaurant Website
## Date: 04-10-2025
## Name: HARI PRASATH E
## Ref No: 25007799

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
administration.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - FRIENDS DABHA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Administration</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="admin-grid">
    <!-- Repeat for 6 people -->
    <div class="admin-card">
      <img src="saudh.jpg" alt="Admin 1">
      <h3>MOHAMED SAUDH</h3>
      <p>Manager</p>
    </div>
    <div class="admin-card">
      <img src="mani.jpg" alt="Admin 2">
      <h3>MANIKANDAN</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="mohan1.jpg" alt="Admin 3">
      <h3>MOHAN RAJI</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="sanjai.jpg" alt="Admin 4">
      <h3>SANJAI</h3>
      <p>Assistant Chef</p>
    </div>
    <div class="admin-card">
      <img src="naveen.jpg" alt="Admin 5">
      <h3>NAVEEN KUMAR</h3>
      <p>Assistant chef</p>
    </div>
    <div class="admin-card">
      <img src="me2.jpg" alt="Admin 6">
      <h3>HARI PRASATH</h3>
      <p>cashier</p>
    </div>
    <div class="admin-card">
      <img src="balaji.jpg" alt="Admin 7">
      <h3>BALAJI B M</h3>
      <p>Inventory Manager</p>
    </div>
    <div class="admin-card">
      <img src="vicky.jpg" alt="Admin 8">
      <h3>VIGNESHWAREN</h3>
      <p>Customer Service</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by  Hari Prasath E</p>
  </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - FRIENDS DABHA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2>Get in Touch</h2>
    <p>📍 <strong>Address:</strong> 999 Friends Street , Chennai , Tamil Nadu</p>
    <p>📞 <strong>Phone:</strong> (999) 123-456-7890 </p>
    <p>✉ <strong>Email:</strong> friendsdabha@gmail.com</p>
  </section>
  


 <!-- Optional: Contact Form (if needed) -->
  <!--
  <section class="contact-form">
    <form>
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br><br>

      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email"><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5"></textarea><br><br>

      <button type="submit">Send Message</button>
    </form>
  </section>
  -->

  <footer>
    <p>&copy; 2025. Designed by  Hari Prasath E</p>
  </footer>

</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - FRIENDS DABHA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
    <!-- Repeat for 09 items -->
    <div class="menu-item">
      <img src="shavarma.png" alt="shavarma">
      <h3>Shavarma</h3>
      <p>Shavarma with the taste of Arabia</p>
    </div>
    <div class="menu-item">
      <img src="parota.png" alt="Parota with Beef Curry">
      <h3>Parota&Beef</h3>
      <p>Parota&Beef with vegies.</p>
    </div>
    <div class="menu-item">
      <img src="mac.png" alt="Mac & Cheese">
      <h3>Creamy Cheese</h3>
      <p>Sooo Cheese.. with bacon.</p>
    </div>
    <div class="menu-item">
      <img src="brownie.png" alt="Brownie">
      <h3>Choco Brownie</h3>
      <p>Spoongy Brownie which melts in your mouth</p>
    </div>
    <div class="menu-item">
      <img src="payasam.png" alt="Payasam">
      <h3>Creamy Payasam</h3>
      <p>Sweetness with the taste of Payasam.</p>
    </div>
    <div class="menu-item">
      <img src="lobster.png" alt="Lobster">
      <h3>Hot Lobster</h3>
      <p>Juicy Lobster with soft bun</p>
    </div>
    <div class="menu-item">
      <img src="prawn.png" alt="Prawn">
      <h3>GRILLED PRAWN</h3>
      <p>Juicy prawn with garlic Flavour.</p>
    </div>
    <div class="menu-item">
      <img src="coke.png" alt="Coke">
      <h3>Zero Sugar Coke</h3>
      <p>Cold and Refreshing Coke.</p>
    </div>
    <div class="menu-item">
      <img src="crab.png" alt="Crab">
      <h3>Smoked Crab</h3>
      <p>Green coloured spicy Crab.</p>
    </div>
    <div class="menu-item">
      <img src="pancake.png" alt="Pancakes">
      <h3>Pancakes</h3>
      <p>Fluffy pancakes with syrup.</p>
    </div>
    <div class="menu-item">
      <img src="ice cream.png" alt="Ice Cream">
      <h3>Ice Cream</h3>
      <p>Vanilla, chocolate, and strawberry scoops.</p>
    </div>
    <div class="menu-item">
      <img src="fries.png" alt="Fries">
      <h3>French Fries</h3>
      <p>Crispy golden fries.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by Hari Prasath E</p>
  </footer>
</body>
</html>

index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - FRIENDS DABHA</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1> FRIENDS DABHA</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>
  <section class="banner">
    <img src="hotel4.jpg"Delicious Food Banner">
  </section>



  <section class="content">
    <h2>Welcome!</h2>
    <p>Discover the best food in town, made with passion and fresh ingredients.</p>
  </section>

  

  <footer>
    <p>&copy; 2025. Designed by Hari Prasath E</p>
  </footer>
</body>
</html>

style.css

/* style.css */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fdf6f0;
  color: #333;
}

header {
  background-color: #8B0000;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.banner img {
  width: 100%;
  height: auto;
}

section.content {
  padding: 40px;
  text-align: center;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px;
}

.menu-item {
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #fff;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.admin-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.contact-info {
  padding: 40px;
  text-align: center;
  line-height: 1.8;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}



```
## OUTPUT:
<img width="1917" height="1070" alt="1" src="https://github.com/user-attachments/assets/d40180c8-d39f-4165-b7fa-54a247442e0d" />
<img width="1913" height="1044" alt="2" src="https://github.com/user-attachments/assets/de58241d-79d1-43c4-b871-f9b56cbb4e23" />
<img width="1907" height="1063" alt="3" src="https://github.com/user-attachments/assets/45ee2061-f20c-4c9d-970e-a5cec3ebc7c7" />
<img width="1904" height="1063" alt="4" src="https://github.com/user-attachments/assets/3ea9f4bb-0d85-43e1-92a5-2f323b0c9d1b" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
