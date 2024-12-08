# Ex04 Places Around Me
## Date: 03/12/2024

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
<html>
<head>
<title> My City</title>
</head>
<body> 
<h1 align="center">
<font color="red"<b>HOSUR</b></font>
</h1>  
<h3 align="center">
<font color="blue"<b>M YOGESWARI</b></font>
</h3> 
<center>
    <img src="map.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="Cafe At The Atelier" title="Cafe At The Atelier" href="Cafe.html" coords="615,202,739,251" shape="rect">
        <area target="_blank" alt=" Panchapalli Lower Falls" title=" Panchapalli Lower Falls" href="falls.html" coords="800,707,76" shape="circle">
        <area target="_blank" alt="Arulmigu Varadaraja Perumal Temple" title="Arulmigu Varadaraja Perumal Temple" href="temple.html" coords="1032,531,1139,588" shape="rect">
        <area target="_blank" alt="Where to eat" title="Where to eat" href="restaurant.html" coords="1304,419,71" shape="circle">
        <area target="_blank" alt="Bannerghatta National Park" title="Bannerghatta National Park" href="park.html" coords="225,299,366,370" shape="rect">
    </map>
</center>
</body>
</html>
```

## OUTPUT

![alt text](<Screenshot 2024-12-03 134307.png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
