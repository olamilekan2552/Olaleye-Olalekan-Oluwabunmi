<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Olalekan Oluwabunmi Olaleye | Portfolio</title>
    <style>
        :root { --primary: #1a2a6c; --secondary: #b21f1f; --accent: #fdbb2d; --dark: #2c3e50; --light: #ecf0f1; }
        body { font-family: 'Inter', sans-serif; line-height: 1.6; color: var(--dark); margin: 0; background: #f9f9f9; }
        header { background: linear-gradient(to right, var(--primary), var(--secondary)); color: white; padding: 4rem 1rem; text-align: center; }
        .container { max-width: 1000px; margin: -50px auto 40px; padding: 30px; background: white; border-radius: 12px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); }
        .intro { font-size: 1.2rem; color: #555; border-bottom: 2px solid #eee; padding-bottom: 20px; margin-bottom: 30px; }
        h2 { color: var(--primary); text-transform: uppercase; letter-spacing: 1px; font-size: 1.5rem; margin-top: 40px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 20px; margin-top: 20px; }
        .card { background: var(--light); padding: 20px; border-radius: 8px; border-top: 4px solid var(--primary); transition: 0.3s; }
        .card:hover { transform: translateY(-5px); box-shadow: 0 5px 15px rgba(0,0,0,0.1); }
        .card strong { color: var(--secondary); display: block; margin-bottom: 8px; }
        .project-link { display: inline-block; background: var(--primary); color: white; padding: 12px 25px; text-decoration: none; border-radius: 50px; font-weight: bold; transition: 0.3s; }
        .project-link:hover { background: var(--accent); color: var(--primary); }
        .contact-info { background: #333; color: white; padding: 40px 1rem; text-align: center; margin-top: 50px; }
        .tag { display: inline-block; background: #eee; padding: 5px 12px; border-radius: 15px; font-size: 0.85rem; margin: 5px; color: var(--primary); font-weight: 600; }
    </style>
</head>
<body>

<header>
    <h1>Olalekan Oluwabunmi Olaleye 👋</h1>
    <p>Economist | Researcher |PhD Candidate | Financial & Data Analyst</p>
</header>

<div class="container">
    <section>
        <p class="intro">
            I am a focused, efficient, and result-oriented economist and researcher with excellent skills in teaching, data analytics, econometrics, financial analysis, policy evaluation, research design, and communication. I have a strong passion for contributing to meaningful and impactful research initiatives that address real-world challenges through data-driven solutions.
        </p>
    </section>

    <h2>🛠 Technical Skills</h2>
    <div class="grid">
        <div class="card">
            <strong>Econometrics</strong>
            Stata, SPSS, Eviews, SmartPLS, Panel Data Analysis.
        </div>
        <div class="card">
            <strong>Data Analytics</strong>
            Data Cleaning, Trend Analysis, Descriptive & Inferential Statistics.
        </div>
        <div class="card">
            <strong>Financial Analysis</strong>
            Portfolio and Risk Analysis.
        </div>
        <div class="card">
            <strong>Tools</strong>
            Advanced Excel Dashboarding (Pivot/Power Query), GitHub.
        </div>
    </div>

    <h2>🎓 Academic & Research Focus</h2>
    <p>
        <span class="tag">🎓 PhD Candidate: Economics (UPM)</span>
        <span class="tag">🏆 PTDF Scholar</span>
        <span class="tag">📜 Registered Teacher (Ireland)</span>
        <span class="tag">📊 World Bank Certified: Field Research</span>
    </p>

    <h2>📈 Current Projects</h2>
    <div class="card" style="border-top: 4px solid var(--accent);">
        <h3>Health-Expectancy-Macro-Analysis</h3>
        <p>A replication study on Health Adjusted Life Expectancy (HALE) and Oil Consumption using robust panel data diagnostics.</p>
        <a href="https://github.com/olamilekan2552/Health-Expectancy-Macro-Analysis" class="project-link">View Project on GitHub</a>
    </div>
</div>

<div class="contact-info">
    <h2>Get In Touch</h2>
    <p>📧 lekinzino@gmail.com | 📱 +60 1117940546</p>
    <p>Selangor, Malaysia</p>
</div>

</body>
</html>
