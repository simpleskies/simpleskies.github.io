# http://simpleskies.github.io
FBLA 2020 Project
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Airplane</title>
    <link href="CSS/bootstrap-4.0.0.css" rel="stylesheet">
	<link href="css/screen styles.css" rel="stylesheet" type="text/css" />
	<link href="css/background_scroll.css" rel="stylesheet" type="text/css" />
	<link href="css/main.css" rel="stylesheet" type="text/css" />
	<link href="css/animate.css" rel="stylesheet" type="text/css" />
	<link href="css/hover.css" rel="stylesheet" type="text/css" />
    <style type="text/css">

    </style>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav mr-auto">
          <li class="nav-item active">
            <a class="nav-link slider_icon" href="index.html">Home <span class="sr-only">(current)</span></a>
          </li>
          <li><a class="nav-link active slider_icon" href="flights.html">Flights</a> </li>
          <li class="nav-item dropdown slider_icon"><a class="nav-link active" href="frequent_flyer.html">Simple Savings</a>
          </li>
			<li class="nav-item slider_icon"> <a class="nav-link active" href="jobs.html">Jobs</a> </li>
			<li class="nav-item slider_icon"> <a class="nav-link active" href="reviews.html">Reviews</a> </li>
        </ul>
		  
        <div class="copyright_1">
		    <a href="https://https://www.twitter.com/" class="socialmedia_icon" style="background-image: url(images/twitter_top.png)"></a>
            <a href="https://www.instagram.com/" class="socialmedia_icon" style="background-image: url(images/instagram_top.png)"></a>
            <a href="https://facebook.com/" class="socialmedia_icon" style="background-image: url(images/facebook_top.png)"></a>
			<a href="index.html" class="socialmedia_icon rounded-circle" style="background-image: url(images/greyplane.png)"></a>
        </div>
      </div>
    </nav>
	  <div class="h2">
	  </div>
	  <br>
	  <br>
    <div class="container">
			<div class="cd-fixed-bg cd-bg-4"> </div>
      
		 <font family="fantasy" size="500"><center> Simple &nbsp; &nbsp;  <img class="mr-3 rounded-circle title_icon" src="images/greyplane.png" alt="Generic placeholder image">  &nbsp; &nbsp;Skies   &nbsp;  </center></font>
        <div> </div>
        </div>
	<center>
		<br>
	<section> </section>
	<p align="center" class="animated slower bounceInDown">Our website is colorless, so YOU can be colorful</p>
	<hr>
      <p align="center" class="animated fadeInDownBig slow">Simple Skies is an affordable flight booking company dedicated to ensuring our customers can traverse the East Coast comfortably for both themselves and their bank accounts. Our prices are unmatched anywhere else!</p>
      <hr>
    <section>
      <div class="container">
		   
        <div class="row">
			
          <div class="col-lg-4 col-md-6 col-12">
			<a href="flights.html">  &nbsp;  &nbsp;<img class="mr-3 rounded-circle review2_icon animated slideInUp" src="images/plane.png" alt="Generic placeholder image"></a>
            <ul class="list-unstyled">
              <li class="media">
              
                <div class="media-body">
                  <h5 class="mt-0 mb-1">Flights</h5>
                  <p class="mb-0">Choose from a selection of affordable, quality flights from as low as a $20 round trip</p>
                </div>
              </li>
            </ul>
          </div>
          <div class="col-lg-4 col-md-6 col-12">
			 <a href="frequent_flyer.html">   &nbsp;  &nbsp;<img class="mr-3 rounded-circle review2_icon animated slideInUp delay-0s" src="images/money.png" alt="Generic placeholder image"></a>
		    <ul class="list-unstyled">
              <li class="media">
                <div class="media-body ">
                  <h5 class="mt-0 mb-1">Simple Savings Club</h5>
                  <p class="mb-0">Check out our Frequent Flyer program and earn money back on each of your flights</p>
                </div>
              </li>
            </ul>
          </div>
          <div class="col-lg-4 d-md-none d-lg-block">
			  <a href="jobs.html">  &nbsp;  &nbsp;<img class="mr-3 rounded-circle review2_icon animated slideInUp delay-1s" src="images/job.jpg" alt="Generic placeholder image"></a>
            <ul class="list-unstyled">
              <li class="media">
                
                <div class="media-body">
                  <h5 class="mt-0 mb-1">Jobs</h5>
                  <p class="mb-0">Love flying? Find out about career oppurtunities in our airliner family!</p>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </section>
    <hr>
<hr>
    <section>
      <div class="container"> </div>
    </section>
    <hr>
    <div class="container" align="center">
      <div class="custom-checkbox">
<div class="col-md-4 col-12 mt-md-0 mt-2 align-content-center">
      <h3>Contact Us</h3>
          <hr>
          <address>
          <strong>Simple Skies</strong><br>
6104 Franconia Station Ln <br>
Alexandria, VA 22310<br>
<abbr title="Phone">P:</abbr> (571) 456-7890 <br>
<a href="mailto:#"><font color="blue">SimpleSkies@gmail.com</font></a>
          </address>
</div>
      </div>
    </div>
		<div id="map"></div>
 		<script>
		  function initMap() {
			var uluru = {lat: 38.786824, lng: -77.154294};
			var map = new google.maps.Map(document.getElementById('map'), {
			  zoom: 7,
			  center: uluru
			});
			var marker = new google.maps.Marker({
			  position: uluru,
			  map: map
			});
		  }
		</script>
		<script async defer
		src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAbbOIi537y3G1HGXOLHuHxZ9Vc1kCDQIw&callback=initMap">
		</script><br>
    <footer class="text-center">
      <div class="container">
        <div class="row">
          <div class="col-12">
			 <div class="copyright">
            <p>©2020 CONNOR SCHICHTEL AND AYUSH JAIN</p>
				 </div>
			  <br><br>
			<div class="copyright_1">
			
		    <a href="https://https://www.facebook.com/" class="social_icon" style="background-image: url(images/facebook.png)"></a>
            <a href="https://www.instagram.com/" class="social_icon" style="background-image: url(images/instagram.png)"></a>
            <a href="https://twitter.com/" class="social_icon" style="background-image: url(images/twitter.png)"></a>
			
        </div>
			  <a href="copy.html" class="social_icon hvr-float-shadow float-lg-right" style="background-image: url(images/copy.png)"></a>
			  <a href="pp.html" class="social_icon hvr-float-shadow float-lg-right" style="background-image: url(images/ppppp.png)"></a>
			  <a href="tc.html" class="social_icon hvr-float-shadow float-lg-right" style="background-image: url(images/tc.png)"></a>
      </div>
		  </div>
		</div>
    </footer>
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) -->
    <script src="js/jquery-3.2.1.min.js"></script>
    <!-- Include all compiled plugins (below), or include individual files as needed -->
    <script src="js/popper.min.js"></script>
    <script src="js/bootstrap-4.0.0.js"></script>
	  </center>
  </body>
</html>
