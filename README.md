# Web-development-project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>navigarion tool</title>
    

<body>
    <header>
        <div class="heading">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Pariatur fugit, culpa velit ipsam laborum fugiat consequatur vel perspiciatis neque cum odio reprehenderit facere totam eaque, ratione impedit! Laboriosam, voluptate voluptatem!</p>
        </div>
    </header>
    <div class="left"></div>
    <div id="navbardec" class="navbar">
        <ul>
            <li><a href="https://youtube.com" target="_blank">youtube</a></li>
            <li><a href="https://facebook.com" target="_blank">facebook</a></li>
            <li><a href="https://google.com" target="_blank">google</a></li>
            <li><a href="https://mgit.ac.in" target="_blank">mgit</a></li>
            <li><a href="index.html" target="_blank">another</a></li>
            <div class="search">
                <input type="text" name="search" placeholder="search here">
            </div>
        </ul>
    </div>
</body>

</html>
#css code 
body {
    background-image: url("img/bmw.jpg");
     background-size: cover ; 
     background-repeat: no-repeat; 
     background-attachment: fixed;
     background-position: top right;
}
#navbardec{
    /* display: inline-block;
    box-sizing: border-box; */
    margin: auto;
    background-color: black;
    border-radius: 30px;

}
.navbar ul{
    overflow: auto;

}
.navbar li{
    float: left;
    list-style-type: none;
    margin: 13px 20px;
}
.navbar li a{
    padding: 3px 3px;
    text-decoration: none;
    color: white;
}
.navbar li a:hover{
    color:yellow
}
.search{
    float: right;
    color: white;
    padding: 12px 75px;
    border-radius: 3px;
}
.heading{
    background-color: grey;
    color: white;
    opacity: 0.5;
}
.heading:hover{
   text-shadow: 5px 5px 5px red;
}
