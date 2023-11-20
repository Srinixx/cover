# Ex.06 Book Front Cover Page Design
## Date : 28-10-2023

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        *{
            font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh; 
            margin: 0; 
            background-color:lightgray;
        }

        .cover{
            display: flex;
            height: 98vh;
            width: 30%;    
            justify-content: center;
            align-items: center;
            border-color: black;
            box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
            overflow: hidden;
            background-image: url(bg.jpg);
            background-repeat: no-repeat;
        }
        
        .title{
            position: absolute;
            color:cornsilk;
            top: 150px;
            font-size: 18px;
        }

        .text1{
            position: absolute;
            color: darkcyan;
            top: 15px;
            left: 560px;
        }

        .line1{
            position: absolute;
            top: 60px;
            left: 540px;
        }

        .edition{
            position:absolute;
            top: 550px;
            left: 560px;
            color:skyblue;
        }

        .line2{
            position: absolute;
            top: 600px;
            left: 540px;
        }

        .author{
            position: absolute;
            top: 610px;
            left: 560px;
            color:coral;
        }

        .image img{
            height: 100px;
            width: 80px;
            position: absolute;
            top: 560px;
            left: 900px;
        }
                
    </style>
</head>
<body>
    <div class="cover">
        <div class="title">
            <h1>THE TWILIGHT SHIP</h1>
        </div>
        <div class="text1">
            <h3>ETERNAL ECHOES</h3>
        </div>
        <hr class="line1" width="210px">
        <div class="edition">
            <h3>FIRST EDITION</h3>
        </div>
        <div class="author">
            <h3>SHREENIVASH V</h3>
        </div>
        <hr class="line2" width="170px">
        <div class="image">
            <img src="Sriini.jpeg.jpg">
        </div>
    </div>
</body>
</html>
```

## OUTPUT:
<img width="960" alt="image-1" src="https://github.com/Srinixx/cover/assets/132982592/283e01df-ed6e-48fc-baf3-d0aa8b2c413b">

<img width="960" alt="image" src="https://github.com/Srinixx/cover/assets/132982592/55419bd5-b894-4728-9dab-9211aed06240">

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
