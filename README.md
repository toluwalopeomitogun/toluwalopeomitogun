<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>University design</title>
        <link rel="stylesheet" href="style.css">
     <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.1.1/css/fontawesome.min.css">   
    </head>
    <body>
        <section class="header">
            <nav>
                <a href="index.html"> <img src="image/logo1.png" alt="logo"></a>
                <div class="nav-links" id="navLLinks">
                    <i class="fa fa-window-close" onclick="hideMenu()"></i>
                    <ul>
                        <li> <a href="HOME">HOME </a> </li>
                        <li> <a href="ABOUT"> ABOUT</a> </li>
                        <li> <a href="COURSE"> COURSE</a> </li>
                        <li> <a href="BLOG"> BLOG</a> </li>
                        <li> <a href="CONTACT">CONTACT </a> </li>
                    </ul>
                </div>
                <i class="fa fa-bars" onclick="showMenu()"></i>
            </nav>
            <div class="text-box">
                <h1>Toluskyy University OF <br> Technology, Abeokuta.</h1>
                <p>I am Toluwalope Emmanuel Omitogun and I am creating my first responsive website <br> with HTML CSS and a little bit of Javascript.<br> I hope you will love it.</p>
                <a href="" class="hero-btn"> Visit to know more</a>
            </div>

        </section>
<!-----coourse--------->
<section class="course">
    <h1>Courses offered</h1>
    <p>Fine arts, Cryptocurrency, NFT, Web development, Barbing, Forex trading</p>

    <div class="row">

    <div class="course-col">
    <h3>Fresher</h3>
    <p>To learn at beginner level is not hard, just be focused and do your best </p>
    </div>

    <div class="course-col">
    <h3>Degree</h3>
    <p>To learn at beginner level is not hard, just be focused and do your best </p>
    </div>

    <div class="course-col">
    <h3>Graduates/Alumni</h3>
    <p>To learn at beginner level is not hard, just be focused and do your best </p>
    </div>
    </div>

</section>

<section class="campus">
    <h1> Our campus</h1>
    <p> I dont know what to put here</p>


    <div class="row">
        <div class="campus-col">
    <img src="image/istockphoto-182444113-170667a.jpg" alt="first campus">
    <div class="layer">
        <h3>AKURE</h3>
        </div>
    </div>

    <div class="campus-col">
        <img src="image/Jefferson-Suites-2400x1500.jpg" alt="first campus">
        <div class="layer">
            <h3>ABEOKUTA</h3>
            </div>
        </div>


        <div class="campus-col">
            <img src="image/pexels-photo-207692.jpeg" alt="first campus">
            <div class="layer">
                <h3>OYO</h3>
                </div>
            </div>
    </div>
</section>


<!------facility------->
<section class="facilities">
    <h1> Our Facilities</h1>
    <p> Ill come back to this too</p>

    <div class="row">
        <div class="facilities-col">
            <img src="image/pexels-pixabay-207684.jpg">
            <h3> World class library</h3>
            <p> I dont know what ill put here too, ill come back to it</p>
        </div>


    <div class="facilities-col">
        <img src="image/pexels-pixabay-207729.jpg">
        <h3> Kitchen</h3>
        <p> I dont know what ill put here too, ill come back to it</p>
    </div>



<div class="facilities-col">
    <img src="image/photo-1618355776464-8666794d2520.jfif">
    <h3> Largest playground</h3>
    <p> I dont know what ill put here too, ill come back to it</p>
</div>
</div>

</section>



<!-----------testimonial---------------->

<section class="testimonials">
    <h1> What our student says</h1>
    <p> IMMA COME back to all paragraphs and h tags</p>

    <div class="row">
    <div class="testimonials-col">
        <img src="image/tolu.png" alt="testimony">
        <div>
            <p> I think im almost done with this website, very tired though</p>
            <h3> Toluwalope Omitogun</h3>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star-o"></i>
        </div>

    </div>

    <div class="testimonials-col">
        <img src="image/ayo.png" alt="testimony">
        <div>
            <p> I think im almost done with this website, very tired though</p>
            <h3> Ayomikun Omitogun</h3>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star"></i>
            <i class="fa fa-star-o"></i>
        </div>
    </div>


        <div class="testimonials-col">
            <img src="image/prommy.png" alt="testimony">
            <div>
                <p> I think im almost done with this website, very tired though</p>
                <h3> Bamidele Ilerioluwa</h3>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star"></i>
                <i class="fa fa-star-half-o"></i>
            </div>
    </div>
    </div>
</section>



<!----------call to  action-------->
<section class="cta">
<h1> Enroll for Various Online Courses <br> Anywhere from the world</h1>
<a href="" class="hero-btn">CONTACT US</a>
</section>

<section class="footer">
    <h4> ABOUT US</h4>
    <P>A deity or a god is a supernatural being who is considered
         divine or sacred. The Oxford Dictionary of English defines deity <br>
         as a god or goddess, or anything revered as divine
        </P>
        <div class="icons">
            <i class="fa fa-facebook-official"></i>
            <i class="fa fa-twitter"></i>
            <i class="fa fa-linkedin"></i>
            <i class="fa fa-instagram"></i>
        </div>
        <p> Made with <i class="fa fa-heart-o"></i> by Toluwalope Emmanuel
        </p>
</section>








        <!----------javascript for the mobile broweser--------->
<script>
    var navLLinks=document.getElementById("navLLinks");
    function showMenu(){
        navLLinks.style.right="0";
    }
    function hideMenu(){
        navLLinks.style.right="-200px";
    }
</script>
    </body>
</html>
