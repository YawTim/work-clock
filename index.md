# yawtim.github.io-work-clock-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<title>罗盘时钟</title>
 
<link rel="stylesheet" href="work clock.css" >
 
</head>
<body>

<div id="clock"></div>
 
<script src="work clock.js"></script>
 
</body>
</html>
# work clock.css
*{
    margin:0;
    padding:0
   }
   html,body{
    width:100%;
    height:100%;
    overflow:hidden;
    background-image: url(Pikaciu.jpg);
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    height: 100%;
    margin: 0;
   }
   #clock{
    position:relative;
    width: 100%;
    height: 100%;
   }
   .label{
    display:inline-block;
    color:#4d4d4d;
    text-align:center;
    padding:0 5px;
    font-size:19px;
    transition:left 1s,top 1s;
    transform-origin:0% 0%
   }
# work clock.js
