# portfolio-website
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>shradha _developer portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,700;1,400&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(0, 0, 33);
            color: white;
            font-family: 'Poppins', sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(18, 18, 62);
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
            color: rgb(155, 155, 218);
            font-size: 1.04rem;
        }

        .left {
            font-size: 1.5rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 110px 0;
        }

        .firstSection>div {
            width=30%;
        }

        .leftSection {
            width: 50%;
            font-size: 3rem;
        }

        .leftSection .btn {
            padding: 12px;
            background: #1e2167;
            color: white;
            border: 2px solid white;
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;
        }

        .rightSection {
            width: 30%;
        }

        .rightSection img {

            width: 80%;
        }

        .purple {
            color: rgb(134, 85, 179);
        }

        #element {
            color: rgb(134, 85, 179)
        }

        .secondSection {
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }

        main hr {
            border: 0;
            background: #9c97f1;
            height: 1.2px;
            margin: 40px 84px;

        }

        .secondSection h1 {
            font-size: 1.9rem;
        }

        .text-gray {
            color: gray;
        }

        .secondSection .box {
            background-color: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondSection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 110px;

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

        footer {
            background-color: #171736;

        }

        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }

        .footer ul {
            list-style: none;
        }

        .footer>div {
            width: 223px;
        }

        footer .footer-rights {
            color: gray;
            text-align: center;
            padding: 12px 0;
        }
        .leftSection .buttons{
            padding: 50px 0;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Shradha's portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Services</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hi , my name is <span class="purple">Shradha </span>
                <div>and I am a passionate</div>
                <div>Web Developer</div>
                <span id="element"></span>
                <div class="buttons">
                    <button class="btn">Download Resume</button>
                    <button class="btn"> Visit Github</button>
                </div>
            </div>
            <div class="rightSection"> <img src="pg.png"> </div>
        </section>
        <hr>

        <section class="secondSection">
            <span class="text-gray">What I have done so far</span>
            <h1>Work Experience </h1>
            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="html.png">
                    <div class="vertical-title">HTML Developer (2020-2021)</div>
                    <div class="vertical-desc">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                        Ab saepe ipsam itaque, nulla mollitia debitis hic consequatur pariatur impedit voluptas
                        aspernatur maxime? Similique.</div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="facebook.png">
                    <div class="vertical-title">NodeJS Developer (2021-2022)</div>
                    <div class="vertical-desc">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                        Ab saepe ipsam itaque, nulla mollitia debitis hic consequatur pariatur impedit voluptas
                        aspernatur maxime? Similique.</div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="insta.png">
                    <div class="vertical-title">Python Developer (2022-2023)</div>
                    <div class="vertical-desc">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                        Ab saepe ipsam itaque, nulla mollitia debitis hic consequatur pariatur impedit voluptas
                        aspernatur maxime? Similique.</div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="youtube.png">
                    <div class="vertical-title">React js Developer (2022-2023)</div>
                    <div class="vertical-desc">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                        Ab saepe ipsam itaque, nulla mollitia debitis hic consequatur pariatur impedit voluptas
                        aspernatur maxime? Similique.</div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="developer.png">
                    <div class="vertical-title">Backend Developer (2022-2023)</div>
                    <div class="vertical-desc">Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                        Ab saepe ipsam itaque, nulla mollitia debitis hic consequatur pariatur impedit voluptas
                        aspernatur maxime? Similique.</div>

                </div>
            </div>
        </section>
    </main>


    <footer>

        <div class="footer">
            <div class="footer-first">
                <h3>Shradha's Developer portfolio</h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Contact</li>
                </ul>
            </div>
            <div class="footer-third">
                <ul>
                    <li>home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Contact</li>
                </ul>
            </div>
            <div class="footer-fourth">
                <ul>
                    <li>home</li>
                    <li>About</li>
                    <li>Services</li>
                    <li>Contact</li>
                </ul>
            </div>
        </div>
        <div class="footer-rights"> copyright &#169; www.shradhasportfolio.com |All rights reserved </div>
    </footer>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <!-- Setup and start animation! -->
    <script>
        var typed = new Typed('#element', {
            strings: ['Web developer!!', 'Web designer!!', 'Video Editor!!'],
            typeSpeed: 50,
        });
    </script>

</body>

</html>
