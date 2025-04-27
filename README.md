# Ex04 Places Around Me
# Date:25/04/2025
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
map.html
```
<html>
<head>
<title>My city</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>Virudhunagar</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Barkavi B (24901000)</b></font>
</h3>
<center>
    <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="meesalur" title="meesalur" href="meesalur.html" coords="411,479,519,532" shape="rect">
    <area target="" alt="aruppukottai" title="aruppukottai" href="arrup.html" coords="1212,690,81" shape="circle">
    <area target="" alt="puliyangulam" title="puliyangulam" href="puli.html" coords="474,577,631,640" shape="rect">
    <area target="" alt="allampatti" title="allampatti" href="allam.html" coords="618,326,50" shape="circle">
    <area target="" alt="sengottai" title="sengottai" href="seng.html" coords="124,145,286,205" shape="rect">
</map>
</center>
</body>
</html>
```
seng.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="brown">
    <h1 align="center">
    <font color="green"><b>Virudhunagar</b></font>
    </h1>
    <h3 align=""center">
    <font color="yellow"><b>Sengottai</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="5" color="white">
        Sengottai is a town within the Tenkasi district of Tamil Nadu, India. 
        The town is located in the Tirunelveli Region and is known as the gateway to southern Tamil Nadu and Kerala. 
    </font>
    </p>
</body>
</html>
```
allam.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="orange">
    <h1 align="center">
    <font color="black"><b>Virudhunagar</b></font>
    </h1>
    <h3 align=""center">
    <font color="white"><b>Allampatti</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="5" color="white">
        Allampatti is a locality within Virudhunagar district in Tamil Nadu, India, known for its postal code of 626001.
         It's a rural area and home to schools like P.U.P.S Allampatti, which was established in 1962 and is managed by the local body.
          The school is co-educational and offers grades 1 to 5    
    </font>
    </p>
</body>
</html>
```
arrup.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="green">
    <h1 align="center">
    <font color="grey"><b>Virudhunagar</b></font>
    </h1>
    <h3 align=""center">
    <font color="pink"><b>Arrupukotai</b></font>
    </h3>
    <hr size="3" color="black">
    <p align="justify">
    <font face="Georgia" size="5" color="white">
        Aruppukottai is a town and a municipality in Virudhunagar district in the state of Tamil Nadu, India. 
        Aruppukottai's classical name is "Sengattu irukkai idathuvali". 
        Aruppukottai is about 50 km from Madurai. It is in the middle of Vellore-Tuticorin National Highways NH-38. 
        The villages and towns surrounding Aruppukottai makes this as a major town as well as a major transit hub and they are also famous for production of jasmine
    </font>
    </p>
</body>
</html>
```
puli.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="grey">
    <h1 align="center">
    <font color="purple"><b>Virudhunagar</b></font>
    </h1>
    <h3 align=""center">
    <font color="yellow"><b>Pulliampatti</b></font>
    </h3>
    <hr size="3" color="pink">
    <p align="justify">
    <font face="Georgia" size="5" color="white">
      pulliampatti is an small vilage loacated in virudhunagar district, which is an famous for historical places
    </font>
    </p>
</body>
</html>
```
meesalur.html
```
<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="white">
    <h1 align="center">
    <font color="red"><b>Virudhunagar</b></font>
    </h1>
    <h3 align=""center">
        <font color="black"><b>Meesalur</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
    <font face="Georgia" size="5" color="black">
        meesalur, located in the virudhunagar district of Tamil Nadu, 
        Meesalur is a Gram Panchayat (village council) located in the Virudhunagar district of Tamil Nadu, India. 
        It is part of the Virudhunagar Panchayat Samiti and Virudhunagar Zila Parishad. 
        The village has a branch post office with the PIN code 626003.
    </font>
    </p>
</body>
</html>
```

# OUTPUT

![alt text](<Screenshot 2025-04-27 213823.png>)


![alt text](<Screenshot 2025-04-27 213956.png>)

![alt text](<Screenshot 2025-04-27 214201.png>)


![alt text](<Screenshot 2025-04-27 214221.png>)


![alt text](<Screenshot 2025-04-27 214552.png>)


![alt text](<Screenshot 2025-04-27 214715.png>)

!
# RESULT
The program for implementing image maps using HTML is executed successfully.
