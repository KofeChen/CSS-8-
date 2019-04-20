# CSS-8-
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS基本样式习题8</title>
    <style>
        .a-ct{
            width: 600px;
            margin: 0 auto;
        }
        .ai{
            display: inline-block;
            padding:8px 10px;
            text-decoration: none;
            color:#000;
            border-radius: 3px;
            cursor: pointer;
            transition: all .3s;
        }
        .ai:hover{
            box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2) ,0 6px 20px 0 rgba(0,0,0,0.19);
        }
        .a1{
            background-color: #009688;
            color: #ffffff;
        }
        .a2{
            background-color: #ffeb3b;
        }
        .a3{
            background-color: #ff9800;
        }
        .a4{
            background-color: #f44336;
            color: #fff;
        }
        .a5{
            background-color: #4CAF50;
            color: #fff;
        }
    </style>
</head>
<body>
    <div class="a-ct">
        <a class="ai a1" href="#">steal</a>
        <a class="ai a2" href="#">yellow</a>
        <a class="ai a3" href="#">orange</a>
        <a class="ai a4" href="#">red</a>
        <a class="ai a5" href="#">green</a>
    </div>
</body>
</html>
```
