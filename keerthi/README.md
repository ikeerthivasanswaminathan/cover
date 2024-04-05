# Ex.06 Book Front Cover Page Design

## Date : 05/04/2024

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

bk.html

```
<html>
<head>
    <title>Book Cover Design</title>
    <style> 
        .bgcolour {
            background-color: rgb(255, 151, 0);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        
        .coverpage{
            width: 400px;
            height: 600px;
            color: black;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(bkcoverpic.jpg);
            background-size: cover;
        }
            
        .insight{
            color: azure;
        
        }
        
        .hrstyle{
            width: 190px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: rgb(255, 255, 255);
            top: 270px;
            font-family: Georgia;
            font-size: medium;
        }
        .booktitle{
            color: rgb(251, 151, 0);
            font-family: 'Courier New', Courier, monospace, bold;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 20px;
            left: 5px;
        
        }
        .id {
            width: 420px;
            right: 10px;
            position: relative;
            top: 280px;
            
        }
        .pub{
            color: azure;
            font-size: medium;
            position: relative;
            top: 240px;
            left: 250px;
        }
        .ed{
            color: azure;
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 190px;
        
        }
        .subtitle{
            color: rgb(255, 97, 97);
            font-family: unicorn;
            font-size: larger;
            position: relative;
            top: 15px;
        }
        .mypic{
            position: relative;
            top: 250px;
            left: 300px;
            width: 90px;
            height: 80px;
            background-size: contain;
        }
    </style>
</head>
<body>
    <div class="bgcolour">
        <div class="coverpage">
            <div class="insight">
                <b>AR / VR / MIXED REALITY</b>
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(255, 255, 255)">
            </div>
            <div class="booktitle">
                <h1><b>AR / VR / MIXED REALITY</b></h1></div>
            <div class="mypic">
                <img src="KEERTHIVASAN S.png" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>KEERTHIVASAN S</b></p>
            </div>
            <div class="pub">
                SAVEETHA <br> ENGINEERING <br> COLLEGE
            </div>
        </div>
    </div>
</body>
</html>
```

## OUTPUT:

![alt text](book.png)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
