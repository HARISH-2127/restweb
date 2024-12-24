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

<html>
<head>
    <meta charset="UTF-8">
    
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
    <title>About Us - ASTRO FOODS </title>
    
    <style>
    
        body {
            background-color: rgb(85, 228, 13);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgba(7, 12, 12, 0.075);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(14, 239, 40);
        }
        nav a {
            color: rgb(246, 10, 10);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(10, 212, 248);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .content {
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.6;
            text-align: justify;
        }
        footer {
            background-color: rgb(209, 253, 33);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>About ASTRO FOODS </h1>
      
    </header>
    
    <nav>
    
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Our Story</h2>
        <div class="content">
            <p>Welcome to ASTRO FOODS, where we bring together a love for fresh, delicious meals and a passion for hospitality. Established with the goal of creating memorable dining experiences, Java Foods is your go-to destination for a delightful culinary journey.</p>
            <p>Our team is committed to using the finest ingredients to prepare dishes that reflect authenticity and innovation. Whether you're here for a hearty meal, a light snack, or a sweet treat, our menu is designed to cater to every craving.</p>
            <p>We take pride in our warm and inviting atmosphere, perfect for family gatherings, friendly get-togethers, or a quiet meal on your own. At Java Foods, we believe food is more than just sustenance—it's an experience, and we are thrilled to share it with you.</p>
        </div>
    </section>
    <footer>
        <p>&copy; ASTRO FOODS. All Rights Reserved.</p>
        <p>Designed And Devloped by: HARISH S</p>
    </footer>
</body>
</html>


<html>
  
<head>
  
    <meta charset="UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Contact Us - ASTRO FOODS </title>
    <style>
        body {
            background-color: rgb(188, 94, 250);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(79, 253, 247);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(243, 77, 31);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(61, 230, 97);
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .contact-info {
            max-width: 600px;
            margin: 0 auto;
            line-height: 1.6;
        }
        footer {
            background-color: rgb(237, 240, 89);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>

    
</head>

<body>
  
    <header>
    
        <h1>Contact Us</h1>
    </header>
    <nav>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>A warm welcome</h2>
        <div class="contact-info">
            <p><strong>Phone:</strong> 8015015341</p>
            <p><strong>Email:</strong> ASTROFOODS@gmail.com</p>
            <p><strong>Address:</strong> 21/3  ANNA NAGAR ROAD , Chennai</p>
            <p>we value your feedback</p>
    </section>
    <footer>
        <p>&copy; ASTRO FOODS. All Rights Reserved.</p>
        <p> Designed And Devloped by:  HARISH S</p>
    </footer>
</body>


</html>



<html>
  
<head>
  
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - ASTRO FOODS</title>
    <style>
        body {
            background-color: rgb(244, 76, 216);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(68, 231, 220);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(234, 83, 69);
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(70, 242, 141);
        }
        .welcome {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 50px;
        }
        .welcome h1 {
            font-size: 2.5rem;
        }
        .welcome p {
            font-size: 1.2rem;
            margin: 20px 0;
        }
        .features {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            padding: 20px;
            text-align: center;
        }
        .feature {
            margin: 10px;
            padding: 20px;
            border: 1px solid silver;
            border-radius: 5px;
            width: 300px;
        }
        footer {
            background-color: rgb(242, 229, 91);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
    
</head>

<body>
  
    <header>
    
        <h1>Welcome to ASTRO FOODS</h1>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="welcome">
        <h1>Your Destination for Exquisite Cuisine</h1>
        <p>ASTRO FOODS offers a wide range of delicious dishes made from the freshest ingredients. Experience the taste of perfection with every bite!</p>
    </div>
    <section class="features">
        <div class="feature">
            <h3>Fresh Ingredients</h3>
            <p>We use only the freshest and highest-quality ingredients to prepare our dishes.</p>
        </div>
        <div class="feature">
            <h3>Family-Friendly</h3>
            <p>Enjoy a welcoming and comfortable atmosphere perfect for family gatherings.</p>
        </div>
        <div class="feature">
            <h3>Exceptional Service</h3>
            <p>Our friendly staff is here to make your dining experience unforgettable.</p>
        </div>
    </section>
    <footer>
        <p>&copy; ASTRO FOODS . All Rights Reserved.</p>
        <p> Designed And Devloped by: HARISH S</p>
    </footer>
</body>

</html>



<html>
  
<head>
  
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - ASTRO FOODS</title>
    <style>
        body {
            background-color: rgb(245, 83, 220);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgb(92, 223, 225);
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: rgb(85, 241, 90);
        }
        nav a {
            color: rgb(248, 97, 97);
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color: rgb(198, 224, 114);
        }
        section {
            padding: 20px;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            text-align: center;
        }
        .menu-item {
            border: 1px solid silver;
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color: rgb(205, 205, 87);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>

<body>
  
    <header>
    
        <h1>Our Menu</h1>
        
    </header>
    
    <nav>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About</a>
        <a href="contact.html">Contact</a>
    </nav>
    <section>
        <h2>Explore Our Dishes</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-24 190406.png" alt="briyani">
                <h3>briyani</h3>
                <p>A flavorful and spicy Indian appetizer made with juicy chicken , steamed to have a tasty perfection.</p>
            </div>
            <div class="menu-item">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-24 190924.png" alt="Parotta 95 Masala">
                <h3>Parotta 95 Masala</h3>
                <p>A rich and creamy North Indian curry with soft parotta in a buttery tomato-based gravy.</p>
            </div>
            <div class="menu-item">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-24 191242.png" alt="grill">
        
             <h3>grill</h3>
                <p>grill is an american based dish made of chicken fired to juicy flavour.</p>
            </div>
        </div>
    </section>
    <footer>
        <p>&copy; ASTRO FOODS . All Rights Reserved.</p>
        <p> Designed And Devloped by: HARISH S</p>
    </footer>
</body>
</html>


<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ASTRO FOODS</title>
    <style>
        body {
            background-color: cornsilk;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color:grey;
            color: white;
            padding: 15px 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color:chocolate;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
        }
        nav a:hover {
            background-color:grey;
        }
        .hero {
             background-color:navajowhite;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .hero h1 {
            font-size: 3rem;
        }
        section {
            padding: 20px;
            text-align: center;
        }
        .menu {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .menu-item {
            border: 1px solid rgb(51, 170, 103);
            border-radius: 5px;
            margin: 10px;
            padding: 20px;
            width: 300px;
        }
        .menu-item img {
            max-width: 100%;
            border-radius: 5px;
        }
        footer {
            background-color:rgb(240, 247, 115);
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
    </style>
</head>
  
<body>
  
    <header>
    
        <h1>ASTRO FOODS</h1>
    </header>
    <nav>
        <a href="home.html">home</a>
        <a href="about.html">About</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
    </nav>
    <div class="hero">
        <h1>Welcome to Our Restaurant</h1>
    </div>
    <section id="about">
        <h2>About Us</h2>
        <p>We are passionate about serving delicious food made with fresh ingredients. Join us for an unforgettable dining experience!</p>
    </section>
    <section id="menu">
        <h2>Our Menu</h2>
        <div class="menu">
            <div class="menu-item">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-24 190406.png">
                <h3>briyani</h3>
                <p>A flavorful and spicy Indian appetizer made with juicy chicken , steamed to have a tasty perfection.</p>
            </div>
            <div class="menu-item">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-24 190924.png">
                <h3>parotta 95</h3>
                <p>A rich and creamy North Indian curry with soft parotta in a buttery tomato-based gravy.</p>
            </div>
            <div class="menu-item">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2024-12-24 191242.png">
                <h3>grill</h3>
                <p>grill is an american based dish made of chicken fired to juicy flavour.</p>
            </div>
        </div>
    </section>
    <section id="contact">
        <h2>Conta8015015341ct Us</h2>
        <p>Phone:</p>
        <p>Email:ASTROFOODS@gmail.com</p>
        <p>Address: 21/3 ANNA NAGAR ROAD ,Chennai</p>
    </section>
    <footer>
        <p>&copy; ASTRO FOODS. All Rights Reserved.</p>
    </footer>
</body>
</html>
 

## OUTPUT:

![Screenshot 2024-12-24 202218](https://github.com/user-attachments/assets/535ccbb0-4e95-4fa0-b6c7-1491ab7d4356)

![Screenshot 2024-12-24 202245](https://github.com/user-attachments/assets/74e7e8f0-efd4-4593-b102-8ce95cf6d990)

![Screenshot 2024-12-24 202304](https://github.com/user-attachments/assets/0dd8034e-b5ac-44c4-be49-1c1735ec9b9e)

![Screenshot 2024-12-24 202343](https://github.com/user-attachments/assets/dbc84374-dc6d-4162-b029-eeb568ebeb6f)

![Screenshot 2024-12-24 202429](https://github.com/user-attachments/assets/24b88737-833b-421e-a1b6-af7c1d63adb7)

![Screenshot 2024-12-24 202444](https://github.com/user-attachments/assets/944497b5-0582-4a37-8aa0-af03baf07ea7)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
