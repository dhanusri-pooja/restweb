# Ex.07 Restaurant Website
## Date:08.05.2025

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
front.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FUSION FEAS</title>
</head>

<style>

    body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #dee1bde2;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
    background-color: rgb(152, 69, 116);
    border-radius: 10px;
}

.menu{
    background-color: rgb(118, 193, 173);
    align-items: center;
    color: rgb(146, 89, 114);
    padding: 25px;
    border-radius: 30px;
}
.logo {
    display: flex;
    align-items: center;
}

.logo img {
    width: 50px;
    height: 80px;
    margin-right: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

.footer{
    padding: 10px 10px;
}

nav ul li a {
    text-decoration: none;
    font-family: 'Times New Roman', Times, serif;
    font-size: large;
    color: #0f1110;
    font-weight: bold;
}

.offer-txt{
    color: rgba(11, 22, 228, 0.47);
}
.hours{
    width: 300px;
    height: 80px;
}

.banner {
    text-align: center;
    background-image: url("Rest background.jpg");
    padding: 10px 40px;
    color: #4f9797;
    border-radius: 10px;
    margin: 25px;
}

.banner h2 {
    font-size: 2.5em;
    margin: 0 0 20px;
}

.features {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: rgb(52, 179, 162);
}

.feature {
    text-align: center;
    font-family: 'Times New Roman', Times, serif;
    font-size: large;
    background-color: rgb(132, 171, 169);
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgb(177, 98, 191);
    flex: 1;
    margin: 0 10px;
}

.feature h3 {
    font-size: 1.5em;
    margin-bottom: 20px;
}

.feature img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}

p {
    text-align: left;
}

ul {
    text-align: left;
}

.copy{
    margin-left: auto
}

.hyperlink{
    color: rgb(61, 78, 75);
}
    

</style>
<body>
    <header>
        <div class="logo">
            <img src="static/see.png" alt="see food">
            <h1 style="font-family: 'Times New Roman', Times, serif;"> SEE FOOD </h1>
        </div>
        <nav class="menu">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="admin.html">Admin</a></li>
                <li><a href="contact.html">Contact us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        
        <section class="banner" style="background-image: url(homepage.jpg)";>         
             <h2 class="offer-txt style="font-family: 'Times New Roman', Times, serif;">Better taste to make you better</h2>
            <h2 class="offer-txt" style="font-family: 'Times New Roman', Times, serif;"> WELCOMING YOU TO THE FUSION FEAST -THE INDIAN RESTAURANT! </h2>
            
            <p class = 'offer-txt' style="font-size: large ; font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;">The World's No. 1 high quality Indian Restaurant.As gentle as a mother's love...
            Food is better when we eat together...Come hungry leave happy...Because we care for your taste..A place to provide you with the best....</p>
        </section>
        <section class="features">
            <div class="feature">
                <h3>Today's menu</h3>
                <img src="menu.html" alt="Our New Menu">
                <p> Today’s menu offers a variety of dishes made with fresh ingredients. Enjoy flavorful starters, delicious main courses, indulgent desserts, chef’s specials, and refreshing drinks. 
                    Every bite is crafted to delight your taste buds!</p>
                
            </div>
            <div class="feature">
                <h3>Book a table</h3>
                <img src="table.jpg" alt="Book a table">
                <p>Reserve your table at Fusion feast for a memorable dining experience. Whether it’s a dinner, celebration, or casual gathering, enjoy our warm ambiance and delicious flavors.
                     Book now for the perfect meal!!</p>
                
            </div>
            <div class="feature">
                <h3>Opening timings</h3>
                <img src="open.jpg" class="hours" alt="Opening Hours">
                <p> Visit us during our convenient hours</p>
                <ul>
                    Monday - Friday: 07:00 AM - 02:00 AM <br>
                    Saturday: 07:00 AM - 11:00 PM <br>
                    Sunday: 07:00 AM - 10:00 PM <br>
                </ul>
                <p> A place for hungry people....!</p>
            </div>
        </section>
        <footer>
            <div class="logo">
                <img src="Fusion feast logo.jpg" class="footer" alt="Fusion feast Logo">
            </div>
            
                <palign="center" class="copy">&copy; Copyright Fusion feast</p>

            <h3align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
                Developed and designed by K Dhanusri pooja</h3>
        </footer>
    </main>
</body>
</html>

home.html


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOME</title>
</head>
<div class="logo">
    <top left>
    <img src="see.png" width="50" height="50"alt="seefood">
</top left>

</div>
    <div class="nav-list">
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Admin</a>
        <a href="contact.html">Contact us</a>
    </div>


<style>
    header{
        font-size: 50px;
        font-style:initial;
        background-color: rgb(221, 172, 233);
    }
    .content{
        font-size: medium;
        padding: 10px;
        font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif
    }
</style>


<body bgcolor="lavender">
    <center>
        <header style="color: rgb(100, 8, 88);">
        SEE FOOD
        </header>

        <img src="hotel.jpg" width="500" height="400">
        
        <div class="content">
        <h2> Welcome to FUSION FEAST Restaurant- A place where taste meets your expectations!!</h2>
        <h2>A short note about fusion feast</h2>
        <p style="font-family:cursive; font-size: large;">
            As you step into FUSION FEAST, you’re greeted by a cozy and inviting atmosphere. Soft, golden light from elegant chandeliers fills the room, highlighting the warm 
            and plush furnishings.The air is filled with the irresistible aroma of freshly baked bread, exotic spices, and slow-cooked dishes, setting the stage for an 
            unforgettable dining experience.The menu offers a delightful mix of global flavors, expertly prepared by skilled chefs. Each dish is beautifully presented, 
            with a perfect blend of textures and flavors that will excite your taste buds. At FUSION FEAST, every meal is more than just food—it’s an experience that
            surprises and delights, leaving you wanting more.Come and enjoy a world of delicious flavors and spices that will make your visit truly special!
            Many traditional dishes are prepared with fresh, locally sourced ingredients that bring out the genuine flavors of the cuisine.This not only ensures 
            quality but also supports local farmers and producers.We are serving traditional dishes often by using age-old techniques, like slow cooking, wood-fire roasting,
             fermenting, or clay pot cooking,to achieve the original taste and texture.The experience of traditional dining extends to the ambiance, often featuring decor, music,
              and even tableware inspired by the culture being celebrated.We often feature dishes specific to festivals or seasons, such as Christmas roasts, Ramadan delicacies, 
              or spring harvest specials.
        </p>
        </div>

        <div class="content">
            
            <img src="Locally sourced ingredients.jpg" width="300" height="200">
            <img src="Traditional cooking tech.jpg" width="300" height="200">
            <img src="Ambiance n experience.jpg" width="300" height="200">
            <img src="seasonal fests.jpg" width="300" height="200">
            
        </div>
        <footer>
            
                <p align="center" class="copy">&copy; Copyright Fusion feast</p>

            <h3 align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
                Developed and designed by K Dhanusri pooja</h3>
        </footer>
    </center>
    <div class="logo">
        <img src="Fusion feast logo.jpg" width="50" height="50" class="footer" alt="Fusion feast Logo">
    </div>
    

</body>
</html>

menu

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <div class="logo">
        <img src="Fusion feast logo.jpg" width="50" height="50" alt="FUSION FEAST Logo">
    </div>
    <title>FUSION FEAST - Menu</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #f6efef;
            background-color: #f4f4f4;
            box-sizing: border-box;
        }

        *, *::before, *::after {
            box-sizing: inherit;
        }

        header {
            background: #cbddf0;
            color: white;
            padding: 15px 20px;
            display: flex;
            align-items: center;
            justify-content: space-between;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 1.8rem;
            font-family: 'Playfair Display', serif;
        }

        header nav a {
            text-decoration: none;
            color: white;
            font-weight: 500;
            margin: 0 15px;
            transition: color 0.3s ease;
            font-size: 1rem;
        }

        header nav a:hover {
            color: #ff95da;
        }

        .menu-container {
            padding: 40px 20px;
            background: #ffffff;
            text-align: center;
        }

        .menu-container h1 {
            font-size: 2.5rem;
            color: #a1c6eb;
            margin-bottom: 30px;
            font-family: 'Playfair Display', serif;
        }

        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
        }

        .menu-item {
            background: white;
            border-radius: 15px;
            box-shadow: 0 6px 10px rgba(0, 0, 0, 0.15);
            width: 280px;
            overflow: hidden;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            text-align: left;
        }

        .menu-item img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .menu-item:hover {
            transform: scale(1.05);
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.2);
        }

        .menu-item:hover img {
            transform: scale(1.1);
        }

        .menu-details {
            padding: 15px;
        }

        .menu-details h3 {
            font-size: 1.4rem;
            color: #8cc5ff;
            margin-bottom: 10px;
            font-weight: 500;
        }

        .menu-details p {
            font-size: 1rem;
            color: #d0cfcf;
            margin-bottom: 10px;
        }

        .menu-details .price {
            font-weight: bold;
            font-size: 1.1rem;
            color: #e74c3c;
        }

        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px 0;
        }

        footer a {
            color: #ff5722;
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

            .menu-items {
                flex-direction: column;
                gap: 20px;
            }

            .menu-item {
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
        <h1>FUSION FEAST</h1>
        <nav>
            <a href="home.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Admin</a>
            <a href="contact.html">Contact us</a>
            
        </nav>
    </header>

    <div class="menu-container">
        <h1>OUR MENU</h1>
        <div class="menu-items">

            <div class="menu-item">
                <img src="veg momo.jpg" alt="Veg momos">
                <div class="menu-details">
                    <h3>Veg momos</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="aloo.jpg" alt="Aloo tikki">
                <div class="menu-details">
                    <h3>Aloo tikki</h3>
                    <p class="price">₹120/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="prawn.jpg" alt="Prawn fry">
                <div class="menu-details">
                    <h3>Prawn fry</h3>
                    <p class="price">₹1800/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="fish.jpg" alt="Fish fry">
                <div class="menu-details">
                    <h3>Fish fry</h3>
                    <p class="price">₹1500/-</p>
                </div>
            </div>

            <div class="menu-item">
                <img src="tc.jpg" alt="Tandoori chicken">
                <div class="menu-details">
                    <h3>Tandoori chicken</h3>
                    <p class="price">₹2000/-</p>
                </div>
            </div>
            
            <div class="menu-item">
                <img src="sfb.jpg" alt="South indian meals">
                <div class="menu-details">
                    <h3>see food boil</h3>
                    <p class="price">₹2000/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="hc.jpg" alt="Hot chocolate">
                <div class="menu-details">
                    <h3>Hot chocolate</h3>
                    <p class="price">₹100/-</p>
                </div>
            </div>
            <div class="menu-item">
                <img src="cappu.jpg" alt="cappuccino">
                <div class="menu-details">
                    <h3>cappuccino</h3>
                    <p class="price">₹120/-</p>
                </div>
            </div>
            
            
                   
            
            </div>
        </div>
    </div>

    <footer>
            
        <p align="center" class="copy">&copy; Copyright Fusion feast</p>

    <h3 align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
        Developed and designed by K Dhanusri pooja</h3>
</footer>
</center>
<div class="logo">
<img src="Fusion feast logo.jpg" width="50" height="50" class="footer" alt="Fusion feast Logo">
</div>


</body>
</html>

admin


<!DOCTYPE html>
 <html lang="en">
 <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Administration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
        }
        header {
            background-color: #edafe1;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav {
            background-color: #000000;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: rgb(49, 140, 140);
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background: rgb(222, 201, 222);
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .team-section {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        .team-member {
            text-align: center;
            background: #f6c1ee;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        .team-member img {
            width: 100%;
            height: 80%;
            max-width: 150px;
            border-radius: 20%;
            margin-bottom: 10px;
        }
        .team-member h3 {
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        .team-member p {
            font-size: 0.9em;
            padding-bottom: 15px;
            color: #2f2e2f;
        }
        .picture{
            width: 100px;
            height: 100px;
            
        }
    </style>
 </head>
 <body>
    <header>
        <top left>
        <div class="logo">
            <img src="Fusion feast logo.jpg" width="100" height="100" alt="FUSION FEAST Logo">
        <h1>Administration</h1>
    </top left>
    </header>
    <nav>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Admin</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <main>
        <div class="container">
            <center>
            <h2>OUR TEAM</h2>
        </center>
            <div class="team-section">
                <div class="team-member">
                    <img src="me.png"  alt="ME.jpg">
                    <h3>DHANUSRI FOUNDER</h3>
                 </div>
                
            
                <div class="team-member">
                    <img src="reshika.jpg" alt="reshika.jpg">
                    <h3>RESHIKA MANAGER</h3>

                </div>
                <div class="team-member">
                    <img src="ashi.jpg" alt="ashi.jpg">
                    <h3>ASHIKA DIRECTOR</h3>
            
                </div>
                <div class="team-member">
                    <img src="aswini.jpg" alt="aswini.jpg">
                    <h3>ASWINI-Master chef</h3>
                    
                </div>
                <div class="team-member">
                    <img src="cari.jpg" alt="cari.jpg">
                    <h3>CLARISA-MASTER Chef</h3>
                 
                    
                </div>
            </div>
        </div>
        <footer>
            <div class="logo">
                <img src="Fusion feast logo.jpg" width="50" height="50" class="footer" alt="Fusion feast Logo">
            </div>
            
                <palign="center" class="copy">&copy; Copyright Fusion feast</p>

            <h3align="center" style="font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif; font-style: italic; ">
                Developed and designed by K Dhanusri pooja</h3>
        </footer>
    </main>
 </body>
</html>
```


## OUTPUT:
![Screenshot 2025-05-22 145144](https://github.com/user-attachments/assets/7b02c639-fe65-412d-acdb-a3a487f51a4b)
![Screenshot 2025-05-22 145320](https://github.com/user-attachments/assets/738c5eb8-b015-48bb-a64d-937a1ae7d069)
![Screenshot 2025-05-22 145358](https://github.com/user-attachments/assets/ad2104a7-57cf-4fac-9189-13a3fcaefdf8)
![Screenshot 2025-05-22 145414](https://github.com/user-attachments/assets/6c3c0410-d4f6-41fd-b9a5-1e1a88217dc3)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
