# landing-page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZenHaven: Your Path to Inner Peace</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />

   </head>

   <style>


    body{
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f2f2f2;
    color: #434343;
 
}


@-webkit-keyframes glow {
  from {
    text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #00e6c0e3, 0 0 40px #10bc72, 0 0 50px #00e66b, 0 0 60px #11bd3f, 0 0 70px #06e93b;
  }
  to {
    text-shadow: 0 0 20px #fff, 0 0 30px #4dff8e, 0 0 40px #4dff8e, 0 0 50px #4dff8e, 0 0 60px #4dff8e, 0 0 70px #4dff8e, 0 0 80px #4dff8e;
  }
}


.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    justify-content: center;
}

.intro h2, .features h2, .testimonials h2{
    color: rgba(7, 39, 13, 0.827);
    text-align: center;
    text-decoration: underline;
    font-size: 30px;
}

.about h2, .contact h2, .newsletter h2{
    color: rgb(11, 38, 16);
    text-align: center;
    text-decoration: underline;
    font-size: 30px;
}

header {
    font-size: medium;
    color: white;
    padding: 10px 0;
    text-align: center;
    }

.img{
    background-image: url("file:///C:/Users/win10/Desktop/landing%20page/image_KRdvvDgQ_1694136284107_512.webp");
    background-size: cover;

   
}
h1 {
  font-weight: 100%;
  font-size: 65px;
  font-style: italic;
   font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
   text-align: center;
  -webkit-animation: glow 1s ease-in-out infinite alternate;
  -moz-animation: glow 1s ease-in-out infinite alternate;
  animation: glow 1s ease-in-out infinite alternate;
}

.intro p{
    color: white;
    text-align: center;
}


.features, .testimonials{
    margin: 40px 0;
    text-align: center;
    color: #333;
}
.about, .contact, .newsletter {
    margin: 40px 0;
    text-align: center;
    color: white;
}


.features ul, .testimonials ul {
    list-style-type: none;
    padding: 0;
}

.features li, .testimonials li {
    background-color: white;
    margin: 10px 0;
    padding: 20px;
    border-radius: 8px;
    text-align: center;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.download-buttons h2{
    color: rgb(11, 38, 16);
    text-align: center;
    text-decoration: underline;
    font-size: 30px;
}

.download-buttons a {
    display:inline-block;
    margin: 10px;
    padding: 17px 50px;
    color: white;
    background-color:  #2ec135;
    text-decoration: none;
    border-radius: 5px;
    align-items: center;
    margin-inline-start: 150px;
    font-size: 1.2rem;
}

.download-buttons a i{
    display: inline;
    margin-inline: 10px;
    align-items: center;
}

.download-buttons a:hover {
    background-color: #45a049;
}

.contact i{
    display: flexbox;
    color: white;
    margin: 10px;
}
.contact i:hover{
    color: #f2f2f2;
}

.newsletter a{
    color: rgb(0, 119, 255);
}

.about a{
    color:  rgb(0, 119, 255);
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px 0;
}
   </style>
<body>
    <div class="img">
    <header>
        <h1>ZenHaven: Your Path to Inner Peace</h1>
    </header>
    <div class="container">
        <section class="intro">
            <h2>Discover the Benefits of Meditation</h2>
            <p>Unlock a healthier, happier you with CalmMind. Our app offers guided meditations, sleep stories,
              breathing exercises, and more to help you find peace and balance in your busy life.</p>
        </section>

        <section class="features">
            <h2>Features</h2>
            <ul>
                <li><strong>Guided Meditations:</strong> Tailored sessions for beginners and advanced practitioners.</li>
                <li><strong>Sleep Stories:</strong> Calm your mind and drift into a restful sleep.</li>
                <li><strong>Breathing Exercises:</strong> Techniques to help you relax and focus.</li>
                <li><strong>Progress Tracking:</strong> Monitor your journey and stay motivated.</li>
                <li><strong>Personalized Recommendations:</strong> Get suggestions based on your preferences and goals.</li>
            </ul>
        </section>

        <section class="testimonials">
            <h2>Testimonials</h2>
            <ul>
                <li>"ZenHaven transformed my daily routine. I sleep better and feel more focused during the day."<strong> - Sarah J.</strong></li>
                <li>"The guided meditations are perfect for my busy schedule. I feel more at peace and balanced." <strong>- Mark T.</strong></li>
            </ul>
        </section>

        <section class="download-buttons">
            <h2>Get Started Today!</h2>
            <a href="#">
                <i class="fa-brands fa-apple"></i>
                <span>Download on the App Store</span>
            </a>
            <a href="#">
                <i class="fa-brands fa-google-play"></i>
                <span>Get it on Google Play</span>
            </a>
        </section>

        <section class="about">
            <h2>About Us</h2>
            <p>At ZenHaven, our mission is to help you find inner peace and balance through the power of meditation. Our team of experts is dedicated to providing the best meditation experience to enhance your well-being.</p>
            <a href="#">Learn More</a>
        </section>

        <section class="contact">
            <h2>Contact Us</h2>
            <p>Have questions or need support? Reach out to our friendly team.</p>
            <p>Email: support@zenhaven.com</p>
            <p>Phone: (123) 456-7890</p>
                <a href="instagram.com"><i class="fa-brands fa-square-instagram"></i></a>
                <a href="twitter.com"><i class="fa-brands fa-twitter"></i></a>
                <a href="facebook.com"><i class="fa-brands fa-facebook"></i></a>
            <p>Follow Us on Social Media</p>
        </section>

        <section class="newsletter">
            <h2>Join Our Newsletter</h2>
            <p>Stay updated with the latest meditation tips and app updates.</p>
            <a href="#">Sign Up</a>
        </section>
    </div>

    <footer>
        <p>© 2024 ZenHaven. All rights reserved.</p>
    </footer>
    </div>
</body>
</html>
