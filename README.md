<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="DMTXZ — Web Developer, Python Developer & Cybersecurity Student">
    <title>DMTXZ — Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="background-grid"></div>

    <header class="header">
        <div class="container nav">
            <a href="#home" class="logo">DMT<span>XZ</span></a>

            <nav class="nav-links">
                <a href="#home">Главная</a>
                <a href="#about">Обо мне</a>
                <a href="#skills">Навыки</a>
                <a href="#projects">Проекты</a>
                <a href="#security">Cybersecurity</a>
                <a href="#contact">Контакты</a>
            </nav>

            <button class="menu-btn" aria-label="Открыть меню">
                <span></span>
                <span></span>
                <span></span>
            </button>
        </div>
    </header>

    <main>

        <section id="home" class="hero">
            <div class="container hero-content">

                <div class="hero-text">
                    <p class="hero-label">WEB DEVELOPER / PYTHON / CYBERSECURITY</p>

                    <h1>
                        Building things<br>
                        <span>in the dark.</span>
                    </h1>

                    <p class="hero-description">
                        Разрабатываю сайты, приложения и небольшие проекты,
                        изучаю программирование и постепенно углубляюсь
                        в информационную безопасность.
                    </p>

                    <div class="hero-buttons">
                        <a href="#projects" class="btn btn-primary">
                            Мои проекты
                        </a>

                        <a href="#contact" class="btn btn-secondary">
                            Связаться
                        </a>
                    </div>

                    <div class="hero-status">
                        <span class="status-dot"></span>
                        Available for projects
                    </div>
                </div>

                <div class="hero-card">
                    <div class="terminal-top">
                        <span></span>
                        <span></span>
                        <span></span>
                    </div>

                    <div class="terminal-body">
                        <p><span class="purple">user</span>@<span class="purple">dmtxz</span>:~$ whoami</p>
                        <p class="terminal-output">DMTXZ</p>

                        <p><span class="purple">user</span>@<span class="purple">dmtxz</span>:~$ skills</p>
                        <p class="terminal-output">
                            Python<br>
                            HTML / CSS / JS<br>
                            C++<br>
                            Linux<br>
                            Cybersecurity
                        </p>

                        <p>
                            <span class="purple">user</span>@<span class="purple">dmtxz</span>:~$
                            <span class="cursor"></span>
                        </p>
                    </div>
                </div>

            </div>
        </section>


        <section id="about" class="section">
            <div class="container">

                <div class="section-heading">
                    <span>01</span>
                    <h2>Обо мне</h2>
                </div>

                <div class="about-grid">

                    <div class="about-text">
                        <p class="accent-text">
                            Привет. Я DMTXZ.
                        </p>

                        <p>
                            Я занимаюсь разработкой сайтов и программ,
                            экспериментирую с Python, C++, JavaScript
                            и различными технологиями веб-разработки.
                        </p>

                        <p>
                            Мне нравится не просто использовать готовые
                            решения, а разбираться в том, как всё работает
                            внутри.
                        </p>

                        <p>
                            Сейчас отдельное направление моего развития —
                            cybersecurity, Linux, сети и основы
                            информационной безопасности.
                        </p>
                    </div>

                    <div class="about-info">
                        <div class="info-item">
                            <span>01</span>
                            <div>
                                <small>Focus</small>
                                <strong>Development</strong>
                            </div>
                        </div>

                        <div class="info-item">
                            <span>02</span>
                            <div>
                                <small>Learning</small>
                                <strong>Cybersecurity</strong>
                            </div>
                        </div>

                        <div class="info-item">
                            <span>03</span>
                            <div>
                                <small>Environment</small>
                                <strong>Linux / Windows</strong>
                            </div>
                        </div>

                        <div class="info-item">
                            <span>04</span>
                            <div>
                                <small>Location</small>
                                <strong>Ukraine</strong>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>


        <section id="skills" class="section">
            <div class="container">

                <div class="section-heading">
                    <span>02</span>
                    <h2>Навыки</h2>
                </div>

                <div class="skills-grid">

                    <div class="skill-card">
                        <div class="skill-number">01</div>
                        <h3>Python</h3>
                        <p>
                            Создание приложений, Telegram-ботов,
                            небольших инструментов и игровых проектов.
                        </p>
                        <div class="skill-tags">
                            <span>Python</span>
                            <span>Flask</span>
                            <span>Tkinter</span>
                        </div>
                    </div>

                    <div class="skill-card">
                        <div class="skill-number">02</div>
                        <h3>Web Development</h3>
                        <p>
                            Разработка адаптивных сайтов с чистой
                            структурой и понятным интерфейсом.
                        </p>
                        <div class="skill-tags">
                            <span>HTML</span>
                            <span>CSS</span>
                            <span>JavaScript</span>
                        </div>
                    </div>

                    <div class="skill-card">
                        <div class="skill-number">03</div>
                        <h3>C++</h3>
                        <p>
                            Основы программирования, алгоритмы,
                            логика и работа с низкоуровневыми концепциями.
                        </p>
                        <div class="skill-tags">
                            <span>C++</span>
                            <span>OOP</span>
                            <span>Logic</span>
                        </div>
                    </div>

                    <div class="skill-card">
                        <div class="skill-number">04</div>
                        <h3>Cybersecurity</h3>
                        <p>
                            Изучение сетей, Linux, безопасности систем,
                            веб-безопасности и базовых принципов защиты.
                        </p>
                        <div class="skill-tags">
                            <span>Linux</span>
                            <span>Networks</span>
                            <span>Security</span>
                        </div>
                    </div>

                </div>
            </div>
        </section>


        <section id="projects" class="section projects-section">
            <div class="container">

                <div class="section-heading">
                    <span>03</span>
                    <h2>Проекты</h2>
                </div>

                <div class="projects-grid">

                    <article class="project-card">
                        <div class="project-top">
                            <span class="project-index">01</span>
                            <span class="project-type">PYTHON</span>
                        </div>

                        <h3>School Schedule Bot</h3>

                        <p>
                            Telegram-бот для школьного расписания.
                            Позволяет получать расписание, время звонков
                            и отправлять сообщения администратору.
                        </p>

                        <div class="project-tech">
                            <span>Python</span>
                            <span>Telegram API</span>
                        </div>
                    </article>


                    <article class="project-card">
                        <div class="project-top">
                            <span class="project-index">02</span>
                            <span class="project-type">GAME DEV</span>
                        </div>

                        <h3>First Person Shooter</h3>

                        <p>
                            Небольшой FPS-проект на Python с системой
                            стрельбы, врагами, HP, картой и элементами
                            взаимодействия с окружением.
                        </p>

                        <div class="project-tech">
                            <span>Python</span>
                            <span>Ursina</span>
                        </div>
                    </article>


                    <article class="project-card">
                        <div class="project-top">
                            <span class="project-index">03</span>
                            <span class="project-type">WEB</span>
                        </div>

                        <h3>Landing Page</h3>

                        <p>
                            Адаптивный веб-интерфейс с аккуратной
                            структурой, кастомным оформлением
                            и адаптацией под мобильные устройства.
                        </p>

                        <div class="project-tech">
                            <span>HTML</span>
                            <span>CSS</span>
                        </div>
                    </article>


                    <article class="project-card">
                        <div class="project-top">
                            <span class="project-index">04</span>
                            <span class="project-type">COMMUNITY</span>
                        </div>

                        <h3>SA Police Community</h3>

                        <p>
                            Веб-проект для игрового сообщества
                            с информационными страницами,
                            оформлением и структурой проекта.
                        </p>

                        <div class="project-tech">
                            <span>HTML</span>
                            <span>CSS</span>
                            <span>JavaScript</span>
                        </div>
                    </article>

                </div>
            </div>
        </section>


        <section id="security" class="section security-section">
            <div class="container">

                <div class="section-heading">
                    <span>04</span>
                    <h2>Cybersecurity</h2>
                </div>

                <div class="security-content">

                    <div class="security-intro">
                        <p class="accent-text">
                            Current direction
                        </p>

                        <h3>
                            From development<br>
                            to security.
                        </h3>

                        <p>
                            Развитие в направлении информационной
                            безопасности является одной из основных
                            целей моего обучения.
                        </p>
                    </div>

                    <div class="roadmap">

                        <div class="roadmap-item active">
                            <span>01</span>
                            <div>
                                <h4>Programming</h4>
                                <p>Python / C++ / Web</p>
                            </div>
                        </div>

                        <div class="roadmap-item">
                            <span>02</span>
                            <div>
                                <h4>Linux</h4>
                                <p>System administration & CLI</p>
                            </div>
                        </div>

                        <div class="roadmap-item">
                            <span>03</span>
                            <div>
                                <h4>Networking</h4>
                                <p>TCP/IP / HTTP / DNS</p>
                            </div>
                        </div>

                        <div class="roadmap-item">
                            <span>04</span>
                            <div>
                                <h4>Web Security</h4>
                                <p>OWASP / vulnerabilities</p>
                            </div>
                        </div>

                        <div class="roadmap-item">
                            <span>05</span>
                            <div>
                                <h4>Cybersecurity</h4>
                                <p>Further specialization</p>
                            </div>
                        </div>

                    </div>

                </div>
            </div>
        </section>


        <section class="section github-section">
            <div class="container">

                <div class="github-box">
                    <div>
                        <p class="hero-label">OPEN SOURCE / DEVELOPMENT</p>

                        <h2>
                            More code.<br>
                            Less noise.
                        </h2>

                        <p>
                            Мои проекты, эксперименты и разработки
                            находятся в открытом доступе.
                        </p>
                    </div>

                    <a
                        href="https://github.com/dmtxz"
                        target="_blank"
                        rel="noopener"
                        class="btn btn-primary"
                    >
                        GitHub →
                    </a>
                </div>

            </div>
        </section>


        <section id="contact" class="section contact-section">
            <div class="container">

                <div class="section-heading">
                    <span>05</span>
                    <h2>Контакты</h2>
                </div>

                <div class="contact-content">

                    <div class="contact-text">
                        <p class="accent-text">Have a project?</p>

                        <h2>
                            Let's build<br>
                            something.
                        </h2>

                        <p>
                            Если у тебя есть идея проекта,
                            предложение или просто хочешь связаться —
                            пиши.
                        </p>
                    </div>

                    <div class="contact-links">

                        <a
                            href="https://github.com/dmtxz"
                            target="_blank"
                            rel="noopener"
                        >
                            <span>GitHub</span>
                            <span>↗</span>
                        </a>

                        <a
                            href="https://t.me/dmtxz"
                            target="_blank"
                            rel="noopener"
                        >
                            <span>Telegram</span>
                            <span>↗</span>
                        </a>

                        <a
                            href="https://www.instagram.com/dkjrzz"
                            target="_blank"
                            rel="noopener"
                        >
                            <span>Instagram</span>
                            <span>↗</span>
                        </a>

                        <a
                            href="https://steamcommunity.com/id/dkjrz"
                            target="_blank"
                            rel="noopener"
                        >
                            <span>Steam</span>
                            <span>↗</span>
                        </a>

                    </div>

                </div>
            </div>
        </section>

    </main>


    <footer class="footer">
        <div class="container footer-content">
            <div class="logo">DMT<span>XZ</span></div>

            <p>
                © <span id="year"></span> DMTXZ. No noise. Just code.
            </p>

            <p class="footer-status">
                SYSTEM ONLINE
            </p>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
