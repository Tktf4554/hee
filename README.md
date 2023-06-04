<!DOCTYPE html>
<html>
	
<style>
  table,
th,
td {
  border: 1px solid rgb(255, 255, 255);
}

body {
  background-color: #000000;
  background-image: url('https://images.alphacoders.com/128/1283140.png');
  background-position: center top;
  background-size: cover;
  background-repeat: no-repeat;
}

.nav ul {
  list-style: none;
  background-color: #444;
  padding: 0;
  margin: 0 auto;
  
}

.nav li {
  font-size: 1.2em;
  line-height: 40px;
  text-align: left;
}

.nav a {
  text-decoration: none;
  color: #fff;
  display: block;
  padding-left: 15px;
  border-bottom: 1px solid #888;
  transition: .3s;
}

.nav a:hover {
  background-color: #005f5f;
}

.nav a.active {
  background-color: #aaa;
  color: #444;
  cursor: default;
}

.nav li li {
  font-size: .8em
}

@media screen and (min-width: 650px) {
  .nav li {
    width: 130px;
    border-bottom: none;
    height: 50px;
    line-height: 50px;
    font-size: 1.4em;
    display: inline-block;
    margin-right: -4px
  }

  .nav a {
    border-bottom: none;
  }

  .nav>ul>li {
    text-align: center;
  }

  .nav>ul>li>a {
    padding-left: 0;
  }

  .nav li ul {
    position: absolute;
    display: none;
    width: inherit;
  }

  .nav li:hover ul {
    display: block;
  }

  .nav li ul li {
    display: block;
  }

}













th {
  color: rgb(255, 255, 255);
}

td {
  color: aliceblue;
}

h1 {
  background-color: rgb(255, 255, 255);
  width: 330px;
  position: relative;
  border: 10px;
  top: 100px;
  padding: 5px;
  margin: 30px;
}

nav {
  background-color: aliceblue;
  width: 1430px;
  border: 10px;
  padding: 5px;
  margin: 30px;
}

a {

  color: rgb(1, 137, 255);
}
#sb{
  position: relative;
  left: 900px;
  top: 100px;
}
#poga{
  position: relative;
  left: 900px;
}

.myButton {
	box-shadow: 3px 4px 0px 0px #8a2a21;
	background:linear-gradient(to bottom, #c62d1f 5%, #f24437 100%);
	background-color:#c62d1f;
	border-radius:18px;
	border:1px solid #d02718;
	display:inline-block;
	cursor:pointer;
	color:#ffffff;
	font-family:Arial;
	font-size:17px;
	padding:7px 25px;
	text-decoration:none;
	text-shadow:0px 1px 0px #810e05;position:relative;
	top:1px;
  left: 1000px;
}
.myButton:hover {
	background:linear-gradient(to bottom, #f24437 5%, #c62d1f 100%);
	background-color:#f24437;
  box-shadow: 7px -10px 0px 1px #8a2a21;
  border-radius:42px;
}
.you{
  position: relative;
  height: 500px;
  top: 50px;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
}
h2{
  height: 500px;
  margin: 0 auto;
  display: flex;
  justify-content: center;
  align-items: center;
}
  
  
  
  
  
  
  
  
  
  
  
  
  </style>
	
<head>
  <title>Calm...</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
  
  
<body>

  <header>
    <div class="nav">
      <ul>
        <li class="hpme"><a href="#">Home</a></li>
        <li class="tutorials"><a href="#">tutorials</a>
          <ul>
            <li><a href="#">tutorials #1</a></li>
            <li><a href="#">tutorials #2</a></li>
            <li><a href="#">tutorials #3</a></li>
          </ul>
        </li>
        <li class="abbout"><a class="active" href="#">abbout</a></li>
        <li class="news"><a href="#">Newsletter</a>
          <ul>
            <li><a href="https://discord.gg/3udAg43b" target="_blank"><img src="G:\D\Dow\Dow1\discord.png"
                  width="30">News #1</a></li>
            <li><a href="https://www.youtube.com/@tktf4554" target="_blank"><img src="G:\D\Dow\Dow1\Youtube.png"
                  width="30">News #2</a></li>
            <li><a href="#">News #3</a></li>
          </ul>
        </li>
        <li class="contact"><a href="https://discord.gg/3udAg43b">Contact</a></li>
      </ul>
    </div>


  </header>

  <h1>Hi! This is my first website...Calm</h1>

  <img id="poga" src="G:\D\Dow\Dow1\pngwing.com 2.png" width="70">
  <img id="poga" src="G:\D\Dow\Dow1\pngwing.com.png" width="95">
  <img id="poga" src="G:\D\Dow\Dow1\pngwing.com 3.png" width="100">
  
  

  <p style="color: rgb(255, 255, 255)">To understand </p>

  <a href="https://www.youtube.com/@tktf4554?sub_confirmation=1" class="myButton">SUBSCRIBE</a>





  <div class="you">
    <iframe width="960" height="515" src="https://www.youtube.com/embed/vqCtZw1vZpw" title="YouTube video player"
      frameborder="100"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen></iframe>
  </div>

  <h2 class="Gojo1">
    <img src="../Gojo1.jpg" width="550" height="300">
  </h2>
  <a id="#dis" href="https://discord.gg/3udAg43b" target="_blank">
    <img src="G:\D\Dow\Dow1\discord.png" width="100"> </a>




</body>

</html>
