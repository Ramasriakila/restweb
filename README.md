# Ex.07 Restaurant Website
# Date:12/05/2025
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to our Restaurent</title>
   
    
</head>
<style>
    body{
        background-image: url("C:\\Users\\admin\\Downloads\\wp1874171.jpg");
       
    }
    .ref{
        position: absolute;
        font-size: 600%;
        top: 70%;
        left: 5%;
    }
    .ref1 a{
        font-size: 600%;
        position: absolute;
        top: 420px;
    }
    header{
        font-size: 700%;
    }
    

</style>
<body>
    <center>
        <header style= "color:blanchedalmond;">
            WELCOME TO TASTY BITES RESTAURENT

        </header>
        <div class="ref">
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/home.html" style="color: goldenrod;">HOME</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/menu.html" style="color: goldenrod;">MENU</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/about.html" style="color: goldenrod;">ABOUT</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/contact.html" style="color: goldenrod;">CONTACT</a>
        <a>†</a>
        </div>
        <footer>
            
        </footer>
    </center>
   
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home</title>
</head>

<style>
    header{
        font-size: 620%;
        font-style: oblique;
        background-color: burlywood;
    }
    .content{
        font-size: larger;
        font-family: cursive;
    }
</style>
<body>
    <center>
        <header style="color: crimson;">
            TASTY BITES RESTAURENT
        </header>

        <img src="s.jpg" width="1100" height="500">
        
        <div class="content">
        <p>Welcome to The Tasty Bites  Restaurent: A Wonderful Dining Experience Like No Other
            Here's a mesmerizing description of a restaurant:

            "As you step through the doors of 'TASTY BITES', a symphony of sensory delights envelops you, 
            transporting you to a world of epicurean bliss. Soft, golden light spills from ornate chandeliers, 
            casting a warm glow on the rich, velvety textures of the furnishings.The air is alive with the intoxicating aromas of exotic spices,
            freshly baked bread, and slow-cooked meats, teasing your taste buds and building anticipation for the feast to come.
            As you peruse the menu, your eyes widen with wonder at the innovative fusion of flavors and techniques,
            expertly crafted by the culinary maestros in the kitchen.Each dish is a masterpiece of presentation and taste, 
            with every bite a harmonious balance of textures, temperatures, and flavors that will leave you spellbound and yearning for more.
            In 'TASTY BITES', every meal is a journey of discovery, a sensory odyssey that will delight, surprise, and leave you enchanted. 
            Come, indulge your senses. Enter into the the world and enjoy the spices......
            
                                     "WELCOME TO THE WORLD OF TASTY BITES"</p>
        </div>
    </center>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <center>
        <img src="logo.jpeg">
        </center>
        <div>
    <title>Restaurant Menu</title>
        </div>

    <style>
        /* General body styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('background.jpg'); /* Replace with your background image */
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: #ffffff;
        }

        /* Overlay to darken the background image */
        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            z-index: -1;
        }

        /* Main container */
        .menu-container {
            width: 80%;
            margin: 50px auto;
            background-color: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            color: #333;
        }

        /* Header styles */
        header {
            text-align: center;
            padding: 20px 0;
            color: #fff;
            background-color: #d35400; /* Orange header */
            border-radius: 15px 15px 0 0;
        }

        header h1 {
            margin: 0;
            font-size: 48px;
        }

        /* Section titles */
        h2 {
            text-align: center;
            color: #27ae60; /* Green color */
            border-bottom: 2px solid #d35400;
            font-size: 36px;
            margin-bottom: 20px;
        }

        /* Menu items */
        .menu-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            align-items: center;
        }

        .menu-item img {
            width: 150px;
            height: 100px;
            border-radius: 10px;
            object-fit: cover;
        }

        .menu-item-details {
            flex-grow: 1;
            margin-left: 20px;
        }

        .menu-item-name {
            font-size: 24px;
            font-weight: bold;
            color: #34495e;
        }

        .menu-item-price {
            font-size: 22px;
            color: #e74c3c;
        }

        .description {
            font-size: 16px;
            color: #7f8c8d;
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 20px;
            color: #bdc3c7;
        }

        /* Responsive styles */
        @media screen and (max-width: 768px) {
            .menu-container {
                width: 95%;
            }

            .menu-item {
                flex-direction: column;
                align-items: flex-start;
            }

            .menu-item img {
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>
<div class="overlay"></div>

<header>
    <h1>WELCOME TO OUR RESTAURENT</h1>    
</header>

<div class="menu-container">

    <div class="menu-section">
        <h2>Appetizers</h2>
        <div class="menu-item">
            <img src="buresstta.jpeg" alt="Bruschetta"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Bruschetta</p>
                <p class="description">Grilled bread topped with tomato, basil, and olive oil.</p>
            </div>
            <p class="menu-item-price">$7.99</p>
        </div>

        <div class="menu-item">
            <img src="stuffed mushroom.jpeg" alt="Stuffed Mushrooms"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Stuffed Mushrooms</p>
                <p class="description">Savory mushrooms filled with garlic and cream cheese.</p>
            </div>
            <p class="menu-item-price">$8.99</p>
        </div>
        <div class="menu-item">
            <img src="sandwhich.jpeg"alt="Italian sandwich"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Italian Sandwich</p>
                <p class="description">Bread,vegetables,mushrooms filled with garlic and cream cheese.</p>
            </div>
            <p class="menu-item-price">$10.99</p>
        </div>
        <div class="menu-item">
            <img src="potato.jpeg"alt="Potato Focaccia"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Potato Focaccia</p>
                <p class="description">potato,vegetables, garlic and cream cheese.</p>
            </div>
            <p class="menu-item-price">$11.99</p>
    </div>
    <div class="menu-item">
        <img src="noodles.jpeg"alt="Noodles"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Noodles</p>
            <p class="description">Bread,vegetables,mushrooms filled with garlic and cream cheese.</p>
        </div>
        <p class="menu-item-price">$14.99</p>
</div>
<div class="menu-item">
    <img src="autumn.jpeg"alt="Autumn Fritto Misto"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Autumn Fritto Misto</p>
        <p class="description">fritto,vegetables and cheese.</p>
    </div>
    <p class="menu-item-price">$12.99</p>
</div>
<div class="menu-item">
    <img src="carbonara.jpeg"alt="Carbonara Arancini"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Carbonara Arancini</p>
        <p class="description">sauce,olive oil,vegetables and cheese.</p>
    </div> 
        <p class="menu-item-price">$6.99</p>
    </div>

    <div class="menu-item">
        <img src="salad.jpeg"alt="Caprese Salad"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Caprese Salad</p>
            <p class="description">Bread,vegetables,mushrooms filled with garlic and cream cheese.</p>
        </div>
    <p class="menu-item-price">$6.99</p>
</div>

<div class="menu-item">
    <img src="white.jpeg"alt="White bean"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">White Bean</p>
        <p class="description">Bean, White sauce and cheese.</p>
    </div>
    <p class="menu-item-price">$8.99</p>
</div>
<div class="menu-item">
    <img src="grilled antis.jpeg"alt="Grilled Antipasto"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Grilled Antipasto</p>
        <p class="description">Chicken,sauce, spicy chilles and cheese.</p>
    </div>
    <p class="menu-item-price">$15.99</p>
</div>
<side>
    <img src="eating.jpeg">
</side>

    <div class="menu-section">
        <h2>Main Courses</h2>
        <div class="menu-item">
            <img src="grilled.jpeg" alt="Grilled salmon"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Grilled Salmon</p>
                <p class="description">Freshly caught salmon fillet served with lemon butter sauce.</p>
            </div>
            <p class="menu-item-price">$18.99</p>
        </div>

        <div class="menu-item">
            <img src="steak frites.jpeg" alt="Steak Frites"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Steak Frites</p>
                <p class="description">Juicy steak served with crispy French fries.</p>
            </div>
            <p class="menu-item-price">$22.99</p>
        </div>
    </div>
    <div class="menu-item">
        <img src="chickhen.jpg" alt="Pan Fried Chicken"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Pan Fried Chickhen</p>
            <p class="description">chicken,onions,chilles</p>
        </div>
        <p class="menu-item-price">$20.99</p>
    </div>
</div>
<div class="menu-item">
    <img src="meat.jpeg" alt="Meatloaf"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Meatloaf</p>
        <p class="description">Meat,onions,chilles</p>
    </div>
    <p class="menu-item-price">$30.99</p>
</div>
<div class="menu-item">
    <img src="pie.jpeg" alt="Frito Pie"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Frito pie</p>
        <p class="description">cilli sauce,corns,onions,chilles</p>
    </div>
    <p class="menu-item-price">$25.99</p>
</div>

    <side>
        <img src="e.jpeg">
    </side>
    <div class="menu-section">
        <h2>Desserts</h2>
        <div class="menu-item">
            <img src="chocolate lava cake.jpg" alt="Chocolate Lava Cake"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Chocolate Lava Cake</p>
                <p class="description">Warm cake with a molten chocolate center.</p>
            </div>
            <p class="menu-item-price">$6.99</p>
        </div>

        <div class="menu-item">
            <img src="triamisu.jpeg" alt="Tiramisu"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Tiramisu</p>
                <p class="description">Traditional Italian coffee-flavored dessert with mascarpone.</p>
            </div>
            <p class="menu-item-price">$7.99</p>
        </div>
    </div>
    <div class="menu-item">
        <img src="straw.jpeg" alt="strawberry cake"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Strawbery Cake</p>
            <p class="description">strwberry flavoured cake</p>
        </div>
        <p class="menu-item-price">$9.99</p>
    </div>
    <div class="menu-item">
        <img src="pudding.jpeg" alt="Pudding"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Pudding</p>
            <p class="description">vanilla flavoured Pudding</p>
        </div>
        <p class="menu-item-price">$10.99</p>
    </div>
    <div class="menu-item">
        <img src="blue berry.jpeg" alt="Pana coota"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Pana Cotta</p>
            <p class="description">berry flavoured Pana cotta</p>
        </div>
        <p class="menu-item-price">$8.99</p>
    </div>
    
    <side>
        <img src="swee.jpeg">
    </side>
    <h2>TIME FOR COFFEE</h2>
        <div class="menu-item">
            <img src="COFFE.jpeg" alt="Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Coffee</p>
                <p class="description">Milk,sugar and coffee powder</p>
            </div>
            <p class="menu-item-price">$6.99</p>
        </div>
        <div class="menu-item">
            <img src="co.jpeg" alt="Cold Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Cold Coffee</p>
                <p class="description">Milk,ice cubes,sugar and coffee powder</p>
            </div>
            <p class="menu-item-price">$8.99</p>
        </div>
        <div class="menu-item">
            <img src="BLACK.jpeg" alt="Black Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Black Coffee</p>
                <p class="description">Water,sugar and coffee powder</p>
            </div>
            <p class="menu-item-price">$4.99</p>
        </div>
        <div class="menu-item">
            <img src="CREAM.jpeg" alt="Creamy Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Creamy Coffee</p>
                <p class="description">MILK,cream,sugar and coffee powder</p>
            </div>
            <p class="menu-item-price">$7.99</p>
        </div>
        <div class="menu-item">
            <img src="capuccino.jpeg" alt="Cappucino Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Cappucino Coffee</p>
                <p class="description">MILK,cream,sugar and coffee powder</p>
            </div>
            <p class="menu-item-price">$10.99</p>
        </div>
        <side>
            <img src="le.jpeg">
        </side>
        
    <h3>CONTACT</h3>
    <h4>PHONE: +91 9042358663| EMAIL ID: tastybites@gmail.com</h4>
    <p>ADDRRESS: 10, Nehru Nagar,Avadi, Chennai</p>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>administartion</title>
</head>

<style>
    body{
        background-color: cornsilk;
    }
    header{
        font-size: 450%;
        background-color: burlywood;
    }
    footer{
        font-size: 350%;
        background-color: burlywood;
    }
</style>

<body>
    <center>
    <header>
        OUR COOKING GOD'S
    </header>

    <img src="luna.avif" width="600" height="500">
    <h1>Chef Luna</h1>
    <p style="font-size: x-large;">With over 10 years of culinary excellence, Chef 'Luna' brings a passion for crafting unforgettable dining experiences. Trained at British culinary school,she has worked in some of the most renowned kitchens around the world, blending global flavors with local ingredients.
       At Tasty Bites Restaurant, Chef 'Luna' leads the kitchen with a philosophy rooted in innovation and tradition. Every dish is a masterpiece, carefully curated to excite the palate and tell a story. Specializing in main Courses, the menu reflects a commitment to quality, sustainability, and creativity.
       When not in the kitchen, Chef 'Luna' enjoys exploring local farmers' markets, experimenting with new techniques, and mentoring the next generation of chefs.
       Come taste the passion, creativity, and dedication in every bite at Tasty Bites Restaurent.</p>

    <img src="john.jpg" width="600" height="500">
    <h1>Chef John</h1>
    <p style="font-size: x-large;">Chef 'John' is the creative force behind the scenes, bringing precision, passion, and innovation to every dish. With 6 years of experience in the culinary world,he has honed his skills in kitchens across countries, mastering a variety of cuisines and techniques.
       Under the guidance of our Chief Chef,'John' plays a vital role in maintaining the highest standards of quality and consistency. Known for Starters,he is dedicated to pushing culinary boundaries while respecting the essence of each ingredient.
       Outside the kitchen,'John' enjoys exploring new cuisines, perfecting baking techniques, or studying food pairings, which further inspires his work at Tasty Bites Restaurant.
       Join us  to experience the artistry and dedication of Chef 'John' in every dish.</p>

    <img src="j.jpg" width="600" height="500">
    <h1>Chef Jessy</h1>
    <p style="font-size: x-large;">A true artist in the world of desserts, Chef 'Jessy' brings a touch of magic to every sweet creation at Tasty Bites Restaurant. With a background in baking&pastry arts and over 4 years of experience in top patisseries and fine dining establishments,she transforms simple ingredients into exquisite works of art.
       Specializing in all pastry items, Chef 'Jessy' combines classic techniques with modern flavors. From decadent cakes to delicate pastries, every dessert is crafted to delight both the eye and the palate.
       Chef 'Jessy' believes that a perfect dessert is the grand finale of any meal.Her passion for precision and creativity is evident in every bite, ensuring that each guest’s experience ends on a sweet note.
       Indulge in the culinary artistry of Chef 'Jessy' at Tasty Bites Restaurent where every dessert tells a story.</p>
    
    <img src="c.jpg" width="600" height="500">
    <h1>Chef charles</h1>
    <p style="font-size: x-large;">Chef 'charles' is the creative force behind the scenes, bringing precision, passion, and innovation to every dish. With 3 years of experience in the culinary world,he has honed his skills in kitchens across countries, mastering a variety of cuisines and techniques.
        Under the guidance of our Chief 'Arnold','charles' plays a vital role in maintaining the highest standards of quality and consistency. Known for Starters,he is dedicated to pushing culinary boundaries while respecting the essence of each ingredient.
        Outside the kitchen,'charles' enjoys exploring new cuisines, perfecting baking techniques, or studying food pairings, which further inspires his work at Haunted Restaurant.
        Join us  to experience the artistry and dedication of Chef 'charles' in every dish.</p>

    <img src="d.avif" width="600" height="500">
    <h1>Chef David</h1>
    <p style="font-size: x-large;">Behind every great dish is a team working in harmony, and our Helper Chef plays a vital role in ensuring everything runs smoothly in the kitchen. With a keen eye for detail and a passion for food, our Helper Chef assists in food preparation, maintains cleanliness, and supports the head chef to execute dishes with precision and care.
       From chopping vegetables to prepping ingredients and ensuring that every plate is perfect, they are dedicated to making sure your dining experience is nothing short of exceptional.
       At our restaurant, teamwork is key, and our Helper Chef brings skill, enthusiasm, and a love of cooking to the heart of our kitchen every day.</p>
    
    
    <footer>
        TASTY BITES RESTAURENT
    </footer>
    </center>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contact</title>
</head>
<style>
    header{
        font-size: 420%;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    .address{
        font-size: x-large;
    }
    .contact{
        font-size: larger;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }
</style>
<body>
    <center>
        <header style="color: rgb(176, 20, 20);">TASTY BITES RESTAURENT
        </header>
        <img src="food-menu-restaurant-social-media-cover-template_929596-318.avif" width="750" height="450">
        
       
        </center>
        <side>
            <img src="emoji.jpeg">
        </side>
        <td><h3 style="font-size:25px"> CONTACT </h3></td>
    <td><h4 style="font-size:25px">PHONE: +91 9042358663|EMAIL ID:Tastybites@gmail.com</h4></td> 
    <td><h3 style="font-size:25px"> ADDRESS:10, Anna Nagar, Avadi, Chennai </h3></td>
    </body>
    </html>

```

# OUTPUT:
# Ex.07 Restaurant Website
# Date:2/12/2024
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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to our Restaurent</title>
   
    
</head>
<style>
    body{
        background-image: url("C:\\Users\\admin\\Downloads\\wp1874171.jpg");
       
    }
    .ref{
        position: absolute;
        font-size: 600%;
        top: 70%;
        left: 5%;
    }
    .ref1 a{
        font-size: 600%;
        position: absolute;
        top: 420px;
    }
    header{
        font-size: 700%;
    }
    

</style>
<body>
    <center>
        <header style= "color:blanchedalmond;">
            WELCOME TO TASTY BITES RESTAURENT

        </header>
        <div class="ref">
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/home.html" style="color: goldenrod;">HOME</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/menu.html" style="color: goldenrod;">MENU</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/about.html" style="color: goldenrod;">ABOUT</a>
        <a>†</a>
        <a href="file:///C:/Users/admin/Desktop/WEB/contact.html" style="color: goldenrod;">CONTACT</a>
        <a>†</a>
        </div>
        <footer>
            
        </footer>
    </center>
   
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home</title>
</head>

<style>
    header{
        font-size: 620%;
        font-style: oblique;
        background-color: burlywood;
    }
    .content{
        font-size: larger;
        font-family: cursive;
    }
</style>
<body>
    <center>
        <header style="color: crimson;">
            TASTY BITES RESTAURENT
        </header>

        <img src="s.jpg" width="1100" height="500">
        
        <div class="content">
        <p>Welcome to The Tasty Bites  Restaurent: A Wonderful Dining Experience Like No Other
            Here's a mesmerizing description of a restaurant:

            "As you step through the doors of 'TASTY BITES', a symphony of sensory delights envelops you, 
            transporting you to a world of epicurean bliss. Soft, golden light spills from ornate chandeliers, 
            casting a warm glow on the rich, velvety textures of the furnishings.The air is alive with the intoxicating aromas of exotic spices,
            freshly baked bread, and slow-cooked meats, teasing your taste buds and building anticipation for the feast to come.
            As you peruse the menu, your eyes widen with wonder at the innovative fusion of flavors and techniques,
            expertly crafted by the culinary maestros in the kitchen.Each dish is a masterpiece of presentation and taste, 
            with every bite a harmonious balance of textures, temperatures, and flavors that will leave you spellbound and yearning for more.
            In 'TASTY BITES', every meal is a journey of discovery, a sensory odyssey that will delight, surprise, and leave you enchanted. 
            Come, indulge your senses. Enter into the the world and enjoy the spices......
            
                                     "WELCOME TO THE WORLD OF TASTY BITES"</p>
        </div>
    </center>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <center>
        <img src="logo.jpeg">
        </center>
        <div>
    <title>Restaurant Menu</title>
        </div>

    <style>
        /* General body styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('background.jpg'); /* Replace with your background image */
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: #ffffff;
        }

        /* Overlay to darken the background image */
        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            z-index: -1;
        }

        /* Main container */
        .menu-container {
            width: 80%;
            margin: 50px auto;
            background-color: rgba(255, 255, 255, 0.9);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            color: #333;
        }

        /* Header styles */
        header {
            text-align: center;
            padding: 20px 0;
            color: #fff;
            background-color: #d35400; /* Orange header */
            border-radius: 15px 15px 0 0;
        }

        header h1 {
            margin: 0;
            font-size: 48px;
        }

        /* Section titles */
        h2 {
            text-align: center;
            color: #27ae60; /* Green color */
            border-bottom: 2px solid #d35400;
            font-size: 36px;
            margin-bottom: 20px;
        }

        /* Menu items */
        .menu-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            align-items: center;
        }

        .menu-item img {
            width: 150px;
            height: 100px;
            border-radius: 10px;
            object-fit: cover;
        }

        .menu-item-details {
            flex-grow: 1;
            margin-left: 20px;
        }

        .menu-item-name {
            font-size: 24px;
            font-weight: bold;
            color: #34495e;
        }

        .menu-item-price {
            font-size: 22px;
            color: #e74c3c;
        }

        .description {
            font-size: 16px;
            color: #7f8c8d;
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 20px;
            color: #bdc3c7;
        }

        /* Responsive styles */
        @media screen and (max-width: 768px) {
            .menu-container {
                width: 95%;
            }

            .menu-item {
                flex-direction: column;
                align-items: flex-start;
            }

            .menu-item img {
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>
<div class="overlay"></div>

<header>
    <h1>WELCOME TO OUR RESTAURENT</h1>    
</header>

<div class="menu-container">

    <div class="menu-section">
        <h2>Appetizers</h2>
        <div class="menu-item">
            <img src="buresstta.jpeg" alt="Bruschetta"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Bruschetta</p>
                <p class="description">Grilled bread topped with tomato, basil, and olive oil.</p>
            </div>
            <p class="menu-item-price">$7.99</p>
        </div>

        <div class="menu-item">
            <img src="stuffed mushroom.jpeg" alt="Stuffed Mushrooms"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Stuffed Mushrooms</p>
                <p class="description">Savory mushrooms filled with garlic and cream cheese.</p>
            </div>
            <p class="menu-item-price">$8.99</p>
        </div>
        <div class="menu-item">
            <img src="sandwhich.jpeg"alt="Italian sandwich"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Italian Sandwich</p>
                <p class="description">Bread,vegetables,mushrooms filled with garlic and cream cheese.</p>
            </div>
            <p class="menu-item-price">$10.99</p>
        </div>
        <div class="menu-item">
            <img src="potato.jpeg"alt="Potato Focaccia"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Potato Focaccia</p>
                <p class="description">potato,vegetables, garlic and cream cheese.</p>
            </div>
            <p class="menu-item-price">$11.99</p>
    </div>
    <div class="menu-item">
        <img src="noodles.jpeg"alt="Noodles"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Noodles</p>
            <p class="description">Bread,vegetables,mushrooms filled with garlic and cream cheese.</p>
        </div>
        <p class="menu-item-price">$14.99</p>
</div>
<div class="menu-item">
    <img src="autumn.jpeg"alt="Autumn Fritto Misto"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Autumn Fritto Misto</p>
        <p class="description">fritto,vegetables and cheese.</p>
    </div>
    <p class="menu-item-price">$12.99</p>
</div>
<div class="menu-item">
    <img src="carbonara.jpeg"alt="Carbonara Arancini"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Carbonara Arancini</p>
        <p class="description">sauce,olive oil,vegetables and cheese.</p>
    </div> 
        <p class="menu-item-price">$6.99</p>
    </div>

    <div class="menu-item">
        <img src="salad.jpeg"alt="Caprese Salad"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Caprese Salad</p>
            <p class="description">Bread,vegetables,mushrooms filled with garlic and cream cheese.</p>
        </div>
    <p class="menu-item-price">$6.99</p>
</div>

<div class="menu-item">
    <img src="white.jpeg"alt="White bean"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">White Bean</p>
        <p class="description">Bean, White sauce and cheese.</p>
    </div>
    <p class="menu-item-price">$8.99</p>
</div>
<div class="menu-item">
    <img src="grilled antis.jpeg"alt="Grilled Antipasto"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Grilled Antipasto</p>
        <p class="description">Chicken,sauce, spicy chilles and cheese.</p>
    </div>
    <p class="menu-item-price">$15.99</p>
</div>
<side>
    <img src="eating.jpeg">
</side>

    <div class="menu-section">
        <h2>Main Courses</h2>
        <div class="menu-item">
            <img src="grilled.jpeg" alt="Grilled salmon"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Grilled Salmon</p>
                <p class="description">Freshly caught salmon fillet served with lemon butter sauce.</p>
            </div>
            <p class="menu-item-price">$18.99</p>
        </div>

        <div class="menu-item">
            <img src="steak frites.jpeg" alt="Steak Frites"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Steak Frites</p>
                <p class="description">Juicy steak served with crispy French fries.</p>
            </div>
            <p class="menu-item-price">$22.99</p>
        </div>
    </div>
    <div class="menu-item">
        <img src="chickhen.jpg" alt="Pan Fried Chicken"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Pan Fried Chickhen</p>
            <p class="description">chicken,onions,chilles</p>
        </div>
        <p class="menu-item-price">$20.99</p>
    </div>
</div>
<div class="menu-item">
    <img src="meat.jpeg" alt="Meatloaf"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Meatloaf</p>
        <p class="description">Meat,onions,chilles</p>
    </div>
    <p class="menu-item-price">$30.99</p>
</div>
<div class="menu-item">
    <img src="pie.jpeg" alt="Frito Pie"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Frito pie</p>
        <p class="description">cilli sauce,corns,onions,chilles</p>
    </div>
    <p class="menu-item-price">$25.99</p>
</div>

    <side>
        <img src="e.jpeg">
    </side>
    <div class="menu-section">
        <h2>Desserts</h2>
        <div class="menu-item">
            <img src="chocolate lava cake.jpg" alt="Chocolate Lava Cake"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Chocolate Lava Cake</p>
                <p class="description">Warm cake with a molten chocolate center.</p>
            </div>
            <p class="menu-item-price">$6.99</p>
        </div>

        <div class="menu-item">
            <img src="triamisu.jpeg" alt="Tiramisu"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Tiramisu</p>
                <p class="description">Traditional Italian coffee-flavored dessert with mascarpone.</p>
            </div>
            <p class="menu-item-price">$7.99</p>
        </div>
    </div>
    <div class="menu-item">
        <img src="straw.jpeg" alt="strawberry cake"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Strawbery Cake</p>
            <p class="description">strwberry flavoured cake</p>
        </div>
        <p class="menu-item-price">$9.99</p>
    </div>
    <div class="menu-item">
        <img src="pudding.jpeg" alt="Pudding"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Pudding</p>
            <p class="description">vanilla flavoured Pudding</p>
        </div>
        <p class="menu-item-price">$10.99</p>
    </div>
    <div class="menu-item">
        <img src="blue berry.jpeg" alt="Pana coota"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Pana Cotta</p>
            <p class="description">berry flavoured Pana cotta</p>
        </div>
        <p class="menu-item-price">$8.99</p>
    </div>
    
    <side>
        <img src="swee.jpeg">
    </side>
    <h2>TIME FOR COFFEE</h2>
        <div class="menu-item">
            <img src="COFFE.jpeg" alt="Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Coffee</p>
                <p class="description">Milk,sugar and coffee powder</p>
            </div>
            <p class="menu-item-price">$6.99</p>
        </div>
        <div class="menu-item">
            <img src="co.jpeg" alt="Cold Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Cold Coffee</p>
                <p class="description">Milk,ice cubes,sugar and coffee powder</p>
            </div>
            <p class="menu-item-price">$8.99</p>
        </div>
        <div class="menu-item">
            <img src="BLACK.jpeg" alt="Black Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Black Coffee</p>
                <p class="description">Water,sugar and coffee powder</p>
            </div>
            <p class="menu-item-price">$4.99</p>
        </div>
        <div class="menu-item">
            <img src="CREAM.jpeg" alt="Creamy Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Creamy Coffee</p>
                <p class="description">MILK,cream,sugar and coffee powder</p>
            </div>
            <p class="menu-item-price">$7.99</p>
        </div>
        <div class="menu-item">
            <img src="capuccino.jpeg" alt="Cappucino Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Cappucino Coffee</p>
                <p class="description">MILK,cream,sugar and coffee powder</p>
            </div>
            <p class="menu-item-price">$10.99</p>
        </div>
        <side>
            <img src="le.jpeg">
        </side>
        
    <h3>CONTACT</h3>
    <h4>PHONE: +91 9042358663| EMAIL ID: tastybites@gmail.com</h4>
    <p>ADDRRESS: 10, Nehru Nagar,Avadi, Chennai</p>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>administartion</title>
</head>

<style>
    body{
        background-color: cornsilk;
    }
    header{
        font-size: 450%;
        background-color: burlywood;
    }
    footer{
        font-size: 350%;
        background-color: burlywood;
    }
</style>

<body>
    <center>
    <header>
        OUR COOKING GOD'S
    </header>

    <img src="luna.avif" width="600" height="500">
    <h1>Chef Luna</h1>
    <p style="font-size: x-large;">With over 10 years of culinary excellence, Chef 'Luna' brings a passion for crafting unforgettable dining experiences. Trained at British culinary school,she has worked in some of the most renowned kitchens around the world, blending global flavors with local ingredients.
       At Tasty Bites Restaurant, Chef 'Luna' leads the kitchen with a philosophy rooted in innovation and tradition. Every dish is a masterpiece, carefully curated to excite the palate and tell a story. Specializing in main Courses, the menu reflects a commitment to quality, sustainability, and creativity.
       When not in the kitchen, Chef 'Luna' enjoys exploring local farmers' markets, experimenting with new techniques, and mentoring the next generation of chefs.
       Come taste the passion, creativity, and dedication in every bite at Tasty Bites Restaurent.</p>

    <img src="john.jpg" width="600" height="500">
    <h1>Chef John</h1>
    <p style="font-size: x-large;">Chef 'John' is the creative force behind the scenes, bringing precision, passion, and innovation to every dish. With 6 years of experience in the culinary world,he has honed his skills in kitchens across countries, mastering a variety of cuisines and techniques.
       Under the guidance of our Chief Chef,'John' plays a vital role in maintaining the highest standards of quality and consistency. Known for Starters,he is dedicated to pushing culinary boundaries while respecting the essence of each ingredient.
       Outside the kitchen,'John' enjoys exploring new cuisines, perfecting baking techniques, or studying food pairings, which further inspires his work at Tasty Bites Restaurant.
       Join us  to experience the artistry and dedication of Chef 'John' in every dish.</p>

    <img src="j.jpg" width="600" height="500">
    <h1>Chef Jessy</h1>
    <p style="font-size: x-large;">A true artist in the world of desserts, Chef 'Jessy' brings a touch of magic to every sweet creation at Tasty Bites Restaurant. With a background in baking&pastry arts and over 4 years of experience in top patisseries and fine dining establishments,she transforms simple ingredients into exquisite works of art.
       Specializing in all pastry items, Chef 'Jessy' combines classic techniques with modern flavors. From decadent cakes to delicate pastries, every dessert is crafted to delight both the eye and the palate.
       Chef 'Jessy' believes that a perfect dessert is the grand finale of any meal.Her passion for precision and creativity is evident in every bite, ensuring that each guest’s experience ends on a sweet note.
       Indulge in the culinary artistry of Chef 'Jessy' at Tasty Bites Restaurent where every dessert tells a story.</p>
    
    <img src="c.jpg" width="600" height="500">
    <h1>Chef charles</h1>
    <p style="font-size: x-large;">Chef 'charles' is the creative force behind the scenes, bringing precision, passion, and innovation to every dish. With 3 years of experience in the culinary world,he has honed his skills in kitchens across countries, mastering a variety of cuisines and techniques.
        Under the guidance of our Chief 'Arnold','charles' plays a vital role in maintaining the highest standards of quality and consistency. Known for Starters,he is dedicated to pushing culinary boundaries while respecting the essence of each ingredient.
        Outside the kitchen,'charles' enjoys exploring new cuisines, perfecting baking techniques, or studying food pairings, which further inspires his work at Haunted Restaurant.
        Join us  to experience the artistry and dedication of Chef 'charles' in every dish.</p>

    <img src="d.avif" width="600" height="500">
    <h1>Chef David</h1>
    <p style="font-size: x-large;">Behind every great dish is a team working in harmony, and our Helper Chef plays a vital role in ensuring everything runs smoothly in the kitchen. With a keen eye for detail and a passion for food, our Helper Chef assists in food preparation, maintains cleanliness, and supports the head chef to execute dishes with precision and care.
       From chopping vegetables to prepping ingredients and ensuring that every plate is perfect, they are dedicated to making sure your dining experience is nothing short of exceptional.
       At our restaurant, teamwork is key, and our Helper Chef brings skill, enthusiasm, and a love of cooking to the heart of our kitchen every day.</p>
    
    
    <footer>
        TASTY BITES RESTAURENT
    </footer>
    </center>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contact</title>
</head>
<style>
    header{
        font-size: 420%;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    .address{
        font-size: x-large;
    }
    .contact{
        font-size: larger;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }
</style>
<body>
    <center>
        <header style="color: rgb(176, 20, 20);">TASTY BITES RESTAURENT
        </header>
        <img src="food-menu-restaurant-social-media-cover-template_929596-318.avif" width="750" height="450">
        
       
        </center>
        <side>
            <img src="emoji.jpeg">
        </side>
        <td><h3 style="font-size:25px"> CONTACT </h3></td>
    <td><h4 style="font-size:25px">PHONE: +91 9042358663|EMAIL ID:Tastybites@gmail.com</h4></td> 
    <td><h3 style="font-size:25px"> ADDRESS:10, Anna Nagar, Avadi, Chennai </h3></td>
    </body>
    </html>

```

# OUTPUT:
![Screenshot 2025-05-12 100900](https://github.com/user-attachments/assets/476d2045-6f07-4ccf-9bca-8fd7a3ddb653)
![Screenshot 2025-05-12 100916](https://github.com/user-attachments/assets/cc76d237-f3ba-4a4e-994c-a606104722c1)
![Screenshot 2025-05-12 100935](https://github.com/user-attachments/assets/ab69dba1-f048-4791-90bf-a0a575fd6e9d)
![Screenshot 2025-05-12 101012](https://github.com/user-attachments/assets/73186d53-9a6a-4d0a-9a7e-ab583ddf47c9)
![Screenshot 2025-05-12 101021](https://github.com/user-attachments/assets/b749be24-ab70-40d5-bed3-60d2cea10dd1)
![Screenshot 2025-05-12 101038](https://github.com/user-attachments/assets/8b67edb1-d50d-4aac-bb11-20a415756bca)
![Screenshot 2025-05-12 101054](https://github.com/user-attachments/assets/f4259412-b82b-4a57-b57f-4101753b6f64)
![Screenshot 2025-05-12 101129](https://github.com/user-attachments/assets/cd97efad-2ead-4cf8-9dd6-9c4d0788316f)
![Screenshot 2025-05-12 101136](https://github.com/user-attachments/assets/0c97d241-7e3a-47fa-96d7-feb30297a9c7)
![Screenshot 2025-05-12 101144](https://github.com/user-attachments/assets/2adb86ab-dc59-4291-9593-a8d96e9dd87f)
![Screenshot 2025-05-12 101153](https://github.com/user-attachments/assets/f101b8d6-c9cf-470d-af39-0baff7bd913a)
![Screenshot 2025-05-12 101201](https://github.com/user-attachments/assets/ebd1e018-2eff-43b7-8621-39ccd2f60bd5)
![Screenshot 2025-05-12 101209](https://github.com/user-attachments/assets/267f9009-f7d4-4bbe-8a25-2dcdb9b17e07)
![Screenshot 2025-05-12 101217](https://github.com/user-attachments/assets/2969b1bd-b98f-410b-94a3-c54c38dcff25)
![Screenshot 2025-05-12 101224](https://github.com/user-attachments/assets/cbf0e17a-cc93-4857-b8c4-2970dcc68553)
![Screenshot 2025-05-12 101232](https://github.com/user-attachments/assets/1663e9c7-050d-478c-ae6e-72a6dadf2078)










# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
