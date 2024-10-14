# Ex04 Places Around Me
## Date:14-10-2024

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
map.html
```
<html>
    <head>
        <title>CHENNAI</title>
    </head>
    <body bgcolor="lightblue">
        <h1>CHENNAI CITY</h1>
        <h3>Name: YUVASHREE S </MADESWARAN></h3>
        <h3>Reg no:212223040251</h3>
        <img src="Screenshot 2024-04-26 154124.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="chennai rail museum" title="chennai rail museum" href="museum.html" coords="1157,344,61" shape="circle">
    <area target="" alt="queens land" title="queens land" href="water park.html" coords="377,667,34" shape="circle">
    <area target="" alt="ashok pillar" title="ashok pillar" href="pillar.html" coords="1176,653,55" shape="circle">
    <area target="" alt="marina beach" title="marina beach" href="beach.html" coords="1478,577,65" shape="circle">
    <area target="" alt="pachaiyamman temple" title="pachaiyamman temple" href="temple.html" coords="832,204,76" shape="circle">
</map>

    </body>
</html>
```
museum.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>CHENNAI RAIL MUSEUM</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            The Chennai Rail Museum is located at the North West side of ICF Furnishing Division, adjacent to New Avadi road, covering 6.25 acres in a serene ambience.

        </font>
        </p>
    </body>
</html>
```
PILLAR.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>ASHOK PILLAR</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            Ashok Nagar is a residential locality situated at the southern part of Chennai, Tamil Nadu, India. It was established in 1964. At the heart of this colony, stands the Ashok Pillar. This four lion head stump, resembles the one erected by king Ashoka during the 3rd century BCE at Sanchi.
        </font>
        </p>
    </body>
</html>
```
TEMPLE.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>PACHAIYAMMAN TEMPLE</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            As this temple is located amidst the dense forest, many Rishis, saints, gurus, and religious persons come to this temple to do penance and gain enlightenment.

        </font>
        </p>
    </body>
</html>
```
water park.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>QUEEN LAND</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            Located on the Chennai - Bangalore Trunk Road, Half an hour drive from Chennai, spread over a very large area of 70 acres.
        </font>
        </p>
    </body>
</html>
```
BEACH.HTML
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body bgcolor="cyan">
        <h1 align="center">
        <font color="gold"><b>chennai</b></font>
        </h1>
        <h3 align="center">
        <font color="pink"><b>MARINA BEACH</b></font>
        </h3>
        <hr size="3" color="yellow">
        <p align="justify">
        <font face="Georgia" size="5">
            Marina Beach, or simply the Marina, is a natural urban beach in Chennai, Tamil Nadu, India, along the Bay of Bengal. The beach runs from near Fort St.
        </font>
        </p>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-04-26 160322.png>)
![alt text](<Screenshot 2024-04-26 160334.png>)
![alt text](<Screenshot 2024-04-26 160348.png>)
![alt text](<Screenshot 2024-04-26 160400.png>)
![alt text](<Screenshot 2024-04-26 160413.png>)
![alt text](<Screenshot 2024-04-26 160424.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
