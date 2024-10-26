<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Starlight Fullscreen Photo</title>
    <style>
        /* Căn chỉnh ảnh để vừa với toàn bộ trang */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body, html {
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #000;
            overflow: hidden;
        }
        img {
            width: 100%;
            height: 100%;
            object-fit: cover; /* Đảm bảo ảnh vừa khít màn hình mà không bị méo */
        }
    </style>
</head>
<body>
    <img src="photo.jpg" alt="Starlight">
</body>
</html>
