<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Seung Sang LEE | Portfolio</title>
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
            width: 150px;
            height: 180px;
            object-fit: cover;
            border-radius: 15px;
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

        .badges img {
            margin: 0 3px;
            transition: transform 0.2s;
        }

        .badges img:hover { transform: translateY(-3px); }

        /* Section Styling */
        section {
            background: var(--card-bg);
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.05);
            margin-bottom: 30px;
        }

        h2 {
            font-size: 1.5rem;
            border-left: 5px solid var(--primary-color);
            padding-left: 15px;
            margin-bottom: 25px;
            color: var(--primary-color);
        }

        /* Overview Table */
        .overview-table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.95rem;
        }

        .overview-table th {
            background: #f1f3f5;
            padding: 12px;
            text-align: left;
        }

        .overview-table td {
            padding: 12px;
            border-bottom: 1px solid #eee;
        }

        .date-badge {
            background: #e9ecef;
            padding: 2px 8px;
            border-radius: 4px;
            font-family: monospace;
            font-weight: bold;
            font-size: 0.85rem;
        }

        /* List Styling */
        .exp-item {
            margin-bottom: 25px;
        }

        .exp-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            margin-bottom: 8px;
        }

        .exp-title {
            font-weight: bold;
            font-size: 1.1rem;
        }

        ul {
            padding-left: 20px;
            margin: 5px 0;
        }

        li { margin-bottom: 5px; }

        /* Skills Grid */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
        }

        .skill-cat h4 {
            margin-bottom: 10px;
            color: var(--accent);
            border-bottom: 1px solid #eee;
            padding-bottom: 5px;
        }

        footer {
            text-align: center;
            padding: 40px 0;
            color: #999;
            font-size: 0.9rem;
        }

        /* Responsive */
        @media (max-width: 600px) {
            .exp-header { flex-direction: column; }
            .date-badge { margin-top: 5px; display: inline-block; }
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <img src="https://raw.githubusercontent.com/iseungsang01/github.io/main/%EC%9D%B4%EC%8A%B9%EC%83%81_%EC%A6%9D%EB%AA%85%EC%82%AC%EC%A7%84.jpg?raw=true" alt="Seung Sang LEE" class="profile-img">
        <h1>Seung Sang, LEE 🚀</h1>
        <p class="subtitle">Bachelor Student of Rural Systems Engineering & Nuclear Engineering at <b>Seoul National University</b></p>
        
        <div class="badges">
            <a href="mailto:lss010330@snu.ac.kr"><img src="https://img.shields.io/badge/Email-lss010330@snu.ac.kr-D14836?style=flat-square&logo=Gmail&logoColor=white"></a>
            <a href="https://www.linkedin.com/in/%EC%8A%B9%EC%83%81-%EC%9D%B4-55560a27a/"><img src="https://img.shields.io/badge/LinkedIn-SeungSang_Lee-0A66C2?style=flat-square&logo=LinkedIn&logoColor=white"></a>
            <a href="https://glaze-frost-837.notion.site/NuScale-Power-25-09-28-27993068735680969e08c3fafc947a5d?source=copy_link"><img src="https://img.shields.io/badge/Notion-Stock_Report-000000?style=flat-square&logo=Notion&logoColor=white"></a>
            <a href="https://github.com/iseungsang01"><img src="https://img.shields.io/badge/GitHub-iseungsang01-181717?style=flat-square&logo=GitHub&logoColor=white"></a>
        </div>
    </header>

    <section>
        <h2>🚀 Experience Overview</h2>
        <table class="overview-table">
            <thead>
                <tr>
                    <th>Category</th>
                    <th>Title</th>
                    <th>Period</th>
                </tr>
            </thead>
            <tbody>
                <tr><td><b>Work</b></td><td>Mirae Asset Securities Internship</td><td><span class="date-badge">2025.01 - 2025.02</span></td></tr>
                <tr><td><b>Project</b></td><td>Quantum AI Contest (1st Place)</td><td><span class="date-badge">2025.07 - 2025.08</span></td></tr>
                <tr><td><b>Club</b></td><td>T-um Team Manager (React/Supabase)</td><td><span class="date-badge">2025.03 - 2025.12</span></td></tr>
                <tr><td><b>Research</b></td><td>Bachelor's Thesis (QGNN)</td><td><span class="date-badge">2024.09 - 2024.12</span></td></tr>
                <tr><td><b>Military</b></td><td>ROKAF Squad Leader</td><td><span class="date-badge">2023.02 - 2023.07</span></td></tr>
            </tbody>
        </table>
    </section>

    <section>
        <h2>📖 Education</h2>
        <div class="exp-item">
            <div class="exp-header">
                <span class="exp-title">Seoul National University</span>
                <span class="date-badge">2020.03 - Present</span>
            </div>
            <ul>
                <li>Rural Systems Engineering & Nuclear Engineering (Double Major)</li>
                <li><b>GPA: 3.92 / 4.30</b> (Exp. Graduation: Feb 2027)</li>
                <li>Scholarships: Sangrok Cultural (Full), Dongwon (Full), On-Campus Customized (Full)</li>
            </ul>
        </div>
        <div class="exp-item">
            <div class="exp-header">
                <span class="exp-title">Daejeon Science High School for the Gifted</span>
                <span class="date-badge">2017.03 - 2020.02</span>
            </div>
            <ul>
                <li>Major: Physics | Nuclear Creativity Contest (2nd Place)</li>
            </ul>
        </div>
    </section>

    <section>
        <h2>💡 Work & Project Experience</h2>
        <div class="exp-item">
            <div class="exp-header">
                <span class="exp-title">Mirae Asset Securities Internship</span>
                <span class="date-badge">2025.01 - 2025.02</span>
            </div>
            <ul>
                <li>Analyzed Uranium producer <b>Cameco(CCJ)</b> and authored a sell report (TP: $33.62)</li>
                <li>Automated data handling and visualization using <b>Excel VBA</b></li>
            </ul>
        </div>

        <div class="exp-item">
            <div class="exp-header">
                <span class="exp-title">Quantum AI Contest (1st Place)</span>
                <span class="date-badge">2025.07 - 2025.08</span>
            </div>
            <ul>
                <li>Developed hybrid AI model for FashionMNIST (Accuracy: <b>0.9165</b>)</li>
                <li>Implemented <b>Renyi entropy estimation</b> using classical shadow and binomial theorem</li>
            </ul>
        </div>

        <div class="exp-item">
            <div class="exp-header">
                <span class="exp-title">T-um Team Manager (CRM & User App)</span>
                <span class="date-badge">2025.03 - 2025.12</span>
            </div>
            <ul>
                <li>Developed tarot-themed stamp system using <b>React & Supabase</b></li>
                <li>Deployed CRM merchant dashboard via <b>Vercel</b></li>
            </ul>
        </div>
    </section>

    <section>
        <h2>🛠 Skills & Others</h2>
        <div class="skills-grid">
            <div class="skill-cat">
                <h4>Programming</h4>
                <ul>
                    <li>Python, C, Excel VBA</li>
                    <li>React, SQL, Qiskit</li>
                </ul>
            </div>
            <div class="skill-cat">
                <h4>Certifications</h4>
                <ul>
                    <li>Investment Manager</li>
                    <li>ADsP, Info. Processing</li>
                </ul>
            </div>
            <div class="skill-cat">
                <h4>Interests</h4>
                <ul>
                    <li>Quantum AI, Stocks</li>
                    <li>Room Escape, Board Games</li>
                </ul>
            </div>
        </div>
    </section>

    <footer>
        <p>Copyright © 2026 Seung Sang LEE. All rights reserved.</p>
    </footer>
</div>

</body>
</html>
