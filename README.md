# Ex.05 Book Front Cover Page Design
# Date: 05-12-2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html>
<head>
    <title>Book Cover</title>

  
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&display=swap" rel="stylesheet">

    <style>
        body {
            margin: 0;
            padding: 0;
            background-color: #e8e2d4;
            font-family: 'Playfair Display', serif;
        }

        #cover {
            width: 400px;
            height: 600px;
            margin: 30px auto;
            position: relative;

           
            background-image: url('bookbg.png');
            background-size: cover;
            background-position: center;

            
            border: 8px double #d4b678;
            box-shadow: 0 0 20px rgba(0,0,0,0.4);

            overflow: hidden;
        }

        
        #pattern {
            position: absolute;
            inset: 0;
            background-image: radial-gradient(rgba(255,255,255,0.12) 1px, transparent 1px);
            background-size: 40px 40px;
            pointer-events: none;
        }

        #title {
            position: absolute;
            top: 120px;
            width: 100%;
            text-align: center;
            font-size: 34px;
            font-weight: 700;
            letter-spacing: 2px;
            color: #ffffff;
            text-shadow: 2px 2px 8px rgba(0,0,0,0.7);
        }

        
        #photobox {
            position: absolute;
            bottom: 30px;
            right: 25px;
            text-align: center;
        }

       
        #photo {
            width: 90px;
            height: 90px;
            border-radius: 50%;
            overflow: hidden;
            border: 3px solid #e9d8a2; 
            box-shadow: 0 0 10px rgba(0,0,0,0.6);
            margin-bottom: 6px;
        }

        #photo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

      
        #authorname {
            font-size: 15px;
            color: #f7df9b; 
            text-shadow: 1px 1px 4px rgba(0,0,0,0.6);
            font-weight: 600;
        }
    </style>
</head>
<body>

<div id="cover">
    
    <div id="pattern"></div>

    
    <div id="title">PRIDE AND PREJUDICE</div>

    
    <div id="photobox">
        <div id="photo">
            <img src="Jane.webp" alt="Author Photo">
        </div>
        <div id="authorname">JANE AUSTEN</div>
    </div>

</div>

</body>
</html>

```
# OUTPUT:
![alt text](Cover.png)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
