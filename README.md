# Snobro
4460 Group Project
Main Page

<!DOCTYPE html>
<html>
<head>
<style>
body{
	background-image: url("snowboard-winter.jpg");
	background-repeat: no-repeat;
    background-attachment: fixed;
    background-position: center; 
}

header {
	padding-bottom: 2em;
	top: 0;
	height: 50px;
	left: 0;
	position: fixed;
	width: 100%;
	color: rgb(198,62,29);
    background-color: rgb(10,10,10);
    text-align: center;
}

ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
	overflow: hidden;
	background-color: rgb(198,62,29);
	
}

li {
    float: left;
}

li a {
    display: block;
    color: white;
    text-align: center;
    padding: 10px 16px;
    text-decoration: none;
}

li a:hover {
    background-color: rgb(10,10,10);
}

footer {
	bottom: 0;
	height: 50px;
	left: 0;
	position: fixed;
	width: 100%;
	color: rgb(198,62,29);
    background-color: rgb(10,10,10);
    text-align: center;
}

div.img {
	padding-top: 9em;
    margin: 30px;
    float: left;
    width: 300px;
}

div.img:hover {
	padding-top: 1em;
    border: 1px solid #777;
}

div.img img {
    width: 100%;
    height: auto;
}

div.desc {
    padding: 15px;
    text-align: center;
	color: rgb(198,62,29);
	background-color: #2D2626;
}
</style>
</head>
<body>



<header id="header">
   <h1>-SnoBro-</h1>
   <ul>
	<li><a>Settings</a></li>
	<li><a>Messages</a></li>
	<li><a>Profile</a></li>
</ul>
</header>

<div class="img">
  <a href="movie-detailsBTLC.php">
    <img src="liftimg.png" alt="" width="300" height="513">
  </a>
  <div class="desc">Riding</div>
</div>

<div class="img">
  <a href="movie-detailsBTLC.php">
    <img src="wheel.jpg" alt="" width="300" height="513">
  </a>
  <div class="desc">Driving</div>
</div>
  
 


<div id="footer">
	<footer>
	<h3>Footer</h3>
	</footer>
</div>



</body>
</html>
