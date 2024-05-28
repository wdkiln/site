
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Census Data Visualization</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .iframe-container {
            position: relative;
            width: 100%;
            padding-bottom: 56.25%; /* 16:9 aspect ratio */
            margin-top: 20px;
        }
        .iframe-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Census Data Visualization</h1>
    </header>

    <div class="iframe-container">
        <iframe src="https://data.census.gov/vizwidget?g=060XX00US5603991815&infoSection=Residential%20Mobility" width="100%" height="100%" frameborder="0"></iframe>
    </div>

    <footer>
        <p>&copy; 2024 Census Data Visualization. All rights reserved.</p>
    </footer>
</body>
</html>
