# Ex02 Commercial Website
## Date:

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
`
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="./index.css">
</head>

<body>
  <div class="Main">
    <div class="page1">
      <header>
        <div class="logo">
          <span class="logo-name">Trabook</span>
          <span class="logo-img"><img src="./asset/Logo.png" alt=""></a></span>
        </div>
        <div class="nav">
          <button class="btn home">Home</button>
          <button class="btn about">About</button>
          <button class="btn destination">Destination</button>
          <button class="btn tour">Tour</button>
          <button class="btn blog">Blog</button>
        </div>
        <div class="action">
          <button class="login">Login</button>
          <button class="sign">Sign up</button>
        </div>
      </header>
      <div class="container">
        <div class="cont1">
          <p class="para1">Get started your exciting <span class="special">journey</span>
            with us.</p>
          <p class="para2">A Team of experienced tourism professionals will provide you with the best advice
            and tips for your desire place. </p>
          <button class="cont1-btn">Discover Now</button>
        </div>
        <div class="cont2">
          <div class="cont2-img">
            <div>
              <div class="award">
                <img src="./asset/trophy-removebg-preview 1.png" alt="">
                <p>Best Tour Awards</p>
              </div>
              <div class="map">
                <img src="./asset/google-maps 1.png" alt="" srcset="">
                <div class="map-cont">
                  <h3>Explore</h3>
                  <p>Every cornar of the world with us</p>
                </div>
              </div>
              <div class="review">
                <img src="./asset/star 1.png" alt="">
                <div class="review-cont">
                  <h3>27K</h3>
                  <p>Customer Reviewed</p>
                </div>
              </div>
            </div>

            <img class="aero" src="./asset/aeroplane.png" alt="">
            <img src="./asset/cont2-img.png" alt="">
            <div class="cont2-img-bg"></div>
          </div>

        </div>


      </div>
      <div class="page1-foot">
        <div>
          <div class="foot-head">
            <div class="h3">Location</div>
            <img src="./asset/Container-foot-arrow.png" alt="">
          </div>
          <div class="foot-head1">
            <p>Where are you going</p>
          </div>
        </div>
        <div>
          <div class="foot-head">
            <div class="h3">Date</div>
            <img src="./asset/Container-foot-arrow.png" alt="">
          </div>
          <div class="foot-head1">
            <p>When you will go</p>
          </div>
        </div>
        <div>
          <div class="foot-head">
            <div class="h3">Guest</div>
            <img src="./asset/Container-foot-arrow.png" alt="">
          </div>
          <div class="foot-head1">
            <p>Number of guest</p>
          </div>
        </div>
        <div>
          <div>
            <button class="foot-btn">Explore Now</button>
          </div>
        </div>
      </div>

    </div>


    <div class="page2">
      <div class="page2-main">
        <div class="page2-cont">
          <div class="page2-tho">
            <div class="quote">Things you need <span class="special">to do</span></div>
            <div class="exe">We ensure that you’ll embark on a perfectly planned, safe vacation at a price
              you can afford. </div>
          </div>
          <div class="page2-img">
            <img src="./asset/page2-img.png" alt="">
          </div>
        </div>
        <div class="page2-boxs">
          <div class="page2-box1">
            <div class="page2-box-img">
              <div class="page-box-img1"><img src="./asset/task.png" alt=""></div>
            </div>
            <div class="page-box-cont">
              <div class="page2-sign">Sign Up</div>
              <div class="sign-cont">Completes all the work associated with planning and processing</div>
            </div>
          </div>
          <div class="page2-box1">
            <div class="page2-box-img">
              <div class="page-box-img2"><img src="./asset/money.png" alt=""></div>
            </div>
            <div class="page-box-cont">
              <div class="page2-sign">Sign Up</div>
              <div class="sign-cont">Completes all the work associated with planning and processing</div>
            </div>
          </div>
          <div class="page2-box1">
            <div class="page2-box-img">
              <div class="page-box-img3"><img src="./asset/map.png" alt=""></div>
            </div>
            <div class="page-box-cont">
              <div class="page2-sign">Sign Up</div>
              <div class="sign-cont">Completes all the work associated with planning and processing</div>
            </div>
          </div>

          <div>

          </div>
          <div>

          </div>
        </div>
      </div>
    </div>


    <div class="page3">
      <div>
        <div class="page3-cont1">Exclusive <span class="special">deals & discounts</span> </div>
        <div class="page3-cont2">Discover our fantastic early booking discounts & start planning your journey.
        </div>
      </div>
      <div class="page3-boxes">

        <div class="page3-box">
          <div>
            <img class="page3-box1-logo" src="./asset/page3-1.png" alt="Madrid">
          </div>
          <div class="page3-box1-cont">
            <div class="page3-box1-cont1">
              <div class="box-name">Madrid</div>
              <div class="rating">
                <span><img class="star" src="./asset/star 1.png" alt="Star"></span>
                <span>
                  <p class="rate-value">4.8</p>
                </span>
              </div>
            </div>
            <div class="page3-box1-cont2">
              <div class="map-cont">
                <img class="page3-map" src="./asset/page3-map.png" alt="Map">
                <span>
                  <p class="country">Spain</p>
                </span>
              </div>
              <div>
                <span><s class="discount">$950</s></span>
                <button class="price">$850</button>
              </div>
            </div>
          </div>
        </div>

        <!-- Repeat for 3 more destinations -->

        <div class="page3-box">
          <div>
            <img class="page3-box1-logo" src="./asset/page3-2.png" alt="Madrid">
          </div>
          <div class="page3-box1-cont">
            <div class="page3-box1-cont1">
              <div class="box-name">Firenze</div>
              <div class="rating">
                <span><img class="star" src="./asset/star 1.png" alt="Star"></span>
                <span>
                  <p class="rate-value">4.5</p>
                </span>
              </div>
            </div>
            <div class="page3-box1-cont2">
              <div class="map-cont">
                <img class="page3-map" src="./asset/page3-map.png" alt="Map">
                <span>
                  <p class="country">Italy</p>
                </span>
              </div>
              <div>
                <span><s class="discount">$850</s></span>
                <button class="price">$750</button>
              </div>
            </div>
          </div>
        </div>

        <div class="page3-box">
          <div>
            <img class="page3-box1-logo" src="./asset/page3-3.png" alt="Madrid">
          </div>
          <div class="page3-box1-cont">
            <div class="page3-box1-cont1">
              <div class="box-name">Paris</div>
              <div class="rating">
                <span><img class="star" src="./asset/star 1.png" alt="Star"></span>
                <span>
                  <p class="rate-value">4.4</p>
                </span>
              </div>
            </div>
            <div class="page3-box1-cont2">
              <div class="map-cont">
                <img class="page3-map" src="./asset/page3-map.png" alt="Map">
                <span>
                  <p class="country">France</p>
                </span>
              </div>
              <div>
                <span><s class="discount">$699</s></span>
                <button class="price">$599</button>
              </div>
            </div>
          </div>
        </div>

        <div class="page3-box">
          <div>
            <img class="page3-box1-logo" src="./asset/page3-4.png" alt="Madrid">
          </div>
          <div class="page3-box1-cont">
            <div class="page3-box1-cont1">
              <div class="box-name">London</div>
              <div class="rating">
                <span><img class="star" src="./asset/star 1.png" alt="Star"></span>
                <span>
                  <p class="rate-value">4.8</p>
                </span>
              </div>
            </div>
            <div class="page3-box1-cont2">
              <div class="map-cont">
                <img class="page3-map" src="./asset/page3-map.png" alt="Map">
                <span>
                  <p class="country">UK</p>
                </span>
              </div>
              <div>
                <span><s class="discount">$850</s></span>
                <button class="price">$850</button>
              </div>
            </div>
          </div>
        </div>



      </div>
      <div class="page3-arrow"> <img src="./asset/page3-btn.png" alt=""></div>






    </div>

    <div class="page4">
      <div class="page4-container">
        <div class="page4-cont">
          <div>
            <div class="page4-cont1">
              <p>Best <span class="special">vacation plan</span></p>
            </div>
            <div class="page4-cont2">
              <p>Plan your perfect vacation with our travel agency. Choose among hundreds of all-inclusive offers! </p>
            </div>
          </div>
          <div>
            <img class="page4-tree" src="./asset/page4-tree.png" alt="">
          </div>
        </div>

        <div class="arrow">
          <img src="./asset/page3-btn.png" alt="">
        </div>

        <div class="page4-showcase">
          <div class="page4-box1">
            <div><img class="page4-img1" src="./asset/page4-3.png" alt=""></div>
            <div class="place">
              <div>
                <p class="place-name">Rome, Italty</p>
              </div>
              <div>
                <p class="place-cost">$5,42k</p>
              </div>
            </div>
            <div class="rate">
              <div><img class="page4-nav" src="./asset/page4-navigation.png" alt=""> <span class="trip-days">10 Days
                  Trip</span></div>
              <div><img class="page4-star" src="./asset/star 1.png" alt=""><span class="trip-rate">4.8</span></div>
            </div>

          </div>

          <div class="page4-box1">
            <div><img class="page4-img1" src="./asset/page4-2.png" alt=""></div>
            <div class="place">
              <div>
                <p class="place-name">London,UK</p>
              </div>
              <div>
                <p class="place-cost">$2,42k</p>
              </div>
            </div>
            <div class="rate">
              <div><img class="page4-nav" src="./asset/page4-navigation.png" alt=""> <span class="trip-days">07 Days
                  Trip</span></div>
              <div><img class="page4-star" src="./asset/star 1.png" alt=""><span class="trip-rate">4.7</span></div>
            </div>
          </div>

          <div class="page4-box1">
            <div><img class="page4-img1" src="./asset/page4-3.png" alt=""></div>
            <div class="place">
              <div>
                <p class="place-name">Osaka,Japan</p>
              </div>
              <div>
                <p class="place-cost">$5,42k</p>
              </div>
            </div>
            <div class="rate">
              <div><img class="page4-nav" src="./asset/page4-navigation.png" alt=""> <span class="trip-days">10 Days
                  Trip</span></div>
              <div><img class="page4-star" src="./asset/star 1.png" alt=""><span class="trip-rate">4.8</span></div>
            </div>
          </div>
        </div>



      </div>



    </div>

    <div class="page5">
      <div class="page5-aero-cont">
        <img class="page4-aero" src="./asset/page5-aero.png" alt="">
      </div>

      <div class="page5-container">

        <div class="page5-container1">
          <div>
            <p class="page5-content1">What people say <span class="special">about Us.</span></p>
          </div>
          <div>
            <p class="page5-content2">Our Clients send us bunch of smilies with our services and we love them.</p>
          </div>
          <div><img class="page5-content3" src="./asset/page3-btn.png" alt=""></div>
        </div>

        <div class="card-container">
          <!-- Back card -->
          <div class="card back-card">
            <p class="page5-cont1">“On the Windows talking painted pasture yet its express parties use. Sure last upon
              he same as knew next. Of believed or diverted no.”</p>
            <div class="author">
              <div class="author11">Chris Thomas</div>
              <div class="author12">CEO of Red Button</div>
            </div>
          </div>

          <!-- Front card -->
          <div class="card front-card">
            <img class="profile-img" src="./asset/page5-man.png" alt="Mike Taylor" />
            <p class="page5-cont1">“On the Windows talking painted pasture yet its express parties use. Sure last upon
              he same as knew next. Of believed or diverted no.”</p>
            <div>
              <div class="author1">Mike taylor</div>
              <div class="author2">Lahore, Pakistan</div>
            </div>
          </div>
        </div>


      </div>
    </div>

    <div class="page6">
      <div>
        <div class="page6-cont1">Get update with <span class="special">latest blog</span> </div>

      </div>
      <div class="page6-boxes">

        <div class="page6-box">
          <div>
            <img class="page6-box1-logo" src="./asset/page6-1.png" alt="Madrid">
          </div>
          <div class="page6-box1-cont">
            <div class="page6-box1-cont1">
              <p>How to Save Money While Visiting Africa .</p>
            </div>
            <div class="page6-box1-cont2">
              <p>July 27, 2021</p>
            </div>
          </div>
        </div>



        <!-- Repeat for 3 more destinations -->

        <div class="page6-box">
          <div>
            <img class="page6-box1-logo" src="./asset/page6-2.png" alt="Madrid">
          </div>
          <div class="page6-box1-cont">
            <div class="page6-box1-cont1">
              <p>How to Save Money While Visiting Africa .</p>
            </div>
            <div class="page6-box1-cont2">
              <p>July 27, 2021</p>
            </div>
          </div>
        </div>

        <div class="page6-box">
          <div>
            <img class="page6-box1-logo" src="./asset/page6-3.png" alt="Madrid">
          </div>
          <div class="page6-box1-cont">
            <div class="page6-box1-cont1">
              <p>How to Save Money While Visiting Africa .</p>
            </div>
            <div class="page6-box1-cont2">
              <p>July 27, 2021</p>
            </div>
          </div>
        </div>

        <div class="page6-box">
          <div>
            <img class="page6-box1-logo" src="./asset/page6-4.png" alt="Madrid">
          </div>
          <div class="page6-box1-cont">
            <div class="page6-box1-cont1">
              <p>How to Save Money While Visiting Africa .</p>
            </div>
            <div class="page6-box1-cont2">
              <p>July 27, 2021</p>
            </div>
          </div>
        </div>



      </div>
      <div class="page6-arrow"> <img src="./asset/page6-btn.png" alt=""></div>






    </div>

    <div class="page7">
      <div class="page7-cont1">
        <div><img class="page7-circle" src="./asset/page7-circle.png" alt=""></div>
        <div>
          <p class="page7-sub-content">Subscribe and get exclusive deals & offer</p>
        </div>
        <div class="page7-textbox">
          <div class="page7-mail-cont"><img class="page7-mail-img" src="./asset/page7-email.png" alt=""><span
              class="page7-mail">Enter your mail</span></div>
          <div><button class="page7-subscribe">Subscribe</button></div>
        </div>
        <div><img class="page7-tree" src="./asset/page7-tree.png" alt=""></div>
      </div>

      <div class="page7-cont2">

        <div class="page7-cont2-box1">
          <div class="page7-logo">
            <span class="page7-logo-name">Trabook</span>
            <span class="page7-logo-img"><img src="./asset/Logo.png" alt=""></a></span>
          </div>
          <div>
            <p class="page7-trip-cont">Book your trip in minute, get full
Control for much longer.</p>
          </div>
          <div class="page7-social">
            <span><img class="page7-face" src="./asset/page7-facebook.png" alt=""></span><img class="page7-insta" src="./asset/page7-insta.png" alt=""><span></span><img class="page7-face" src="./asset/page7-x.png" alt=""><span></span>
          </div>
        </div>
        <div class="page7-cont2-box2">
               <div class="page7-company">
                <p class="page7-feature-tittle">Company</p>

                <ul class="page7-feature">
                  <li class="page7-feature-item1">About</li>
                  <li class="page7-feature-item2">Careers</li>
                  <li class="page7-feature-item3">Logistic</li>
                  <li class="page7-feature-item4">Privacy & Policy</li>
                </ul>
               </div>
               <div class="page7-contact">
                <p class="page7-feature-tittle">Contact</p>
                 <ul class="page7-feature">
                  <li class="page7-feature-item5">Help/FQA</li>
                  <li class="page7-feature-item6">Press</li>
                  <li class="page7-feature-item7">Affilates</li>
                 </ul>
               </div>
               <div class="page7-more">
                <p class="page7-feature-tittle">More</p>
                <ul class="page7-feature">
                  <li class="page7-feature-item8">Press Centre</li>
                  <li class="page7-feature-item9">Our Blog</li>
                  <li class="page7-feature-item10">Low fare tips</li>
                </ul>
               </div>

        </div>

      </div>
        <hr class="line">
      <div class="page7-cont3">
        <div><p class="page7-copyright">Copyright, Trabook 2022. All rights reserved.</p></div>
        <div><p class="page7-terms">Terms & Conditions</p></div>
      </div>
    </div>

  </div>
</body>
</body>

</html>


*,*::before,*::after{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
body::-webkit-scrollbar {
    display: none;
}
/* html, body {
  overflow-x: hidden;  
} */


@font-face {
  font-family: 'Volkhov';
  src: url('./asset/Volkhov/Volkhov-Bold.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: 'Poppins-Regular';
  src: url('./asset/poppins/Poppins-Regular.ttf') format('truetype');
  /* You can add more formats like .woff, .otf if you have them */
  font-weight: normal;
  font-style: normal;
}
@font-face {
  font-family: 'Poppins-SemiBold';
  src: url('./asset/poppins/Poppins-SemiBold.ttf') format('truetype');
  /* You can add more formats like .woff, .otf if you have them */
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Poppins-Medium';
  src: url('./asset/poppins/Poppins-Medium.ttf') format('truetype');
  /* You can add more formats like .woff, .otf if you have them */
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Roboto-Regular';
  src: url('./asset/Roboto-Regular.ttf') format('truetype');
  /* You can add more formats like .woff, .otf if you have them */
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'Inter';
  src: url('./asset/Inter.ttf') format('truetype');
  /* You can add more formats like .woff, .otf if you have them */
  font-weight: normal;
  font-style: normal;
}

.page1{
  width: 1920px;
  height: 999px;
}
header{
    margin: 0px auto;
    width: 1170px;
    height: 114px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.logo{
    width: 130px;
    height: 24px;
    font-family:'Volkhov';
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
}
.logo-name{
    font-size: 24px; 
}
.logo-img{
    width: 19px;
    height: 19px;

}
.nav{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 32px;
    width: 386px;
    height: 24px;
}
.btn{
    border: none;
    font-family: 'Poppins-Regular';
    font-size: 16px;
    color: #222222;
    background-color: white;
}
.action{
     display: flex;
    align-items: center;
    justify-content: center;
    gap: 5rem;
}

.login{
   height: 44px;
   width: 24px;
   font-family: 'Poppins-SemiBold';
   font-size: 16px;
   border: none;
   background-color: white;
   color: #FD8D3A;
}

.sign{
   height: 50px;
   width: 160px;
   font-size: 'Poppins-SemiBold';
   font-size: 16px;
   border-radius: 5px;
   border: none;
   background-color: #FA7436;
   color: #FFFFFF;
}
.container{
    display: flex;
    align-items: center;
    justify-content:center;
    margin-left: 100px;

}
.cont1{
    height: 521px;
    width: 486px;
    display: flex;
    flex-direction: column;
    gap:3rem;
}
.cont2 {
  width: 785px;
  height: 585px;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden; /* Prevent circle overflow */
}

.aero{
    margin-top: 0 auto;
    color: #CCCCCC;
    width: 784.99px;
    height: 191.01px;
}
.award{
    width: 150px;
    height: 66px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    gap: 0.5rem;
    background-color: #FFFFFF;
    border-radius: 10px;
    font-family: "Poppins-Medium";
    font-size: 16px;
    color: #444444;
    position: absolute;
  top: 110px;
  left: -85px;
  z-index: 10;
  box-shadow: 0 6px 16px rgba(0, 0, 0, 0.2);
  
}
.map{
    width: 173px;
    height: 74px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    background-color: #FFFFFF;
    border-radius: 10px;
    position: absolute;
  top: 50%;
  right: -25px;
  transform: translateY(-50%);
  z-index: 3;
}
.map-cont{
    display: flex;
    flex-direction: column;
}
.map-cont >h3{
    font-family: "Poppins-Medium";
    font-size: 16px;
    color: #444444;
}

.map-cont >p{
    font-family: "Poppins-Regular";
    font-size: 12px;
    color: #666666;
}
.review{
    width: 192px;
    height: 68px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
    background-color: #FFFFFF;
    border-radius: 10px;
    position: absolute;
  bottom: 120px;
  left: -50px;
  z-index: 3;
}
.review-cont{
    flex-direction: column;
    align-items: center;
    justify-content: center;
}

.review-cont >h3{
      font-family: "Poppins-Medium";
    font-size: 16px;
    color: #444444;
}
.review-cont > p{
    font-family: "Poppins-Regular";
    font-size: 12px;
    color: #666666;
}
.cont2-img {
  position: relative;
  width: 450px;
  height: 530px; /* Enough space for image + circle */
}

.cont2-img > img {
  position: absolute;
  top: 10px; /* Slightly push image down */
  left: 50%;
  transform: translateX(-50%);
  width: 100%;
  height: auto;
  z-index: 2;
}

.cont2-img-bg {
  position: absolute;
  bottom: -15px; /* Move circle downward */
  left: 50%;
  transform: translateX(-50%);
  width: 500px;
  height: 250px;
  background: #FA7436;
  border-bottom-left-radius: 250px;
  border-bottom-right-radius: 250px;
  z-index: 1;
}


.para1{
    width: 521px;
    height: 210px;
    font-family: "Volkhov";
    font-size: 64px;
    text-align: left;
    
}
.special{
    color:#FA7436;
}
.para2{
    width: 497px;
    height: 120px;
    font-family: "Poppins-Regular";
    font-size: 20px;
    color:#666666 ;
    text-align: left;
}
.cont1-btn{
    background-color: #FFFFFF;
    width: 178px;
    height: 60px;
    font-family: "Poppins-Medium";
    font-size: 18px;
    color:#FA7436;
    border-color:#FA7436 ;
    border-radius: 5px;
}
.page1-foot{
  width: 841px;
  height: 124px;
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  margin: 50px auto;
   z-index: 999;            /* Ensure it's on top */
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.15);  /* Optional: add depth */
  border-radius: 10px;
}
.foot-head{
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 0.5rem;
}

.foot-head >img{
  width: 10px;
  height: 5px;

}

.foot-head >.h3{
    width: 69px;
    height: 24px;
    font-family: "Poppins-Medium";
    font-size: 16px;
    color: #222222;
}

.foot-head1 > p{
  width: 126px;
  height: 18px;
  font-family:"Poppins-Regular" ;
  font-size: 12px;
  color: #666666;
}
.foot-btn{
  width: 165px;
  height: 60px;
  background-color: #FA7436;
  color:#FFFFFF ;
  border: none;
  border-radius: 5px;
}
.page2{
  width: 1920px;
  height: 742px;
  background-color:#F7F8FC ;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.page2-main{
  width: 1170px;
   height: 484px;
}

.page2-cont{
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 50px;
  gap: 5rem;
}

.page2-tho{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 2rem;
}
.quote{
  width: 521px;
  height: 54px;
  font-family: "Volkhov";
  font-size: 48px;
}
.exe{
  width: 482px;
  height: 64px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  text-align: center;
  color: #666666;
}
.page2-img{
  width: 179.9px;
  height: 130.73px;
  color: #999999;
}
.page2-boxs{
  display: flex;
  justify-content: space-around;
  align-items: center;
}

/* Card Box */
.page2-box1 {
  width: 370px;
  height: 278px;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  position: relative;
  padding: 20px;
  margin-bottom: 40px;
  background-color: white;
  border-radius: 16px;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.15);
  overflow: hidden;
  border: 1.5px solid #ddd;
  z-index: 1;
}

/* Background Line Image */
.page2-box1::before {
  content: "";
  position: absolute;
  top: 0; left: 0; right: 0; bottom: 0;
  background-image: url('./asset/page2-box-bg.png');
  
  background-repeat: no-repeat;
  background-size: contain;
  background-position: center;
  z-index: 0;
  opacity: 0.5;
  filter: hue-rotate(10deg) saturate(3);
}

/* Alternate Direction + Color */
.page2-box1:nth-child(2)::before {
  transform: scaleX(-1);
  filter: hue-rotate(180deg) saturate(3);
}

.page2-box1:nth-child(3)::before {
  filter: hue-rotate(90deg) saturate(5);
}

/* Content Above Background */
.page2-box-img,
.page-box-cont {
  position: relative;
  z-index: 2;
}

/* Icon Container */
.page2-box-img {
  align-self: flex-start;
  margin-bottom: 1rem;
}

/* Individual Icons */
.page-box-img1 img {
  width: 48px;
  height: 48px;
}
.page-box-img2 img {
  width: 46.57px;
  height: 48px;
}
.page-box-img3 img {
  width: 41.11px;
  height: 48px;
}

/* Content Box */
.page-box-cont {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  flex-grow: 1;
  text-align: center;
  width: 100%;
}

/* Title */
.page2-sign {
  font-family: "Poppins-SemiBold", sans-serif;
  font-size: 24px;
  color: #222222;
  margin-bottom: 0.5rem;
}

.sign-cont {
  font-family: "Poppins-Regular", sans-serif;
  font-size: 16px;
  color: #666666;
  padding: 0 10px;
  line-height: 1.4;
  max-width: 250px;
}

.page3{
  width: 1920px;
  height: 960px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
.page3-cont{
  display: flex;
  flex-direction: column;
  justify-content: center;


}

.page3-cont1{
  width: 675px;
  height: 54px;
  font-family: "Volkhov";
  font-size: 48px;
  color: #222222;
  margin-bottom: 24px;
  text-align: center;
  
}
.page3-cont2{
  width: 433px;
  height: 64px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  text-align: center;
  color: #666666;
  margin-left: 100px;
  margin-bottom: 60px;
}
.page3-boxes{
  width: 1170px;
  height: 426px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  
}
.page3-box{
  width: 270px;
  height: 426px;
  color: FEFCFB;
  border-radius: 8px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  position: relative;
  z-index: 10;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);

}


.page3-box1-logo{
  width: 270px;
  height: 290px;
  border-radius: 8px;

}
.page3-box1-cont{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  gap:2rem;
}

.page3-box1-cont1{
  width: 238px;
  height: 26px;
  border-radius: 8px;
  display: flex;
  align-items: center;
  justify-content:space-between;
}

.page3-box1-cont2
{
   width: 238px;
  height: 26px;
  border-radius: 8px;
  margin-bottom: 20px;
  display: flex;
  align-items: center;
  justify-content:space-between;
}
.rating{
   display: flex;
  align-items: center;
  justify-content:space-between;
  margin-top: 15px;
}
.box-name{
  width: 86px;
  height: 26px;
  color: #222222;
  font-family: "Poppins-Medium";
  font-size: 24px;
}
.star{
  width: 16px;
  height: 16px;
  border-radius: 8px;
  margin-right: 8px;
}
.rate-value{
  width: 24px;
  height: 24px;
  font-family: "Poppins-Regular";
  font-size: 16px;
  color: #666666;
}
.map-cont{
  display: flex;
  flex-direction: row;
  align-items: center;
  gap: 0.5rem;
}

.page3-map{
  width: 12.57px;
  height: 16px;
  color: #999999;
}
.country{
  width: 26px;
  height: 20px;
  font-family: "Poppins-Regular";
  font-size: 16px;
  color: #666666;
}
.discount{
  font-family:"Poppins-Medium" ;
  font-size: 16px;
  width: 42px;
  height: 24px;
  color: #999999;
  margin-right: 20px;
}
.price{
  border: none;
  width: 42px;
  height: 24px;
  font-family: "Poppins-SemiBold";
  color: #FA7436;
  background-color: #FFE7DB;
  border-radius: 8px;
}

.page3-arrow{
  width: 104px;
  height: 40px;
  margin-top: 30px;
}


.page4{
  width: 1920px;
  height: 893px;
  display:flex;
  align-items: center;
  justify-content: center;
}

.page4-container{
  width: 1170px;
  height: 653px;
  display: flex;
  flex-direction: column;
  /* justify-content: space-between; */
  
}

.page4-cont{
  display: flex;
  justify-content: center;
  align-items: center;
}
.page4-cont1{
  width: 432px;
  height: 54px;
  font-family: "Volkhov";
  font-size: 48px;
  color: #222222;
}

.page4-cont2{
   width: 521px;
   height: 64px;
   font-family: "Poppins-Regular";
   font-size: 18px;
   color: #666666;
   text-align: center;
   margin-top: 20px;
}

.page4-tree{
  width: 105.51px;
  height: 81px;
  color: #999999;
  margin-bottom: 50px;
  margin-left: 20px;
}

.arrow{
  display: flex;
  justify-content: end;
  margin-right: 20px;
}

.page4-showcase{
  width:1170px;
  height: 447px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin-top: 50px;
}


.page4-box1{
  width: 370px;
  height: 447px;
  display: flex;
 display: flex;
 flex-direction: column;
 align-items: center;
 justify-content: space-between;
 border-radius: 16px;
 box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
  
}

.page4-img1{
  width: 369px;
  height: 327px;
}

.place{
  width: 319px;
  height: 32px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.rate{
  width: 317.31px;
  height: 24px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.place-name{
  width: 164px;
  height: 32px;
  font-family: "Poppins-Medium";
  font-size: 24px;
  color: #222222;
}

.place-cost{
  width: 81px;
  height: 32px;
  font-family: "Poppins-SemiBold";
  font-size: 24px;
  color: #FA7436;
}

.page4-nav{
  width: 18.79px;
  height: 16px;
  color: #FA7436;
}

.page4-star{
  width: 16px;
  height: 16px;
  border-radius: 10px;
}

.trip-days{
  width: 111.59px;
  height: 24px;
  font-family: "Poppins-Medium";
  font-size: 16px;
  color: #666666;
}

.trip-rate{
  width: 24px;
  height: 24px;
  font-family: "Poppins-regular";
  font-size: 16px;
  color: #666666;
}


.page5{
  width: 1920px;
  height: 596px;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: #F7F8FC;
}
.page5-aero-cont{
  position: absolute;
}

.page4-aero{
  margin-left: 1100px;
  margin-bottom: 200px;
  width: 168.56px;
  height: 188.06px;
}

.page5-container{
  width: 1103px;
  height: 356px;
  display: flex;
  align-items: center;
  gap: 5rem;
}

.page5-container1{
  display: flex;
  flex-direction: column;
  gap: 2rem;
}

.page5-content1{
  width: 387px;
  height: 108px;
  font-family: "Volkhov";
  font-size: 48px;
  color: #222222;
}

.page5-content2{
  width: 384px;
  height: 64px;
  font-family: "Roboto-Regular";
  font-size: 16px;
  color: #666666;
}

.page5-content3{
  width: 112px;
  height: 40px;
}

.card-container {
  position: relative;
  width: 400px;
  margin-bottom: 250px;
}

.card {
  background-color: white;
  border-radius: 12px;
  padding: 20px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
  width: 100%;
  position: absolute;
}

/* Back card */
.back-card {
  top: 75px;
  left: 50px;
  z-index: 1;
  opacity: 0.2;
  width: 502px;
  height: 232px;
}

/* Front card */
.front-card {
  top: 0;
  left: 0;
  z-index: 2;
  width: 504px;
  height: 245px;
  display: flex;
  flex-direction: column;
  gap: 3rem;
}

/* Profile image */
.profile-img {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  object-fit: cover;
  position: absolute;
  top: -50px;
  left: -10px;
  border: 3px solid white;
  box-shadow: 0 2px 8px rgba(0,0,0,0.15);
}

.page5-cont1{
   width: 402px;
   height: 96px;
   font-family: "Poppins-Medium";
   font-size: 16px;
   color: #444444;
}

.author1{
  width: 101px;
  height: 27px;
  font-family: "Poppins-SemiBold";
  font-size: 18px;
  color: #222222;
}

.author2{
  width: 116px;
  height: 21px;
  font-family: "Poppins-Medium";
  font-size: 14px;
  color: #666666;
}

.author11{
  width: 150px;
  height: 27px;
  font-family: "Poppins-SemiBold";
  font-size: 18px;
  color: #222222;
  margin-top: 50px;
}

.author12{
  width: 130px;
  height: 21px;
  font-family: "Poppins-Medium";
  font-size: 14px;
  color: #666666;
}




.page6{
  width: 1920px;
  height: 960px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}



.page6-cont1{
  width: 646px;
  height: 54px;
  font-family: "Volkhov";
  font-size: 48px;
  color: #222222;
  margin-bottom: 50px;
  text-align: center;
  
}

.page6-boxes{
  width: 1170px;
  height: 426px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  
}
.page6-box{
  width: 270px;
  height: 388px;
  color: FEFCFB;
  border-radius: 8px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  position: relative;
  z-index: 10;
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);

}


.page6-box1-logo{
  width: 270px;
  height: 270px;
  border-radius: 8px;

}
.page6-box1-cont{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  /* gap:2rem; */
}

.page6-box1-cont1{
  width: 244px;
  height: 52px;
  font-family: "Poppins-Medium";
  font-size: 18px;
  color: #222222;
  margin-bottom: 20px;
}

.page6-box1-cont2
{
   width: 98px;
   height: 26px;
   font-family: "Inter";
   font-size: 16px;
   color: #999999;
   margin-bottom: 10px;
   margin-right: 150px;
}


.page6-arrow{
  width: 104px;
  height: 40px;
  margin-top: 30px;
  margin-left: 60px;
}


.page7{
  width: 1920px;
  height: 898px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
}

.page7-cont1{
  width: 1170.25px;
  height: 416px;
  position: relative;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-around;
  background-color: #FA7436;
}

.page7-cont2{
  width: 1205px;
  height: 210px;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.page7-cont3{
   width: 1172px;
   height: 24px;
   display: flex;
   align-items: center;
   justify-content: space-between;
}

.page7-textbox{
  width: 674px;
  height: 68px;
  margin-left: 60px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color: #FFFFFF;
   z-index: 999;            /* Ensure it's on top */
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.15);  /* Optional: add depth */
  border-radius: 10px;
}

.page7-sub-content{
  width: 708px;
  height: 124px;
  font-family: "Volkhov";
  font-size: 48px;
  text-align: center;
  color: #FFFFFF;
}

.page7-subscribe{
  width: 132px;
  height: 50px;
  border-radius: 8px;
  margin-left: 300px;
  color: #FFFFFF;
  background-color: #FA7436;
  font-family: "Poppins-Regular";
  font-size: 16px;
  border: none;
}
.page7-mail-cont{
  display: flex;
  align-items: center;
  justify-content: center;
}

.page7-mail{
  height: 24px;
  width: 120px;
  font-family: "Poppins-Regular";
  font-size: 16px;
  color: #999999;
}

.page7-mail-img{
  width: 18.67px;
  height: 16px;
  color: #666666;
  margin-left: 30px;
  margin-right: 10px;
}

.page7-cont2-box1{
  width: 254px;
  height: 176px;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: space-between;
  margin-left: 20px;
}

.page7-cont2-box2{
  width: 598px;
  height: 210px;
  display: flex;
  padding-top: 15px;
  justify-content: center;
  gap: 5rem;
}

.page7-logo{
    width: 130px;
    height: 24px;
    font-family:'Volkhov';
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 10px;
    margin-right: 130px;
}
.page7-logo-name{
    font-size: 24px; 
}
.page7-logo-img{
    width: 19px;
    height: 19px;

}

.page7-trip-cont{
  width: 254px;
  height: 64px;
  font-family: "Poppins-Medium";
  font-size: 16px;
  color: #666666;
  margin-top: 20px;
}

.page7-social{
  width: 176px;
  height: 48px;
  margin-right: 80px;
}
.page7-face{
  width: 40px;
  height: 40px;
  background-color: #FFFFFF;
  color: #444444;
}

.page7-insta{
  width: 48px;
  height: 48px;
  background-color: #FFFFFF;
  color: #FA7436;
}

.page7-company{
  width: 140px;
  height: 210px;
  
}

.page7-contact{
  width: 85px;
  height: 168px;
}

.page7-more{
  width: 113px;
  height: 168px;
}

.page7-feature{
  list-style-type: none;
}

.page7-feature-tittle{
  width: 92px;
  height: 26px;
  font-family: "Poppins-SemiBold";
  font-size: 18px;
  color: #222222;
  margin-bottom: 20px;
}

.page7-feature-item1{
  width: 54px;
  height: 26px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  color: #666666;
  margin-bottom: 10px;
}

.page7-feature-item2{
  width: 72px;
  height: 26px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  color: #666666;
  margin-bottom: 10px;
}

.page7-feature-item3{
  width: 68px;
  height: 26px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  color: #666666;
  margin-bottom: 10px;
}

.page7-feature-item4{
  width: 140px;
  height: 26px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  color: #666666;
  margin-bottom: 10px;
}

.page7-feature-item5{
  width: 85px;
  height: 26px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  color: #666666;
  margin-bottom: 10px;
}

.page7-feature-item6{
  width: 48px;
  height: 26px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  color: #666666;
  margin-bottom: 10px;
}

.page7-feature-item7{
  width: 73px;
  height: 26px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  color: #666666;
  margin-bottom: 10px;
}

.page7-feature-item8{
  width: 113px;
  height: 26px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  color: #666666;
  margin-bottom: 10px;
}

.page7-feature-item9{
  width: 77px;
  height: 26px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  color: #666666;
  margin-bottom: 10px;
}

.page7-feature-item10{
  width: 113px;
  height: 26px;
  font-family: "Poppins-Regular";
  font-size: 18px;
  color: #666666;
  margin-bottom: 10px;
}

.page7-copyright{
  width: 347px;
  height: 24px;
  font-family: "Poppins-Regular";
  font-size: 16px;
  color: #666666;
}

.page7-terms{
  width: 156px;
  height: 24px;
  font-family: "Poppins-Regular";
  font-size: 16px;
  color: #666666;
}

.line{
  width: 1170px;
  height: 0px;
  color: #999999;
}

.page7-circle{
  position: absolute;
  top: 55px;
  left: 0;
  color: #C4C4C4;
}

.page7-tree{
  position: absolute;
  top: 10px;
  right: 0;
  color: #E5E5E5;
  width: 112.25px;
  height: 113.12px;
}
`

## OUTPUT
<img width="1600" height="855" alt="image" src="https://github.com/user-attachments/assets/689c9d2d-9154-4e04-9617-80f7b689a3fd" />
<img width="1678" height="719" alt="image" src="https://github.com/user-attachments/assets/b8353f2c-65b8-45eb-858e-3cb542f4f0c2" />
<img width="1802" height="853" alt="image" src="https://github.com/user-attachments/assets/6690e65a-f6d0-407d-8918-4fba412b97e8" />

<img width="1790" height="752" alt="image" src="https://github.com/user-attachments/assets/d1e15101-3ad3-415f-a70c-b54d2e3efccc" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
