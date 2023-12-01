<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <!-- =====BOX ICONS===== -->
    <link href='https://cdn.jsdelivr.net/npm/boxicons@2.0.5/css/boxicons.min.css' rel='stylesheet'> 
    <title>portfolio websites</title>
</head>
<body>
    <!--===== HEADER =====-->
    <header class="l-header">
        <nav class="nav bd-grid">
            <div>
                
         <a href="#" class="nav__logo">Portfolio</a>
            </div>

            <div class="nav__menu" id="nav-menu">
                <ul class="nav__list">
                    <li class="nav__item"><a href="#home" class="nav__link active">Home</a></li>
                    <li class="nav__item"><a href="#about" class="nav__link">About</a></li>
                    <li class="nav__item"><a href="#skills" class="nav__link">Skills</a></li>
                    <li class="nav__item"><a href="#work" class="nav__link">Work</a></li>
                    <li class="nav__item"><a href="#contact" class="nav__link">Contact</a></li>
                </ul>
            </div>
                
           
        </nav>
    </header>

    <main class="l-main">
        <!--===== HOME =====-->
        <section class="home bd-grid" id="home">
            <div class="home__data">
                <h1 class="home__title">Hello<br>I'm <span class="home__title-color">rowdo</span><br>Web Developer</h1>
            </div>

        </section>


        <!--===== ABOUT =====-->
        <section class="about section " id="about">
            <h2 class="section-title">About</h2>

            <div class="about__container bd-grid">
                <div class="about__img">
                    <img src="img.jpg" alt="">
                </div>
                    
                <div>
                    <h2 class="about__subtitle">I'm rowdo</h2>
                    <p class="about__text">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Voluptate cum expedita quo culpa tempora, assumenda, quis fugiat ut voluptates soluta, aut earum nemo recusandae cumque perferendis! Recusandae alias accusamus atque.</p>           
                </div>                                   
            </div>
        </section>

        <!--===== SKILLS =====-->
        <section class="skills section" id="skills">
            <h2 class="section-title">Skills</h2>

            <div class="skills__container bd-grid">          
                <div>
                    <h2 class="skills__subtitle">Profesional Skills</h2>
                    <p class="skills__text">  <p class="description"></p>
                       <p class="mr">Welcome to my web developer portfolio! I'm Mitchell, a skilled and
                        creative web developer with a passion for creating beautiful,
                        responsive, and user-friendly websites. I've worked on a variety of
                        web projects, ranging from personal blogs to e-commerce platforms.
                      </p>

                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bxl-html skills__icon'></i>
                            <span class="skills__name">HTML</span>
                        </div>
                        <div class="skills__bar skills__html">

                        </div>
                        <div>
                            <span class="skills__percentage">75%</span>
                        </div>
                    </div>

                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bxl-css3 skills__icon'></i>
                            <span class="skills__name">CSS3</span>
                        </div>
                        <div class="skills__bar skills__css">
                                
                        </div>
                        <div>
                            <span class="skills__percentage">65%</span>
                        </div>
                    </div>

                    <div class="skills__data">
                        <div class="skills__names">
                            <i class='bx bxl-javascript skills__icon' ></i>
                            <span class="skills__name">JAVASCRIPT</span>
                        </div>
                        <div class="skills__bar skills__js">
                                
                        </div>
                        <div>
                            <span class="skills__percentage">50%</span>
                        </div>
                    </div>
                <div>              
                
                </div>
            </div>
        </section>

        <!--===== WORK =====-->
        <section class="work section" id="work">
            <h2 class="section-title">Work</h2>

            <div class="work__container bd-grid">
                <a href="" class="work__img">
                    <img src="work1.jpg" alt="">
                </a>
                <a href="" class="work__img">
                    <img src="work2.jpg" alt="">
                </a>
                <a href="" class="work__img">
                    <img src="work3.jpg" alt="">
                </a>
                <a href="" class="work__img">
                    <img src="work4.jpg" alt="">
                </a>
                <a href="" class="work__img">
                    <img src="work5.jpg" alt="">
                </a>
                <a href="" class="work__img">
                    <img src="work6.jpg" alt="">
                </a>
            </div>
        </section>

        <!--===== CONTACT =====-->
        <section class="contact section" id="contact">
            <h2 class="section-title">Contact</h2>

            <div class="contact__container bd-grid">
                <form action="" class="contact__form">
                    <input type="text" placeholder="Name" class="contact__input">
                    <input type="mail" placeholder="Email" class="contact__input">
                    <textarea name="" id="" cols="0" rows="10" class="contact__input"></textarea>
                    <input type="button" value="Send" class="contact__button button">
                </form>
            </div>
        </section>
    </main>

    <!--===== FOOTER =====-->
    <footer class="footer">
        <p class="footer__title">social media</p>
        <div class="footer__social">
            <a href="#" class="footer__icon"><i class='bx bxl-facebook' ></i></a>
            <a href="#" class="footer__icon"><i class='bx bxl-instagram' ></i></a>
            <a href="#" class="footer__icon"><i class='bx bxl-twitter' ></i></a>
        </div>
        <p class="footer__copy">&#169; All rights reserved</p>
    </footer>
</body>
</html>
