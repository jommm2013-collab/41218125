<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>個人網頁</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            color: #333;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            background-color: #fff;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        .profile {
            text-align: center;
        }
        .profile img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            margin-top: 20px;
        }
        .info {
            margin: 20px 0;
            font-size: 18px;
        }
        .info div {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>個人資料</h1>

        <div class="profile">
            <!-- 顯示個人相片 -->
            <img src="your-photo.jpg" alt="個人相片">
        </div>

        <div class="info">
            <!-- 顯示學號 -->
            <div>學號 ： NNNNNNN</div>

            <!-- 顯示姓名 -->
            <div>姓名 ： XXXXXXXXXX</div>
        </div>
    </div>

</body>
</html>
