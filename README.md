# site


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 0 20px;
        }
        .image-wrapper {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-top: 20px;
        }
        .image-box {
            width: calc(50% - 10px);
            margin-bottom: 20px;
        }
        .image-box img {
            max-width: 100%;
            height: auto;
            display: block;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Image Gallery</h1>
        <div class="image-wrapper">
            <div class="image-box">
                <img src="image1.jpg" alt="Image 1">
            </div>
            <div class="image-box">
                <img src="image2.jpg" alt="Image 2">
            </div>
            <!-- Add more image-box divs for additional images -->
        </div>
    </div>
</body>
</html>
