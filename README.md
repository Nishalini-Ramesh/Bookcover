# Ex.06 Book Front Cover Page Design
## Date:05/05/25

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
<html lang="en">
  <!DOCTYPE html>
  <html>
  <head>
    <style>
      body {
        margin: 0;
        background-color: black;
        font-family: Arial, sans-serif;
      }
  
      .book-cover {
        width: 500px;
        height: 500px;
        background-color: black;
        color: white;
        margin: auto;
        padding: 20px;
        text-align: center;
        position: relative;
        overflow: hidden;
      }
  
      .title {
        font-size: 35px;
        font-weight: bold;
        margin-top: 40px;
      }
  
      .subtitle {
        font-size: 18px;
        margin-top: 10px;
        color: #888;
      }
  
      .cover-image {
        width: 100%;
        margin-top: 30px;
        border-radius: 8px;
      }
  
      .author {
        position: absolute;
        bottom: 20px;
        padding-top:20px;
        width: 100%;
        text-align: center;
        font-size: 16px;
        color: #ccc;
        display: inline-block;
      }
      .img{
        height:100px;
        width:500px;
      }
      .three{
        padding:10px;
        padding-top:50px;
      }
      .authorimg{
        
        width: 5px; 
        height: 5px; 
        border-radius: 1px;
        display: inline-block;
      }
    </style>
  </head>
  <body>
  
    <div class="book-cover">
      <div class="title">Into the Black Hole</div>
      <div class="subtitle">A Journey Beyond Time</div><hr style="height:5px;" "color:white;">
      
      <div class="three">Black holes are the most mysterious objects in the universe — where time stands still and space folds in on itself</div>
      
      <!-- Add your image here -->
      <div class="img"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSACdLOdJ0tdlQTvEQs048HBoEr8QJeHHyGJzPoeE_XsA&s&ec=72940543" alt="Black Hole" class="cover-image"> </div>
  
        
    </div>
      
      <div class="author">by Stephen Hawking</div>
      <div class="authorimg"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRq_cKaU_C6GvH-DzarM98ogFcwgnQbq2bPQH11ZBeGPWOFbdRsMZjkZHEnJvxVM_lqPcc&usqp=CAU"</div>
    
  
  </body>
  </html>
  ```

## OUTPUT:
![alt text](<npp/nppapp/static/Screenshot 2025-05-05 104827.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
