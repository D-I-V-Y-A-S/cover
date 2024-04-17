# Ex.06 Book Front Cover Page Design
## Date:17:04:2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>book-front-cover</title>
    <style>
        body{
            background-image: url("images/coffee-cover.jpg") ;
            background-repeat: no-repeat;
            background-size: cover;
            color:white;
        }
        p{
            margin-bottom:0;
            padding-bottom: 0;
        }
        h4,h3{

            margin: 0;
    
        }
    </style>
</head>
<body>
    <div style="margin:2%;">
    <p style="margin-top: 5%;color:wheat;font-size: 25px;"><i>READER INSIGHT</i></p>
    <div style="width:15%;">
    <hr>
</div>
    <h1 style="text-align: center;margin-top:2%;font-size:50px;color:gold"><i>Brewed Culture: A Sip Through History<i></h1>
        <p style="text-align: center">Step into the rich tapestry of coffee's journey through time and culture in "Brewed Culture."</p>
        <div style="display: flex;justify-content: space-between;font-size:25px;color:wheat;">
            <h3 style="margin-top:25%">Second Edition</h3>
            <img src="images/author.avif" width="100px" height="100px" style="margin-top:20%" >
            </div>
            <hr>
            <div style="display: flex;justify-content: space-between;font-size:25px;color:wheat">
            <h4>DIVYA</h4>
            <h4>PACT></h4>
        </div>
        </div>
</body>
</html>

## OUTPUT:

![Screenshot (505)](https://github.com/D-I-V-Y-A-S/cover/assets/141506417/b0ef3167-92a9-42f0-833c-03d131640c35)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
