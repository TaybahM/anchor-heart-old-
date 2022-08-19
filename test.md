
<html lang="en">
<head>
<link rel="stylesheet" href="https://fonts.googleapis.com/icon?family=Material+Icons">
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-9741419733823699"
     crossorigin="anonymous"></script>
<meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Untitled</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/ionicons/2.0.1/css/ionicons.min.css">
    <link rel="stylesheet" href="assets/css/style.css">
<link href="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<title>Anchorheart</title>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="author" content="Taybah Mohammad">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<!-- Commento -->
<script defer src="https://cdn.commento.io/js/commento.js"></script>
<div id="commento"></div>
<!-- Content for FAQ portion -->
   <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FAQ PAGE</title>
    <link href="https://fonts.googleapis.com/css2?family=Work+Sans&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">

<style>
* {
  box-sizing: border-box;
}
  

  body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

var faq = document.getElementsByClassName("faq-page");
var i;
for (i = 0; i < faq.length; i++) {
    faq[i].addEventListener("click", function () {
        /* Toggle between adding and removing the "active" class,
        to highlight the button that controls the panel */
        this.classList.toggle("active");
        /* Toggle between hiding and showing the active panel */
        var body = this.nextElementSibling;
        if (body.style.display === "block") {
            body.style.display = "none";
        } else {
            body.style.display = "block";
        }
    });
}

/* for FAQ  start*/


body{
    font-family: 'Work Sans', sans-serif;
}
.faq-heading{
    border-bottom: #777;
    padding: 20px 60px;
}
.faq-container{
display: flex;
justify-content: center;
flex-direction: column;
}
.hr-line{
  width: 60%;
  margin: auto;
  
}
/* Style the buttons that are used to open and close the faq-page body */
.faq-page {
    /* background-color: #eee; */
    color: #444;
    cursor: pointer;
    padding: 30px 20px;
    width: 60%;
    border: none;
    outline: none;
    transition: 0.4s;
    margin: auto;
}
.faq-body{
    margin: auto;
    /* text-align: center; */
   width: 50%; 
   padding: auto;
   
}
/* Add a background color to the button if it is clicked on (add the .active class with JS), and when you move the mouse over it (hover) */
.active,
.faq-page:hover {
    background-color: #F9F9F9;
}
/* Style the faq-page panel. Note: hidden by default */
.faq-body {
    padding: 0 18px;
    background-color: white;
    display: none;
    overflow: hidden;
}
.faq-page:after {
    content: '\02795';
    /* Unicode character for "plus" sign (+) */
    font-size: 13px;
    color: #777;
    float: right;
    margin-left: 5px;
}
.active:after {
    content: "\2796";
    /* Unicode character for "minus" sign (-) */
}

/* for FAQ  end*/

.button {
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.button1 {
  background-color: white;
  color: black;
  border: 2px solid #4CAF50;
}

.button1:hover {
  background-color: #4CAF50;
  color: white;
}

.button2 {
  background-color: white;
  color: black;
  border: 2px solid #008CBA;
}

.button2:hover {
  background-color: #008CBA;
  color: white;
}

body {
  font-family: Arial, Helvetica, sans-serif;
}

/* Style the header */
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}

/* Create two columns/boxes that floats next to each other */
nav {
  float: left;
  width: 30%;
  height: 300px; /* only for demonstration, should be removed */
  background: #ccc;
  padding: 20px;
}

/*style the list in the footer*/
nav2 {
  text-align: center;
  width: 500%;
  height: 200px; /* only for demonstration, should be removed */
  background: ;
  padding: 20px;
}

/* Style the list inside the menu */
nav ul {
  list-style-type: none;
  padding: 0;
}

article {
  float: left;
  padding: 20px;
  width: 100%;
  background-color: #f1f1f1;
}

/* Clear floats after the columns */
section::after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the two columns/boxes stack on top of each other instead of next to each other, on small screens */
@media (max-width: 600px) {
  nav, article {
    width: 100%;
    height: auto;
  }
}

*{
  font-family: Verdana, Geneva, Tahoma, sans-serif;
}

body{
  background-color: grey;
  margin: 0px;
}

.nav-container{
  width: 100%;
  height: 75px;
  top: 0px;

  background-color: #696969;
}

.nav-buttons{
  justify-content: center;
  display: flex;
}

.nav-button{
  display: inline-block;
}

.nv-btn{
  background-color: lightgrey;
  border: transparent;
  border-radius: 5px 30px;
  
  height: 30px;
  width: 150px;

  margin-left: 30px;
  margin-right: 30px;
  margin-top: 18.75px;
}

.nv-log{
  background-color: lightgrey;
  border: transparent;
  border-radius: 5px 30px;
  float: right;
  margin-right: 25px;
  transform: translateY(-100%)
}

.nv-btn, .nv-log{
  font-weight: bold;
}

.nv-btn:hover, .nv-log:hover{
  background-color: yellow;
  box-shadow: 10px 10px 25px black;
}

</style>
</head>
<body>

<div class="nav-container">
  <div class="nav-buttons">
    <div class="nav-button"><button class="nv-btn"  onclick="location.href='https://anchor-heart.github.io/owner.html'" type="button">About Us</button></div>
    <div class="nav-button"><button class="nv-btn"  onclick="location.href='https://anchor-heart.github.io/message.html'" type="button">Contact</button></div>
    <div class="nav-button"><button class="nv-btn"  onclick="location.href='#'" type="button">Resources</button></div>
    <div class="nav-button"><button class="nv-btn" onclick="location.href='#'" type="button"></button></div>
  </div>
  <div class="nav-login">
    <div class="login"><button class="nv-log" onclick="location.href='https://anchor-heart.github.io/index.html'" type="button"><i class="material-icons">home</i></button>
  </div>
</div>

<header>
 <h2>Welcome to</h2>
 <h1 style="font-size:50px;">Anchorheart</h1>
  </header>
    
  <article>
    <p>Anchoheart is a remote from home start up volunteer project. It’s a virtual support network that provides individualized one on one support. Our mission is to promote connection, community, end loneliness and isolation. Anchorheart support buddies are caring individuals that provide virtual non proffesional individualized emotional support and companionship to clients. </p>
    <p>Clients are not the only ones who will receive support. Volunteers will also be able to have community connection and support anytime they need it. Here at Anchorheart we don’t have employees, we have family. If you want to be a part of the Anchorheart family, sign up to be a volunteer or a client.</p>
  </article>

  <div align="center">
    <button onclick="window.location.href='https://anchor-heart.github.io/volunteer.html';" class="button button1">Volunteer</button>
    <button onclick="window.location.href='https://anchor-heart.github.io/client.html';" class="button button2">Client</button>
  </div>

<h1 class="faq-heading">FAQ'S</h1>
        <section class="faq-container">
            <div class="faq-one">
                <!-- faq question -->
                <h1 class="faq-page">What is an FAQ Page?</h1>
                <!-- faq answer -->
                <div class="faq-body">
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Velit saepe sequi, illum facere
                        necessitatibus cum aliquam id illo omnis maxime, totam soluta voluptate amet ut sit ipsum
                        aperiam.
                        Perspiciatis, porro!</p>
                </div>
            </div>
            <hr class="hr-line">
            <div class="faq-two">
                <!-- faq question -->
                <h1 class="faq-page">Why do you need an FAQ page?</h1>
                <!-- faq answer -->
                <div class="faq-body">
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Velit saepe sequi, illum facere
                        necessitatibus cum aliquam id illo omnis maxime, totam soluta voluptate amet ut sit ipsum
                        aperiam.
                        Perspiciatis, porro!</p>
                </div>
            </div>
            <hr class="hr-line">
            <div class="faq-three">
                <!-- faq question -->
<h1 class="faq-page">Does it improves the user experience of a website?</h1>
                <!-- faq answer -->
                <div class="faq-body">
                    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Velit saepe sequi, illum facere
                        necessitatibus cum aliquam id illo omnis maxime, totam soluta voluptate amet ut sit ipsum
                        aperiam.
                        Perspiciatis, porro!</p>
                </div>
            </div>
        </section>

  <div class="footer-clean">
        <footer>
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-sm-4 col-md-3 item">
                        <h3>About</h3>
                        <ul>
                            <li><a href="https://anchor-heart.github.io/owner.html">Owner</a></li>
                            <li><a href="#">What We Do</a></li>
                            <li><a href="https://anchor-heart.github.io/FAQS.html">FAQS</a></li>
                        </ul>
                    </div>
                    <div class="col-sm-4 col-md-3 item">
                        <h3>Join Us</h3>
                        <ul>
                            <li><a href="https://anchor-heart.github.io/volunteer.html">Volunteer</a></li>
                            <li><a href="https://anchor-heart.github.io/client.html">Client</a></li>
                            <li><a href="#"></a></li>
                        </ul>
                    </div>
                    <div class="col-sm-4 col-md-3 item">
                        <h3>Other</h3>
                        <ul>
                            <li><a href="https://anchor-heart.github.io/terms.html">Terms & Conditions</a></li>
                            <li><a href="https://anchor-heart.github.io/message.html">Questions & Feedback</a></li>
                            <li><a href="#">Privacy Policy</a></li>
                        </ul>
                    </div>
                    <div class="col-lg-3 item social"><a href="#"><i class="icon ion-social-facebook"></i></a><a href="#"><i class="icon ion-social-twitter"></i></a><a href="#"><i class="icon ion-social-snapchat"></i></a><a href="#"><i class="icon ion-social-instagram"></i></a>
                        <p class="copyright">Anchorheart © 2022</p>
                    </div>
                </div>
            </div>
        </footer>
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/js/bootstrap.bundle.min.js"></script>
</body>
</html>

<!-- Credit to https://epicbootstrap.com/snippets/footer-with-columns -->