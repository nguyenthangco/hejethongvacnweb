# hethongvacnweb
Bài tập hệ thống và công nghệ web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baitap</title>
    <link rel="stylesheet" href="css.css">
</head>
<body>
    <div class="main">
        <div class="wrap">
            <div class="section">
                section
            </div>
            <div class="box2">
                box2
            </div>
        </div>
    </div>
</body>
</html>
file css:
*{
    padding:0;
    margin: 0;
    box-sizing: border-box;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
}
.main{
    width: 1089px;
    height: 800px;
    background-color: blueviolet;
}
.wrap{
    display: flex;
    margin-left: 30%;
    width: 100%;
    height: 500px;
    margin-top: 150px;
    margin-bottom: 130px;
}
.section{
    width: 52%;
    background-color: aqua;
}
.box2{
    width: 18%;
    background-color: brown;
}
