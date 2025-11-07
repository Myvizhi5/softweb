# Ex.07 Restuarant Website
## Date:07/11/2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
rest.html
<!DOCTYPE html>
<html lang="en"?>
    <head>
        <title>MM RESTAURANT</title>
        
    </head>
    <style>
        body{
            background-image: url("img.png");
            background-size: cover;
            background-position: center;
        }
        .nav-list{
            position: absolute;
            top: 30px;
            left: 70%;
            transform:  translatex(10%);
        }
        .nav-list a{
            display: inline blocks;
            margin: 0 10px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            color: white;
        }
        .nav-list a:hover{
            color: rgb(235, 9, 149);
        }
    </style>
        <div class="nav-list">
        
        <a href="rest.html">Home</a>
        <a href="contact.html">contact</a>
        <a href="menu.html">menu</a>
        <a href="administration.html">Administration</a>

        </div>
    <body style="color: white;">
        
        <center>
            <h1 style="color:rgb(255, 255, 255); font-size: 50px;">MM RESTAURANT</h1>
    <table> 
        <center>
        <tr>
            <td><img src="5.png" style="width: 250px; height: 235px;"></td>
            <td><img src="4.png" style="width:250px; height: 235px;"></td>
            <td><img src="3.png" style="width:250px; height: 235px;"></td>
            <td><img src="2.png" style="width:250px; height: 235px;"></td>
            <td><img src="1.png" style="width:250px; height: 235px;"></td>
        </tr>
        </center>
        <tr>
            <td><h3 style="color:white;"><center>MEALS</center></h3></td>
            <td><h3 style="color:white;"><center>CHEESE PASTA</center></h3></td>
            <td><h3 style="color:azure;"><center>BIRIYANI</center></h3></td>
            <td><h3 style="color:azure;"><center>MUTTON CURRY</center></h3></td>
            <td><h3 style="color:azure;"><center>PAN CAKE</center></h3></td>
        </tr>
    </table>
    <h2>OUR DISHES:
        <h2><center>ARE:</center></h2>
    </h2>
        <p style="font-family: 'Times New Roman',Times, serif";><center>Warm Welcome to our MM RESTAURANT, where flavors come alive and every bite tells a story. Our carefully crafted menu, warm ambiance, and impeccable service create the perfect setting for unforgettable dining experiences. Whether you're craving bold culinary creations or comforting classics, we’re here to delight your taste buds. Welcome to a place where passion for food meets perfection. Join us and savor the extraordinary!

        </p> 
        <hr>
        <tr>
            <td><h4 style="font-size: larger;"><center>HEALER TO STRESS</center></h4></td>
        </tr>
         <footer align="center" id="copywrite">
            Designed and developed by MYVIZHI M &copy 2025
        </footer>
    </body>        
</html>

contact.html

<html>
    <head>
        <title> CONTACT </title>
    </head>
    <style>
        
        body{
        
            background-image: url("o.png");
            background-size: cover;
            background-position: center;
        }
        body{
            display: inline blocks;
            margin:0 600px;
            font-family:MS Sans Serif;
            text-decoration: none;
            font-size: 23px;
            font-weight: bolder;
            color: lavender(217, 231, 239);
            position:absolute;
            top: 200px;
        }
    </style>
    <div class="nav-list">
        
        <a href="rest.html">Home</a>
        <a href="contact.html">contact</a>
        <a href="menu.html">menu</a>
        <a href="administration.html">Administration</a>

        </div>
    <center>
        <section id="contact">  
            <h1 style="color:rgb(255, 255, 255)">CONTACT<h1>
            <h4  style="color:rgb(255, 255, 255)">+91 8903236048 <br> |MM RESTAURANT Restuarant@gmail.com</h4>
            <P  style="color:rgb(255, 255, 255)">ADDRESS: NO.105 SIVAM STREET ,MANNARGUDI,THIRUVARUR <br>
                <br> contact us to place the order<br>
            <hr style="color: rgb(255, 255, 255)"> HEALER TO STRESS<hr/>
            </P>
         </section> 
    </center>
    </body>
</html>


menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - MM RESTAURANT</title>
  <style>
    body { font-family: Arial, sans-serif; background: lightblue; margin: 0; color: #333; }
    .header, .footer { background: purple; color: #fff; text-align: center; padding: 1rem; }
    .header nav ul { list-style: none; display: flex; justify-content: center; padding: 0; }
    .header nav ul li { margin: 0 1rem; }
    .header nav ul li a { color: #fff; text-decoration: none; font-size: 1.1rem; }
    .menu { padding: 2rem; text-align: center; }
    .menu ul { list-style: none; padding: 0; display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; }
    .menu ul li { background: #fff; border: 1px solid #ddd; padding: 1rem; border-radius: 5px; }
    .menu ul li:hover { transform: scale(1.05); transition: transform 0.3s; }
  </style>
</head>
<body>
  <header class="header">
    <h1>TASTY MENU</h1>
    <nav>
      <ul>
        <li><a href="res.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="adminis.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>
<section class="menu">
    <h2>OUR MENU</h2>
    <ul>
        <li>
            <img src="man.png" alt="MANDI" width="150" height="125">
            MANDI - $480
        </li>
        <li>
            <img src="h.png" alt="HONEY CHICKEN" width="150" height="125">
            HONEY CHICKEN - $210
        </li>
        <li>
            <img src="PR.PNG" alt="PRAWN FRY" width="150" height="125">
            PRAWN FRY- $150
        </li>
        <li>
            <img src="F.PNG" alt="FISH MEALS" width="150" height="125">
            FISH MEALS - $450
        </li>
        <li>
            <img src="W.PNG" alt="WAFFLES" width="150" height="125">
            WAFFLES - $130
        </li>
        <li>
            <img src="C.PNG" alt="CROISSANT WITH HOT CHOCOLATE" width="150" height="125">
            CROISSANT WITH HOT CHOCOLATE - $350
        </li>
        <li>
            <img src="r.png" alt="RASAMALAI" width="150" height="125">
            RASAMALAI - $200
        </li>
        <li>
            <img src="b.png" alt="BLUE MOJITO " width="150" height="125">
            BLUE MOJITO - $129
        </li>
        
    </ul>
</section>


administration.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>THE FIRTHOS  RESTAURANT - Administration</title>

    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: darkkhaki;
            background-color: #f63a3a;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #27cbbe;
            color: rgb(69, 171, 199);
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(1, 33, 15, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: rgb(33, 121, 176);
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #2a688b;
        }

        .admin-container {
            padding: 40px 20px;
            background: peachpuff;
            text-align: center;
        }

        .admin-container h1 {
            font-size: 2.5rem;
            color: #315b67;
            margin-bottom: 20px;
            font-family: 'Playfair Display', serif;
        }

        .admin-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .admin-item {
            background: rgb(180, 185, 153);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(159, 154, 149, 0.1);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease;
            text-align: left;
        }

        .admin-item img {
            width: 100%;
            height: 250px;
            object-fit: cover;
        }

        .admin-item:hover {
            transform: scale(1.05);
        }

        .admin-details {
            padding: 15px;
        }

        .admin-details h3 {
            font-size: 1.4rem;
            color: #2c3e50;
            margin-bottom: 8px;
        }

        .admin-details p {
            font-size: 1rem;
            color: #555;
            margin-bottom: 10px;
        }

        footer {
            background: #978b5a;
            color: rgb(123, 154, 169);
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #dba419;
            text-decoration: none;
            font-weight: 500;
            transition: color 0.3s ease;
        }

        footer a:hover {
            color: #ecf0f1;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 1.5rem;
            }

            .admin-items {
                flex-direction: column;
                gap: 20px;
            }

            .admin-item {
                width: 100%;
            }

            header nav a {
                font-size: 0.9rem;
                margin: 0 5px;
            }
        }
    </style>
</head>
<body>    

<header>
        <h1>MM RESTAURANT</h1>
        <nav>
            <a href="rest.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="contact.html">Contact</a>
            <a href="administration.html">Administration</a>
        </nav>
    </header>

    <div class="admin-container">
        <h1>OUR GUARDS</h1>
        <div class="admin-items">
            <div class="admin-item">
                <img src="PAN.jpg" alt="CHIEF CHEF">
                <div class="admin-details">
                    <h3>MYVIZHI</h3>
                    <p>CHIEF CHEF OF THE MM</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="HEM.jpg" alt="SENIOR CHEF">
                <div class="admin-details">
                    <h3>HEMALA</h3>
                    <p>SENIOR CHEF OF THE MM</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="BOO.jpg" alt="JUNIOR CHEF">
                <div class="admin-details">
                    <h3>BUVANA</h3>
                    <p>ASSISTANT MANAGING DIRECTOR</p>
                </div>
            </div>

            <div class="admin-item">
                <img src="EMI.jpg" alt="Assistant Managing Director">
                <div class="admin-details">
                    <h3>EMI</h3>
                    <p>JUNIOR CHEF OF THE MM</p>
                </div>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2024 THE RESTAURANT. All rights reserved. | <a href="resT.html">Back to Home</a></p>
    </footer>

</body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2025-11-07 225045.png>)

![alt text](<Screenshot 2025-11-07 225520.png>)

![alt text](<Screenshot 2025-11-07 225219.png>)

![alt text](<Screenshot 2025-11-07 225506.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
