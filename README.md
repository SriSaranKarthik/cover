# Ex.6 Book Cover Page Design
## Date: 12.11.2025

## AIM:
To design a book back cover page using HTML and CSS.

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
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: aquamarine;
      background-size: cover;
      background-position: center;
      color: black;
      background-color: cyan;
    }
    .cover {
      width: 600px;
      height: 850px;
      margin: 40px auto;
      padding: 40px;
      position: relative;
      background: skyblue;
      border: 5px solid black;
      border-radius: 6%;
    }
    .top {
      font-size: 22px;
      font-weight: bold;
      color: white;
      text-align: left;
      letter-spacing: 2px;
    }
    .title {
      font-size: 38px;
      font-weight: bold;
      text-align: center;
      margin-top: 120px;
      color: black;
      font-family: 'Times New Roman', serif;
    }
    .subtitle {
      font-size: 20px;
      text-align: center;
      margin-top: 30px;
      font-style: oblique;
      color: black;
    }
    .special {
      font-size: 22px;
      font-weight: bold;
      margin-top: 200px;
      color: darkblue;
      text-align: left;
    }
    .author {
      font-size: 20px;
      font-weight: bold;
      color: white;
      margin-top: 20px;
      text-align: left;
    }
    .sec {
      position: absolute;
      bottom: 30px;
      right: 20px;
      font-size: 18px;
      color: white;
    }
    .photo {
      width: 100px;
      height: 120px;
      position: absolute;
      bottom: 60px;
      right: 100px;
      border-radius: 8px;
      border: 2px solid red;
      box-shadow: 0 0 10px black
    }
  </style>
</head>
<body>
  <h1>K SRISARAN KARTHIK (212224230275) </h1>
  <div class="cover">
    <div class="top">SEC Insights</div>
    
    <div class="title">
      The Digital Awakening: Techno AI Revolution<br>
    </div>
    
    <div class="subtitle">
      Unveiling the Next Era of Intelligence, Innovation, and Human Evolution <br>
    </div>
    
    <div class="special">SPECIAL EDITION</div>
    
    <img src="me.jpg" class="photo" alt="Author Photo">
    
    <div class="author">K SRISARAN KARTHIK</div>
    <div class="sec">SEC</div>
  </div>
</body>
</html>

```


## OUTPUT:

![alt text](<fundwe 6 ss (1).png>)

## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
