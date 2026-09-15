/* =========================
   GLOBAL
========================= */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

:root {
    --bg: #070b17;
    --bg2: #0d1326;
    --card: rgba(255, 255, 255, 0.05);
    --text: #ffffff;
    --muted: #a8b0c5;
    --primary: #7c5cff;
    --secondary: #00d4ff;
    --border: rgba(255, 255, 255, 0.1);
}

body {
    font-family: "Poppins", sans-serif;
    background: var(--bg);
    color: var(--text);
    overflow-x: hidden;
}

a {
    text-decoration: none;
    color: inherit;
}

section {
    scroll-margin-top: 90px;
}


/* =========================
   NAVBAR
========================= */

.header {
    position: fixed;
    top: 0;
    left: 0;

    width: 100%;
    height: 75px;

    display: flex;
    align-items: center;
    justify-content: space-between;

    padding: 0 8%;

    background: rgba(7, 11, 23, 0.75);
    backdrop-filter: blur(15px);

    border-bottom: 1px solid var(--border);

    z-index: 1000;
}

.logo {
    font-size: 25px;
    font-weight: 800;
}

.logo span {
    color: var(--secondary);
}

.navbar {
    display: flex;
    gap: 30px;
}

.navbar a {
    color: var(--muted);
    font-size: 14px;
    transition: 0.3s;
}

.navbar a:hover,
.navbar a.active {
    color: var(--secondary);
}

.menu-icon {
    display: none;
    font-size: 25px;
    cursor: pointer;
}


/* =========================
   HOME
========================= */

.home {
    min-height: 100vh;

    display: flex;
    align-items: center;
    justify-content: space-between;

    padding: 130px 8% 70px;

    position: relative;

    background:
        radial-gradient(circle at 15% 30%, rgba(124, 92, 255, 0.18), transparent 30%),
        radial-gradient(circle at 85% 70%, rgba(0, 212, 255, 0.12), transparent 30%);
}

.home-content {
    width: 52%;
}

.small-title {
    color: var(--secondary);
    letter-spacing: 4px;
    font-size: 12px;
    margin-bottom: 20px;
}

.home h1 {
    font-size: clamp(42px, 5vw, 72px);
    line-height: 1.1;
    margin-bottom: 15px;
}

.home h1 span {
    background: linear-gradient(90deg, var(--primary), var(--secondary));
    -webkit-background-clip: text;
    color: transparent;
}

.home h2 {
    color: var(--secondary);
    font-size: 27px;
    min-height: 42px;
}

.home-content > p:not(.small-title) {
    color: var(--muted);
    max-width: 650px;
    line-height: 1.8;
    margin: 20px 0 30px;
}

.home-buttons {
    display: flex;
    gap: 15px;
    flex-wrap: wrap;
}

.btn {
    display: inline-flex;
    align-items: center;
    gap: 10px;

    padding: 13px 24px;

    border-radius: 8px;

    background: linear-gradient(90deg, var(--primary), #5b8cff);

    color: white;
    font-weight: 600;

    transition: 0.3s;

    border: none;
    cursor: pointer;
}

.btn:hover {
    transform: translateY(-3px);
    box-shadow: 0 10px 30px rgba(124, 92, 255, 0.35);
}

.btn-outline {
    background: transparent;
    border: 1px solid var(--border);
}

.social-icons {
    display: flex;
    gap: 12px;
    margin-top: 30px;
}

.social-icons a {
    width: 42px;
    height: 42px;

    display: grid;
    place-items: center;

    border: 1px solid var(--border);
    border-radius: 50%;

    color: var(--muted);

    transition: 0.3s;
}

.social-icons a:hover {
    color: var(--secondary);
    border-color: var(--secondary);
    transform: translateY(-4px);
}


/* =========================
   CODE CARD
========================= */

.developer-card {
    width: 42%;
    display: flex;
    justify-content: center;
}

.code-window {
    width: 100%;
    max-width: 500px;

    background: rgba(13, 19, 38, 0.9);

    border: 1px solid rgba(124, 92, 255, 0.3);

    border-radius: 18px;

    box-shadow:
        0 0 80px rgba(124, 92, 255, 0.15),
        0 30px 80px rgba(0, 0, 0, 0.5);

    overflow: hidden;

    animation: float 5s ease-in-out infinite;
}

@keyframes float {

    0%, 100% {
        transform: translateY(0);
    }

    50% {
        transform: translateY(-15px);
    }
}

.window-top {
    height: 45px;

    display: flex;
    align-items: center;

    gap: 8px;

    padding: 0 18px;

    border-bottom: 1px solid var(--border);
}

.window-top span {
    width: 11px;
    height: 11px;
    border-radius: 50%;
    background: #555;
}

.code-content {
    padding: 30px;

    font-family: "Courier New", monospace;
    line-height: 2;

    font-size: 14px;
}

.indent {
    padding-left: 25px;
}

.purple {
    color: #c792ea;
}

.yellow {
    color: #ffcb6b;
}

.green {
    color: #c3e88d;
}


/* =========================
   SECTION
========================= */

.section {
    padding: 110px 8%;
}

.section-title {
    text-align: center;
    margin-bottom: 60px;
}

.section-title p {
    color: var(--secondary);
    font-size: 12px;
    letter-spacing: 4px;
}

.section-title h2 {
    font-size: 42px;
    margin-top: 10px;
}

.section-title span {
    color: var(--secondary);
}


/* =========================
   ABOUT
========================= */

.about-container {
    display: grid;
    grid-template-columns: 1fr 1.3fr;
    gap: 70px;

    align-items: center;
}

.about-image {
    display: flex;
    justify-content: center;
}

.profile-box {
    width: 320px;
    height: 320px;

    border-radius: 30px;

    background:
        linear-gradient(145deg, rgba(124, 92, 255, 0.2), rgba(0, 212, 255, 0.08));

    border: 1px solid var(--border);

    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    text-align: center;

    box-shadow: 0 30px 80px rgba(0, 0, 0, 0.3);
}

.profile-icon {
    width: 100px;
    height: 100px;

    display: grid;
    place-items: center;

    border-radius: 50%;

    font-size: 45px;

    background: linear-gradient(135deg, var(--primary), var(--secondary));

    margin-bottom: 20px;
}

.profile-box h3 {
    font-size: 22px;
}

.profile-box p {
    color: var(--muted);
    margin-top: 10px;
}

.about-content h3 {
    font-size: 30px;
    margin-bottom: 20px;
}

.about-content h3 span {
    color: var(--secondary);
}

.about-content > p {
    color: var(--muted);
    line-height: 1.8;
    margin-bottom: 15px;
}

.about-stats {
    display: flex;
    gap: 15px;
    margin-top: 30px;
}

.stat {
    padding: 20px;
    min-width: 120px;

    border: 1px solid var(--border);
    background: var(--card);

    border-radius: 12px;
}

.stat h3 {
    color: var(--secondary);
    margin: 0;
    font-size: 25px;
}

.stat p {
    color: var(--muted);
    font-size: 12px;
}


/* =========================
   SKILLS
========================= */

.skills-section {
    background: var(--bg2);
}

.skills-container {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}

.skill-card {
    padding: 28px;

    background: var(--card);
    border: 1px solid var(--border);

    border-radius: 15px;

    transition: 0.4s;
}

.skill-card:hover {
    transform: translateY(-8px);
    border-color: rgba(0, 212, 255, 0.5);
}

.skill-card > i {
    font-size: 35px;
    color: var(--secondary);
    margin-bottom: 20px;
}

.skill-card h3 {
    margin-bottom: 8px;
}

.skill-card p {
    color: var(--muted);
    font-size: 13px;
    min-height: 45px;
}

.progress {
    height: 5px;

    background: rgba(255, 255, 255, 0.1);

    border-radius: 10px;

    margin-top: 20px;

    overflow: hidden;
}

.progress span {
    display: block;
    height: 100%;

    background: linear-gradient(90deg, var(--primary), var(--secondary));
}


/* =========================
   PROJECTS
========================= */

.projects-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 25px;
}

.project-card {
    position: relative;

    padding: 35px;

    background: var(--card);

    border: 1px solid var(--border);

    border-radius: 18px;

    overflow: hidden;

    transition: 0.4s;
}

.project-card:hover {
    transform: translateY(-8px);
    border-color: rgba(124, 92, 255, 0.6);
}

.project-number {
    position: absolute;
    right: 25px;
    top: 20px;

    font-size: 45px;

    font-weight: 800;

    color: rgba(255, 255, 255, 0.04);
}

.project-icon {
    width: 60px;
    height: 60px;

    display: grid;
    place-items: center;

    border-radius: 14px;

    background: rgba(124, 92, 255, 0.12);

    color: var(--secondary);

    font-size: 25px;

    margin-bottom: 25px;
}

.project-card h3 {
    font-size: 23px;
    margin-bottom: 15px;
}

.project-card > p {
    color: var(--muted);
    line-height: 1.7;
}

.project-tech {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;

    margin: 22px 0;
}

.project-tech span {
    font-size: 11px;

    padding: 6px 10px;

    border-radius: 20px;

    background: rgba(0, 212, 255, 0.08);

    color: var(--secondary);
}

.project-link {
    color: white;
    font-size: 13px;
    font-weight: 600;
}

.project-link:hover {
    color: var(--secondary);
}


/* =========================
   DSA
========================= */

.dsa-section {
    background: var(--bg2);
}

.dsa-container {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 50px;

    align-items: center;

    padding: 45px;

    background: var(--card);

    border: 1px solid var(--border);

    border-radius: 20px;
}

.dsa-content h3 {
    font-size: 30px;
    margin-bottom: 20px;
}

.dsa-content h3 span {
    color: var(--secondary);
}

.dsa-content p {
    color: var(--muted);
    line-height: 1.8;
    margin-bottom: 25px;
}

.dsa-stats {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 15px;
}

.dsa-stats div {
    text-align: center;
    padding: 25px 10px;

    border: 1px solid var(--border);
    border-radius: 12px;
}

.dsa-stats i {
    color: var(--secondary);
    font-size: 25px;
    margin-bottom: 12px;
}

.dsa-stats h3 {
    font-size: 22px;
}

.dsa-stats p {
    color: var(--muted);
    font-size: 11px;
}


/* =========================
   TIMELINE
========================= */

.timeline {
    max-width: 850px;
    margin: auto;

    position: relative;
}

.timeline::before {
    content: "";

    position: absolute;

    left: 12px;
    top: 0;
    bottom: 0;

    width: 2px;

    background: linear-gradient(
        var(--primary),
        var(--secondary)
    );
}

.timeline-item {
    position: relative;

    padding-left: 55px;

    margin-bottom: 45px;
}

.timeline-dot {
    position: absolute;

    left: 4px;
    top: 5px;

    width: 18px;
    height: 18px;

    border-radius: 50%;

    background: var(--secondary);

    box-shadow: 0 0 20px var(--secondary);
}

.timeline-content {
    padding: 25px;

    border: 1px solid var(--border);

    background: var(--card);

    border-radius: 14px;
}

.timeline-content > span {
    color: var(--secondary);
    font-size: 12px;
}

.timeline-content h3 {
    margin: 8px 0;
}

.timeline-content p {
    color: var(--muted);
    line-height: 1.6;
}


/* =========================
   CONTACT
========================= */

.contact-section {
    background: var(--bg2);
}

.contact-container {
    display: grid;
    grid-template-columns: 1fr 1fr;

    gap: 60px;
}

.contact-info h3 {
    font-size: 30px;
    margin-bottom: 15px;
}

.contact-info > p {
    color: var(--muted);
    line-height: 1.8;
    margin-bottom: 30px;
}

.contact-item {
    display: flex;
    gap: 15px;
    margin: 25px 0;
}

.contact-item > i {
    width: 45px;
    height: 45px;

    display: grid;
    place-items: center;

    border-radius: 10px;

    background: rgba(124, 92, 255, 0.12);

    color: var(--secondary);
}

.contact-item span {
    font-size: 12px;
    color: var(--muted);
}

.contact-item p {
    margin-top: 3px;
}

.contact-form {
    display: flex;
    flex-direction: column;
    gap: 25px;
}

.input-group {
    position: relative;
}

.input-group input,
.input-group textarea {
    width: 100%;

    background: transparent;

    border: 1px solid var(--border);

    border-radius: 10px;

    padding: 16px;

    color: white;

    outline: none;

    font-family: inherit;
}

.input-group label {
    position: absolute;

    left: 16px;
    top: 16px;

    color: var(--muted);

    font-size: 13px;

    pointer-events: none;

    transition: 0.3s;

    background: var(--bg2);

    padding: 0 5px;
}

.input-group input:focus,
.input-group textarea:focus {
    border-color: var(--secondary);
}

.input-group input:focus + label,
.input-group input:valid + label,
.input-group textarea:focus + label,
.input-group textarea:valid + label {
    top: -9px;
    color: var(--secondary);
    font-size: 11px;
}


/* =========================
   FOOTER
========================= */

footer {
    padding: 50px 8%;

    text-align: center;

    border-top: 1px solid var(--border);
}

.footer-logo {
    font-size: 25px;
    font-weight: 800;
    margin-bottom: 15px;
}

.footer-logo span {
    color: var(--secondary);
}

footer > p {
    color: var(--muted);
    font-size: 13px;
}

.footer-social {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin: 25px 0;
}

.footer-social a {
    width: 40px;
    height: 40px;

    display: grid;
    place-items: center;

    border: 1px solid var(--border);
    border-radius: 50%;

    transition: 0.3s;
}

.footer-social a:hover {
    color: var(--secondary);
    border-color: var(--secondary);
}

.copyright {
    margin-top: 20px;
}


/* =========================
   SCROLL TOP
========================= */

#scrollTop {
    position: fixed;

    right: 25px;
    bottom: 25px;

    width: 45px;
    height: 45px;

    border: none;

    border-radius: 50%;

    background: linear-gradient(
        135deg,
        var(--primary),
        var(--secondary)
    );

    color: white;

    cursor: pointer;

    display: none;

    z-index: 500;
}

#scrollTop.show {
    display: block;
}


/* =========================
   RESPONSIVE
========================= */

@media (max-width: 1000px) {

    .skills-container {
        grid-template-columns: repeat(2, 1fr);
    }

    .home {
        gap: 40px;
    }

    .home-content {
        width: 55%;
    }

    .developer-card {
        width: 45%;
    }
}


@media (max-width: 800px) {

    .header {
        padding: 0 5%;
    }

    .menu-icon {
        display: block;
    }

    .navbar {
        position: absolute;

        top: 75px;
        left: -100%;

        width: 100%;

        flex-direction: column;

        background: #080d1c;

        padding: 25px;

        transition: 0.4s;
    }

    .navbar.show {
        left: 0;
    }

    .navbar a {
        padding: 10px;
    }

    .home {
        flex-direction: column;
        text-align: center;
        padding: 130px 5% 70px;
    }

    .home-content,
    .developer-card {
        width: 100%;
    }

    .home-buttons,
    .social-icons {
        justify-content: center;
    }

    .about-container,
    .contact-container,
    .dsa-container {
        grid-template-columns: 1fr;
    }

    .projects-container {
        grid-template-columns: 1fr;
    }

    .section {
        padding: 80px 5%;
    }
}


@media (max-width: 550px) {

    .home h1 {
        font-size: 40px;
    }

    .section-title h2 {
        font-size: 32px;
    }

    .skills-container {
        grid-template-columns: 1fr;
    }

    .about-stats {
        flex-direction: column;
    }

    .dsa-container {
        padding: 25px;
    }

    .dsa-stats {
        grid-template-columns: 1fr;
    }

    .code-content {
        font-size: 11px;
        padding: 20px;
    }
}