<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>长图展示网页</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: "Microsoft Yahei", sans-serif;
            background-color: #f5f5f5;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }
        .header {
            background-color: #2c3e50;
            color: #fff;
            padding: 15px;
            text-align: center;
        }
        .image-container {
            width: 100%;
            overflow: auto;
            white-space: nowrap;
            padding: 10px 0;
        }
        .long-image {
            display: block;
            max-width: 100%;
            height: auto;
            margin: 0 auto;
        }
        .footer {
            text-align: center;
            padding: 15px;
            color: #666;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1>酒店房型详情展示</h1>
        </div>
        <div class="image-container">
            <img src="你的长图图片地址.jpg" alt="园景私汤高级大床房详情" class="long-image">
        </div>
        <div class="footer">
            <p>点击图片可查看更大尺寸，滑动可浏览完整内容</p>
        </div>
    </div>
</body>
</html>
