# Ex.06 Book Front Cover Page Design
## Date:14-05-2025

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
<head>
  <meta charset="UTF-8">
  <title>Harry Potter Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: serif;
    }

    .book-cover {
      width: 400px;
      height: 600px;
      background-image: url("background.jpg"); 
      background-size: cover;
      background-position: center;
      border: 5px solid #504f4c;
      border-radius: 15px;
      color: #0a0a0a;
      box-shadow: 0 0 40px rgba(255, 215, 0, 0.3);
      padding: 30px 25px;
      box-sizing: border-box;
      position: relative; 
      text-shadow: 1px 1px 3px #000;
    }

    .title {
      font-size: 30px;
      text-align: center;
      margin-top: 10px;
    }

    .subtitle {
      font-size: 16px;
      text-align: center;
      margin-top: 10px;
      font-style: italic;
    }

    .author-img {
      position: absolute;
      bottom: 60px;
      right: 20px;
      width: 100px;
      height: 100px;
      border-radius: 50%;
      border: 3px solid #422c2c;
      object-fit: cover;
      box-shadow: 0 0 10px #100f0f;
    }

    .author-info-text {
      position: absolute;
      bottom: 20px;
      right: 20px;
      text-align: center;
      font-size: 14px;
      line-height: 1.2;
    }

    .author-name {
      font-weight: bold;
    }

    .reg-number {
      opacity: 0.8;
      font-size: 12px;
    }

    .footer {
      position: absolute;
      bottom: 20px;
      left: 20px;
      font-size: 13px;
      opacity: 0.7;
      max-width: 55%;
      line-height: 1.3;
      color:rgb(255, 255, 255);
      font-weight: bold;
    }
  </style>
</head>
<body>
  <div class="book-cover">
    <div class="title">HARRY POTTER AND<br>THE GUARDIAN KEEPER</div>
    <div class="subtitle">There's no Hogwarts without you, Hagrid.</div>

    <img src="myimage.jpg" alt="Author Photo" class="author-img">

    <div class="author-info-text">
      <div class="author-name">S KANUSHA SREE</div>
      <div class="reg-number">Reg No: 212224040149</div>
    </div>

    <div class="footer">
      After all this time? ALWAYS<br>
      A timeless edition for the ones who never left Hogwarts
    </div>
  </div>
</body>
</html>

```

## OUTPUT:
![alt text](<harrypotter/bookapp/static/Screenshot 2025-05-14 211636.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
