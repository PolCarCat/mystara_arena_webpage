<!DOCTYPE html>
<html>
<title>Mystara Arena</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}
body, html {
    height: 100%;
    line-height: 1.8;
}
.w3-bar .w3-button {
    padding: 16px;
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-white w3-card" id="myNavbar">
    <a href="#home" class="w3-bar-item w3-button w3-wide">HOME</a>
    <!-- Right-sided navbar links -->
    <div class="w3-left w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button">ABOUT</a>
      <a href="#team" class="w3-bar-item w3-button"><i class="fa fa-user"></i> TEAM</a>
      <a href="#work" class="w3-bar-item w3-button"><i class="fa fa-male"></i> HEROES</a>
      <a href="#pricing" class="w3-bar-item w3-button"><i class="fa fa-archive"></i> ITEMS</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-angellist"></i> OUR GAME</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">ABOUT</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">TEAM</a>
  <a href="#work" onclick="w3_close()" class="w3-bar-item w3-button">HEROES</a>
  <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">ITEMS</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">OUR GAME</a>
</nav>

<!-- Header with full-height image -->
<p>
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
</p>
<br>
<br>
  <div class="w3-display-left w3-text-black" style="padding:48px">
    <span class="w3-jumbo w3-hide-small">Mystara Arena</span><br>
    <span class="w3-xxlarge w3-hide-large w3-hide-medium">Start something that matters</span><br>
    <span class="w3-large">Are you ready to enter the Arena?</span>
    <p><a href="#about" class="w3-button w3-white w3-padding-large w3-large w3-margin-top w3-opacity w3-hover-opacity-off">by No Readme Studio</a></p>
   
  </div> 
  <div class="w3-display-bottomleft w3-text-grey w3-large" style="padding:24px 48px">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
  </div>
</header>

<!-- About Section -->
<div class="w3-container" style="padding:128px 16px" id="about">
  <h3 class="w3-center">ABOUT THE COMPANY</h3>
  <p class="w3-center w3-large">Key features of our company</p>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <i class="fa fa-desktop w3-margin-bottom w3-jumbo w3-center"></i>
      <p class="w3-large">Responsive</p>
      <p>We listen to our fanbase and we try to make dreams come true.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-heart w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Passion</p>
      <p>The team never gives (even after getting a 0) All the content comes directly from our heart.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-diamond w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Design</p>
      <p> Design polished like a shining diamond. It will blow your mind.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-cog w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Support</p>
      <p> Our team is capable of fixing anything (even the world).</p>
    </div>
  </div>
</div>

<!-- Promo Section - "We know design" -->
<div class="w3-container w3-light-grey" style="padding:128px 16px">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>Download our game here.</h3>
      <p>Prepare to have an amazing experience playing with your friends.</p>
      <p><a href="https://github.com/NOREADMEStudios/ProjectII/releases/tag/1.0" class="w3-button w3-black"><i class="fa fa-file"> </i> Download our game</a></p>
     <p><a href="https://github.com/NOREADMEStudios/ProjectII" class="w3-button w3-black"><i class="fa fa-search"> </i> Repository</a></p>
        <p><a href="https://www.instagram.com/noreadmestudio/" class="w3-button w3-black"><i class="fa fa-home"> </i> Instagram</a></p>
        <p><a href="https://twitter.com/NoReadmeStudio?lang=es" class="w3-button w3-black"><i class="fa fa-home"> </i> Twitter</a></p>
    </div>
    <div class="w3-col m6">
        <iframe width="420" height="315"
src="https://www.youtube.com/embed/KRnLJtiJEfU">
</iframe>
        <iframe width="420" height="315"
src="https://www.youtube.com/embed/b-HkTnfMdrw">
</iframe>
       
    </div>
  </div>
</div>

<!-- Team Section -->
<div class="w3-container" style="padding:128px 16px" id="team">
  <h3 class="w3-center">THE TEAM</h3>
  <p class="w3-center w3-large">The ones who run this company</p>
  <div class="w3-row-padding w3-grayscale" style="margin-top:64px">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="pol.jpg" alt="pol" style="width:100%">
        <div class="w3-container">
          <h3>Pol Carrera</h3>
          <p class="w3-opacity">Designer</p>
          <p></p>
         <p><a href="https://polcarcat.github.io/Personal_Page/" class="w3-button w3-black"><i class="fa fa-user"> </i> Personal Page</a></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="nina.jpg" alt="nina" style="width:100%">
        <div class="w3-container">
          <h3>Nina Lopez</h3>
          <p class="w3-opacity">Artist</p>
          <p></p>
          <p><a href="https://ninalb13.github.io/personalpage/" class="w3-button w3-black"><i class="fa fa-user"> </i> Personal Page</a></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="carles.jpg" alt="carles" style="width:100%">
        <div class="w3-container">
          <h3>Carles Margeli</h3>
          <p class="w3-opacity">Coder</p>
          <p></p>
          <p><a href="https://margeli.github.io/PersonalWebPage/" class="w3-button w3-black"><i class="fa fa-user"> </i> Personal Page</a></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="marc.jpg" alt="marc" style="width:100%">
        <div class="w3-container">
          <h3>Marc Moreno</h3>
          <p class="w3-opacity">Leader</p>
          <p></p>
          <p><a href="https://marc094.github.io/Personal-Page/" class="w3-button w3-black"><i class="fa fa-user"> </i> Personal Page</a></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="norman.jpg" alt="norman" style="width:100%">
        <div class="w3-container">
          <h3>Norman Benet</h3>
          <p class="w3-opacity">Manager</p>
          <p></p>
          <p><a href="https://normanbg.github.io/personal_page/" class="w3-button w3-black"><i class="fa fa-user"> </i> Personal Page</a></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="albert.jpg" alt="albert" style="width:100%">
        <div class="w3-container">
          <h3>Albert Mas</h3>
          <p class="w3-opacity">QA</p>
          <p></p>
          <p><a href="https://albertmas.github.io/project2Web/" class="w3-button w3-black"><i class="fa fa-user"> </i> Personal Page</a></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="joel.jpg" alt="joel" style="width:100%">
        <div class="w3-container">
          <h3>Joel Cabaco</h3>
          <p class="w3-opacity">QA</p>
          <p></p>
          <p><a href="https://dynamiczero99.github.io/Mystara-Arena-Personal-Page/" class="w3-button w3-black"><i class="fa fa-user"> </i> Personal Page</a></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="roger.jpg" alt="roger" style="width:100%">
        <div class="w3-container">
          <h3>Roger Sanchez</h3>
          <p class="w3-opacity">UI</p>
          <p></p>
          <p><a href="https://rogerjimbo.github.io/Personal_Page/" class="w3-button w3-black"><i class="fa fa-user"> </i> Personal Page</a></p>
        </div>
      </div>
    </div>
    <img src="team.jpg" alt="team" style="width:100%">
  </div>
</div>

<!-- Promo Section "Statistics" -->
<div class="w3-container w3-row w3-center w3-dark-grey w3-padding-64">
  <div class="w3-quarter">
    <span class="w3-xxlarge">1</span>
    <br>Rounded marks so far
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">1</span>
    <br>Projects Done
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">1980+</span>
    <br>Happy Clients
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">420+</span>
    <br>Meetings
  </div>
</div>

<!-- Work Section -->
<div class="w3-container" style="padding:128px 16px" id="work">
  <h3 class="w3-center">HEROES</h3>
  <p class="w3-center w3-large">Characters and abilities:</p>

  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-col l3 m6">
      <img src="warrior.JPG" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="WARRIOR">
    </div>
    <div class="w3-col l3 m6">
      <img src="rogue.JPG" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="ROGUE">
    </div>
    <div class="w3-col l3 m6">
      <img src="wizard.JPG" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="WIZARD">
    </div>
    <div class="w3-col l3 m6">
      <img src="cleric.JPG" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="CLERIC">
    </div>
  </div>

  

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-xxlarge w3-black w3-padding-large w3-display-topright" title="Close Modal Image">×</span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Skills Section -->
<div class="w3-container w3-light-grey w3-padding-64">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>Our Skills.</h3>
      <p>We are currently coursing the second year of the Bachelor's degree in Videogames by UPC and CITM. </p>
      <p>Our team is formed by: artists, coders and designers.</p>
    </div>
    <div class="w3-col m6">
      <p class="w3-wide"><i class="fa fa-code-fork w3-margin-right"></i>Code</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:100%">100%</div>
      </div>
      <p class="w3-wide"><i class="fa fa-lightbulb-o w3-margin-right"></i>Design</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:100%">100%</div>
      </div>
      <p class="w3-wide"><i class="fa fa-photo w3-margin-right"></i>Art</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:100%">100%</div>
      </div>
    </div>
  </div>
</div>

<!-- Work Section -->
<div class="w3-container" style="padding:128px 16px" id="pricing">
  <h3 class="w3-center">ITEMS</h3>
  <p class="w3-center w3-large">Choose wisely:</p>

  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-col l3 m6">
      <img src="item_1.gif" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Staff of Thoth">
    </div>
    <div class="w3-col l3 m6">
      <img src="item_2.gif" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="DragonSlayer">
    </div>
    <div class="w3-col l3 m6">
      <img src="item_3.gif" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Plate Mail">
    </div>
    <div class="w3-col l3 m6">
      <img src="item_4.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Ring of Protection">
    </div>
    <div class="w3-col l3 m6">
      <img src="item_5.gif" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Swiftboots">
    </div>
    <div class="w3-col l3 m6">
      <img src="item_6.png" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Tiara">
    </div>
  </div>
    
   

<!-- Contact Section -->
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="contact">
  <h3 class="w3-center">Game Description</h3>
  <p class="w3-center w3-large">Read about our game!</p>
  <br>
  <div class="w3-row-padding" style="margin-top:64px">
    <p>Mystara Arena is a college project game that has been developed over the course in the subject Project II by our team, NOREADME Studios. The objective of this project was to create a fully featured game that could be learned in around 10 to 20 minutes and that could create a competitive environment for a group of friends to try and challenge each other in the 1vs1 and 2vs2 game modes, while ensuring a very fun gameplay. We have taken most of the art and sounds from the arcade game "Dungeons and Dragons: Shadow over Mystara", a beat'em up game released by Capcom in 1996.

In the Gold version you will be able to enjoy the complete experience of a very fun fighting game with 1vs1 and 2vs2 game modes. That will allow you to have fun with three of your friends or to challenge each of them to a duel to see who is the best. Before starting a match, you will have to choose between two of six items that will help you face your opponents. Learning how to use each hero and item best, will help you achieve the victory. All heroes are able to perform combos and link their attacks but will require a a lot of practice to master. There are four very diferent charaters that will fit every player's playstyle with more defenssive/agressive and attack/spell based characters. Learn how to use and play against every one of them and you will make your friends bite the dust. Are you ready to enter the Arena? </p>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
  </div>
</footer>
 
<!-- Add Google Maps -->
<script>
function myMap()
{
  myCenter=new google.maps.LatLng(41.3818, 2.1685);
  var mapOptions= {
    center:myCenter,
    zoom:12, scrollwheel: false, draggable: false,
    mapTypeId:google.maps.MapTypeId.ROADMAP
  };
  var map=new google.maps.Map(document.getElementById("googleMap"),mapOptions);

  var marker = new google.maps.Marker({
    position: myCenter,
  });
  marker.setMap(map);
}

// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}


// Toggle between showing and hiding the sidebar when clicking the menu icon
var mySidebar = document.getElementById("mySidebar");

function w3_open() {
    if (mySidebar.style.display === 'block') {
        mySidebar.style.display = 'none';
    } else {
        mySidebar.style.display = 'block';
    }
}
function resizeWinTo() {
    myWindow.resizeTo(1807, 776);
    myWindow.focus();
}
// Close the sidebar with the close button
function w3_close() {
    mySidebar.style.display = "none";
}
</script>
<script src="https://maps.googleapis.com/maps/api/js?key=AIzaSyBu-916DdpKAjTmJNIgngS6HL_kDIKU0aU&callback=myMap"></script>
<!--
To use this code on your website, get a free API key from Google.
Read more at: https://www.w3schools.com/graphics/google_maps_basic.asp
-->

</body>
</html>
