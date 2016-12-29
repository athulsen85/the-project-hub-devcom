<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- The above 3 meta tags *must* come first in the head; any other head content must come *after* these tags -->
    <title>DEVCOM PROJECTS</title>

    <!-- Bootstrap -->
    <link href="css/bootstrap.min.css" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css?family=Droid+Serif" rel="stylesheet">

    <!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
      <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
      <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script>
    <![endif]-->
<style>
table {
    border-collapse: separate;
    border-spacing: 20px 10px;
}
* {box-sizing:border-box}
body {font-family: Verdana,sans-serif;}
.mySlides {display:none}

.slideshow-container {
  max-width: 1390px;
  position: relative;
  margin: auto;
}


.text {
  color: #f2f2f2;
  font-size: 3em;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
  font-family: 'Droid Serif', serif;
    font-size: 3em;
}


.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}


.dot {
  height: 13px;
  width: 13px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4} 
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 400px) {
  .text {font-size: 5em;}
}
</style>

  </head>
  <body style="background-image:url(http://previews.123rf.com/images/ilyaka1972/ilyaka19721210/ilyaka1972121000055/15964956-technology-gray-abstract-background-Stock-Photo-wallpaper-web-design.jpg);">
    <hr>
    <div class="slideshow-container">

<div class="mySlides fade">
  <img src="img1.jpg" style="width:100%">
  <div class="text" style="height: 100vh;width: auto;"> DEVCOM PROJECTS</div>
</div>

<div class="mySlides fade">
  <img src="image2.jpg" style="width:100%">
  <div class="text"> DEVCOM PROJECTS</div>
</div>

<div class="mySlides fade">
  <img src="img4.jpg" style="width:100% ">
  <div class="text"> DEVCOM PROJECTS</div>
</div>

</div>
<br>

<div style="text-align:center">
  <span class="dot"></span> 
  <span class="dot"></span> 
  <span class="dot"></span> 
 
</div>

<script>
var slideIndex = 0;
showSlides();

function showSlides() {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    for (i = 0; i < slides.length; i++) {
       slides[i].style.display = "none";  
    }
    slideIndex++;
    if (slideIndex> slides.length) {slideIndex = 1}    
    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active";
    setTimeout(showSlides, 5000);
}
</script>
    <br>
   
<br>
<br>
<br>



<div class="container">
<h2>About us</h2>
<div class="row">
<div class="col-md-7">
<div class="well">

<p>DEVCOM (Developer community)TEAM 
as the community is not bound by this team, its extend exceeds beyond its previous members ,seniors and passouts . I hope this time, this platform will be able to incubate some truly amazing developers out of CEC . 
Teach.
Learn.
Contribute.
hoping for the best 
we are devcom 
</p>
</div></div></div></div>



<div class="container">
<h2>Our Team</h2>
<br>
<div class="row">
<div class="col-lg-9">
<div class="well">
<table >
<tr>
      <th>Sooraj Parakkattil</th>
      <th> Team Leader</th>
      <th><a href="https://www.facebook.com/soorajiam" class="btn">More info</a></th>
      </tr>
<tr>
      <th>Adnan Maqbool</th>
      <th>Communicator</th>
      <th><a href="https://www.facebook.com/profile.php?id=1397376003" class="btn">More info</a></th></tr>
<tr>
      <th>Megha Nair</th>
      <th>Coordinator</th>
      <th><a href="https://www.facebook.com/megha.nair.758" class="btn">More info </a></th></tr>
<tr>
      <th>Team Members</th>
      <th><a href="https://www.facebook.com/photo.php?fbid=1286798481376571&set=a.310638012325961.73424.100001392943546&type=3&theater" class="btn">More info</a></th></tr>

</table>
</div></div></div></div>

   <h3>Our New Projects</h3>
<





    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/bootstrap.min.js"></script>
 





  </body>
</html>
