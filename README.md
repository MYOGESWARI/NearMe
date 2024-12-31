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
map.html

<html>
<head>
    <title>My City</title>
</head>
<body>

    <h1 align="center">
        <font color="red"><b>HOSUR</b></font>
    </h1>
    <h3 align="center">
      <font color="blue"><b>M YOGESWARI (24011145) </b></font>
    </h3>
    <center>
        <img src="Screenshot 2024-12-13 155524.png" usemap="#image-map">
    <map name="image-map">
    <area target="_blank" alt="hotel" title="hotel" href="Hotel Hills " coords="1234,395,1011,335" shape="rect">
    <area target="_blank" alt="theatre" title="theatre" href="grand cinemas" coords="905,765,1161,845" shape="rect">
    <area target="_blank" alt="school" title="school" href="advaith international academy" coords="1181,16,1389,102" shape="rect">
    <area target="_blank" alt="shop" title="shop" href="bluestone jewellery" coords="1323,441,1503,500" shape="rect">
    <area target="_blank" alt="dam" title="dam" href="Kelavarapalli dam" coords="1481,194,1692,263" shape="rect">
</map>
    </center>
</body>
</html>

dam.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Kelavarapalli dam</h1>
    </header>
    <div class="content">
        <p>The Kelavarapalli Dam is a scenic and important water reservoir located near Hosur in the Krishnagiri district of Tamil Nadu, India. It is built across the Ponnaiyar River and serves as both a functional irrigation project and a popular tourist spot.

        </p>
    </div>
</body>
</html>

hotel.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hotel Hills</h1>
    </header>
    <div class="content">
        <p>Hotel Hills, located in Hosur, Tamil Nadu, is a popular accommodation choice for travelers visiting the region. It offers comfortable stays with various amenities catering to business and leisure travelers alike. Below are some details about the hotel.
        </p>
    </div>
</body>
</html>

school.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>advaith international academy</h1>
    </header>
    <div class="content">
        <p>Advaith International Academy is a prominent educational institution located near Hosur, Tamil Nadu. It is known for providing quality education with a focus on holistic development and modern teaching methodologies. Here are some key details about the academy.
        </p>
    </div>
</body>
</html>

shop.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>bluestone jewellery</h1>
    </header>
    <div class="content">
        <p>BlueStone Jewellery is a renowned brand specializing in fine jewelry, offering a wide range of exquisitely designed ornaments. Their showroom in Hosur caters to customers looking for high-quality, stylish, and contemporary jewelry pieces.
        </p>
    </div>
</body>
</html>

theatre.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My House</title>
    <style>
        body {
            background-color: lightblue; /* Background color for the page */
            font-family: Arial, sans-serif; /* Sets the font style */
            margin: 0;
            padding: 0;
            color: #333;
        }
        header {
            background-color: #4CAF50; /* Green header background */
            color: white;
            padding: 20px;
            text-align: center;
        }
        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>grand cinemas</h1>
    </header>
    <div class="content">
        <p>Grand Cinemas is a popular multiplex located in Hosur, Tamil Nadu, offering an excellent movie-watching experience with modern amenities and comfortable seating. It is a go-to entertainment hub for residents of Hosur and nearby areas. Here's what you can expect
        </p>
    </div>
</body>
</html>


```

## OUTPUT



 ![alt text](<Screenshot 2024-12-30 173428.png>)

 ![alt text](<Screenshot 2024-12-30 173329.png>)

 ![alt text](<Screenshot 2024-12-30 173344.png>)

 ![alt text](<Screenshot 2024-12-30 173355.png>)
  
 ![alt text](<Screenshot 2024-12-30 173408.png>)

 
## RESULT
The program for implementing image maps using HTML is executed successfully.
