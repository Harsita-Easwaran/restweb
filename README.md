# Ex.07 Restaurant Website
## Date: 28/05/2025

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
'''

index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Atisrah</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <div class="logo">
      <img src="logo.jpeg" alt="Atisrah Logo" />
      <h1>Atisrah</h1>
    </div>
    <nav class="menu">
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">Dish Directory</a></li>
        <li><a href="#">Secure a Table</a></li>
        <li><a href="#">About</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="banner">
      <div class="banner-content">
        <h2 class="offer-txt">30% Off This Weekend</h2>
        <p class="offer-txt">
          Treat yourself to your favorite dishes and get 30% off your bill.
          Whether you're dining in or taking out, it's the perfect time to
          savor more and spend less. Limited time only, don’t miss out!
        </p>
      </div>
    </section>

    <section class="features">
      <div class="feature">
        <h3>Our New Menu</h3>
        <img src="menu.jpg" alt="Our Menu" />
        <p>
          From comforting classics to chef’s specials, our menu is crafted to
          delight every palate. Whether you're craving something light or
          indulgent, there's something for everyone. Come taste the flavors
          that make us special!
        </p>
        <a href="#">See our new menu</a>
      </div>

      <div class="feature">
        <h3>Book a table</h3>
        <img src="book.jpg" alt="Book a table" />
        <p>
          Planning a cozy dinner or a celebration? Book your table in advance
          to ensure the perfect spot is waiting for you. Quick, easy, and just
          a few clicks away—your seat at the table is ready!
        </p>
        <a href="#">Book your table now</a>
      </div>

      <div class="feature">
        <h3>Opening Hours</h3>
        <img src="hours.webp" class="hours" alt="Opening Hours" />
        <p>
          We’re excited to serve you! Our doors are open daily with flexible
          hours. Whether for breakfast, lunch, or dinner, we’re here to serve!
        </p>
        <ul>
          <li>Mon - Fri: 11:00 AM - 10:00 PM</li>
          <li>Saturday: 10:00 AM - 11:00 PM</li>
          <li>Sunday: 10:00 AM - 9:00 PM</li>
        </ul>
      </div>
    </section>

    <footer>
      <div class="footer-container">
        <img src="footer.jpg" class="footer-img" alt="Atisrah Logo" />
        <p class="copy">&copy; 2025 Atisrah. All Rights Reserved.</p>
      </div>
    </footer>
  </main>
</body>
</html>


styles.css

body {
  font-family: Roboto, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #b9fbe9;
}

/* Header styling */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 40px;
  background-color: rgb(162, 211, 176);
  border-radius: 0 0 10px 10px;
}

.logo {
  display: flex;
  align-items: center;
}

.logo img {
  width: 50px;
  height: auto;
  margin-right: 10px;
}

nav.menu {
  background-color: black;
  border-radius: 25px;
  padding: 10px 20px;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 20px;
  margin: 0;
  padding: 0;
}

nav ul li a {
  text-decoration: none;
  color: white;
  font-weight: bold;
}

/* Banner section */
.banner {
  background: url('offer.jpg') no-repeat center center/cover;
  padding: 100px 20px;
  text-align: center;
  color: white;
  border-radius: 10px;
  margin: 30px;
}

.banner-content {
  background-color: rgba(0, 0, 0, 0.4);
  padding: 30px;
  border-radius: 12px;
}

.offer-txt {
  margin: 10px auto;
  max-width: 600px;
  font-size: 1.2em;
}

/* Features section */
.features {
  display: flex;
  gap: 20px;
  padding: 40px;
  background-color: rgb(162, 211, 176);
  flex-wrap: wrap;
}

.feature {
  background-color: rgb(240, 202, 133);
  border-radius: 12px;
  padding: 25px;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  flex: 1 1 30%;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.feature img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 8px;
  margin-bottom: 15px;
}

.feature h3 {
  margin-bottom: 10px;
  font-size: 1.5em;
}

.feature p,
.feature ul {
  text-align: left;
  font-size: 1em;
  margin-bottom: 15px;
}

.feature a {
  color: #0044cc;
  font-weight: bold;
  text-decoration: underline;
}

/* Footer */
footer {
  background-color: rgb(162, 211, 176);
  padding: 20px;
  text-align: center;
  border-radius: 10px;
}

.footer-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.footer-img {
  max-width: 100px;
  height: auto;
  margin-bottom: 10px;
}

.copy {
  color: #333;
  font-weight: bold;
}

'''

## OUTPUT:
![alt text](<Restaurant/RestApp/static/Screenshot 2025-05-28 220037.png>)
![alt text](<Restaurant/RestApp/static/Screenshot 2025-05-28 220050.png>)
![alt text](<Restaurant/RestApp/static/Screenshot 2025-05-28 220102.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
