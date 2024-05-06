# Ex.07 Software Product Company Website
## Date: 06/05/2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

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
Home.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Company</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-image: url(web.avif);
            background-size: cover;
        }

        header {
            background-color: rgba(51, 51, 51, 0.7); 
            color: #fff;
            padding: 10px 0;
            display: flex; 
            justify-content: space-between; 
            align-items: center; 
            font-family: 'verdana', 'verdana';
        }

        nav {
            overflow: hidden;
            background-color: #2478a1;
        }

        nav a {
            float: right;
            display: block;
            color: #fff;
            text-align: left;
            padding: 15px 20px;
            text-decoration: none;
        }

        .company-name {
            font-size: 40px;
            margin: 20px;
        }

        nav a:hover {
            background-color: rgba(111, 205, 248, 0.7); 
            color: #333;
        }

        .content {
            padding: 100px 0px 200px; 
            color:#fff;
            text-align: left;
            font-size: 50px; 
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1 class="company-name">Technex Solution </h1>
</header>

<nav>
    <a href="contact.html">Contact us</a>
    <a href="products.html">Products</a>
    <a href="people.html">People</a>
    <a href="home.html">Home</a>
</nav>

<div class="content">
    <div class="company-description">
        <pre>
            Welcome to Technex Solution,
            where innovation meets collaboration
            TechNex Solutions is a leading IT company 
            specializing in providing innovative 
            technology solutions to businesses
            
        </pre>
    </div>
</div>

<footer>
    &copy; Created and developed by M.Hashwatha
</footer>

</body>
</html>
```

```
people.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Our Team</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #80c0d7;
        }

        header {
            background-color: #8b3737;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }

        .team-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .person {
            width: 250px;
            margin: 20px;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .person img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        footer {
            background-color: #8b3737;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>OUR TEAM</h1>
</header>

<div class="team-container">
    <div class="person">
        <img src="person-1.jpeg" alt="Person 1">
        <h3>Vecteezy</h3>
        <p>CEO</p>
    </div>

    <div class="person">
        <img src="person-2.avif" alt="Person 2">
        <h3>Robert taylor</h3>
        <p>COO</p>
    </div>

    <div class="person">
        <img src="person-3.webp" alt="Person 3">
        <h3>Brycewalker</h3>
        <p>CTO</p>
    </div>

    <div class="person">
        <img src="person-4.jpg" alt="Person 4">
        <h3>justin Henderson</h3>
        <p>Marketing Manager</p>
    </div>

    <div class="person">
        <img src="person-5.png" alt="Person 5">
        <h3>Joon Park</h3>
        <p>Product Manager</p>
    </div>

    <div class="person">
        <img src="person-6.jpeg" alt="Person 6">
        <h3>Wilson</h3>
        <p>Software Engineer</p>
    </div>
</div>

<footer>
    <p>&copy; Created and developed by M.Hashwatha</p>
</footer>

</body>
</html>
```

```
products.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PRODUCT CATALOG</title>
    <style>
        body {
            font-family: 'Verdana';
            margin: 0;
            padding: 0;
            background-image: url(360_F_327387577_Lz3kFftViJSj4CGcNjiRCuv9oHVUHUkS.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
        }

        .product-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .product {
            color: #f4f4f4;
            width: 200px;
            margin: 20px;
            padding: 10px;
            text-align: center;
        }

        .product img {
            width: 150px;
            height: 150px;
            margin-bottom: 10px;
        }

        .product-details{
            background-color: #ffffff;
            padding: 10px;
            border-radius: 5px;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 5px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<div class="product-container">
    <div class="product">
        <img src="h7RghmVhRSKgsqSpRCgiL-1200-80.jpg" alt="Product 1">
        <h3>Laptop</h3>
        <p>Product 1</p>
    </div>

    <div class="product">
        <img src="03.jpg" alt="Product 1">
        <h3>Mouse</h3>
        <p>Product 2</p>
    </div>

    <div class="product">
        <img src="Nzxt-H7-Flow-E-ATX-Mid-Tower-Cabinet-White-1.jpg" alt="Product 1">
        <h3>CPU</h3>
        <p>Product 3</p>
    </div>

    <div class="product">
        <img src="41oqUzGdwxL._AC_.jpg" alt="Product 1">
        <h3>Mobile phone</h3>
        <p>Product 4</p>
    </div>

    <div class="product">
        <img src="2609034453.jpg" alt="Product 1">
        <h3>Printer</h3>
        <p>Product 5</p>
    </div>

    <div class="product">
        <img src="1 (17).webp" alt="Product 1">
        <h3>Watch</h3>
        <p>Product 6</p>
    </div>

</div>

<footer>
    <p>&copy; Created and developed by M.Hashwatha.</p>
</footer>

</body>
</html>
```

```
contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #7c8996;
        }

        header {
            background-color: #719ecb;
            color: #fff;
            text-align: center;
            padding: 20px 0;
        }

        .contact-container {
            max-width: 800px;
            margin: 0 auto;
            padding: 50px 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .contact-info {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
            padding: 40px;
            flex: 1;
            margin-right: 20px;
        }

        .contact-info h2 {
            color: #343a40;
            font-size: 28px;
            margin-bottom: 20px;
        }

        .contact-info p {
            color: #6c757d;
            font-size: 18px;
            margin-bottom: 10px;
        }

        .contact-info p:last-child {
            margin-bottom: 0;
        }

        .contact-info a {
            color: #007bff;
            text-decoration: none;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        #map {
            flex: 1;
            border-radius: 10px;
            overflow: hidden;
        }

        footer {
            background-color: #95c4f3;
            color: #fff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>Contact Us</h1>
</header>

<div class="contact-container">
    <div class="contact-info">
        <h2>Company Name</h2>
        <p><strong>Address:</strong> 123 Main Street Anytown, London, UK</p>
        <p><strong>Email:</strong> <a href="mailto:info@example.com">TechnexSolution@gmail.com</a></p>
        <p><strong>Phone:</strong> <a href="tel:+15551234567">+1 (444) 132-4567</a></p>
        
    </div>
    <div id="map">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d384288.2393136501!2d-74.1180869943186!3d40.70582519288286!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c259e26a514215%3A0x52963a5addd52a99!2sNew%20York%2C%20USA!5e0!3m2!1sen!2sca!4v1646476982727!5m2!1sen!2sca" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
      </div>
</div>

<footer>
    <p>&copy; Created and developed by M.Hashwatha</p>
</footer>

</body>
</html>
```

## OUTPUT:
![alt text](01.png)
![alt text](02.png)
![alt text](03.png)
![alt text](04.png)

## RESULT:

The program for designing software company website using HTML and CSS is completed successfully.
