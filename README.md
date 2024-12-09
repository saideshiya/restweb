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
```
<!DOCTYPE html>
<html lang="en">
<head style="background-color: black;">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body background="c:\Users\admin\Downloads\Another Round.jpg">
    
    <header align="center"  style="background-color: rgb(7, 3, 4) " ><h1 style="color:rgba(255, 171, 199, 0.849)"> Welcome to Our Restaurant</h1>
        <h2 style="color: aliceblue;"> The Spicy Hut </h2>
        <nav>
            <p><a href="file:///C:/Users/admin/tt/Eligibility-for-Admission/index.html" style="color: beige;"> ~ MENU </a> <a href="file:///C:/Users/admin/tt/Eligibility-for-Admission/index.html" style="color: beige;"> ~ HOME </a> <a href="file:///C:/Users/admin/tt/Eligibility-for-Admission/index.html" style="color: beige;">~ ABOUT </a> </p>
        </nav>
    </header>
    <section id="about" style="color: beige;">
        <h1>About Us :</h1>
        <p> <h2>Welcome to My Restaurant, where we serve delicious food made from the freshest ingredients. Our chefs are passionate about creating dishes that bring joy and flavor to every meal, fully made of fresh and hygienic things.</h2></p>
        <p>for further information contact = <a href="@spicy_hut.com"> @spity_hut.com</a> / <a href="080 102 203 000"> 080 102 203 000</a></p>
        
    </section>

    <section id="contact" style="color: beige;">
        <h2>Contact Us</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section><br>
    <body background="c:\Users\admin\Downloads\Wallpaper for Free Downl.html">
    <section style="color: bisque;">
        <center><br>
           <br> <a href="c:\Users\admin\Downloads\Black digital signage catering menu template idea.jpg"> <button>➡ MENU CARD </button> </a>
        <h1> 1. Our Delicious Dishes ❤‍🔥</h1>        
        <img src="file:///C:/Users/admin/Downloads/realistic%20pizza.webp" alt="Delicious Pizza" width="1000" height="600"><p><h2> # cheesy pizza 🍕</h2></p>
        <img src="c:\Users\admin\Downloads\Easy Chocolate Cheesecake Bars - Baker by Nature.jpg" alt="Tasty Dessert" width="1000" height="600"><P> <h2># tasty Dessert 🍰</h2></P>
        <img src="c:\Users\admin\Downloads\Indian Chili Paneer Step By Step Recipe - Tasty Cooking Aroma.jpg"alt="paneer masala" width="1000" height="600"><P> <h2># paneer masala 🥗</h2> </P>
        <img src="c:\Users\admin\Downloads\Easy Tteokbokki (Spicy Korean Rice Cakes) ll Korean food ll Yammy tasty Tteokbokki.jpg" width="1000" height="600"><P><h2># Tteokbokki 🥘</h2></P>
        <img src="c:\Users\admin\Downloads\9dc26749-c449-4ec1-82c9-4b279ed8c427.jpg" width="1000" height="600" ><P><h2># korean gigimbab 🍚</h2> </P>
        <img src="c:\Users\admin\Downloads\barbecue food.jpg" alt=" barbecue"  width="1000" height="600" ><P> <h2># spicy barbecue 🍗</h2></P>
        <img src="c:\Users\admin\Downloads\Food.jpg" alt=" madurai parotta " width="1000" height="600"><P> <h2># madurai parotta 🌯</h2></P>
        <img src="c:\Users\admin\Downloads\Watermelon Lemonade Without Added Sugar.jpg" width="1000" height="600"> <p><h2># watermelon juice 🍷</h2></p>
        <img src="c:\Users\admin\Downloads\1c347bc3-4e3e-4c4e-9a7a-98ccd86d9419.jpg" alt="ice cream" width="1000" height="600"><p><h2># choco icecream 🍨</h2></p>
        <hr width="2000px" height="200px">
        </center>
    </section>

    <section style="color: beige;">
        <center>
        <h1 style="color: beige;"> 2. dining styles</h1>
        <img src="c:\Users\admin\Downloads\Colourful, magical restaurant design for Enfes in Milton Keynes_ — Bar & Restaurant Interior Designers - Creative & Original.jpg" width="1000" height="600"><p><h2> Family space</h2></p>
        <img src="c:\Users\admin\Downloads\Rajwada- The Traditional Style Restaurant In Jabalpur _ Design cloud (1).jpg" width="1000" height="600" ><p><h2> Group dining</h2></p>
        <img src="c:\Users\admin\Downloads\Commercial Restaurant Banquette Seating Design.jpg" width="1000" height="600" > <P><h2>Banquette seating </h2></P>
        <img src="c:\Users\admin\Downloads\Mesas terraza.jpg" width="1000" height="600"> <p> <h2> Roof Top </h2></p>
        </center>
    </section>
    <section style="color: bisque;" style="width: 1000;">
    <center><hr>
        <h2> TABLE BOOKING </h2>
    <form width="1000"> 
        <label for="seatings">Name:</label>
        <input type="text" id="seatings" seat="type" required><br>

        <br><label for="seatings">no.of ppl:</label>
        <input type="text" id="seatings" seat="type" required>
         <label for="seatings">phone no:</label>
        <input type="text" id="seatings" seat="type" required><br>
        <br> <label for="seatings"> seating code:</label>
        <input type="text" id="seatings" seat="type" required><br>
        <br> <label for="seatings">Date:</label>
        <input type="text" id="seatings" seat="type" required>
         <label for="seatings">Day:</label>
        <input type="text" id="seatings" seat="type" required><br>
          <br> <button align="center" style="background-color: aquamarine;"> <a href="c:\Users\admin\Downloads\tenor (1).gif"> DONE </a> </button>         
    </center>
    <section style="color: azure;">
        <center>
             <h1 style="color: aquamarine;"> ONLINE FOOD ORDER  </h1>
             <iframe src="https://www.food.com/" width="1000" height="600"></iframe>
        </center><hr>
    </section>
    </form>
    </section><br>
    <br>
    <br>
    <section style="color: beige;">
    <h1 style="color: bisque;"> PAYMENT SITE :</h1>
    <p> UPI : <a href="https://www.npci.org.in/what-we-do/upi/product-overview"> PAYMENT </a></p>
    <p> NET BANKING :<a href="https://retail.onlinesbi.sbi/npersonal/"> PAYMENT </a></p>
    </section>
     <h1 style="color: beige;">DETAILS :</h1><p style="color: aqua;"> PHONE NUMBER : <a href="tel:+123456789" style="color: aliceblue;">+1-234-567-8900</a> </p><p style="color: aqua;"> MAIL ID :<a href="@spicy_hit.com"> @spicy_hut.com</a></p>
    <p style="color: aquamarine;"> ADDRESS : <p style="color: azure;"> Tamil Nadu , Chennai , CoraFood Street no : 123 , opposite to the jayam mahal  </p> </p>
    <p style="color: aquamarine;"> WEBSITE : <a href="WWW.spityhut.com"> WWW.spityhut.com </a></p> 
    <p style="color: aquamarine;"> INSTA ID : <a href="Spi_y@hut"> Spi_y@hut</a></p>
    
    <section style="color: blanchedalmond;" width="500" height="100">
        <center>
            <span style="font-size:30px ;"> &#9733;&#9733;&#9733;&#9733;&#9734;</span>
            <h2> THANK YOU FOR VISITING OUR PAGE ! </h2>
        </center>
    </section>
    <center>       
    <h2 style="background-color: azure;" > copyright©spicy_hut reg no : 24005381  </h2>
    </center>
    </body>
```

## OUTPUT:
![Screenshot (84)](https://github.com/user-attachments/assets/addb2a17-4e71-4f28-9543-9aff79208c2a)






## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
