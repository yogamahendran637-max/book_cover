#exp:no 5
# Date:05/12/25
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
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Book Cover</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f0f0f0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .cover-container {
      width: 400px;
      height: 600px;
      position: relative;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.3);
    }

    .cover {
      width: 100%;
      height: 100%;
      position: relative;
      overflow: hidden;
      border-radius: 10px;
    }

    .background {
      width: 100%;
      height: 100%;
      object-fit: cover;
      position: absolute;
      top: 0;
      left: 0;
      z-index: 1;
    }

    .overlay {
      position: relative;
      z-index: 2;
      color: white;
      text-align: center;
      padding: 40px 20px;
      background: rgba(0, 0, 0, 0.5);
      height: 100%;
      box-sizing: border-box;
    }

    .author-photo {
    position: absolute;
      bottom: 20px;
      right: 20px;
      width: 120px;
      height: 120px;
      border-radius: 50%;
      object-fit: cover;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.4);
    }

    .title {
      font-size: 32px;
      margin: 10px 0;
    }

    .subtitle {
      font-size: 20px;
      margin: 10px 0;
      font-style: italic;
    }

    .author {
      font-size: 18px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <div class="cover-container">
    <div class="cover">
      <img src="back.jpg" alt="Background" class="background" />
      <div class="overlay">
        <img src="me.jpg" alt="Author" class="author-photo" />
        <h1 class="title">A WITCH CAT</h1>
        <h2 class="subtitle">A Tale Of Fur And Fire</h2>
        <p class="author">by PRIYARITHANYA</p>
      </div>
    </div>
  </div>
</body>
</html>
```
# OUTPUT:

<img width="1920" height="1080" alt="book cover" src="https://github.com/user-attachments/assets/8230bd1f-7461-491a-92cd-64ffe082be3e" /># Ex.06 Book Front Cover Page Design


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
