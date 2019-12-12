<!DOCTYPE html>
<html>
    <head>
        <title>Blog</title>
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" type="text/css" href="../CSS files/blog.css">
        <link rel="stylesheet" type="text/css" href="../CSS files/menuBarCnt.css">
        <link rel="stylesheet" type="text/css" href="../CSS files/slide.css">
        <link href="https://fonts.googleapis.com/css?family=Comfortaa" rel="stylesheet">
    
    <style>
        /*body contains entire content */
        body{
            background:url("aa.jpg");
            background-size:fill;
        }

        .slideContainer{
            /* background:rgba(128, 128, 128, 0.418); */
            padding: 10px;
        }
        .blogIMG{
            height:200px;
            width:400px;
        }

        #demo{
            color:white;
            font-size: 15px;
            font-family: 'Montserrat', sans-serif;
            text-align: center;
            display: block;
            background: rgba(16, 173, 221, 0.781);
        }

    </style>

    </head>
        <body>

            <div class="bar">
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="cv.html">Cv</a></li>
                    <li><a href="research.html">Research</a></li>
                    <li><a href="blog.html">Blog</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
                </div>
            
            <marquee style="color:white;" direction="right"><h2>~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</h2></marquee>    
            <div class="header"><h2>Effects of Technology</h2></div>
            <marquee style="color:white;" direction="left"><h2>~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~</h2></marquee>
            
                
            
            <div class="container">



                <div class="lower-grid">

                    <div class="zoom"><h4 style="margin-left:65%; color:white; font-family: 'Montserrat', sans-serif;">COMMUNICATION</h4><div class="lower-grid-left"><img src="../HTML files/com.PNG" class="blogIMG"><p class="paragraph"> &nbsp Technology speeds up the communication between people.
                                                                         Technology provides convenience to use more than one method of communication. 
                                                                         Now people can use email, social media, chat messengers, video conferencing, 
                                                                         video calls, images, videos, symbols etc. for the communication.
                                                                         Technology should not affect humans adversely, it is not created to affect in that manner.
                                                                         But when we overuse it, when we forget the basic rules and methods then it hits back at us.
                                                                        This is true for any communication machine and technology. Even if you eat too much you become unhealthy.
                                                                        If you sleep too much you will become unhealthy. There are certain limits of each machine.
                                                                        Fast shipment options allow businesses to move products over a large geographic area. When customers use technology 
                                                                        to interact with a business, communication creates a stronger public image.</p></div> </div>

                    <div class="zoom"><h4 style="margin-left:65%; color:white; font-family: 'Montserrat', sans-serif;">BUSINESS</h4><div class="lower-grid-left"><img src="../HTML files/bus.PNG" class="blogIMG"><p class="paragraph"> &nbsp During the 1990s, the world of photography started to see a shift from film photography to digital photography.
                                                                    Three big names in the field of film photography then were Fujifilm, Konica and Kodak.
                                                                    The change in technology affected these businesses greatly.
                                                                    The introduction of new technology has constantly changed the way a company functions.
                                                                    The developments in IT has taken over almost all departments of an organization.
                                                                    Today, information is mostly stored in servers as opposed to decades-old method of storing 
                                                                    in hard copies (files and registers). Thanks to the advancement in the internet, companies use digital marketing
                                                                     strategies to market and sell their products today.Technology also helps a business understand its cash flow 
                                                                     needs and preserve precious resources such as time and physical space</p></div></div>

                    <div class="zoom"><h4 style="margin-left:65%; color:white; font-family: 'Montserrat', sans-serif;">TRANSPORTATION</h4><div class="lower-grid-left"><img src="../HTML files/transportation.jpg" class="blogIMG"><p class="paragraph"> &nbsp Technology has impacted the modern transportation. Transportation has become faster like individuals
                                                                         can move rapidly starting with one place then on to the next. In the past, people cannot travel as 
                                                                         rapidly as today because of not having enough modern transportation. It takes just a few hours to travel 
                                                                         nowadays, so this lead to people travel more.
                                                                         The advent of self-driving driving cars such as the Google car and Telsa are making the idea of autonomous
                                                                         cars a reality. Several, states across the country have begun passing laws to regulate the technology and 
                                                                         encourage its development.Ever since they showed up, drones were on a constantly evolving path and now,
                                                                        the models come with much more advanced features then the features that are available today, that allow them to perform tasks we would never have 
                                                                        imagined them doing some 10 years ago.</p></div></div>div>

                </div>

            </div>
            
            <br><br>
            <div class="slideshow-container">

                <div class="mySlides fade">
                  <img src="../CSS files/computer.jpg" class="slideIMG">
                </div>
                
                <div class="mySlides fade">
                  <img src="../CSS files/b.png" class="slideIMG">
                </div>
                
                <div class="mySlides fade">
                  <img src="../CSS files/drone.jpg" class="slideIMG">
                </div>

                <div class="mySlides fade">
                    <img src="../CSS files/d.jpg" class="slideIMG">
                  </div>
                
                <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
                <a class="next" onclick="plusSlides(1)">&#10095;</a>
                
            </div>
                <h1 style="color:white; text-align: center; font-family: 'Montserrat', sans-serif;">Slide Show</h1>
                <div class="endDetails"><h3>About Author</h3><br> <img src="employee.png" height="28px" width="30px"> &nbsp ANIL SHRESTHA <br>
                     <img src="university.png" height="28px" width="30px"> &nbsp Islington College
                     <br><img src="phone.png" height="29px" width="30px"> &nbsp 9843291445 </div>

                <p id="demo"></p>

            <div class="footer"> &copy Rights Reserved. &nbsp &#9742  9843291445</div>
            <script src="../JS files/slide.js"></script>

            <script>
                var day;
                switch (new Date().getDay()) {
                case 0:
                    day = "Sunday";
                    break;
                case 1:
                    day = "Monday";
                    break;
                case 2:
                    day = "Tuesday";
                    break;
                case 3:
                    day = "Wednesday";
                    break;
                case 4:
                    day = "Thursday";
                    break;
                case 5:
                    day = "Friday";
                    break;
                case  6:
                    day = "Saturday";
                }
                document.getElementById("demo").innerHTML = "Today is " + day;
            </script>
            
        </body>

</html>