# sitesavvy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SiteSavvy | Portfolio</title>
    <link rel="stylesheet" href="./fontawesome-free-6.7.2-web/css/all.min.css">
    <link rel="stylesheet" href="./CSS/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Sora:wght@600;700&display=swap" rel="stylesheet">
</head>
<body>
    <nav class="navbar">
        <div class="logo"><span class="logo-icon"><i class="fa-solid fa-laptop-code" aria-hidden="true"></i></span>SiteSavvy</div>
        <ul class="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#work">Work</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        <a href="#contact" class="btn btn-primary">Hire Me</a>
    </nav>

    <section class="hero">
        <div class="hero-copy">
            <span class="eyebrow">Webdevelopment</span>
            <h1>Beautiful websites that convert visitors into customers.</h1>
            <p class="hero-text">I build performant, modern web experiences for startups, agencies, and small businesses. Clear structure, bold visuals, and fast launch-ready code.</p>
            <div class="hero-actions">
                <a href="#work" class="btn btn-primary">View Work</a>
                <a href="#about" class="btn btn-secondary">Learn More</a>
            </div>
            <div class="hero-stats">
                <div class="stat-card">
                    <strong>2</strong>
                    <span>Projects launched</span>
                </div>
                <div class="stat-card">
                    <strong>2</strong>
                    <span>Years experience</span>
                </div>
                <div class="stat-card">
                    <strong>5x</strong>
                    <span>Faster delivery</span>
                </div>
            </div>
        </div>
        <div class="hero-panel">
            <div class="panel-header">
                <span>Featured project</span>
                <strong>Brand launch website</strong>
            </div>
            <p class="panel-text">A responsive landing experience crafted for a creative agency, with interactive cards, site speed optimization, and a polished design system.</p>
            <div class="panel-tags">
                <span>HTML</span>
                <span>CSS</span>
                <span>JavaScript</span>
                <span>PHP</span>
            </div>
        </div>
    </section>

    <main>
        <section id="about" class="section about-section">
            <div class="section-heading">
                <span class="section-number">01</span>
                <h2>About Me</h2>
            </div>
            <div class="about-grid">
                <div class="about-text">
                    <p>Hello! I am Thelma (SiteSavvy), a full-stack developer who blends clean code with meaningful design. I specialize in websites and web apps that feel polished, perform fast, and deliver measurable results.</p>
                    <p>From concept to launch, I focus on clarity and quality. I enjoy translating bold ideas into responsive experiences that help brands stand out online.</p>
                    <div class="about-meta">
                        <div>
                            <strong>Full-stack developer</strong>
                            <p>PHP / JAVASCRIPT / CSS / HTML / BOOTSTRAP</p>
                        </div>
                        <div>
                            <strong>Based in</strong>
                            <p>Remote / Worldwide</p>
                        </div>
                    </div>
                </div>
                <img src="./img/WhatsApp Image 2026-05-11 at 8.29.44 AM.jpeg" alt="Thelma profile portrait" class="profile-pic">
            </div>
        </section>

        <section id="work" class="section work-section">
            <div class="section-heading">
                <span class="section-number">02</span>
                <h2>Selected Work</h2>
            </div>
            <div class="work-grid">
                <article class="project-card" data-video="./VID/coffee.mp4">
                    <div class="project-thumbnail">
                        <video src="./VID/coffee.mp4"></video>
                        <div class="play-button">▶</div>
                    </div>
                    <div class="project-content">
                        <h3>Coffee & Snacks Launch</h3>
                        <p>A modern personal portfolio with smooth transitions, a responsive layout, and a polished visual style.</p>
                        <div class="project-footer">
                            <span class="project-tech">HTML, CSS, JS</span>
                            <a href="#" class="project-link" aria-label="View project details">→</a>
                        </div>
                    </div>
                </article>
                <article class="project-card" data-video="./VID/crypto.mp4">
                    <div class="project-thumbnail">
                        <video src="./VID/crypto.mp4"></video>
                        <div class="play-button">▶</div>
                    </div>
                    <div class="project-content">
                        <h3>Crypto Experience</h3>
                        <p>Product-led storefront design with checkout optimization, mobile-first layouts, and fast performance.</p>
                        <div class="project-footer">
                            <span class="project-tech">HTML, CSS, JS</span>
                            <a href="#" class="project-link" aria-label="View project details">→</a>
                        </div>
                    </div>
                </article>
                <article class="project-card" data-video="./VID/gold.mp4">
                    <div class="project-thumbnail">
                        <video src="./VID/gold.mp4"></video>
                        <div class="play-button">▶</div>
                    </div>
                    <div class="project-content">
                        <h3>Gold Jewelry Store</h3>
                        <p>Component library built for consistency and scalability, with reusable UI patterns and accessible styles.</p>
                        <div class="project-footer">
                            <span class="project-tech">HTML, CSS, JS</span>
                            <a href="#" class="project-link" aria-label="View project details">→</a>
                        </div>
                    </div>
                </article>
            </div>
        </section>

        <!-- Video Modal -->
        <div id="videoModal" class="modal">
            <div class="modal-content">
                <button class="modal-close" aria-label="Close video">&times;</button>
                <div class="modal-body">
                    <video id="modalVideo" controls autoplay>
                        <source src="" type="video/mp4">
                        Your browser does not support the video tag.
                    </video>
                </div>
            </div>
        </div>

        <section id="skills" class="section skills-section">
            <div class="section-heading">
                <span class="section-number">03</span>
                <h2>Skills</h2>
            </div>
            <div class="skills-grid">
                <div class="skill-card">JavaScript</div>
                <div class="skill-card">HTML & CSS</div>
                <div class="skill-card">Bootstrap</div>
                <div class="skill-card">Responsive Design</div>
                <div class="skill-card">Web Performance</div>
                
            </div>
        </section>

        <section id="contact" class="section contact-section">
            <div class="section-heading">
                <span class="section-number">04</span>
                <h2>Let's build something together</h2>
            </div>
            <div class="contact-card">
                <p>If you have a project, a product idea, or a brand that needs a fresh online presence, I am ready to help.</p>
                <a href="https://wa.me/message/GHLCNZD4AGOSP1" class="btn btn-primary">Say Hello</a>
            </div>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2026 SiteSavvy. Crafted with intention.</p>
    </footer>

    <script src="./js/main.js" defer></script>
</body>
</html>
html {
    scroll-behavior: smooth;
    scroll-padding-top: 96px;
}

:root {
    --bg: #f6f8ff;
    --surface: #ffffff;
    --panel: #f8fbff;
    --accent: #7c3aed;
    --accent-alt: #0ea5e9;
    --text-main: #0f172a;
    --text-muted: #5b6778;
    --border: 1px solid rgba(15, 23, 42, 0.08);
    --shadow: 0 30px 90px rgba(15, 23, 42, 0.08);
}

* {
    box-sizing: border-box;
}

body {
    margin: 0;
    min-height: 100vh;
    font-family: 'Inter', sans-serif;
    color: var(--text-main);
    background: radial-gradient(circle at top left, rgba(124, 58, 237, 0.14), transparent 24%),
                radial-gradient(circle at 90% 20%, rgba(14, 165, 233, 0.08), transparent 18%),
                linear-gradient(180deg, #f8faff 0%, #f4f7ff 44%, #eef2ff 100%);
}

::selection {
    background: rgba(14, 165, 233, 0.18);
    color: #0f172a;
}

h1, h2, .logo {
    font-family: 'Sora', sans-serif;
}

body, button, input, textarea, select {
    color: inherit;
}

button, a {
    text-decoration: none;
}

html, body {
    scroll-behavior: smooth;
}

/* Navbar */
.navbar {
    position: fixed;
    top: 1rem;
    left: 50%;
    transform: translateX(-50%);
    width: min(95%, 1180px);
    padding: 1rem 1.5rem;
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 1rem;
    background: rgba(255, 255, 255, 0.95);
    border: 1px solid rgba(15, 23, 42, 0.08);
    border-radius: 26px;
    backdrop-filter: blur(18px);
    box-shadow: 0 28px 90px rgba(15, 23, 42, 0.08);
    z-index: 100;
}

.logo {
    display: inline-flex;
    align-items: center;
    gap: 0.65rem;
    font-size: 1.85rem;
    color: var(--text-main);
    letter-spacing: 0.8px;
    font-weight: 700;
}

.logo-icon {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 2.35rem;
    height: 2.35rem;
    border-radius: 14px;
    background: rgba(124, 58, 237, 0.12);
    color: var(--accent);
    font-size: 1.2rem;
}

.logo span.logo-dot {
    color: var(--accent);
}

.nav-links {
    display: flex;
    gap: 1.75rem;
    list-style: none;
    margin: 0;
    padding: 0;
}

.nav-links a {
    color: var(--text-muted);
    font-weight: 600;
    font-size: 1rem;
    transition: color 0.2s ease;
}

.nav-links a:hover,
.nav-links a:focus {
    color: var(--accent);
}

.nav-links a.active {
    color: var(--accent);
    position: relative;
}

.nav-links a.active::after {
    content: '';
    position: absolute;
    bottom: -6px;
    left: 0;
    right: 0;
    height: 2px;
    background: var(--accent);
    border-radius: 1px;
}

/* Mobile Navigation Toggle */
.nav-toggle {
    display: none;
    flex-direction: column;
    gap: 5px;
    background: none;
    border: none;
    cursor: pointer;
    padding: 0;
    width: 30px;
    height: 24px;
}

.nav-toggle span {
    display: block;
    width: 100%;
    height: 2px;
    background: var(--text-main);
    border-radius: 2px;
    transition: all 0.3s ease;
}

.nav-toggle.active span:nth-child(1) {
    transform: rotate(45deg) translate(8px, 8px);
}

.nav-toggle.active span:nth-child(2) {
    opacity: 0;
}

.nav-toggle.active span:nth-child(3) {
    transform: rotate(-45deg) translate(7px, -7px);
}

/* Hero */
.hero {
    min-height: calc(100vh - 100px);
    display: grid;
    grid-template-columns: 1.2fr 0.9fr;
    gap: 2rem;
    align-items: center;
    padding: 120px 5% 4rem;
    position: relative;
}

.hero::before {
    content: '';
    position: absolute;
    width: 520px;
    height: 520px;
    top: -120px;
    right: -140px;
    border-radius: 50%;
    background: rgba(124, 58, 237, 0.14);
    filter: blur(90px);
    z-index: 0;
}

.hero::after {
    content: '';
    position: absolute;
    width: 360px;
    height: 360px;
    bottom: -110px;
    left: -90px;
    border-radius: 50%;
    background: rgba(14, 165, 233, 0.1);
    filter: blur(80px);
    z-index: 0;
}

.hero-copy,
.hero-panel {
    position: relative;
    z-index: 1;
    border-radius: 28px;
    padding: 2.5rem;
    background: rgba(255, 255, 255, 0.95);
    border: 1px solid rgba(15, 23, 42, 0.1);
    box-shadow: 0 30px 80px rgba(15, 23, 42, 0.08);
}

.eyebrow,
.section-number {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.65rem 0.9rem;
    border-radius: 999px;
    background: rgba(124, 58, 237, 0.08);
    color: var(--accent);
    font-size: 0.85rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    font-weight: 700;
}

.hero-copy h1 {
    margin: 1.25rem 0 1rem;
    font-size: clamp(3rem, 4.5vw, 4.8rem);
    line-height: 0.95;
    color: var(--text-main);
}

.hero-text,
.panel-text,
.about-text p,
.project-card p,
.contact-card p {
    color: var(--text-muted);
    line-height: 1.85;
    margin: 0;
}

.hero-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 1rem;
    margin: 2rem 0 1rem;
}

.btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 1rem 1.9rem;
    border-radius: 999px;
    font-weight: 700;
    transition: all 0.25s ease;
}

.btn-primary {
    background: linear-gradient(135deg, #7c3aed, #0ea5e9);
    color: #fff;
    border: 1px solid transparent;
}

.btn-primary:hover,
.btn-primary:focus {
    transform: translateY(-2px);
    background: linear-gradient(135deg, #5b21b6, #0284c7);
}

.btn-secondary {
    background: #ffffff;
    color: var(--text-main);
    border: 1px solid rgba(15, 23, 42, 0.12);
}

.btn-secondary:hover,
.btn-secondary:focus {
    background: #f8fafc;
    transform: translateY(-2px);
}

.hero-stats {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
    margin-top: 1.75rem;
}

.stat-card {
    padding: 1.3rem;
    border-radius: 22px;
    background: var(--panel);
    border: 1px solid rgba(15, 23, 42, 0.08);
    text-align: center;
}

.stat-card strong {
    display: block;
    font-size: 1.6rem;
    color: var(--text-main);
}

.stat-card span {
    display: block;
    margin-top: 0.4rem;
    color: var(--text-muted);
    font-size: 0.95rem;
}

.hero-panel {
    display: grid;
    gap: 1.5rem;
}

.panel-header {
    display: flex;
    flex-direction: column;
    gap: 0.5rem;
}

.panel-header span {
    color: var(--accent-alt);
    font-weight: 700;
    font-size: 0.95rem;
    letter-spacing: 0.08em;
    text-transform: uppercase;
}

.panel-header strong {
    font-size: 1.8rem;
    color: var(--text-main);
}

.panel-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
}

.panel-tags span {
    padding: 0.7rem 1rem;
    border-radius: 999px;
    background: rgba(14, 165, 233, 0.12);
    color: #0f172a;
    font-size: 0.9rem;
}

main {
    position: relative;
    z-index: 1;
}

.section {
    padding: 5rem 5%;
    max-width: 1180px;
    margin: 0 auto;
}

.section-heading {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin-bottom: 2rem;
}

.section-heading h2 {
    margin: 0;
    font-size: clamp(2rem, 3vw, 2.8rem);
    color: var(--text-main);
}

.about-grid {
    display: grid;
    grid-template-columns: 1.1fr 0.9fr;
    gap: 2rem;
    align-items: center;
    background: rgba(255, 255, 255, 0.95);
    border: 1px solid rgba(15, 23, 42, 0.08);
    border-radius: 32px;
    padding: 2rem;
    box-shadow: 0 30px 90px rgba(15, 23, 42, 0.08);
    overflow: hidden;
}

.about-text {
    padding: 0;
    background: transparent;
    border: none;
}

.about-text p {
    margin: 0;
}

.about-text p + p {
    margin-top: 1.4rem;
}

.about-meta {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    margin-top: 2rem;
}

.about-meta > div {
    background: rgba(14, 165, 233, 0.08);
    padding: 1rem 1.15rem;
    border-radius: 22px;
}

.about-meta strong {
    display: block;
    margin-bottom: 0.35rem;
    color: var(--text-main);
}

.about-meta p {
    margin: 0;
    color: var(--text-muted);
    line-height: 1.7;
}

.profile-pic {
    width: 100%;
    max-width: 320px;
    max-height: 400px;
    height: auto;
    border-radius: 24px;
    object-fit: cover;
    display: block;
    margin: 0 auto;
}

.work-grid,
.skills-grid {
    display: grid;
    gap: 1.5rem;
}

.work-grid {
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
}

.project-card,
.skill-card,
.contact-card {
    background: var(--panel);
    border-radius: 28px;
    padding: 2rem;
    border: 1px solid rgba(15, 23, 42, 0.08);
    box-shadow: 0 24px 70px rgba(15, 23, 42, 0.06);
}

.project-card {
    overflow: hidden;
    padding: 0;
    display: flex;
    flex-direction: column;
    transition: all 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
    cursor: pointer;
}

.project-card:hover {
    transform: translateY(-12px);
    box-shadow: 0 40px 100px rgba(15, 23, 42, 0.15);
}

.project-thumbnail {
    position: relative;
    width: 100%;
    height: 180px;
    background: linear-gradient(135deg, rgba(124, 58, 237, 0.1), rgba(14, 165, 233, 0.08));
    display: flex;
    align-items: center;
    justify-content: center;
    overflow: hidden;
}

.project-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    transition: transform 0.3s ease;
}

.project-card:hover .project-image {
    transform: scale(1.08);
}

.play-button {
    position: absolute;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.95);
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.5rem;
    color: var(--accent);
    font-weight: bold;
    transition: all 0.3s ease;
    box-shadow: 0 10px 30px rgba(15, 23, 42, 0.15);
}

.project-card:hover .play-button {
    background: var(--accent);
    color: white;
    transform: scale(1.1);
}

.project-content {
    padding: 1.75rem;
    display: flex;
    flex-direction: column;
    gap: 0.75rem;
    flex-grow: 1;
}

.project-card h3 {
    margin: 0;
    font-size: 1.3rem;
    color: var(--text-main);
}

.project-card p {
    margin: 0;
    flex-grow: 1;
}

.project-footer {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: auto;
    padding-top: 1rem;
    border-top: 1px solid rgba(15, 23, 42, 0.06);
}

.project-tech {
    font-size: 0.85rem;
    color: var(--accent);
    font-weight: 600;
}

.project-link {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    width: 32px;
    height: 32px;
    border-radius: 50%;
    background: rgba(124, 58, 237, 0.1);
    color: var(--accent);
    transition: all 0.3s ease;
    font-weight: bold;
}

.project-card:hover .project-link {
    background: var(--accent);
    color: white;
    transform: translateX(4px);
}

.skills-grid {
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
}

.skill-card {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    min-height: 120px;
    font-size: 1rem;
    font-weight: 700;
    text-align: center;
    color: var(--text-main);
}

.contact-card {
    display: grid;
    gap: 1.5rem;
    text-align: center;
    padding: 2.5rem;
}

.contact-card p {
    margin: 0;
    font-size: 1.05rem;
}

.footer {
    text-align: center;
    padding: 2rem 5%;
    color: var(--text-muted);
    background: #f8f9ff;
}

.reveal {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.7s ease, transform 0.7s ease;
}

.is-visible {
    opacity: 1;
    transform: translateY(0);
}

/* Video Modal */
.modal {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(15, 23, 42, 0.8);
    backdrop-filter: blur(10px);
    z-index: 1000;
    align-items: center;
    justify-content: center;
    animation: fadeIn 0.3s ease;
}

.modal.active {
    display: flex;
}

@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}

.modal-content {
    position: relative;
    width: 90%;
    max-width: 900px;
    max-height: 85vh;
    background: #000;
    border-radius: 20px;
    overflow: hidden;
    box-shadow: 0 50px 150px rgba(15, 23, 42, 0.3);
    animation: slideUp 0.3s cubic-bezier(0.34, 1.56, 0.64, 1);
}

@keyframes slideUp {
    from {
        transform: translateY(40px);
        opacity: 0;
    }
    to {
        transform: translateY(0);
        opacity: 1;
    }
}

.modal-close {
    position: absolute;
    top: 1rem;
    right: 1rem;
    width: 44px;
    height: 44px;
    background: rgba(255, 255, 255, 0.15);
    border: none;
    border-radius: 50%;
    color: white;
    font-size: 2rem;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    transition: all 0.3s ease;
    z-index: 1001;
}

.modal-close:hover {
    background: rgba(255, 255, 255, 0.25);
}

.modal-body {
    width: 100%;
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
}

.modal-body video {
    width: 100%;
    height: 100%;
    max-height: 85vh;
    object-fit: contain;
    outline: none;
}

@media (max-width: 768px) {
    .modal-content {
        width: 95%;
        max-height: 70vh;
    }

    .modal-body video {
        max-height: 70vh;
    }

    .hero {
        grid-template-columns: 1fr;
    }

    .about-grid {
        grid-template-columns: 1fr;
    }
}

/* Interactive Effects */
.project-card {
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    cursor: pointer;
}

.project-card:hover {
    box-shadow: 0 30px 90px rgba(15, 23, 42, 0.12);
}

.skill-card {
    transition: transform 0.3s ease, background 0.3s ease;
    cursor: default;
}

.skill-card:hover {
    background: rgba(124, 58, 237, 0.08);
}

.btn {
    border: none;
    cursor: pointer;
    font-size: 1rem;
}

.btn:active {
    transform: translateY(-1px);
}

/* Page Load Animation */
body.loaded {
    opacity: 1;
}

/* Smooth reveal animations with stagger */
.reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.8s cubic-bezier(0.34, 1.56, 0.64, 1),
                transform 0.8s cubic-bezier(0.34, 1.56, 0.64, 1);
}

.is-visible {
    opacity: 1;
    transform: translateY(0);
}

@media (max-width: 720px) {
    .navbar {
        padding: 0.75rem 1rem;
    }

    .nav-toggle {
        display: flex;
        order: 2;
    }

    .nav-links {
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100vh;
        background: rgba(255, 255, 255, 0.98);
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 2rem;
        z-index: 99;
        transform: translateX(-100%);
        transition: transform 0.3s ease;
        backdrop-filter: blur(20px);
    }

    .nav-links.active {
        transform: translateX(0);
    }

    .nav-links a {
        font-size: 1.25rem;
    }

    .nav-links a.active::after {
        bottom: -12px;
    }

    .hero {
        padding-top: 140px;
    }

    .hero-copy,
    .hero-panel,
    .project-card,
    .skill-card,
    .contact-card {
        padding: 1.75rem;
    }

    .hero-actions {
        flex-direction: column;
    }

    .btn {
        width: 100%;
    }

    .btn-primary,
    .btn-secondary {
        padding: 1rem;
    }

    .hero-stats {
        grid-template-columns: 1fr;
    }
}

@media (max-width: 540px) {
    .hero {
        padding: 120px 4rem 3rem 4rem;
    }

    .hero-copy h1 {
        font-size: 2.8rem;
    }

    .section {
        padding: 3.5rem 4rem;
    }
}
// Mobile Navigation Toggle
const navToggle = document.querySelector('.nav-toggle');
const navLinks = document.querySelector('.nav-links');
const navButtons = navLinks?.querySelectorAll('a');

// Create hamburger menu if not exists
if (!navToggle && navLinks) {
    createMobileMenu();
}

function createMobileMenu() {
    const navbar = document.querySelector('.navbar');
    const toggle = document.createElement('button');
    toggle.className = 'nav-toggle';
    toggle.innerHTML = '<span></span><span></span><span></span>';
    toggle.setAttribute('aria-label', 'Toggle navigation');
    navbar.insertBefore(toggle, navLinks);

    toggle.addEventListener('click', () => {
        navLinks.classList.toggle('active');
        toggle.classList.toggle('active');
    });

    // Close menu when link is clicked
    document.querySelectorAll('.nav-links a').forEach(link => {
        link.addEventListener('click', () => {
            navLinks.classList.remove('active');
            toggle.classList.remove('active');
        });
    });
}

// Active Navigation Highlighting
function updateActiveNav() {
    const sections = document.querySelectorAll('section[id]');
    const navLinks = document.querySelectorAll('.nav-links a');

    let current = '';
    sections.forEach(section => {
        const sectionTop = section.offsetTop;
        const sectionHeight = section.clientHeight;
        if (scrollY >= sectionTop - 200) {
            current = section.getAttribute('id');
        }
    });

    navLinks.forEach(link => {
        link.classList.remove('active');
        if (link.getAttribute('href').slice(1) === current) {
            link.classList.add('active');
        }
    });
}

window.addEventListener('scroll', updateActiveNav);

// Reveal Animation Observer
const revealObserver = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
        if (entry.isIntersecting) {
            entry.target.classList.add('is-visible');
            // Optional: stop observing after revealed
            // revealObserver.unobserve(entry.target);
        }
    });
}, { threshold: 0.15 });

// Add reveal class and observe elements
document.querySelectorAll('.section, .hero-copy, .hero-panel, .project-card, .skill-card, .contact-card, .stat-card').forEach(el => {
    el.classList.add('reveal');
    revealObserver.observe(el);
});

// Smooth Scroll Enhancement
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        const href = this.getAttribute('href');
        if (href !== '#' && document.querySelector(href)) {
            e.preventDefault();
            const target = document.querySelector(href);
            const headerOffset = 96;
            const elementPosition = target.getBoundingClientRect().top;
            const offsetPosition = elementPosition + window.pageYOffset - headerOffset;

            window.scrollTo({
                top: offsetPosition,
                behavior: 'smooth'
            });
        }
    });
});

// Interactive Card Hover Effects
const projectCards = document.querySelectorAll('.project-card');
projectCards.forEach(card => {
    card.addEventListener('click', function(e) {
        e.preventDefault();
        const videoUrl = this.getAttribute('data-video');
        if (videoUrl && videoUrl !== '#') {
            openVideoModal(videoUrl);
        }
    });
});

// Video Modal Functions
function openVideoModal(videoUrl) {
    const modal = document.getElementById('videoModal');
    const video = document.getElementById('modalVideo');
    
    if (!videoUrl || videoUrl === '#') {
        alert('Video URL not configured');
        return;
    }
    
    // Set video source
    video.src = videoUrl;
    modal.classList.add('active');
    document.body.style.overflow = 'hidden';
    
    // Ensure video plays with a small delay for rendering
    setTimeout(() => {
        video.play().catch(err => {
            console.log('Video playback error:', err);
        });
    }, 100);
}

function closeVideoModal() {
    const modal = document.getElementById('videoModal');
    const video = document.getElementById('modalVideo');
    
    modal.classList.remove('active');
    video.pause();
    video.currentTime = 0;
    document.body.style.overflow = '';
}

// Modal close button
document.getElementById('videoModal')?.addEventListener('click', function(e) {
    if (e.target === this) {
        closeVideoModal();
    }
});

document.querySelector('.modal-close')?.addEventListener('click', closeVideoModal);

// Close modal on Escape key
document.addEventListener('keydown', (e) => {
    if (e.key === 'Escape' && document.getElementById('videoModal')?.classList.contains('active')) {
        closeVideoModal();
    }
});

// Skills Card Animation on Hover
const skillCards = document.querySelectorAll('.skill-card');
skillCards.forEach(card => {
    card.addEventListener('mouseenter', function() {
        this.style.transform = 'scale(1.05)';
    });
    card.addEventListener('mouseleave', function() {
        this.style.transform = 'scale(1)';
    });
});

// Navbar Background on Scroll
const navbar = document.querySelector('.navbar');
window.addEventListener('scroll', () => {
    if (window.scrollY > 50) {
        navbar.style.background = 'rgba(255, 255, 255, 0.98)';
        navbar.style.backdropFilter = 'blur(20px)';
        navbar.style.boxShadow = '0 28px 90px rgba(15, 23, 42, 0.12)';
    } else {
        navbar.style.background = 'rgba(255, 255, 255, 0.95)';
        navbar.style.backdropFilter = 'blur(18px)';
        navbar.style.boxShadow = '0 28px 90px rgba(15, 23, 42, 0.08)';
    }
});

// Stat Counter Animation
function animateCounters() {
    const statCards = document.querySelectorAll('.stat-card strong');
    
    const counterObserver = new IntersectionObserver((entries) => {
        entries.forEach(entry => {
            if (entry.isIntersecting && !entry.target.dataset.animated) {
                const element = entry.target;
                const finalValue = element.textContent;
                element.dataset.animated = 'true';
                
                // Extract number and unit
                const match = finalValue.match(/(\d+)(.*)/);
                if (match) {
                    const number = parseInt(match[1]);
                    const unit = match[2];
                    let current = 0;
                    const increment = Math.ceil(number / 30);
                    
                    const interval = setInterval(() => {
                        current += increment;
                        if (current >= number) {
                            element.textContent = number + unit;
                            clearInterval(interval);
                        } else {
                            element.textContent = current + unit;
                        }
                    }, 30);
                }
            }
        });
    }, { threshold: 0.5 });
    
    statCards.forEach(card => counterObserver.observe(card));
}

// Call counter animation when DOM is ready
if (document.readyState === 'loading') {
    document.addEventListener('DOMContentLoaded', animateCounters);
} else {
    animateCounters();
}

// Form mailto enhancement
document.querySelectorAll('a[href^="mailto:"]').forEach(link => {
    link.addEventListener('click', function(e) {
        // Allow default behavior but can add tracking here
        console.log('Email link clicked:', this.href);
    });
});

// Prevent body scroll when mobile menu is open
function toggleBodyScroll(disable) {
    if (disable) {
        document.body.style.overflow = 'hidden';
    } else {
        document.body.style.overflow = '';
    }
}

// Listen for mobile menu toggle
document.addEventListener('click', (e) => {
    const navToggle = document.querySelector('.nav-toggle');
    const navLinks = document.querySelector('.nav-links');
    
    if (navToggle?.classList.contains('active')) {
        toggleBodyScroll(true);
    } else {
        toggleBodyScroll(false);
    }
});

// Page Load Animation
window.addEventListener('load', () => {
    document.body.classList.add('loaded');
});

// Keyboard Navigation Enhancement
document.addEventListener('keydown', (e) => {
    // Close mobile menu on Escape
    const navToggle = document.querySelector('.nav-toggle');
    const navLinks = document.querySelector('.nav-links');
    
    if (e.key === 'Escape' && navLinks?.classList.contains('active')) {
        navToggle.classList.remove('active');
        navLinks.classList.remove('active');
        toggleBodyScroll(false);
    }
});

console.log('🚀 SiteSavvy portfolio is now interactive!');
