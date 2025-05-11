# Ex.06 Book Front Cover Page Design
## Date:11.05.2025

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
book.html:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>3D Book Cover</title>
  <style>
    body {
      margin: 0;
      height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background:white;
      font-family: 'Poppins', sans-serif;
    }

    .book-container {
      width: 420px;
      height: 600px;
      background: skyblue;
      border-radius: 20px;
      padding: 30px;
      color: black;
      box-shadow: 15px 15px 30px #0d0e12, -15px -15px 30px #2c2f36;
      position: relative;
      overflow: hidden;
    }

    .title {
      font-size: 26px;
      font-weight: bold;
      text-align: center;
      margin-top: 30px;
      letter-spacing: 1px;
    }

    .subtitle {
      font-size: 18px;
      text-align: center;
      margin-top: 10px;
      color: #e01212;
      font-style: italic;
    }

    .branding {
      text-align: center;
      font-size: 20px;
      color: #3b1fa1;
      margin-top: 40px;
    }

    .author {
      position: absolute;
      bottom: 30px;
      left: 30px;
      font-size: 16px;
      color: #e10808;
    }

    .publisher {
      position: absolute;
      top: 30px;
      right: 30px;
      font-size: 14px;
      color: #4125aa;
    }

    .edition {
      position: absolute;
      bottom: 80px;
      left: 30px;
      font-size: 14px;
      color: #4234ad;
    }

    .image-frame {
      position: absolute;
      bottom: 30px;
      right: 30px;
      width: 110px;
      height: 140px;
      border-radius: 12px;
      overflow: hidden;
      box-shadow: 0 0 10px rgba(255, 255, 255, 0.3);
    }

    .image-frame img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .highlight-line {
      height: 3px;
      width: 60%;
      background: #ff9800;
      margin: 30px auto;
      border-radius: 50px;
      box-shadow: 0 0 8px #ff9800;
    }
  </style>
</head>
<body>
  <div class="book-container">
    <div class="publisher">EXPERT INSIGHT</div>
    <div class="title">RESPONSIVE WEB DESIGN WITH HTML5 AND CSS</div>
    <div class="subtitle">Develop future-proof responsive websites using HTML5 and CSS Techniques.</div>
    <div class="highlight-line"></div>
    <div class="edition">FOURTH EDITION</div>
    <div class="author"><b>KARJHANI PRIYANKA S B</b></div>
    <div class="image-frame">
      <img src="212224040150.PNG.png" alt="Author">
    </div>
  </div>
</body>
</html>


## OUTPUT:
![alt text](<Screenshot 2025-05-11 230237.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
