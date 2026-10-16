
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>GE 4120 | My Digital Portfolio</title>

<style>
:root {
    --background: #f1f6e9;
    --pistachio: #dce8cb;
    --green: #78966b;
    --dark-green: #385641;
    --white: #fffefa;
}

* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: "Segoe UI", Arial, sans-serif;
    background: linear-gradient(135deg, #f1f6e9, #e4eedb, #f8f7ed);
    color: #354638;
    line-height: 1.7;
}

header {
    background: linear-gradient(135deg, #c7dcb7, #a9c69a, #dce8cb);
    color: #294631;
    text-align: center;
    padding: 55px 20px;
    border-bottom: 5px solid #91ad80;
}

header h1 {
    font-size: clamp(1.5rem, 4vw, 2.4rem);
    margin-bottom: 8px;
}

header p {
    margin-top: 8px;
}

.badges {
    margin-top: 18px;
}

.badge {
    display: inline-block;
    background: #f8f9ee;
    color: #55734c;
    padding: 6px 13px;
    margin: 4px;
    border-radius: 20px;
    font-size: 0.85rem;
    font-weight: bold;
}

.container {
    width: min(1150px, 92%);
    margin: auto;
    padding: 38px 0;
}

.section-title {
    color: #385641;
    margin-bottom: 18px;
    border-left: 5px solid #91ad80;
    padding-left: 12px;
}

.about {
    background: rgba(255, 254, 250, 0.9);
    border: 1px solid #d6e4ca;
    border-radius: 18px;
    padding: 28px;
    margin-bottom: 40px;
    box-shadow: 0 5px 18px #526c4010;
}

.about h3 {
    color: #58774e;
    margin-bottom: 10px;
}

.activities {
    display: grid;
    grid-template-columns: repeat(4, minmax(0, 1fr));
    gap: 20px;
}

.card {
    border-radius: 18px;
    overflow: hidden;
    border: 1px solid #ffffff;
    box-shadow: 0 7px 20px #526c4014;
    transition: transform 0.25s, box-shadow 0.25s;
}

.card:hover {
    transform: translateY(-7px);
    box-shadow: 0 12px 25px #526c4028;
}

.card-1 {
    background: #e4eedc;
}

.card-2 {
    background: #f9e7ed;
}

.card-3 {
    background: #e3f1f7;
}

.card-4 {
    background: #f3f0d5;
}

.card-header {
    padding: 24px 16px;
    text-align: center;
    min-height: 155px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.card-1 .card-header {
    background: #c7dcb7;
}

.card-2 .card-header {
    background: #f0cbd8;
}

.card-3 .card-header {
    background: #c5e2ed;
}

.card-4 .card-header {
    background: #e5e5ae;
}

.activity-number {
    font-size: 0.85rem;
    font-weight: bold;
    letter-spacing: 1px;
    margin-bottom: 6px;
}

.card-header h3 {
    font-size: 1.1rem;
    line-height: 1.4;
}

.card-content {
    padding: 22px;
}

.card-content p {
    font-size: 0.93rem;
    margin-bottom: 20px;
}

.button {
    display: inline-block;
    text-decoration: none;
    color: white;
    background: #58774e;
    padding: 9px 14px;
    border-radius: 9px;
    font-weight: bold;
    font-size: 0.9rem;
    transition: background 0.2s;
}

.button:hover {
    background: #385641;
}

.card-2 .button {
    background: #b66f88;
}

.card-3 .button {
    background: #588ca2;
}

.card-4 .button {
    background: #858641;
}

.notice {
    background: #dce8cb;
    border: 1px solid #c5d8b5;
    border-radius: 16px;
    text-align: center;
    padding: 27px 18px;
    margin-top: 40px;
    color: #385641;
}

footer {
    background: #385641;
    color: #f7faef;
    text-align: center;
    padding: 30px 15px;
    margin-top: 20px;
}

footer p + p {
    margin-top: 6px;
}

footer .motto {
    color: #dce8cb;
    font-weight: bold;
}

@media (max-width: 950px) {
    .activities {
        grid-template-columns: repeat(2, minmax(0, 1fr));
    }
}

@media (max-width: 560px) {
    .activities {
        grid-template-columns: 1fr;
    }

    header {
        padding: 40px 15px;
    }
}
</style>
</head>

<body>

<header>
    <h1>🌿 GE 4120: 21ST CENTURY IT SKILLS 🌿</h1>
    <p>🍃 My Digital Portfolio</p>
    <p><em>Creativity • Technology • Growth</em></p>

    <div class="badges">
        <span class="badge">🌱 Pastel Pistachio</span>
        <span class="badge">💻 GE 4120</span>
    </div>
</header>

<main class="container">

    <section class="about">
        <h2 class="section-title">🌱 About the Portfolio</h2>
        <h3>Welcome to My Digital Showcase! ✨</h3>
        <p>
            This portfolio highlights my creative and technical growth
            in GE 4120: 21st Century IT Skills. It contains my course
            deliverables, including activity outputs, design
            documentation, mini projects, and assignments completed
            throughout the term.
        </p>
    </section>

    <section>
        <h2 class="section-title">🍃 My Showcase</h2>

        <div class="activities">

            <article class="card card-1">
                <div class="card-header">
                    <span class="activity-number">🌿 ACTIVITY 01</span>
                    <h3>Presentation Design Principles</h3>
                </div>
                <div class="card-content">
                    <p>
                        Applying alignment, contrast, whitespace, and
                        layout principles to create clear and effective
                        presentations.
                    </p>
                    <a class="button"
                       href="./Activity%201:%20Presentation%20Design%20Principles/">
                        🍏 View Activity
                    </a>
                </div>
            </article>

            <article class="card card-2">
                <div class="card-header">
                    <span class="activity-number">🌸 ACTIVITY 02</span>
                    <h3>Color Palette &amp; Typography</h3>
                </div>
                <div class="card-content">
                    <p>
                        Exploring color theory, accessible color
                        combinations, and font pairing for visual
                        storytelling.
                    </p>
                    <a class="button"
                       href="./Activity%202:%20Color%20Palette%20and%20Typography/">
                        🌷 View Activity
                    </a>
                </div>
            </article>

            <article class="card card-3">
                <div class="card-header">
                    <span class="activity-number">🩵 ACTIVITY 03</span>
                    <h3>Social Media Infographics &amp; Project Documentation</h3>
                </div>
                <div class="card-content">
                    <p>
                        Communicating real-world issues and technology
                        solutions through infographics and project
                        documentation.
                    </p>
                    <a class="button"
                       href="./Activity%203:%20Social%20Media%20Infographics%20and%20Project%20Documentation/">
                        🩵 View Activity
                    </a>
                </div>
            </article>

            <article class="card card-4">
                <div class="card-header">
                    <span class="activity-number">🍋 ACTIVITY 04</span>
                    <h3>Google Sheets Report</h3>
                </div>
                <div class="card-content">
                    <p>
                        Demonstrating spreadsheet skills through data
                        organization, formulas, formatting, and report
                        preparation using Google Sheets.
                    </p>
                    <a class="button"
                       href="./Activity%204:%20Google%20Sheets%20Report/">
                        🍋 View Activity
                    </a>
                </div>
            </article>

        </div>
    </section>

    <section class="notice">
        <h2>🌼 Upcoming Deliverables</h2>
        <p>
            Outputs and deliverables for the Prefinal period
            will be updated soon. Stay tuned! 🌱
        </p>
    </section>

</main>

<footer>
    <p class="motto">
        ✨ Growth, Creativity, and Progress through Technology ✨
    </p>
    <p>GE 4120 | 21st Century IT Skills</p>
    <p>© 2026 Edd Lawrence C. Porras</p>
    <p><em>Growing one skill at a time. 🍃</em></p>
</footer>

</body>
</html>
