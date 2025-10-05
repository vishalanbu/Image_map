# Ex04 Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
```
map.html

<html>
    <head></head>
    <title>map</title>
    </head>
    <body>
        <h1 align="center">kalakurichi</h1>
        <h3 align="center">gopinath s-25012981</h3>

<img src="saran.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="vellu fruit shop" title="vellu fruit shop" href="shop.html" coords="741,108,555,169" shape="rect">
    <area target="" alt="rahman textiles" title="rahman textiles" href="textiles.html" coords="867,535,1053,505,931,447,833,460" shape="poly">
    <area target="" alt="halloween mens wear" title="halloween mens wear" href="menswear.html" coords="367,244,192,358" shape="rect">
    <area target="" alt="vaigai lodge" title="vaigai lodge" href="lodge.html" coords="527,0,140" shape="circle">
    <area target="" alt="karthik medicals" title="karthik medicals" href="medicals.html" coords="153,128,79" shape="circle">
</map>
</body>
</html>

medicals.html

<html>
    <head>
        <title>karthik medicals</title>
    </head>
    <body bgcolor="blue">
        <h1 align="center">kartik medicals</h1>
        <p>Karthik Medicals is a well-known pharmacy in Kallakurichi, offering a wide range of medicines and healthcare products. The staff is knowledgeable and provides excellent customer service.</p>
        <br>Address: 15, Main Rd, Kallakurichi, Tamil Nadu
   </body>
</html>

lodge.html

<html>
    <head>
        <title>vaigai lodge</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">vaigai lodge</h1>
        <p>The Hotel Vaigai is located at the heart of the town with adequate parking. The room was neat and well furnished. The service personnel were courteous and well .</p>
        <br> Price range: Hotel Vaigai Residency Price starts at INR 2,263/Night
   </body>
</html>

medicals.html

<html>
    <head>
        <title>haloween menswear</title>
    </head>
    <body bgcolor="red">
        <h1 align="center">haloween menswear</h1>
        <p>Haloween Menswear is a popular clothing store in Kallakurichi, known for its trendy and affordable</p>
        <br>Address: 21, Main Rd, Kallakurichi, Tamil Nadu 606202
   </body>
</html>

textile.html
<html>
    <head>
        <title>rahman textiles</title>
    </head>
    <body bgcolor="lime">
        <h1 align="center">rahman textiles</h1>
        <p>Trendy readymade garment retailer offering a wide range of men's shirts. Address: 1 Pariyar Nagar 4thstreet, Adambakkam-600088</p>
    </body>
</html>

shop.html

<html>
    <head>
        <title>vellu fruit shop</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">vellu fruit shop</h1>
        <p>Vellu Fruits Shop Kottaimedu, kallakurichi. Vellu Fruits Shop. 5.02 Ratings. Bus Stand Kottaimedu.</p>
        <br>Address: Bus Stand, Kottaimedu, Kallakurichi, Tamil Nadu 606213
    </body>
</html>

```
# OUTPUT
![alt text](<Screenshot 2025-10-05 222643.png>)
![alt text](IMG-20251005-WA0028.jpg)
![alt text](IMG-20251005-WA0029.jpg)
![alt text](IMG-20251005-WA0032.jpg)
![alt text](IMG-20251005-WA0032-1.jpg)
# RESULT
The program for implementing image maps using HTML is executed successfully.
