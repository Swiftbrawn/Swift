# Swift
project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dance contest</title>
    <link rel="stylesheet" href="/Assets/CSS/styles.css">
    <link rel="stylesheet" href="/CSS/css/all.css">
    <link id="themecolor" rel="stylesheet" href="/Assets/CSS/light.css">



</head>

<body>
    <!-- the Header -->
    <div class="logo">
        <div>
            <header>
                <div class="logo2">
                    <img src="/Assets/IMG/logo.png" alt="Dance Logo" width="50px" class="logo-img">

                    <nav>
                        <div class="List">
                            <ul class="main">
                                <li><a href="#">intro</a></li>
                                <li><a href="#">countdown</a></li>
                                <li><a href="#">notes</a></li>
                                <li><a href="#">location</a></li>
                                <li><a href="#">contact</a></li>
                            </ul>
                    </nav>
                    <!-- <a href="#" class="call">call me</a> -->

                    <button onclick="document.getElementById('themecolor').setAttribute('href','/Assets/CSS/dark.css')"><i class="fa-solid fa-moon"></i></button>
                </div>
        </div>
        </header>

        <!-- Hero  -->
        <section>
            <div class="presents">
                <h5>imomotimi foundation presents</h5>
                <div class="ijaw">
                    <h1>imomotimi ijaw </h1>
                    <h1>dance contest 2024</h1>
                </div>
                <button value="submit">Download entry form <i class="fa-solid fa-download"></i></button>
                <p>All duly filled out forms and the entry
                    fees should be brought to the auditions.</p>
            </div>
            <div class="shape">
                <img src="/Assets/IMG/shape-top-white-80.png" alt="" width="100%">
            </div>
    </div>
    </section>
    <!-- countdown -->
    <section>
        <div class="countdown-container">
            <h2>Countdown to Audition</h2>
            <div class="countdown-timer">
                <div class="time-section">
                    <span class="time">29</span>
                    <hr width="15px">
                    <p>Days</p>
                </div>
                <span class="colon">:</span>
                <div class="time-section">
                    <span class="time">02</span>
                    <hr width="15px">
                    <p>Hours</p>
                </div>
                <span class="colon">:</span>
                <div class="time-section">
                    <span class="time">08</span>
                    <hr width="15px">
                    <p>Minutes</p>
                </div>
                <span class="colon">:</span>
                <div class="time-section">
                    <span class="time">06</span>
                    <hr width="15px">
                    <p>Seconds</p>
                </div>
            </div>For More Information:
            <img src="/Assets/IMG/shape-top-grey-80.png" alt="Logo Bottom" class="logoBottom" width="100%">
        </div>
    </section>



    <section>
        <div class="important">
            <h2> Important things to note....</h2>
            <div class="detail">
                <ul class="prize-list">
                    <li><i class="fa fa-money-bill-wave"></i></li>
                    <li>Pricing</li>
                    <li>Audition forms are available for </li>
                    <li> &#8358;1,000 single contestants,</li>
                    <li>and &#8358;1,500 for a group of five.</li>
                </ul>
            </div>
            <div class="detail">
                <ul>
                    <li><i class="fa fa-trophy"></i></li>
                    <li><strong>Prizes</strong></li>
                    <li><strong>1st Prize: &#8358;</strong>2,000,000</li>
                    <li><strong>2nd Prize: &#8358;</strong>1,000,000</li>
                    <li><strong>3rd Prize: &#8358;</strong>500,000</li>
                </ul>
            </div>
        </div>
    </section>
    <!-- map area-->
    <div>
        <iframe
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3975.0515592997285!2d6.318390373439563!3d4.931030995044984!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x106a055be1dcce59%3A0xa6c5b6a97ac6c1a!2sNitro%20Studios!5e0!3m2!1sen!2sng!4v1727795628840!5m2!1sen!2sng"
            width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"
            referrerpolicy="no-referrer-when-downgrade" class="map"></iframe>
        <div class="grey"><img src="/Assets/IMG/shape-top-grey-80.png" alt="" width="100%"></div>
    </div>

    <section>
        <div class="contact-section">
            <div class="contact-info">
                <h2>For More Information:</h2>
                <p><strong>Hotlines:</strong> 07035973706 & 08108112759</p>
                <p><strong>Email:</strong> info@ijawdancecontest.ng</p>
                <p><strong>Audition Location:</strong> Nitro Studio, Tamara Hall, Otiotio Road, Yenegoa, Bayelsa State.
                </p>
            </div>

            <div class="contact-form">
                <form action="" method="POST">
                    <div class="form-group">
                        <div class="inputicon">
                            <i class="fas fa-user"></i><input type="text" name="fname" placeholder="Name">
                        </div>
                        <div class="inputicon">
                            <i class="fas fa-phone-volume"><input type="tel" name="phone" placeholder="Phone"></i>
                        </div>
                    </div>
                    <div class="form-group">
                        <div class="inputicon">
                            <p><i class="fas fa-envelope"><input type="email" name="email" placeholder="Email"></i></p>
                        </div>
                        <div class="inputicon">
                            <i class="fas fa-info-circle"><input type="text" name="subject" placeholder="Subject"></i>
                        </div>
                    </div>
                    <!-- <label for="message">How can we help you? Feel free to get in touch!</label> -->

                    <i class="fa-solid fa-pencil"><textarea name="message" id="message"
                            placeholder="How can we help you? Feel free to get in touch!"></textarea></i>
                    <button type="submit">Get In Touch</button>
                </form>
            </div>
        </div>
    </section>
    <section>
        <footer>
            <div class="footerarea">
                <h3>We are social</h3>
                <div class="socialIcons">
                    <a href="#"><span class="icon-container"><i class="fa-brands fa-facebook-f"></i></span></i></a>
                    <a href="#"><span class="icon-container"><i class="fa-brands fa-x-twitter"></i></span></i></a>
                    <a href="#"><span class="icon-container"><i class="fa-brands fa-instagram"></i></span></i></a>
                    <a href="#"><span class="icon-container"><i class="fa-brands fa-youtube"></i></span></i></a>
                </div>
            </div>
            <p>
                <hr>
            </p>
            <p>&copy; 2024 Imomotimi Foundation. All Rights Reserved.</p>
        </footer>
    </section>
</body>

</html>
