# Ex.06 Book Front Cover Page Design
## Date:15.04.2024

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
```
<!DOCTYPE html>
<html>

<head>
    <title>SCIENCE</title>
    <style>
        .bookpage{

            width: 450px;
            height: 670px;
            color:rgb(15, 13, 13);
            margin-left: auto;
            margin-right: auto;
            padding: 26px;
            font-family: ' Arial, sans-serif';
            background-image: url(aadi.png);
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(194, 221, 221);
            font-family: brush script;
        }
        
        
        .font{
            width:170px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(216, 118, 118);
            top:263px;
            
            font-family:red serifs;
            font-size: medium large;
        }
        .booktitle{
            color:rgb(169, 217, 217);
            font-family: Garamond;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 40px;
        
        }
        .id {
            width: 100px;
            color:rgb(1, 9, 9);
            position: relative;
            top:300px;
            
        }
        .publisher{
            color:rgb(240, 209, 209);
            font-size: large;
            font-family: algerian;
            position: relative;
            top:230px;
            left:315px;
        }
        .general{
            color:rgb(231, 224, 224);
            font-size: large;
            font-family: cambria;
            position:relative;
            top: 110px;
            left:3px;
        
        }
        .subtitle{
            color:rgb(247, 247, 243);
            font-family:courier;
            font-size: large;
            position: relative;
            top: 70px;
        }
        .photo{
            position: relative;
            top: 297px;
            left: 340px;
            width: 70px;
            height: 100px;
            border-radius: 500px;

        }
        </style>
        <title>BLACKHOLE</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                SCIENCE & TECHNOLOGY
            </div>
            <div class="font">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1> SCIENCE AND <br> NEURAL NETWORKS </h1></div>
            <div class="subtitle"><b>
                ORIGINAL EDITION
                <br>
                ONE AND ONLY PIECE 
            </div>
            <div class="subtitle">
                 FROM BOOKS OF GEOFFREY HINTON</b>
            </div>

            <div class="photo">
                <img src="AADITHYA IMG.jpg" width="100" height="125" >
            </div>
            <div class="id">
                <hr style="color:rgb(143, 177, 109)">
            </div>
            <div class="author">
               <p><b> AADITHYA.R </b></p>
               <p><b>212223240001</b></p>
            </div>
            <div class="publisher">
                NOVA PUBLISHERS
            </div>
            <div class="general">
                    <b>INTO THE WORLD </b> 
            </div>
            <div class="general">
                     <b> OF TECHNOLOGY</b>
            </div>
        </div>
        </body>
        
</html>

```
## OUTPUT:
![alt text](<Screenshot (31).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
