# Ex.07 Restaurant Website
# Date:05.12.2025
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
index.html (HOME PAGE):
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>FOOD FEST</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="title">FOOD FEST</div>

<header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="administration.html">Team</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <h1>Welcome to Food Fest</h1>
    <p>Experience delicious food crafted with love and passion.</p>
</section>

<footer>
    <p>© 2024 Food Fest</p>
</footer>

</body>
</html>

```
menu.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Food Fest - Menu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="title">FOOD FEST</div>

<header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="administration.html">Team</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="menu-section">
    <h2>Our Specials</h2>

    <div class="menu-items">
        <div class="menu-item">
            <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2021/06/chicken-biryani.jpg">
            <h3>Chicken Biryani</h3>
            <p>₹250</p>
        </div>

        <div class="menu-item">
            <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2020/12/masala-dosa.jpg">
            <h3>Dosa</h3>
            <p>₹80</p>
        </div>

        <div class="menu-item">
            <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2022/03/chicken-65.jpg">
            <h3>Chicken 65</h3>
            <p>₹180</p>
        </div>
    </div>
</section>

<footer>
    <p>© 2024 Food Fest</p>
</footer>

</body>
</html>

```
administration.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Food Fest - Team</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="title">FOOD FEST</div>

<header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="administration.html">Team</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="administration">
    <h2>Meet Our Team</h2>

    <div class="team-member">
        <img src="https://randomuser.me/api/portraits/men/32.jpg">
        <h3>Arun Kumar</h3>
        <p>Founder</p>
    </div>

    <div class="team-member">
        <img src="https://randomuser.me/api/portraits/men/45.jpg">
        <h3>Ravi Shankar</h3>
        <p>Head Chef</p>
    </div>
</section>

<footer>
    <p>© 2024 Food Fest</p>
</footer>

</body>
</html>

```
contact.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Food Fest - Contact</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="title">FOOD FEST</div>

<header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="administration.html">Team</a></li>
            <li><a href="contact.html">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="contact">
    <h2>Contact Us</h2>
    <p>Email: foodfest@gmail.com</p>
    <p>Phone: +91 98765 43210</p>
</section>

<footer>
    <p>© 2024 Food Fest</p>
</footer>

</body>
</html>

```
style.css (NEW COLORS):
```
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #fdf6ec;
}

.title {
    background-color: #1b5e20;
    color: white;
    text-align: center;
    font-size: 32px;
    padding: 15px;
}

header {
    background-color: #2e7d32;
    padding: 10px;
}

nav ul {
    list-style: none;
    text-align: center;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    text-align: center;
    padding: 80px 20px;
}

.menu-section {
    text-align: center;
    padding: 40px;
}

.menu-items {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
}

.menu-item {
    background-color: white;
    width: 250px;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.1);
}

.menu-item img {
    width: 100%;
    border-radius: 10px;
}

.administration {
    text-align: center;
    padding: 40px;
}

.team-member {
    display: inline-block;
    margin: 30px;
}

.team-member img {
    width: 200px;
    border-radius: 50%;
}

.contact {
    text-align: center;
    padding: 40px;
}

footer {
    background-color: #1b5e20;
    color: white;
    text-align: center;
    padding: 10px;
}

```
# OUTPUT:
<img width="852" height="495" alt="Screenshot 2025-12-28 183649" src="https://github.com/user-attachments/assets/131698cc-6040-4ce8-9e72-610d95e34a00" />
<img width="846" height="469" alt="Screenshot 2025-12-28 183720" src="https://github.com/user-attachments/assets/df38d679-12ef-4257-be9e-aebb9bc35120" />
<img width="1099" height="365" alt="Screenshot 2025-12-28 183738" src="https://github.com/user-attachments/assets/4860ef3b-3c38-42fe-b9e2-0b7a85f84348" />



# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
