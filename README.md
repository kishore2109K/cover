# Ex.06 Book Front Cover Page Design
## Date:18.11.24

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
         @import url('https://fonts.googleapis.com/css2?family=Anton&display=swap');
         @import url('https://fonts.googleapis.com/css2?family=Anton&family=Black+Ops+One&display=swap');

        body {
            margin: 0;
            padding: 0;
            background-color: white;
            background: url(3F7OyaE.webp);
            background-repeat: no-repeat;
            background-size: cover;
        }

        .book-cover {
            width: 533px;
            height: 800px;
            background-color:black;
            box-shadow: 10px 10px 10px rgb(0, 0, 0);
            margin: 50px auto;
            position: relative;
            font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
        }

        .book-cover .insight {
            font-family: "Anton", sans-serif;
            font-weight: 400;
            font-style: normal;
            position: relative;
            top: 40px;
            /* right: 70px; */
            font-size: 50px;
            font-weight: bolder;
            color: #9b361b;
            text-shadow: 0px  0px 3px rgb(0, 0, 0);  
            text-align: center;
        }
        
        .book-cover .title1 {
            font-family: "Black Ops One", system-ui;
            font-weight: 400;
            font-style: normal;
            position: absolute;
            top: 110px;
            right: 30px;
            text-shadow: 3px  3px 3px rgb(0, 0, 0);    
            text-align: right;
            font-size: 60px;
            font-weight: bold;
            color: #e7e7e7;
        }
        .book-cover .subtitle1 {
            position: absolute;
            top: 200px;
            right: 160px;
            text-shadow: 0px  0px 3px rgb(0, 0, 0);    
            font-size: 20px;
            font-weight: bold;
            color: #eaf3e7;
        }

        .book-cover .author {
            position: absolute;
            bottom: 50px;
            right: 70px;
            font-size: 18px;
            color: #b02323;
            text-shadow: 0px  0px 5px rgb(0, 0, 0);
        }

        .book-cover .mypic
        {
            position: absolute;
            top: 600px;
            right: 70px;
            border-radius: 10%;
        }

        .book-cover .image {
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
            top:  0;
            left: 0;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <img src="punisher-4k-ultra-hd-dark-phone-n1o3i33y7sdjdsk1.webp" alt="Book Cover Image" class="image">
        <div class="insight"><b>MARVEL</b></div>
        <div class="title1">THE PUNISHER</div>
        <div class="subtitle1">A HERO CAN BE ANYONE</div>
        <img src="WhatsApp Image 2024-11-18 at 20.55.58_d755bdaf.jpg" width="120" height="120" class="mypic">
        <div class="author">KISHORE K</div>
    </div>
</body>
</html>
```
## OUTPUT:

![Screenshot 2024-11-18 211911](https://github.com/user-attachments/assets/a960ba38-c6f0-477c-970a-c2c977613d7c)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
