<!DOCTYPE html>
<html lang="en">
    <style>
        * {
    margin: 0;
    padding: 0;
    list-style: none;
    text-decoration: none;
}

.container {
    width: 85%;
    margin: auto;
}

.banner {
    background: url(background.jpg);
    height: 50vh;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center center;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.banner .w {
    font-family: sans-serif;
    font-weight: 700;
    font-size: 50px;
    line-height: 70px;
    letter-spacing: 0%;
    color: #ffffff;
}

.banner .d {
    font-family: sans-serif;
    font-weight: 400px;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 10%;
    color: #ffffff;
    padding: 20px 0;
}

.banner a {
    padding: 10px;
    width: 150px;
    text-align: center;
    background-color: dodgerblue;
    font-weight: 400px;
    font-size: 20px;
    line-height: 30px;
    color: #ffffff;
    border-radius: 7px;
}

.wrap {
    background: url(print.png );
    height: 43vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: gainsboro;
}

.wrap .box {

    display: flex;
    flex-direction: column;
    text-align: center;
    background-color: #ffffff;
    margin: 15px;
    padding: 40px;
    border-radius: 3px;
}

.wrap .box span:nth-child(1) {
    font-family: sans-serif;
    font-weight: 700;
    font-size: 35px;
    line-height: 70px;
    letter-spacing: 0%;
    color: #000000;
}

.wrap .box span:nth-child(2) {
    font-family: sans-serif;
    font-weight: 400px;
    font-size: 25px;
    line-height: 30px;
    letter-spacing: 10%;
    color: #000000;
}

.footer {
    display: flex;
    background-color: #3d3b3b;
    height: 7vh;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.footer span {
    font-family: sans-serif;
    font-weight: 400px;
    font-size: 20px;
    line-height: 30px;
    letter-spacing: 10%;
    color: #ffffff;
}
    </style>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Document</title>
</head>

<body>

    <div class="banner">

        <span class="w">Welocome to Our Service</span>
        <span class="d">Discover the future of online experience.</span>
        <a href="">Learn More</a>

    </div>

    <div class="wrap">

        <div class="box">
            <span>Feature One</span>
            <span>Description of Feature One.</span>
        </div>

        <div class="box">
            <span>Feature Two</span>
            <span>Description of Feature Two.</span>
        </div>

    </div>


    <div class="footer">
        <span>&copy;2023 Dynamic Landing Page. All rights reserved.</span>
    </div>


</body>

</html>
