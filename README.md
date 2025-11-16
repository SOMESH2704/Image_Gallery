# Ex.08 Design of Interactive Image Gallery

## AIM
  To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS

## Step 1:

Clone the github repository and create Django admin interface

## Step 2:

Change settings.py file to allow request from all hosts.

## Step 3:

Use CSS for positioning and styling.

## Step 4:

Write JavaScript program for implementing interactivit

## Step 5:

Validate the HTML and CSS code

## Step 6:

Publish the website in the given URL.

## PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Disney Dream Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #cca7d3;
            text-align: center;
            margin: 0;
            padding: 0;
        }

        .header {
            background-color: #a060a9;
            color: rgb(61, 30, 85);
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        h2 {
            color: rgb(71, 26, 116);
            margin-top: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }

        .gallery-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            padding: 20px;
        }

        .gallery-item {
            margin: 15px;
            border: 2px solid #8aaedf;
            border-radius: 10px;
            overflow: hidden;
            width: 200px;
            background-color: rgb(65, 51, 77);
            transition: transform 0.3s, box-shadow 0.3s;
        }

         .gallery-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .caption {
            padding: 10px;
            background-color: #ad97c8;
            font-weight: bold;
            font-size: 14px;
        }

        .gallery-item:hover {
            transform: scale(1.05);
            box-shadow: 0 4px 15px hwb(283 43% 14% / 0.3);
        


    background-image: url('yourimage1.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: center;
}

    </style>
</head>

<body>
    <div class="header">FINALLISMA FRAMES</div>
    <h2>Enchanta</h2>
    <h3>SOMESHWAR KUMAR</h3>

    <div class="gallery-container">
        <div class="gallery-item">
            <img src="c:\Users\ROSHINI\Downloads\ALADIN.jpg" alt="ALLADIN">
            <div class="caption">ALLADIN<br>Magic of Arabian Nights</div>
        </div>
        <div class="gallery-item">
            <img src="c:\Users\ROSHINI\Downloads\BEAUTY.jpeg" alt="BEAUTY AND THE BEAST">
            <div class="caption">BEAUTY AND THE BEAST<br>The Cursed Castle Realm</div>
        </div>
        <div class="gallery-item">
            <img src="c:\Users\ROSHINI\Downloads\CINDERELLA.jpg" alt="CINDERELLA">
            <div class="caption">CINDERELLA<br>Princess of Midnight</div>
        </div>
        <div class="gallery-item">
            <img src="c:\Users\ROSHINI\Downloads\FROZEN.jpg" alt="FROZEN">
            <div class="caption">FROZEN<br>Arendelle’s Frozen Story</div>
        </div>
        <div class="gallery-item">
            <img src="c:\Users\ROSHINI\Downloads\MOANA.jpeg" alt="MOANA">
            <div class="caption">MOANA<br>Across the Endless Sea</div>
        </div>
        <div class="gallery-item">
            <img src="c:\Users\ROSHINI\Downloads\MILAN.jpeg" alt="MILAN">
            <div class="caption">MILAN<br>History beyond sports</div>
        </div>
        <div class="gallery-item">
            <img src="c:\Users\ROSHINI\Downloads\TANGLED.jpeg" alt="TANGLED">
            <div class="caption">TANGLED<br>Lanterns in the Night</div>
        </div>
    </div>
</body>
</html>


```

## OUTPUT

<img width="1917" height="991" alt="Screenshot 2025-11-16 205904" src="https://github.com/user-attachments/assets/aa74104b-b8f9-4b4f-968f-938bbb518408" />

<img width="1919" height="1007" alt="Screenshot 2025-11-16 205936" src="https://github.com/user-attachments/assets/f208bf08-132b-49c9-a604-00af3a7b4d3f" />

<img width="1919" height="1007" alt="Screenshot 2025-11-16 205959" src="https://github.com/user-attachments/assets/52140caf-6888-4ee5-a81c-892e905d6ce1" />

## RESULT
  The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
