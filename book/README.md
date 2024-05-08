# Ex.06 Book Front Cover Page Design
## Date: 8-05-24

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
    <title>CLOUD COMPUTING</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;

            background-image: url("bc1.jpg");
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(8, 35, 122);
        
        }
        
        
        .hrstyle{
            width:90px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(241, 242, 247);
            top:240px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(241, 242, 247);
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 5px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:240px;
            
        }
        .pub{
            color:rgb(241, 242, 247)
            font-size: medium;
            position: relative;
            top:200px;
            left:285px;
        }
        .ed{
            color:rgb(241, 242, 247);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:145px;
        
        }
        .subtitle{
            color:rgb(241, 242, 247);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top:220px;
            left: 290px;
            width: 100px;
            height: 70px;
            background-size:contain;
        }
        </style>
                <div class="bookpage">

        <title>Book Cover Page</title>
        </head>
        <body>
            <div class="insight">
               CLOUD HORIZONS,DATA DELIGHTS
            </div>
            <div class="hrstyle">
                <hr style="color:blanchedalmond">
            </div>
            <div class="booktitle">
                <h1>Cloud Computing -Complete overview </h1></div>
            <div class="subtitle">
                 Securing Data
            </div>
            <div class="subtitle">
                Top seller of 2024

            </div>

            <div class="mypic">
                <img src="mypic.jpg" width="100" height="100" >
            </div>
            <div class="id">
                <hr style="color:blanchedalmond">
            </div>
            <div class="author">
               <p><b>BEATRICE</b></p>
            </div>
            <div class="pub">
                <b> <mark>SPECIAL EDITION<mark></b>
            </div>
            <div class="ed">
                <b> SEC</b>
            </div>
        </div>
        </body>
        

</html>

```

## OUTPUT:
![alt text](<Screenshot 2024-05-08 143236.png>)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
