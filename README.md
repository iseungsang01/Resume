<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seung Sang LEE | Portfolio</title>
    <link rel="stylesheet" as="style" crossorigin href="https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.css" />
    <style>
        :root {
            --primary-color: #003a71; /* SNU Blue */
            --secondary-color: #607d8b;
            --bg-color: #f8f9fa;
            --card-bg: #ffffff;
            --text-main: #333;
            --text-sub: #666;
            --accent: #007bff;
        }

        body {
            font-family: 'Pretendard', -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
            line-height: 1.6;
            color: var(--text-main);
            background-color: var(--bg-color);
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 40px 20px;
        }

        /* Header Section */
        header {
            text-align: center;
            margin-bottom: 50px;
        }

        .profile-img {
            width: 140px;
            height: 170px;
            object-fit: cover;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            margin-bottom: 20px;
        }

        h1 {
            font-size: 2.5rem;
            margin: 10px 0;
            color: var(--primary-color);
        }

        .subtitle {
            font-size: 1.1rem;
            color: var(--secondary-color);
            margin-bottom: 20px;
        }

        .contact-links a {
            text-decoration: none;
            margin: 0 5px;
            display: inline-block;
        }

        /* Section Styling */
        section {
            background: var(--card-bg);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 2px 12px rgba(0,0,0,0.05);
            margin-bottom: 30px;
        }

        h2 {
            font-size: 1.5rem;
            border-left: 5px solid var(--primary-color);
            padding-left: 15px;
            margin-bottom: 25px;
            color: var(--primary-color);
            display: flex;
            align-items: center;
        }

        .section-icon { margin-right: 10px; }

        /* Item Styling */
        .item {
            margin-bottom: 25px;
            border-bottom: 1px solid #f0f0f0;
            padding-bottom: 15px;
        }

        .item:last-child { border-bottom: none; }

        .item-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            flex-wrap: wrap;
        }

        .item-title { font-weight: bold; font-size: 1.15rem; color: #111; }
        .item-date { font-family: monospace; color: var(--text-sub); font-size: 0.9rem; background: #eee; padding: 2px 8px; border-radius: 4px; }
        .item-sub { color: var(--secondary-color); font-style: italic; margin-bottom: 8px; font-size: 0.95rem; }

        ul { padding-left: 20px; margin: 8px 0; }
        li { margin-bottom: 6px; }
        b { color: var(--primary-color); }

        /* Award & Scholarship Badges */
        .badge-list { display: flex; flex-wrap: wrap; gap: 8px; margin-top: 10px; }
        .badge { font-size: 0.85rem; padding: 3px 10px; border-radius: 20px; background: #eef2f7; color: var(--primary-color); border: 1px solid #d0dbe9; }

        footer { text-align: center; padding: 40px 0; color: #999; font-size: 0.9rem; }

        @media (max-width: 600px) {
            .item-header { flex-direction: column; }
            .item-date { margin-top: 5px; }
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <img src="https://raw.githubusercontent.com/iseungsang01/github.io/main/%EC%9D%B4%EC%8A%B9%EC%83%81_%EC%A6%9D%EB%AA%85%EC%82%AC%EC%A7%84.jpg?raw=true" alt="Seung Sang LEE" class="profile-img">
        <h1>Seung Sang, LEE 🚀</h1>
        <p class="subtitle">Bachelor Student of <b>Rural Systems Engineering & Nuclear Engineering</b> at SNU</p>
        
        <div class="contact-links">
            <a href="mailto:lss010330@snu.ac.kr"><img src="https://img.shields.io/badge/Email-lss010330@snu.ac.kr-D14836?style=flat-square&logo=Gmail&logoColor=white"></a>
            <a href="https://www.linkedin.com/in/%EC%8A%B9%EC%83%81-%EC%9D%B4-55560a27a/"><img src="https://img.shields.io/badge/LinkedIn-SeungSang_Lee-0A66C2?style=flat-square&logo=LinkedIn&logoColor=white"></a>
            <a href="https://github.com/iseungsang01"><img src="https://img.shields.io/badge/GitHub-iseungsang01-181717?style=flat-square&logo=GitHub&logoColor=white"></a>
        </div>
    </header>

    <section id="education">
        <h2><span class="section-icon">🎓</span> Academic Background</h2>
        <div class="item">
            <div class="item-header">
                <span class="item-title">Seoul National University (SNU)</span>
                <span class="item-date">2020.03 - Present</span>
            </div>
            <div class="item-sub">Rural Systems Engineering & Nuclear Engineering (Double Major)</div>
            <ul>
                <li>Cumulative <b>GPA: 3.92 / 4.30</b></li>
                <li>Expected Graduation: <b>Feb 2027</b></li>
            </ul>
        </div>
        <div class="item">
            <div class="item-header">
                <span class="item-title">Daejeon Science High School for the Gifted</span>
                <span class="item-date">2017.03 - 2020.02</span>
            </div>
            <div class="item-sub">Major: Physics</div>
        </div>
    </section>

    <section id="honors">
        <h2><span class="section-icon">🏅</span> Honors & Awards</h2>
        <div class="item">
            <div class="item-header"><span class="item-title">Quantum AI Contest (1st Place - Grand Prize)</span><span class="item-date">2025.08</span></div>
            <ul><li>Hybrid AI model development & Renyi entropy estimation</li></ul>
        </div>
        <div class="item">
            <div class="item-header"><span class="item-title">SNUVALUE Investment Club (1st Place)</span><span class="item-date">2025.Fall</span></div>
            <ul><li>Winner of the SNUVALUE competition for the 2nd semester of 2025</li></ul>
        </div>
        <div class="item">
            <div class="item-header"><span class="item-title">Agricultural Engineering Creativity Fair (3rd Place)</span><span class="item-date">2024.12</span></div>
            <ul><li>Project: GNN-based defect detection</li></ul>
        </div>
        <div class="badge-list">
            <span class="badge">Dean's List (2024.Fall)</span>
            <span class="badge">Nuclear Creativity Contest (2nd Place, 2018)</span>
        </div>
    </section>

    <section id="projects">
        <h2><span class="section-icon">💻</span> Project & Research</h2>
        <div class="item">
            <div class="item-header">
                <span class="item-title">Bachelor's Thesis: QGNN-Based Failure Prediction Model</span>
                <span class="item-date">2024.09 - 2024.12</span>
            </div>
            <ul>
                <li>Studied <b>Quantum Graph Neural Networks (QGNN)</b> for real-time damage prediction</li>
                <li>Developed a visualization model to predict structural failure probabilities using AE sensors</li>
                <li>Analyzed latest academic papers on QGNN architectures</li>
            </ul>
        </div>
        <div class="item">
            <div class="item-header">
                <span class="item-title">Personal Project: Tarot-Themed Stamp System</span>
                <span class="item-date">2025.03 - 2025.12</span>
            </div>
            <ul>
                <li>Built a gamified stamp system for regional revitalization using <b>React</b> and <b>Supabase</b></li>
                <li>Deployed CRM merchant dashboard and mobile-responsive app via <b>Vercel</b></li>
            </ul>
        </div>
    </section>

    <section id="leadership">
        <h2><span class="section-icon">🚩</span> Activities & Leadership</h2>
        <div class="item">
            <div class="item-header">
                <span class="item-title">Squad Leader (ROKAF 11th Fighter Wing)</span>
                <span class="item-date">2023.02 - 2023.07</span>
            </div>
            <ul>
                <li>Taught advanced <b>Excel VBA</b> techniques, improving office speed by <b>50%</b></li>
                <li>Mediated conflict resolution and ensured fair treatment within the organizational unit</li>
            </ul>
        </div>
        <div class="item">
            <div class="item-header">
                <span class="item-title">Chungbuk Science Gifted Mentoring</span>
                <span class="item-date">2024.07 - 2024.11</span>
            </div>
            <ul>
                <li>Designed a customized <b>Python</b> curriculum for science gifted mentees</li>
                <li>Guided the development of a rhythm game project using <b>Pygame</b></li>
            </ul>
        </div>
    </section>

    <section id="scholarships">
        <h2><span class="section-icon">💰</span> Scholarships</h2>
        <ul>
            <li><b>Sangrok Cultural Foundation:</b> Full (2024.Fall)</li>
            <li><b>Dongwon Scholarship:</b> Full (2024.Spring)</li>
            <li><b>On-Campus Customized:</b> Full (2025.Spring), Half (2021.Spring)</li>
            <li><b>Agricultural Engineers:</b> Half (2021.Spring & Fall)</li>
        </ul>
    </section>

    <footer>
        <p>Copyright © 2026 Seung Sang LEE. All rights reserved.</p>
    </footer>
</div>

</body>
</html>
