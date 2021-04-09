<!DOCTYPE html>
<html lang="en">
<head>
    <title>The Ultimate Bike Tracker</title>
    <link rel="stylesheet" type="text/css" media="screen" href="main.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="initial-scale=1.0">
    <meta name="description" content="The Ultimate bike tracker">
    <meta name="keywords" content=" Biking riding miles tracker">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <!-- Load an icon library to show a hamburger menu (bars) on small screens -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    
    <script>
/* Toggle between showing and hiding the navigation menu links when the user clicks on the hamburger menu / bar icon */
function myFunction() {
  var x = document.getElementById("myLinks");
  if (x.style.display === "block") {
    x.style.display = "none";
  } else {
    x.style.display = "block";
  }
}
  </script>
  </head>
  <div id="title">
    <h1>The Ultimate Bike Tracker</h1>
  </div>

<!-- Top Navigation Menu - mobile-->
<div class="topnav">
  <a href="#home" class="active"></a>
  <!-- Navigation links (hidden by default) -->
  <div id="myLinks">
    <a href="tracker.html">Tracker</a>
    <a href="blog.html">blog</a>
  </div>

  <!-- "Hamburger menu" / "Bar icon" to toggle the navigation links -->
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>
  
  </div>

<header>
<div class="container">
   <!--- <h1>The Ultimate Bike Traker</h1>-->
</div>
</header>
<!--bike image-->
<div class="bike">
    <img src="images/gray-commuter-bike.jpg" alt="gray bike">
</div> 


<body>

<div id="purpose">
    <h2>Welcome!</h2>
    <p>This site is the place for cyclist to keep track of there rides both indoors and out.</p>
    <p>Be sure to take a look at my blog while you are here.  I will update it regularly.</p>
  
</div>

</br>
</br>
<button onclick="location.href='http://www.ninjaelk.net/cycling/tracker.html'" type="button">
    Click to Enter</button>

  <script type="text/javascript">

var _gaq = _gaq || [];
_gaq.push(['_setAccount', 'UA-9901444-1']);
_gaq.push(['_trackPageview']);

(function() {
  var ga = document.createElement('script'); ga.type = 'text/javascript'; ga.async = true;
  ga.src = ('https:' == document.location.protocol ? 'https://ssl' : 'https://www') + '.google-analytics.com/ga.js';
  var s = document.getElementsByTagName('script')[0]; s.parentNode.insertBefore(ga, s);
})();

  </script>
<div class= "space"></div>
</body>


<footer>Created by Alisha Jacobs &copy; 2021</footer>  
</div>


</html>
