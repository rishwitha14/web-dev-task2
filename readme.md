*{
    margin: 0%;
    padding: 0%;
}
body{

}
/* .header{
    background-color: rgba(0, 0, 0, 0.8) !important;
}
.bg-light {
    background-color:rgba(0, 0, 0, 0.8)!important;
} */
.navbar-light .navbar-brand {
    color:white !important;
    font-size: 30px;
    padding-left: 45px;
    font-weight: 700;
}
.titleright{
    color: orange;
    font-size: 40px;
}
.nav-item{
    padding: 10px;
    font-size: 17px;
    font-family: system-ui;
    font-weight: 500;
}
.navbar-light .navbar-nav .active>.nav-link, .navbar-light .navbar-nav .nav-link.active, .navbar-light .navbar-nav .nav-link.show, .navbar-light .navbar-nav .show>.nav-link {
    color: white !important;
}
/* .hitems:hover{
    color: orange !important;
} */
.btn-secondary {
    color: #0ead3e;
    background-color:#21b750 !important ;
    border-color: rgb(29, 155, 54) !important;
    padding: 6px 25px 6px 25px !important;
    margin-right: 150px !important;
    border-width: 2px !important;
}
/* Banner section Start */
#banner{
    background-image: url(OIP1.jpg);
    width: 100%;
    height: 700px;
    background-size: cover;

}
#banner h1 {
    margin: 0;
    font-size: 56px;
    font-weight: 700;
    line-height: 64px;
    color: #f1ecec;
    font-family: system-ui;
    margin-top: 100px;
    line-height: 75px;
}
#banner h2{
    font-size: 29px;
    color: #e5d8d8;
    font-family: italic;
}
.box6{
    margin: 80px;
}
.box{
    margin: 100px;
    border-style: solid;
    border-color: black;
    border-width: 1px;
    margin: 18px;
    height: 150px;
    box-shadow: 2px 2px 10px black;
}
.box h3 {
    font-size: 25px;
    position: relative;
    top: 40px;
    color: black;
    font-family: system-ui;
    font-weight: 700;
}
.iconft{
    font-size: 30px;
    text-align: center;
    position: relative;
    top: 30px;
    color: orange;
}
#about2{
    margin: 20px;
}
.abticon{
    font-size: 30px;
    color: orange;
}
.abt2content{
    padding-left: 30px;
}


#countdown{
    font-size: 35px;
    font-family: cursive;
    letter-spacing: 8px;
    color: orange;
    display: flex;
    justify-content: center;
    background-color: black;
    border-style: solid;
    border-width: 7px;
    border-color: black;

}
.card-title1{
    font-size: 30;
    display: flex;
    justify-content: center;
    font-family: monospace;
    color: orange;
}
.card-text1{
    margin-top: 45px;
    display: flex;
    justify-content: center;
    font-size: 20px;
    text-align: center;
    font-family: cursive;
}
.card-text{
    font-size: 16px;
    font-family: sans-serif;
}
.coun{
    margin-top: 40px;
}
<html>
    <head>
        <title> the CAR</title>
        <link rel="stylesheet" href="./style.css">
        <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
        <script src="https://cdnjs.cloudflare.com/ajax/libs/aos/2.3.4/aos.js" integrity="sha512-A7AYk1fGKX6S2SsHywmPkrnzTZHrgiVT7GcQkLGDe2ev0aWb8zejytzS8wjo7PGEXKqJOrjQ4oORtnimIRZBtw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    </head>
    <body>
        <section id="header">
            <nav class="navbar navbar-expand-lg navbar-light bg-dark">
                <a class="navbar-brand" data-aos="flip-left" href="#">RP<span class="titleright">.</span></a>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                  <span class="navbar-toggler-icon">.</span>
                </button>
              
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                  <ul class="navbar-nav m-auto" data-aos="fade-down">
                    <li class="nav-item active">
                      <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item active">
                      <a class="nav-link" href="#">About <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item active">
                      <a class="nav-link" href="#">Event<span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item active">
                      <a class="nav-link" href="#">Team <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item active">
                      <a class="nav-link" href="#">Contact <span class="sr-only">(current)</span></a>
                    </li>
                  </ul>
                  <div class="btn-group" role="group" aria-label="Basic example">
                    <button type="button" class="btn btn-secondary">Get Started</button>
                  </div>
                </div>
              </nav>
        </section>

        <section id="banner">
            <div class="container">
                <div class="row justify-content-center" data-aos="fade-up"
                data-aos-anchor-placement="top-bottom">
                    <div class="col-xl-6 col-lg-8">
                        <h1>Find Your Perfect Car, We Are Welcoming U<span style="color: orange;">.</span></h1>
                        <h2>We can help you find the best car. Check our reviews, compare models and find cars for sale.</h2>
                    </div>
                      
                </div>
                </div>
        </section>
        <section class="coun">
            <p id="countdown"></p>x
        </section>

        <section id="about2">
            <div class="section-title pb-md-4 pb-sm-0 d-flex justify-content-center">
                <h2 class="fs-2 fw-bold text-uppercase mb-4 pb-3" style="margin-top: 50px;
                font-size: 55px;
                font-family: cursive;
                color: gray;">Why Choose Us!</h2>
            </div>
            <div class="row">
                <div class="col-sm-4">
                  <div class="card" data-aos="zoom-in">
                    <div class="card-body" >
                      <h5 class="card-title1"  data-aos="flip-up">Wide range of brands</h5>
                      <p class="card-text1">We can help with your financing plan, we can offer some tips and tricks. Drive off with this dream car of yours regardless of your credit history.</p>
                    </div>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="card" data-aos="zoom-in">
                    <div class="card-body" >
                      <h5 class="card-title1" data-aos="flip-up">Trusted by our clients</h5>
                      <p class="card-text1">We can help with your financing plan, we can offer some tips and tricks. Drive off with this dream car of yours regardless of your credit history.</p>
                    </div>
                  </div>
                </div>
                <div class="col-sm-4">
                  <div class="card" data-aos="zoom-in">
                    <div class="card-body">
                      <h5 class="card-title1" data-aos="flip-up">Fast & easy financing</h5>
                      <p class="card-text1">We can help with your financing plan, we can offer some tips and tricks. Drive off with this dream car of yours regardless of your credit history.</p>
                    </div>
                  </div>
                </div>
              </div>
          </section>

        <section style="margin-top: 90px;">
            <div class="section-title pb-md-4 pb-sm-0 d-flex justify-content-center">
                <h2 class="fs-2 fw-bold text-uppercase mb-4 pb-3" style="
                font-size: 55px;
                font-family: cursive;
                color: gray;">Our Poducts!</h2>
            </div>
            <div class="card-group">
                <div class="card" data-aos="fade-up"
                data-aos-duration="3000">
                  <img src="yellow.jpg" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Swift 8-series Yellow model</h5>
                    <h5 class="card-title">$ 10,00,000...</h5>
                    <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                    <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                  </div>
                </div>
                <div class="card" data-aos="fade-up"
                data-aos-duration="3000">
                  <img src="OIP.jpg" class="card-img-top" alt="..." >
                  <div class="card-body">
                    <h5 class="card-title">Swift 8-series black model</h5>
                    <h5 class="card-title">$ 10,00,000...</h5>
                    <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                    <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                  </div>
                </div>
                <div class="card" data-aos="fade-up"
                data-aos-duration="3000">
                  <img src="redcar.avif" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Swift 8-series Red model</h5>
                    <h5 class="card-title">$ 10,00,000...</h5>
                    <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
                    <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                  </div>
                </div>
              </div>
        </section>

        <section>
            <div class="card-group">
                <div class="card" data-aos="fade-up"
                data-aos-duration="3000">
                  <img src="white_car.webp" class="card-img-top" alt="...">
                  <div class="card-body">
                    <h5 class="card-title">Swift 8-series White model</h5>
                    <h5 class="card-title">$ 10,00,000...</h5>
                    <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                    <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                  </div>
                </div>
                <div class="card">
                  <img src="bluecar.webp" class="card-img-top" alt="...">
                  <div class="card-body" data-aos="fade-up"
                  data-aos-duration="3000">
                    <h5 class="card-title">Swift 8-series Blue model</h5>
                    <h5 class="card-title">$ 10,00,000...</h5>
                    <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                    <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                  </div>
                </div>
                <div class="card">
                  <img src="graycar.jpg" class="card-img-top" alt="..." >
                  <div class="card-body" data-aos="fade-up"
                  data-aos-duration="3000">
                    <h5 class="card-title">Swift 8-series Gray model</h5>
                    <h5 class="card-title">$ 10,00,000...</h5>
                    <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
                    <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
                  </div>
                </div>
              </div>
        </section>

        <div class="section-title pb-md-4 pb-sm-0 d-flex justify-content-center">
            <h2 class="fs-2 fw-bold text-uppercase mb-4 pb-3" style="
            font-size: 55px;
            font-family: cursive;
            margin-top: 50px;
            color: gray;">Contact</h2>
        </div>

        <section style="
        background: rgb(212, 138, 232);
        ">


            <section id="contact" class="contact">
                <div class="container" data-aos="fade-up">
          
                  <div class="row gx-lg-0 gy-4">
          
                    <div class="col-lg-4" style="margin-top: 30px;">
          
                        <div class="info-item d-flex">
                          <i class="bi bi-geo-alt flex-shrink-0"></i>
                          <div>
                            <h4>Location:</h4>
                            <p>19-1/D, APHB Conlony, Hyderabad, Telangana 500064</p>
                          </div>
                        </div>
          
                        <div class="info-item d-flex">
                          <i class="bi bi-envelope flex-shrink-0"></i>
                          <div>
                            <h4>Email:</h4>
                            <p>shift@example.com</p>
                          </div>
                        </div>
          
                        <div class="info-item d-flex">
                          <i class="bi bi-phone flex-shrink-0"></i>
                          <div>
                            <h4>Call:</h4>
                            <p>+1 4498 48855 66</p>
                          </div>
                        </div>
          
                        <div class="info-item d-flex">
                          <i class="bi bi-clock flex-shrink-0"></i>
                          <div>
                            <h4>Open Hours:</h4>
                            <p>Mon-Sat: 11AM - 10PM</p>
                          </div>
                        </div>
          
                    </div>
          
                    <div class="col-lg-8" style="margin-top: 30px;">
                      <form action="forms/contact.php" method="post" role="form" class="php-email-form">
                        <div class="row">
                          <div class="col-md-6 form-group">
                            <input type="text" name="name" class="form-control" id="name" placeholder="Your Name" required>
                          </div>
                          <div class="col-md-6 form-group mt-3 mt-md-0">
                            <input type="email" class="form-control" name="email" id="email" placeholder="Your Email" required>
                          </div>
                        </div>
                        <div class="form-group mt-3">
                          <input type="text" class="form-control" name="subject" id="subject" placeholder="Subject" required>
                        </div>
                        <div class="form-group mt-3">
                          <textarea class="form-control" name="message" rows="7" placeholder="Message" required></textarea>
                        </div>
                        <div class="my-3">
                          <div class="loading">Loading</div>
                          <div class="error-message"></div>
                          <div class="sent-message">Your message has been sent. Thank you!</div>
                        </div>
                        <div class="text-center"><button type="submit">Send Message</button></div>
                      </form>
                    </div><!-- End Contact Form -->
          
                  </div>
          
                </div>
              </section><!-- End Contact Section -->
        </section>
        
        <script>
        // Set the date we're counting down to
        var countDownDate = new Date("Mar 31, 2024 00:00:00").getTime();
        
        // Update the countdown every 1 second
        var x = setInterval(function() {
        
          // Get the current date and time
          var now = new Date().getTime();
            
          // Calculate the time remaining
          var distance = countDownDate - now;
            
          // Calculate days, hours, minutes, and seconds
          var days = Math.floor(distance / (1000 * 60 * 60 * 24));
          var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
          var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
          var seconds = Math.floor((distance % (1000 * 60)) / 1000);
            
          // Display the countdown
          document.getElementById("countdown").innerHTML = days + "d " + hours + "h "
          + minutes + "m " + seconds + "s ";
            
          // If the countdown is over, display a message
          if (distance < 0) {
            clearInterval(x);
            document.getElementById("countdown").innerHTML = "EXPIRED";
          }
        }, 1000);
        </script>
        
        </body>
        <script>
            AOS.init();
          </script>
        

</html>