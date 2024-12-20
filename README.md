# Ex.06 Book Front Cover Page Design
# Date: 2-12-2024
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
	<link rel="stylesheet" href="style.css">
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #333333;
      }
    
    .book-cover {
      width: 100vw; 
      height: 100vh;
      position: relative;
    }
    
    .expert-insight {
      position: absolute;
      top: 3%;
      left: 30px;
      width: auto;
      text-align: left;
      font-size: 25px;
      font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
      color: #f7f4f4;
    }
    
    .top-line {
      position: absolute;
      top: 7%;
      left: 0;
      width: 35%;
      height: 2px;
      background-color: #f54906;
    }
    
    .book-title {
      position: absolute;
      top: 5%;
      left: 0;
      width: 100%;
      text-align: left;
      font-size: 90px;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      font-weight: bold;
      color: #fff;
      margin: 30px;
    }
    
    
    .bottom-line {
      position: absolute;
      bottom: 15%;
      left: 0;
      width: 100%;
      height: 2px;
      background-color: #f54906;
    }
    .content{
      position: absolute;
      top: 55%;
      left: 0;
      width: 100%;
      text-align: left;
      font-size: 35px;
      font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
      color: #fff;
      margin: 30px;
    
    }
    .edition {
      position: absolute;
      bottom: 16%; 
      left: 30px;
      font-size: 45px;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      font-weight: bold;
      color: #f54906;
    }
    .author{
      position: absolute;
      bottom: 1%;
      left: 3px;
      font-size: 35px;
      font-weight: bold;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #fff;
      margin: 30px;
    }
    .publisher {
      position: absolute;
      bottom: 14%; /* Adjust spacing */
      right: 350px; /* Right corner */
      width: 1px; /* Adjust max-width */
      height: 1px; /* Adjust max-height */
    
    }
    .author-image{
      position:absolute;
      bottom:45%;
      right: 320px;
      height:1px;
      width: 1px;
    }
    
    
    
    
    </style>
</head>
<body>
    <div class="book-cover">
	  <div class="expert-insight">EXPERT INSIGHT</div>
	  <div class="top-line"></div>
	  <div class="book-title">
            Responsive Web<br>
            Design with<br>
            HTML5 and CSS
      </div>
      <div class="content">Develop future-proof responsive websites<br>
                           using the latest HTML5 and CSS techniques</div>
      <div class="edition">Third Edition</div>
	  <div class="bottom-line"></div>
      <div class="author">Ben Frain</div>
      <div class="publisher">
        <img src="packtt.jpg" alt="Packt Logo">
      </div>
      <div class="author-image">
        <img src="ben frain.jpg" alt="author">
      </div>
      
      
</body>
</html>

```


# OUTPUT:
![alt text](image.png)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
