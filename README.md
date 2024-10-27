<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Starlight Fullscreen Photo</title>
    <style>
        /* Đặt phần tử bao phủ toàn bộ màn hình */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            height: 100%;
            overflow: hidden;
        }
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #000;
            margin: 0;
        }
        img {
            position: absolute;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            object-fit: cover; /* Đảm bảo ảnh bao phủ toàn bộ màn hình */
        }
    </style>
</head>
<body>
    <img src="photo.jpg" alt="Starlight">
</body>
</html>
