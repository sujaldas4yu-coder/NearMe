# Ex04 Places Around Me
## Date: 28/09/2025 

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
map.html
<html>
    <head>
        <title>Vanakkam Chennai</title>
    </head>
    <body>
    <h1 align="center">
        <b>CHENNAI</b>   
    </h1>
    <h3 align="center">
        <b>SUJAL DAS-25013553</b>
    </h3>
    <center>
    <img src="Screenshot 2025-09-28 161313.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="CIT CHENNAI" title="CIT CHENNAI" href="cit.html" coords="744,85,600,14" shape="rect">
    <area target="" alt="VANDALUR ZOO" title="VANDALUR ZOO" href="zoo.html" coords="890,471,51" shape="circle">
    <area target="" alt="VGP THEME PARK" title="VGP THEME PARK" href="vgp.html" coords="1703,324,61" shape="circle">
    <area target="" alt="SIPCOT IT PARK" title="SIPCOT IT PARK" href="sipcot.html" coords="1450,683,1408,724,1452,771,1509,751,1510,690" shape="poly">
    <area target="" alt="MGM DIZZEE" title="MGM DIZZEE" href="mgm.html" coords="1685,688,1580,781" shape="rect">
</map>
</center>
</body>
</html>

cit.html
<html>
    <head>
        <title>CIT CHENNAI</title>
    </head>
    <body bgcolor="beige">
        <br>
        <br>
    <h1 align="center">
    <font size="100">CHENNAI INSTITUTE OF TECHNOLOGY</font>
    </h1> 
    <center>
    <img src="cit img.jpg" height="450" width="1000" border="5">  
    </center>
    <h2 align="center">Chennai Institute of Technology (CIT) is a private engineering college located in Kundrathur, Chennai, Tamil Nadu, India.<br>Established in 2010, the institution is affiliated with Anna University and approved by the All India Council for Technical Education (AICTE)</h2>
    <h1 align="center" style="color:olive;">NIRF Ranking : 150-200 Band<br>BE Courses with Specifications <br>Masters programs in CAD,CSE,APPLIED ELECTRONICS<br>Sports infrastructure with cricket and football grounds<br>One of the best placement giving colleges in TN
    </h1>
    <h1 align="center" style="color:brown;">
        <font size="70">MOTTO:TRANSFORMING LIVES,EMPOWERING FUTURES</font>
    </h1>

    </body>
 </html>

 zoo.html
 <html>
    <head>
        <title>VANDALUR ZOO</title>
    </head>
    <body bgcolor="white">
        <br>
        <br>
    <h1 align="center">
    <font size="100">ARIGNAR ANNA ZOOLOGICAL PARK</font>
    </h1> 
    <center>
    <img src="zoo img.jpg" height="400" width="550" border="5">  
    </center>
    <h2 align="center">Arignar Anna Zoological Park also known as the Vandalur Zoo, is a zoological garden in Chennai, India.<br> It is located at Vandalur in the south western part of the city, about 32 km (20 mi) from the city center.<br>It is spread over an area of 602 ha (1,490 acres) and is amongst the largest zoos in South Asia. The park is open for public viewing.</h2>
    <h1  align="center" style="color:forestgreen;">
        <font size="50">No. of animals-2,389<br>
                        No. of species-178<br>
                        PARKS INSIDE:CHIDRENS PARK,AQUARIUM,BUTTTERFLY PARK 
</font>
<h1  align="center" style="color:teal;">
    <font size="50">TICKET PRICE:<br>200 (Adults)  50(Kids)</font>

</h1>
    </h1>
    <h1  align="center">
        <font size="50">#RUN TO CONSERVE WILDLIFE </font>
    </h1>
        

    </body>
 </html>
 
vgp.html
<html>
    <head>
        <title>VGP</title>
    </head>
    <body bgcolor="grey">
        <br>
        <br>
    <h1 align="center">
    <font size="100">VGP UNIVERSAL KINGDOM</font>
    </h1> 
    <center>
    <img src="vgp img.jpg" height="450" width="1000" border="5">  
    </center>
    <h2 align="center">VGP Universal Kingdom is an amusement park located in East Coast Road in Chennai, Tamil Nadu, India.<br>The park offering small rides during the early days of its history became a full-fledged amusement park in 1997.<br>VGP Universal kingdom, spread over 44 acres provides several fun and adventure rides for children, youth and adults, including attractions such as Tamil Nadu's first Snow park, Petting Zoo, Beach Live Shows, Paneer fort, a massive water complex and more.<br>VGP 2000 millennium tower, Water cascades, Paneer fort and statueman are some of the main attractions.</h2>
    <h1  align="center" style="color:TEAL;">
        <font size="70">TICKET PRICE-1,250.00 INR</font>
    </h1>
    <h1  align="center">
        <font size="50">FUN IS A SERIOUS BUSINESS</font>
    </h1>
        

    </body>
 </html>
 
 mgm.html
 <html>
    <head>
        <title>MGM</title>
    </head>
    <body bgcolor="tan">
        <br>
        <br>
    <h1 align="center">
    <font size="100">MGM DIZZEE WORLD</font>
    </h1> 
    <center>
    <img src="mgm img.jpg" height="450" width="1000" border="5">  
    </center>
    <h2 align="center">MGM Dizzee World is an amusement park located on East Coast Road in Chennai, Tamil Nadu, India.<br> The park has 47 rides, including a log flume, a Ferris wheel, a roller coaster, and bumper cars.<br>It also has a water park, with sections for kids and adults. It also hosts special seasonal shows.</h2>
    <h1  align="center" style="color:grey;">
        <font size="70">TICKET PRICE-1,179.00 INR</font>
    </h1>
    <h1  align="center">
        <font size="50">SUN.SPLASH.SCREAMS.SMILES</font>
    </h1>
        

    </body>
 </html>

 sipcot.html
 <html>
    <head>
        <title>SIPCOT IT OARK</title>
    </head>
    <body bgcolor="khaki">
        <br>
        <br>
    <h1 align="center">
    <font size="100">SIPCOT IT PARK</font>
    </h1> 
    <center>
    <img src="sipcot img.jpg" height="500" width="600" border="5">  
    </center>
    <h2 align="center">SIPCOT IT Park is an IT park located in Siruseri in the city of Chennai, along the IT Corridor, Chengalpattu District, India.<br>It was developed on 782.51 acres (4 km2) of land by SIPCOT, the State Industries Promotion Corporation of Tamil Nadu, a fully government-owned institution.<br> Founded in June 1971, it is the second-largest IT park in Asia</h2> 
     <h1 align="center">COMPANIES:<br>TATA CONSULTANCY SERVICES<br>     HEXAWARE<br>CAPEGEMINI   <br>  ASPIRE SYSTEMS<br>PRELUDESYS</h1>
        

    </body>
 </html>
```

## OUTPUT
![alt text](<mapapp/static/Screenshot 2025-09-28 161313.png>)
![alt text](<mapapp/static/zoo img.jpg>)
![alt text](<mapapp/static/vgp img.jpg>)
![alt text](<mapapp/static/sipcot img.jpg>)
![alt text](<mapapp/static/cit img.jpg>)
![alt text](<mapapp/static/mgm img.jpg>)






## RESULT
The program for implementing image maps using HTML is executed successfully.
