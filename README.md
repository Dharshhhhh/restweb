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
~~~
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Family Diner</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="banner">
        <div class="banner-content">
            <h1>Welcome to Our Restaurant</h1>
            <p>We serve the finest dishes made with fresh ingredients. Come visit us!</p>
        </div>
    </section>

    <footer>
        <p>Designed by [DHARSHINI]</p>
    </footer>
</body>
</html>

administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - The Family Diner</title>
    <link rel="stylesheet" href="sty.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="administration">
        <h1>Meet Our Team</h1>
        <div class="team-grid">
            <div class="team-member">
                <img src="Screenshot 2024-12-25 141823.png" alt="Admin 1">
                <h2>Dharshini</h2>
                <p>General Manager</p>
            </div>
            <div class="team-member">
                <img src="Screenshot 2024-12-25 141836.png" alt="Admin 2">
                <h2>Saikripa</h2>
                <p>Head Chef</p>
            </div>
            <div class="team-member">
                <img src="Screenshot 2024-12-25 142132.png" alt="Admin 3">
                <h2>Srisha</h2>
                <p>Operations Manager</p>
            </div>
            <div class="team-member">
                <img src="Screenshot 2024-12-25 142122.png" alt="Admin 4">
                <h2>shafadh</h2>
                <p>Marketing Manager</p>
            </div>
            <div class="team-member">
                <img src="Screenshot 2024-12-25 142149.png" alt="Admin 5">
                <h2>Lavanya</h2>
                <p>HR Manager</p>
            </div>
            <div class="team-member">
                <img src="Screenshot 2024-12-25 142217.png" alt="Admin 6">
                <h2>Akshaya</h2>
                <p>Head Waiter</p>
            </div>
        </div>
    </section>

    <footer>
        <p>Designed by [Dharshini R]</p>
    </footer>
</body>
</html>

menu.html

 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - The Family Diner</title>
    <link rel="stylesheet" href="styless.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="menu">
        <h1>Our Menu</h1>
        <div class="menu-grid">
            <div class="menu-item">
                <img src="Screenshot 2024-12-25 142946.png" alt="Pizza Margherita">
                <h2>Pizza Margherita</h2>
                <p>A classic pizza with fresh mozzarella, tomato sauce, and basil.</p>
                <p class="price">rs.400</p>
            </div>
            <div class="menu-item">
            <img src="Screenshot 2024-12-25 143151.png" alt="Pasta Alfredo">
                <h2>Pasta Alfredo</h2>
                <p>Creamy Alfredo sauce with fettuccine pasta.</p>
                <p class="price">rs.200</p>
            </div>
            <div class="menu-item">
                <img src="Screenshot 2024-12-25 143042.png" alt="Cheeseburger">
                <h2>Cheeseburger</h2>
                <p>A juicy beef patty with cheddar cheese, lettuce, and tomato.</p>
                <p class="price">rs.232</p>
            </div>
            <div class="menu-item">
                <img src="Screenshot 2024-12-25 143119.png" alt="Caesar Salad">
                <h2>Caesar Salad</h2>
                <p>Crisp romaine lettuce with Caesar dressing, croutons, and parmesan.</p>
                <p class="price">rs.350</p>
            </div>
            <div class="menu-item">
                <img src="Screenshot 2024-12-25 143015.png" alt="Spaghetti Bolognese">
                <h2>Spaghetti Bolognese</h2>
                <p>Spaghetti pasta topped with rich, flavorful meat sauce.</p>
                <p class="price">rs.555</p>
            </div>
            <div class="menu-item">
                <img src="Screenshot 2024-12-25 143223.png" alt="Grilled Steak">
                <h2>Grilled Steak</h2>
                <p>Juicy grilled steak served with mashed potatoes and veggies.</p>
                <p class="price">rs.499</p>
            </div>
        
        





    </section>

    <footer>
        <p>Designed by [Dharshini R]</p>
    </footer>
</body>
</html>

contact.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - The Family Diner</title>
    <link rel="stylesheet" href="st.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h1>Contact Us</h1>
        <p>Address: 123 Restaurant St., City, Country</p>
        <p>Phone: +123 456 7890</p>
        <p>Email: contact@restaurant.com</p>
    </section>

    <footer>
        <p>Designed by [Dharshini R]</p>
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
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

section {
    padding: 20px;
    margin: 20px;
}

section h1 {
    font-size: 2em;
    color: #333;
}

section .menu ul {
    list-style-type: none;
}

section .menu li {
    margin: 15px 0;
}

section .team-member {
    display: inline-block;
    margin: 10px;
    text-align: center;
}

section .team-member img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

/* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Administration Section */
.administration {
    padding: 40px;
    text-align: center;
    background-color: #fff;
}

.administration h1 {
    font-size: 2.5em;
    margin-bottom: 40px;
    color: #333;
}

/* Grid Layout for Team Members */
.team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 30px;
    justify-items: center;
    padding: 20px;
}

/* Individual Team Member Card */
.team-member {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
    width: 100%;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.team-member:hover {
    transform: scale(1.05); /* Slight zoom effect */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Team Member Image Styling */
.team-member img {
    width: 100%;
    height: 200px; /* Fixed height for uniformity */
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 15px;
}

/* Team Member Name */
.team-member h2 {
    font-size: 1.5em;
    margin: 10px 0;
    color: #333;
}

/* Team Member Designation */
.team-member p {
    font-size: 1em;
    color: #777;
    margin-top: 5px;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

/* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Banner section with background image */
.banner {
    background-image: url('BG\ .1.avif'); /* Change this to the path of your image */
    background-size: cover;
    background-position: center;
    height: 400px; /* Adjust the height of the banner */
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
    position: relative;
}

.banner-content {
    z-index: 1; /* Makes sure the text is above the background */
}

.banner h1 {
    font-size: 3em;
    margin: 0;
}

.banner p {
    font-size: 1.2em;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

/* Other sections styling */
section {
    padding: 20px;
    margin: 20px;
}

section h1 {
    font-size: 2em;
    color: #333;
}

section .menu ul {
    list-style-type: none;
}

section .menu li {
    margin: 15px 0;
}

section .team-member {
    display: inline-block;
    margin: 10px;
    text-align: center;
}

section .team-member img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

/* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Menu Section */
.menu {
    padding: 20px;
    text-align: center;
}

.menu h1 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #333;
}

/* Grid Layout for Menu Items */
.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 20px;
    justify-items: center;
    padding: 20px;
}

/* Individual Menu Item Styles */
.menu-item {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
    width: 100%;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.menu-item:hover {
    transform: scale(1.05); /* Slight zoom effect */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Menu Item Image */
.menu-item img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

/* Menu Item Name */
.menu-item h2 {
    font-size: 1.5em;
    margin: 15px 0;
    color: #333;
}

/* Menu Item Description */
.menu-item p {
    color: #777;
    font-size: 1em;
    margin-bottom: 10px;
}

/* Price Styling */
.menu-item .price {
    font-size: 1.2em;
    font-weight: bold;
    color: #e60000;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

section {
    padding: 20px;
    margin: 20px;
}

section h1 {
    font-size: 2em;
    color: #333;
}

section .menu ul {
    list-style-type: none;
}

section .menu li {
    margin: 15px 0;
}

section .team-member {
    display: inline-block;
    margin: 10px;
    text-align: center;
}

section .team-member img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}
st.css

/* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Administration Section */
.administration {
    padding: 40px;
    text-align: center;
    background-color: #fff;
}

.administration h1 {
    font-size: 2.5em;
    margin-bottom: 40px;
    color: #333;
}

/* Grid Layout for Team Members */
.team-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 30px;
    justify-items: center;
    padding: 20px;
}

/* Individual Team Member Card */
.team-member {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
    width: 100%;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.team-member:hover {
    transform: scale(1.05); /* Slight zoom effect */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Team Member Image Styling */
.team-member img {
    width: 100%;
    height: 200px; /* Fixed height for uniformity */
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 15px;
}

/* Team Member Name */
.team-member h2 {
    font-size: 1.5em;
    margin: 10px 0;
    color: #333;
}

/* Team Member Designation */
.team-member p {
    font-size: 1em;
    color: #777;
    margin-top: 5px;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}   sty.css

/* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Banner section with background image */
.banner {
    background-image: url('BG\ .1.avif'); /* Change this to the path of your image */
    background-size: cover;
    background-position: center;
    height: 400px; /* Adjust the height of the banner */
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    text-align: center;
    position: relative;
}

.banner-content {
    z-index: 1; /* Makes sure the text is above the background */
}

.banner h1 {
    font-size: 3em;
    margin: 0;
}

.banner p {
    font-size: 1.2em;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}

/* Other sections styling */
section {
    padding: 20px;
    margin: 20px;
}

section h1 {
    font-size: 2em;
    color: #333;
}

section .menu ul {
    list-style-type: none;
}

section .menu li {
    margin: 15px 0;
}

section .team-member {
    display: inline-block;
    margin: 10px;
    text-align: center;
}

section .team-member img {
    width: 100px;
    height: 100px;
    border-radius: 50%;
}

/* General styles for the body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4; /* fallback color */
}

/* Header styles */
header {
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent black background */
    color: white;
    padding: 10px 0;
    text-align: center;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Menu Section */
.menu {
    padding: 20px;
    text-align: center;
}

.menu h1 {
    font-size: 2.5em;
    margin-bottom: 20px;
    color: #333;
}

/* Grid Layout for Menu Items */
.menu-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 20px;
    justify-items: center;
    padding: 20px;
}

/* Individual Menu Item Styles */
.menu-item {
    background-color: #fff;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    text-align: center;
    padding: 20px;
    width: 100%;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.menu-item:hover {
    transform: scale(1.05); /* Slight zoom effect */
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
}

/* Menu Item Image */
.menu-item img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

/* Menu Item Name */
.menu-item h2 {
    font-size: 1.5em;
    margin: 15px 0;
    color: #333;
}

/* Menu Item Description */
.menu-item p {
    color: #777;
    font-size: 1em;
    margin-bottom: 10px;
}

/* Price Styling */
.menu-item .price {
    font-size: 1.2em;
    font-weight: bold;
    color: #e60000;
}

/* Footer styles */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
~~~

## OUTPUT:
![sceenshot td](https://github.com/user-attachments/assets/b1d691a0-7eee-452d-af76-96cbfb0b8977)
![screenshot td2](https://github.com/user-attachments/assets/d36300ec-9f20-4b8c-b24f-83e98b9f5ea1)
![screenshot td3](https://github.com/user-attachments/assets/5f3aeb45-634e-4280-ba5e-a5440d90e3ae)
![screenshot td4](https://github.com/user-attachments/assets/497d9a6a-1dcf-4d27-b029-af78a2391d54)
![screenshot td5](https://github.com/user-attachments/assets/b735c23e-467d-4273-86d9-62fb8a560bbb)
![screenshot td6](https://github.com/user-attachments/assets/b6cfcbca-6913-411a-8031-88b8cee939aa)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
