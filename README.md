<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Danish Ahmed Khan - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Inter:ital,opsz,wght@0,14..32,100..900;1,14..32,100..900&family=Monsieur+La+Doulaise&family=Roboto+Slab:wght@100..900&display=swap"
        rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        .left {
            font-size: 2rem;
        }

        body {
            background-color: rgb(1, 1, 22);
            color: white;
            font-family: 'Roboto+Slab', sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(30, 30, 100);

        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
        }

        nav ul li a:hover {
            color: rgb(81, 81, 197);
            font-size: 1.01rem;
        }

        main hr {
            border: 0;
            background: rgb(104, 138, 231);
            height: 1.2px;
            margin: 60px 84px;
        }

        .leftsection {
            font-size: 3rem;
        }

        .firstsection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 130px 0;
        }

        .firstsection>div {
            width: 40%;
        }

        .leftsection {

            font-size: 2rem;

        }

        .leftsection .button {

            padding: 50px 0;

        }

        .leftsection .btn {
            padding: 12px;
            background-color: #191971;
            color: white;
            border: 2px solid white;
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;
        }

        .rightsection img {
            width: 80%;
            margin: 50px 0;
        }

        .purple {
            color: rgb(156, 103, 206);
        }

        .text-gray {
            color: gray;
        }

        #element {
            color: rgb(156, 103, 206);
        }

        .secondsection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }

        .secondsection hr {
            font: 1.9rem;
        }

        .secondsection .box {
            background: white;
            width: 86vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondsection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 120px;
        }

        .image-top {
            width: 23px;
            position: relative;
            top: -32px;
            left: -9px;
        }

        .vertical-title {
            position: relative;
            top: 75px;
            width: 150px;
            font-size: 14px;
        }

        .vertical-desc {
            position: relative;
            top: 86px;
            color: gray;
            width: 150px;
            font-size: 9px;
        }

        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;

        }

        footer {
            background-color: #110c48;
            /* height: 200px; */
        }

        .footer ul {
            list-style: none;
        }

        .footer>div {
            width: 223px;
        }

        footer .footer-rights {
            text-align: center;
            color: gray;
            padding: 12px 0;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Danish Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstsection">
            <div class="leftsection">
                Hi, My name is <span class="purple">Danish</span>
                <div>
                    and I am a passionate
                </div>
                <span id="element"></span>
                <div class="button">
                    <a href="Danish Ahmed Khan final and update.pdf"><button class="btn">Download Resume</button></a>
                    <a href="https://github.com/"> <button class="btn">Visit Github</button></a>
                </div>
                <div>

                </div>


            </div>

            <div class="rightsection">
                <img src="bg.png">
            </div>
        </section>
        <hr>
        <section class="secondsection">
            <span class="text-gray">
                What I have done so far
            </span>
            <h1>Work Experience</h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="ckc logo.png" alt="">
                    <div class="vertical-title">
                        Math & Computer Teacher
                    </div>
                    <div class="vertical-desc">
                        Experience: (April,2023 – November 2025)
                       <br> Work Company : Christ the King College , Safa
                        <br>Location : Jhansi (U.P)
                    </div>
                </div>

                <div class="vertical">
                    <img class="image-top" src="planetspark.png" alt="">
                    <div class="vertical-title">
                        Public Speaking & Creative Writing Expert
                    </div>

                    <div class="vertical-desc">
                        Expertise : Public Speaker
                        <br> Status : ( June 2023 - July 2024)
                        Work Company: PlanetSpark
                        Location : Gurugram , India
                        <br>Work Mode : Online
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="alphonsa logo.png" alt="">
                    <div class="vertical-title">
                        Senior Computer Teacher
                    </div>
                    <div class="vertical-desc">
                        Expertise : Computer
                        <br>Status : ( November 2024 - Present )
                        Work Company: St. Alphonsa High School
                        <br>Location : Prithvipur (M.P)
                    </div>
                </div>
               



            </div>

        </section>
    </main>
    <footer>
        <div class="footer">
            <div class="footer-first">
                <h3>
                    Danish's Developer Portfolio
                </h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>youtube</li>
                    <li>instagram</li>
                    <li>Twitter</li>
                    <li>Html</li>
                    <li>Css</li>
                </ul>
            </div>
            <div class="footer-third">
                <ul>
                    <li>youtube</li>
                    <li>instagram</li>
                    <li>Twitter</li>
                    <li>Html</li>
                    <li>Css</li>
                </ul>
            </div>
            <div class="footer-fourth">
                <ul>
                    <li>youtube</li>
                    <li>instagram</li>
                    <li>Twitter</li>
                    <li>Html</li>
                    <li>Css</li>
                </ul>
            </div>
        </div>
        <div class="footer-rights">
            Copyright &#169; www.danishportfolio.com | All rights reseved
        </div>
    </footer>

    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
    <!-- Setup and start animation! -->
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'Social Media Manager', 'Web Designer', 'Graphic Designer', 'Video Editor'],
            typeSpeed: 50,
        });
    </script>
</body>

</html>
