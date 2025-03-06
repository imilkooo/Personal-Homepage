<!DOCTYPE html>
<html lang="en" data-theme="light">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HeyStar</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
</head>
<body>
    <div class="hexagon-bg">
        <div class="hexagon"></div>
    </div>
    <header>
        <nav>
            <div class="logo">HeyStar</div>
            <ul class="nav-links">
                <li><a href="#home">首页</a></li>
                <li><a href="#about">关于我</a></li>
                <li><a href="#projects">学习</a></li>
                <li><a href="#contact">联系我</a></li>
            </ul>
            <button id="theme-toggle" class="theme-toggle">
                <i class="fas fa-sun"></i>
                <i class="fas fa-moon"></i>
            </button>
        </nav>
    </header>

    <main>
        <section id="home" class="hero">
            <div class="hero-content">
                <h1>Welcome to HeyStarの世界</h1>
                <p>探索、创造、分享</p>
                <div class="social-links">
                    <a href="https://www.douyin.com/user/self?from_tab_name=main&showTab=like" target="_blank" class="social-icon"><i class="fab fa-tiktok"></i></a>
                    <a href="https://www.youtube.com/" target="_blank" class="social-icon"><i class="fab fa-youtube"></i></a>
                    <a href="https://space.bilibili.com/48025256?spm_id_from=333.1365.0.0" target="_blank" class="social-icon"><i class="fab fa-bilibili"></i></a>
                    <a href="https://www.xiaohongshu.com/user/profile/614ad34f000000001f03a5eb" target="_blank" class="social-icon"><i class="fas fa-book"></i></a>
                </div>
            </div>
        </section>

        <section id="about" class="about">
            <h2>关于我</h2>
            <div class="about-content">
                <div class="about-text">
                    <p>你好！我是 HeyStar，欢迎来到我的个人空间。</p>
                    <p>这里是我分享想法、和经验的地方。</p>
                </div>
            </div>
        </section>

        <section id="projects" class="projects">
            <h2>我的创造</h2>
            <div class="project-grid">
                <div class="project-card">
                    <h3>创作分享</h3>
                    <p>分享生活，记录成长</p>
                    <a href="https://grok.com/chat/b3379c45-21b4-40c6-8923-76bf45e9498e" class="btn" target="_blank">了解更多</a>
                </div>
                <div class="project-card">
                    <h3>技术探索</h3>
                    <p>探索前沿，持续学习</p>
                    <a href="https://sspai.com/" class="btn" target="_blank">了解更多</a>
                </div>
            </div>
        </section>

        <section id="contact" class="contact">
            <div class="contact-content">
                <p>如果你有任何问题或合作意向，欢迎联系我！</p>
                <div class="contact-info">
                    <p><i class="fas fa-envelope"></i> Email: imilko1009@163.com</p>
                    <a href="#" class="contact-link" id="showContact">
                        <i class="fas fa-qrcode contact-icon"></i>
                        <span>点击查看联系方式</span>
                    </a>
                </div>
            </div>
        </section>
    </main>

    <!-- Modal -->
    <div id="imageModal" class="modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <img src="images/WechatIMG49.jpg" alt="联系方式" id="contactImage">
        </div>
    </div>

    <footer>
        <p>&copy; 2025 HeyStarの世界</p>
    </footer>

    <script src="script.js"></script>
</body>
</html> 
