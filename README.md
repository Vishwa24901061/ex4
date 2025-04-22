# Ex04 Places Around Me
## Date: 22/04/2025
## Name: V VISHWA
## Register No: 212224110062

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
#map.html
<head>
    <title>My City</title>
</head>
<body>
    <h1 allign="center">
        <font color="red"><center><b>Anna Nagar</b></font></center>
    </h1>
    <h3 allign="center">
        <font color="blue"><center><b>VISHWA V (212224110062)</b></font></center>
    </h3>
    <center>
        <img src="c:\Users\admin\OneDrive\Pictures\Screenshots\Screenshot 2025-04-22 161059.png" usemap="#MyCity" height="1083" width="1908">
        <map name="MyCity">
            <area shape="rect" coords="970,720,1101,817" href="home.html" title="My Home Town">
            <area shape="rect" coords="736,726,976,863" href="mall.html" title="VR Mall">
            <area shape="rect" coords="698,856,938,993" href="movie.html" title="Rohini Theatre">
            <area shape="rect" coords="1062,632,1250,725" href="food.html" title="Kora Food Street">
            <area shape="rect" coords="1323,589,1511,682" href="park.html" title="Anna Tower Park">
        </map>
    </center>
</body>
</html>

#home.html

```<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="#fff3e0">
<h1 align="center">
<font color="#36454F"><b>shanthi Colony</b></font>
</h1>
<h3 align="center">
<font color="#FFD700"><b>My Home Town</b></font>
</h3>
<hr size="3" color="#ffccbc">
<p align="justify">
<font face="Georgia" size="5" color="#212121">
    A home is much more than just a physical structure; it's a space where people live, build memories, and feel a sense of belonging and comfort
    Physical Shelter: Protects inhabitants from environmental elements like weather and hazards.
    Emotional Comfort: Offers a personal space for relaxation and emotional well-being.
    Social Hub: Acts as a gathering space for family, friends, and social activities.
    Identity and Expression: Reflects personal and cultural values through decor, structure, and usage



</font>
</p>
</body>
</html>

#movie.html 

<head>
    <title>My Home Town</title>
    </head>
    <body bgcolor="#e8f5e9">
    <h1 align="center">
    <font color="#388e3c"><b>Rohini Cinemas</b></font>
    </h1>
    <h3 align="center">
    <font color="#fbc02d"><b>Chennai's Top Theatre for FDFS</b></font>
    </h3>
    <hr size="3" color="#a5d6a7">
    <p align="justify">
    <font face="Georgia" size="5" color="#1b5e20">
    
        Rohini Silver Screens, commonly referred to as Rohini Cinemas, is a highly celebrated multiplex located in Chennai, India. Established in 1991 as a single-screen theater, it has grown significantly over the years. In 1999, it became India’s first six-screen multiplex and was rebranded as Rohini Silver Screens in 2016. It is renowned for its state-of-the-art amenities, luxurious interiors, and a vibrant movie-watching atmosphere
    
    </font>
    </p>
    </body>
    </html>

#food.html 
<head>
    <title>My Home Town</title>
    </head>
    <body bgcolor="#f5f5f5">
    <h1 align="center">
    <font color="#2e3a87"><b>Kora Food Street</b></font>
    </h1>
    <h3 align="center">
    <font color="#ff6347"><b>Chennai's Top Food Street</b></font>
    </h3>
    <hr size="3" color="#dcdcdc">
    <p align="justify">
    <font face="Arial, sans-serif" size="4" color="#333333">
    
        Kora Food Street is a vibrant food destination in Chennai, Tamil Nadu, known for its unique concept and diverse culinary options. Located in Anna Nagar, it brings together a wide variety of street food and gourmet cuisines, all served from outlets crafted from repurposed shipping containers. The lively ambiance, colorful decor, and enticing aromas create an exciting dining experience
    
    </font>
    </p>
    </body>
    </html>

#park.html

<head>
    <title>My Home Town</title>
    </head>
    <body bgcolor="#f3e5f5">
    <h1 align="center">
    <font color="#8e24aa"><b>Anna Tower Park</b></font>
    </h1>
    <h3 align="center">
    <font color="#0288d1"><b>Landmark of Anna Nagar</b></font>
    </h3>
    <hr size="3" color="#e1bee7">
    <p align="justify">
    <font face="Georgia" size="5" color="#4a148c">
    
        Tower Park, officially known as Anna Nagar Tower Park or Dr. Visveswaraya Tower Park, is a popular recreational spot located in Anna Nagar, Chennai. Established in 1968 as part of the World Trade Fair, the park features lush greenery, well-maintained pathways, and Chennai’s tallest tower, which stands at 135 feet. Visitors can climb the tower for panoramic views of the city, making it a highlight of the park
    
    </font>
    </p>
    </body>
    </html>

#mall.html

<head>
    <title>My Home Town</title>
    </head>
    <body bgcolor="#fff3e0">
    <h1 align="center">
    <font color="#d32f2f"><b>VR Chennai</b></font>
    </h1>
    <h3 align="center">
    <font color="#0288d1"><b>Chennai's Iconic Mall</b></font>
    </h3>
    <hr size="3" color="#ffccbc">
    <p align="justify">
    <font face="Georgia" size="5" color="#212121">
    
    VR Chennai, located in Koyambedu, is one of the most iconic shopping destinations in Chennai, known for its vast array of products and affordable pricing. The store is famous for offering everything from textiles to household goods, making it a one-stop-shop for customers. VR Chennai is especially popular for its wide selection of sarees, apparel, and traditional garments, attracting people from all over the city. The massive shopping complex spans several floors, providing a wide range of products in various categories, including electronics, footwear, and toys. Its convenient location in Koyambedu makes it easily accessible to customers from surrounding areas. The store is known for its bustling environment and large crowds, especially during festive seasons, offering exciting deals and discounts. VR Chennai has built a strong reputation over the years for offering quality products at competitive prices, which has contributed to its success. The shopping experience at VR chennai is lively and vibrant, with music and colorful displays adding to the atmosphere. Despite its immense popularity, the store has faced challenges related to overcrowding, but it remains one of the city's top retail destinations. Overall, VR Chennai in Koyambedu continues to be an essential part of Chennai's retail landscape, catering to a wide variety of customers.
    
    </font>
    </p>
    </body>
    </html>
```

## OUTPUT

![Screenshot 2025-04-22 162148](https://github.com/user-attachments/assets/c842aa64-09aa-4d46-a0bb-311acb9de4f0)

![Screenshot 2025-04-22 162354](https://github.com/user-attachments/assets/4d2b9810-ae70-4c69-a99b-d7bb9c1b9deb)

![Screenshot 2025-04-22 162411](https://github.com/user-attachments/assets/87199024-28fa-47e4-9987-d4a3e50ab351)

![Screenshot 2025-04-22 162437](https://github.com/user-attachments/assets/8232edc2-7757-49f2-a944-f536fc716fea)

![Screenshot 2025-04-22 162451](https://github.com/user-attachments/assets/4da99882-8f7a-4fb5-8267-bca483b5a1e0)

![Screenshot 2025-04-22 162426](https://github.com/user-attachments/assets/0e3fee48-2041-4687-a452-2df01105d175)

## RESULT
The program for implementing image maps using HTML is executed successfully.
