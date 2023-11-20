# Ex04 Places Around Me
## Date: 19/10/2023

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
# map.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Map</title>
</head>
<body>
    <img src="map.png" usemap="#image-map">

    <map name="image-map">
        <area target="_blank" alt="Udhayam Theatre" title="Udhayam Theatre" href="theatre.html" coords="962,331,1127,450" 
shape="rect">
        <area target="_blank" alt="Kendriya Vidyalaya School" title="Kendriya Vidyalaya School" href="school.html" coords="1762,307,1876,413" shape="rect">
        <area target="_blank" alt="Domino's Pizza" title="Domino's Pizza" href="dominos.html" coords="87,666,263,723" shape="rect">
        <area target="_blank" alt="ESIC Hospital" title="ESIC Hospital" href="hospital.html" coords="1031,487,1192,567" shape="rect">
        <area target="_blank" alt="Ashok Nagar Metro" title="Ashok Nagar Metro" href="metro.html" coords="1444,495,1647,597" shape="rect">
    </map>
</body>
</html>
```
# cinema.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Udhayam Theatre</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Udhayam Theatre Ashok Nagar</h1>
    <br>
    <hr color="Brown">
    <p>Udhayam Theatre - Ashok Nagar is a popular theatre located at 3, Pillar Road, Near Indian Oil Petrol Pump, Ashok Nagar, South, Chennai. Udhayam Theatre - Ashok Nagar has 4 screens. Movies now showing at Udhayam Theatre - Ashok Nagar are Japan, Jigarthanda DoubleX and Raid. Facilities available at Udhayam Theatre - Ashok Nagar are Parking Facility.</p>

</body>
</html>
```
# school.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kendriya Vidyalaya</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Kendriya Vidyalaya Ashok Nagar</h1>
    <br>
    <hr color="Brown">
    <p>The Kendriya Vidyalaya Ashok Nagar is a centre of excellence in the field of secondary and senior secondary education. This institution produces holistic students with a strong feeling of National Integration and a unique sense of Indianness in them.

        Nestled in the heart of the city with Ashoka Pillar as an important landmark. About 14 kms from chennai Central station. Adjacent to the Police Training College.</p>

</body>
</html>
```
# domino.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Domino's Pizza</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Domino's Pizza Ashok Nagar</h1>
    <br>
    <hr color="Brown">
    <p>The Domino's menu varies by region. The current Domino's menu in the United States features a variety of Italian-American main and side dishes. Pizza is the primary focus, with traditional, specialty, and custom pizzas available in a variety of crust styles and toppings. In 2011, Domino's launched artisan-style pizzas. Additional entrees include pasta, bread bowls, and oven-baked sandwiches. The menu offers chicken and bread side dishes, as well as beverages and desserts.</p>

</body>
</html>
```
# hospital.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ESIC Hospital</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>ESIC Hospital Ashok Nagar</h1>
    <br>
    <hr color="Brown">
    <p>ESIC Hospital is one of the leading hospital in Chennai. The best healthcare professionals provide Comprehensive healthcare. It is located at K. K. Nagar. It provides advanced levels of care in over different specialties including General Medicine, General Surgery, Gynaecologist and Obstetrician, Paediatrician, ENT, Orthopaedics & Joint Replacement, Dentist, Ophthalmology.</p>

</body>
</html>
```
# metro.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ashok Nagar Metro</title>
    <style>
        h1{
            text-align: center;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            color:darkslategray;
        }
        p{
            text-align: justify;
            color:darkolivegreen;
            font-size: x-large;
            
        }
    </style>
</head>
<body>
    <h1>Ashok Nagar Metro Station</h1>
    <br>
    <hr color="Brown">
    <p>Upon completion, Ashok Nagar Metro Rail station will be the highest elevated station in the entire Chennai Metro Rail system. Initially planned to have a ground floor, a concourse floor and a platform floor, four additional floors have been planned to the original plan to make it a six-storey structure, chiefly to generate revenue by letting out the floors to offices and commercial establishments. After completion, the station will have a height of more than 40 metres, which will be higher than the Alandur metro rail elevated station where the two corridors of Phase I of the Chennai Metro Rail (viz. Washermenpet-Airport and Central-St Thomas Mount lines) converge.</p>

</body>
</html>
```
## OUTPUT

![Alt text](<Screenshot (8).png>)

![Alt text](<Screenshot (9).png>)

![Alt text](<Screenshot (10).png>)

![Alt text](<Screenshot (11).png>)

![Alt text](<Screenshot (12).png>)

![Alt text](<Screenshot (13).png>)

![Alt text](<Screenshot (14).png>)





## RESULT
The program for implementing image maps using HTML is executed successfully.
