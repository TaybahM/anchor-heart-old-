<html lang="en">
<head>
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
<!-- Content for FAQ portion -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<!-- FontAwesome CSS -->
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.css">
<!-- jQuery first, then Popper.js, then Bootstrap JS -->
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>

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
.text-secondary {
    color: #3d5d6f;
  }
  
  .h4,
  h4 {
    font-size: 1.2rem;
  }

  h2 {
    color: #333;
  }
  
  .fa,
  .fas {
    font-family: 'FontAwesome';
    font-weight: 400;
    font-size: 1.2rem;
    font-style: normal;
  }
  
  .right-0 {
    right: 0;
  }
  
  .top-0 {
    top: 0;
  }
  
  .h-100 {
    height: 100%;
  }
  
  a.text-secondary:focus,
  a.text-secondary:hover {
    text-decoration: none;
    color: #22343e;
  }
  
  #accordion .fa-plus {
    transition: -webkit-transform 0.25s ease-in-out;
    transition: transform 0.25s ease-in-out;
    transition: transform 0.25s ease-in-out, -webkit-transform 0.25s ease-in-out;
  }
  
  #accordion a[aria-expanded=true] .fa-plus {
    -webkit-transform: rotate(45deg);
    transform: rotate(45deg);
  }

/* for FAQ  end*/

.topnav {
  overflow: hidden;
  background-color: #333;
}

.topnav a {
  float: left;
  display: block;
  color: ##f1f1f1;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
  font-size: 17px;
}

.topnav a:hover {
  background-color: #ddd;
  color: black;
}

.topnav a.active {
  background-color: #04AA6D;
  color: white;
}

.topnav .icon {
  display: none;
}

@media screen and (max-width: 600px) {
  .topnav a:not(:first-child) {display: none;}
  .topnav a.icon {
    float: right;
    display: block;
  }
}

@media screen and (max-width: 600px) {
  .topnav.responsive {position: relative;}
  .topnav.responsive .icon {
    position: absolute;
    right: 0;
    top: 0;
  }
  .topnav.responsive a {
    float: none;
    display: block;
    text-align: left;
  }
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

p.ex1 {
  margin: 35px;
}

</style>
</head>
<body>



<div class="topnav" id="myTopnav">
  <a href="https://anchor-heart.github.io/index.html" class="active">Home</a>
  <a href="#Learn">Learn</a>
  <a href="https://anchor-heart.github.io/message.html">Contact</a>
  <a href="https://anchor-heart.github.io/owner.html">Owner</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>

<script>
function myFunction() {
  var x = document.getElementById("myTopnav");
  if (x.className === "topnav") {
    x.className += " responsive";
  } else {
    x.className = "topnav";
  }
}
</script>
  
  
<header>
 <h1 style="font-size:50px;">Frequently Asked Questions</h1>
</header>
<br>
  <p>Anchorheart is a support network that provides individualized one on one support. Read on for more information about our platform, how to become a volunteer and how we're promoting communuty and friendship. Can't find the asnwers to your questions? Email annahewi@me.com.</p>

  <p><a href="https://anchor-heart.github.io/FAQS.html#chatting">Chatting</a>------<a href="https://anchor-heart.github.io/FAQS.html#messaging_apps">Messaging Apps</a>------<a href="https://anchor-heart.github.io/FAQS.html#volunteering">Volunteering</p>


<div class="text-center">
    <h2 class="mt-5 mb-5">FAQ</h2>
  </div>
  <section class="container my-5" id="maincontent">
    <section id="accordion">
      <a class="py-3 d-block h-100 w-100 position-relative z-index-1 pr-1 text-secondary border-top" aria-controls="faq-17" aria-expanded="false" data-toggle="collapse" href="#faq-17" role="button">
        <div class="position-relative">
          <h2 class="h4 m-0 pr-3">
            What if I want custom gear?
          </h2>
          <div class="position-absolute top-0 right-0 h-100 d-flex align-items-center">
            <i class="fa fa-plus"></i>
          </div>
        </div>
      </a>
      <div class="collapse" id="faq-17" style="">
        <div class="card card-body border-0 p-0">
          <p>Custom gear can be ordered through our contact form. Additional fees may apply.</p>

        </div>
      </div>

      <a class="py-3 d-block h-100 w-100 position-relative z-index-1 pr-1 text-secondary border-top" aria-controls="faq-18" aria-expanded="false" data-toggle="collapse" href="#faq-18" role="button">
        <div class="position-relative">
          <h2 class="h4 m-0 pr-3">
            What is the official mission statement?
          </h2>
          <div class="position-absolute top-0 right-0 h-100 d-flex align-items-center">
            <i class="fa fa-plus"></i>
          </div>
        </div>
      </a>
      <div class="collapse" id="faq-18" style="">
        <div class="card card-body border-0 p-0">
          <p>Our official mission statement is lorem ipsum dolor sit.</p>
          <p>
          </p>
        </div>
      </div>

      <a class="py-3 d-block h-100 w-100 position-relative z-index-1 pr-1 text-secondary border-top" aria-controls="faq-19" aria-expanded="false" data-toggle="collapse" href="#faq-19" role="button">
        <div class="position-relative">
          <h2 class="h4 m-0 pr-3">
            What is the purpose of LunarXP?
          </h2>
          <div class="position-absolute top-0 right-0 h-100 d-flex align-items-center">
            <i class="fa fa-plus"></i>
          </div>
        </div>
      </a>
      <div class="collapse" id="faq-19" style="">
        <div class="card card-body border-0 p-0">
          <p>The purpose of LunarXP is to give you the best Mars experience!</p>
          <p>
          </p>
        </div>
      </div>

      <a class="py-3 d-block h-100 w-100 position-relative z-index-1 pr-1 text-secondary  border-top" aria-controls="faq-20" aria-expanded="false" data-toggle="collapse" href="#faq-20" role="button">
        <div class="position-relative">
          <h2 class="h4 m-0 pr-3">
            What is the best email to reach you at?
          </h2>
          <div class="position-absolute top-0 right-0 h-100 d-flex align-items-center">
            <i class="fa fa-plus"></i>
          </div>
        </div>
      </a>
      <div class="collapse" id="faq-20">
        <div class="card card-body border-0 p-0">
          <p>The best email for any inquiries is email@email.com!</p>
          <p>
          </p>
        </div>
      </div>

      <a class="py-3 d-block h-100 w-100 position-relative z-index-1 pr-1 text-secondary  border-top" aria-controls="faq-21" aria-expanded="false" data-toggle="collapse" href="#faq-21" role="button">
        <div class="position-relative">
          <h2 class="h4 m-0 pr-3">
            Where can I read more about this company?
          </h2>
          <div class="position-absolute top-0 right-0 h-100 d-flex align-items-center">
            <i class="fa fa-plus"></i>
          </div>
        </div>
      </a>
      <div class="collapse" id="faq-21">
        <div class="card card-body border-0 p-0">
          <p>Lorem ipsum dolor sit!</p>
          <p>
          </p>
        </div>
      </div>

      <a class="py-3 d-block h-100 w-100 position-relative z-index-1 pr-1 text-secondary  border-top" aria-controls="faq-22" aria-expanded="false" data-toggle="collapse" href="#faq-22" role="button">
        <div class="position-relative">
          <h2 class="h4 m-0 pr-3">
            What is the best time to call?
          </h2>
          <div class="position-absolute top-0 right-0 h-100 d-flex align-items-center">
            <i class="fa fa-plus"></i>
          </div>
        </div>
      </a>
      <div class="collapse" id="faq-22">
        <div class="card card-body border-0 p-0">
          <p>The best time to call is 24/7! We are always available to answer any questions.</p>
          <p>
          </p>
        </div>
      </div>
    </section>
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