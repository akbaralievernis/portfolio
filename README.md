<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
</head>
<body>
    <header class="l-header">
        <nav class="nav bd-grid">
            <div>
                <a href="#" class="nav-logo">Akbaraliev</a>
            </div>
            <div class="nav-menu" id="nav-menu">
                <ul class="nav-list">
                    <li class="nav-item"><a href="#home" class="nav-link active">Главная</a></li>
                    <li class="nav-item"><a href="#about" class="nav-link">О нас</a></li>
                    <li class="nav-item"><a href="#skills" class="nav-link">Навыки</a></li>
                    <li class="nav-item"><a href="#work" class="nav-link">Работы</a></li>
                    <li class="nav-item"><a href="#contact" class="nav-link">Контакты</a></li>
                </ul>
            </div>
            <div class="nav-toggle" id="nav-toggle">
                <i class='bx bx-menu'></i>
            </div>
        </nav>
    </header>
    <main class="l-main">
        <section class="home bd-grid" id="home">
            <div class="home-data">
                <h1 class="home-title">Привет <br>Меня зовут<span class="home-title-color">Эрнис</span><br> Веб дизайнер</h1>
                <a href="#" class="button">Контакты</a>
            </div>
            <div class="home-social">
                <a href="#" class="home-social-icon"><i class='bx bxl-linkedin' ></i></a>
                <a href="#" class="home-social-icon"><i class='bx bxl-instagram' ></i></a>
                <a href="#" class="home-social-icon"><i class='bx bxl-github' ></i></a>
            </div>
            <div class="home-img">
                <img src="photo_2024-10-28_21-37-21.jpg" alt="image">
            </div>
        </section>
        <section class="about section" id="about">
            <h2 class="section-title">О нас</h2>
            <div class="about-container bd-grid">
                <div class="about-img">
                    <img src="oshsu.png" alt="image">
                </div>
                <div>
                    <h2 class="about-subtitle">Ауб 1-24</h2>
                    <p class="about-text">Ошский Государственный университет</p>
                </div>
            </div>
        </section>
        <section class="skills section" id="skills">
            <h2 class="section-title">Навыки</h2>
            <div class="skills-container bd-grid">
                <div>
                    <h2 class="skills-subtitle">Профессиональные навыки</h2>
                    <p class="skills-text">Я люблю мыслить нестандартно и воплощать в жизнь уникальные идеи посредством дизайна. Я владею HTML, CSS и JavaScript, что гарантирует, что мои проекты не только красивы, но и функциональны. Я ставлю во главу угла потребности и предпочтения пользователей, провожу исследования, чтобы понять их поведение и предпочтения.</p>
                    <div class="skills-data">
                        <div class="skills-names">
                            <i class='bx bxl-html5 skills-icon' ></i>
                            <span class="skills-name">HTML5</span>
                        </div>
                        <div>
                            <span class="skills-percentage">95%</span>
                        </div>
                        <div class="skills-bar skills-html"></div>
                    </div>
                    <div class="skills-data">
                        <div class="skills-names">
                            <i class='bx bxl-css3 skills-icon' ></i>
                            <span class="skills-name">CSS3</span>
                        </div>
                        <div>
                            <span class="skills-percentage">85%</span>
                        </div>
                        <div class="skills-bar skills-css"></div>
                    </div>
                    <div class="skills-data">
                        <div class="skills-names">
                            <i class='bx bxl-javascript skills-icon' ></i>
                            <span class="skills-name">JAVASCRIPT</span>
                        </div>
                        <div>
                            <span class="skills-percentage">65%</span>
                        </div>
                        <div class="skills-bar skills-js"></div>
                    </div>
                    <div class="skills-data">
                        <div class="skills-names">
                            <i class='bx bxs-paint skills-icon' ></i>
                            <span class="skills-name">UX/UI</span>
                        </div>
                        <div>
                            <span class="skills-percentage">85%</span>
                        </div>
                        <div class="skills-bar skills-ux"></div>
                    </div>
                </div>
                <div>
                    <img src="https://i.postimg.cc/52LWbPyt/work3.jpg" alt="image" class="skills-img">
                </div>
            </div>
        </section>
        <section class="work section" id="work">
            <h2 class="section-title">Работы</h2>
            <div class="work-container bd-grid">
                <div class="work-img">
                    <img src="https://i.postimg.cc/NM0n9bsm/work1.jpg" alt="image">
                </div>
                <div class="work-img">
                    <img src="https://i.postimg.cc/tJZmDTVg/work2.jpg" alt="image">
                </div>
                <div class="work-img">
                    <img src="https://i.postimg.cc/52LWbPyt/work3.jpg" alt="image">
                </div>
                <div class="work-img">
                    <img src="https://i.postimg.cc/fW1wsSCB/work4.jpg" alt="image">
                </div>
                <div class="work-img">
                    <img src="https://i.postimg.cc/m2MTgZ6R/work5.jpg" alt="image">
                </div>
                <div class="work-img">
                    <img src="https://i.postimg.cc/Qd3h9LR7/work6.jpg" alt="image">
                </div>
            </div>
        </section>
        <section class="contact section" id="contact">
            <h2 class="section-title">Контакты</h2>
            <div class="contact-container bd-grid">
                <form action="" class="contact-form">
                    <input type="text" placeholder="Name" class="contact-input">
                    <input type="email" placeholder="Email" class="contact-input">
                    <textarea name="" id="" cols="0" rows="10" class="contact-input"></textarea>
                    <input type="button" value="Send" class="contact-button button">
                </form>
            </div>
        </section>
    </main>
    <footer class="footer">
        <p class="footer-title">Акбаралиев</p>
        <div class="footer-social">
            <a href="#" class="footer-icon"><i class='bx bxl-facebook'></i></a>
            <a href="#" class="footer-icon"><i class='bx bxl-instagram' ></i></a>
            <a href="#" class="footer-icon"><i class='bx bxl-twitter' ></i></a>
        </div>
        <p>&#169; ОШМУ</p>
    </footer>
    <script src="https://unpkg.com/scrollreveal"></script>
    <script src="app.js"></script>
</body>
</html>
