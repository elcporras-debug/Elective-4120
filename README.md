
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GE 4120 | Digital Portfolio</title>

    <style>
        :root {
            --dark-green: #14532d;
            --forest-green: #166534;
            --green: #22c55e;
            --light-green: #dcfce7;
            --pale-green: #f0fdf4;
            --white: #ffffff;
            --text: #26382c;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: "Segoe UI", Arial, sans-serif;
            background: var(--pale-green);
            color: var(--text);
            line-height: 1.7;
        }

        header {
            background: linear-gradient(
                135deg,
                var(--dark-green),
                var(--forest-green),
                var(--green)
            );
            color: white;
            text-align: center;
            padding: 45px 20px;
            border-bottom: 6px solid #bbf7d0;
        }

        header h1 {
            font-size: 2rem;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }

        header p {
            font-size: 1rem;
            color: #dcfce7;
        }

        main {
            max-width: 1100px;
            margin: auto;
            padding: 35px 20px;
        }

        section {
            margin-bottom: 35px;
        }

        .section-title {
            color: var(--dark-green);
            font-size: 1.5rem;
            margin-bottom: 15px;
            border-left: 5px solid var(--green);
            padding-left: 12px;
        }

        .intro {
            background: var(--white);
            padding: 25px;
            border-radius: 14px;
            border: 1px solid #bbf7d0;
            box-shadow: 0 4px 12px rgba(20, 83, 45, 0.07);
        }

        .intro p {
            margin-top: 10px;
        }

        .showcase {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }

        .card {
            background: var(--white);
            border-radius: 14px;
            overflow: hidden;
            border: 1px solid #bbf7d0;
            box-shadow: 0 5px 15px rgba(20, 83, 45, 0.08);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .card:hover {
            transform: translateY(-6px);
            box-shadow: 0 10px 22px rgba(20, 83, 45, 0.15);
        }

        .card-header {
            background: var(--light-green);
            padding: 24px 15px;
            text-align: center;
            color: var(--dark-green);
            font-size: 1.15rem;
            font-weight: bold;
            min-height: 100px;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .card-body {
            padding: 20px;
        }

        .card-body p {
            font-size: 0.95rem;
        }

        .tag {
            display: inline-block;
            background: var(--light-green);
            color: var(--forest-green);
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.8rem;
            font-weight: 600;
            margin-top: 15px;
        }

        .notice {
            background: #dcfce7;
            border-left: 5px solid var(--green);
            padding: 20px;
            border-radius: 10px;
            text-align: center;
            color: var(--dark-green);
        }

        footer {
            background: var(--dark-green);
            color: white;
            text-align: center;
            padding: 25px 15px;
            margin-top: 20px;
        }

        footer p {
            margin: 5px 0;
            font-size: 0.9rem;
        }

        footer .motto {
            color: #bbf7d0;
            font-weight: 600;
        }

        @media (max-width: 800px) {
            .showcase {
                grid-template-columns: 1fr 1fr;
            }
        }

        @media (max-width: 550px) {
            header h1 {
                font-size: 1.5rem;
            }

            .showcase {
                grid-template-columns: 1fr;
            }

            main {
                padding: 25px 15px;
            }
        }
    </style>
</head>

<body>

    <header>
        <h1>🌿 GE 4120: 21ST CENTURY IT SKILLS 🌿</h1>
        <p>My Digital Portfolio | Creativity • Technology • Growth</p>
    </header>

    <main>

        <section class="intro">
            <h2 class="section-title">🌱 About the Portfolio</h2>

            <h3>Welcome to My Digital Showcase!</h3>

            <p>
                This repository serves as a centralized hub highlighting
                my creative and technical growth in GE 4120: 21st Century
                IT Skills. It contains my required course deliverables,
                including activity outputs, design documentation, mini
                projects, and assignments completed throughout the term.
            </p>
        </section>

        <section>
            <h2 class="section-title">🍃 My Showcase</h2>

            <div class="showcase">

                <article class="card">
                    <div class="card-header">
                        Presentation Design Principles
                    </div>

                    <div class="card-body">
                        <p>
                            Focuses on applying core visual design
                            principles to improve layout structure and
                            clarity. It emphasizes alignment, contrast,
                            whitespace, and effective slide design for
                            presentation outputs.
                        </p>

                        <span class="tag">Design Principles</span>
                    </div>
                </article>

                <article class="card">
                    <div class="card-header">
                        Color Palette &amp; Typography
                    </div>

                    <div class="card-body">
                        <p>
                            Explores color theory, accessibility ratios,
                            and font pairing techniques. It highlights
                            selecting harmonious palettes and typography
                            systems for effective visual storytelling.
                        </p>

                        <span class="tag">Visual Design</span>
                    </div>
                </article>

                <article class="card">
                    <div class="card-header">
                        Social Media Infographics &amp; Project Documentation
                    </div>

                    <div class="card-body">
                        <p>
                            Features a one-page infographic simplifying
                            a real-world issue alongside project
                            documentation. It proposes a technology
                            solution through clear visual and written
                            communication.
                        </p>

                        <span class="tag">Mini Project</span>
                    </div>
                </article>

            </div>
        </section>

        <section class="notice">
            <h3>🌿 More Outputs Coming Soon!</h3>
            <p>
                Outputs and deliverables for the Prefinal period
                will be updated soon. Stay tuned!
            </p>
        </section>

    </main>

    <footer>
        <p class="motto">
            ✨ Growth, Creativity, and Progress through Technology ✨
        </p>

        <p>
            GE 4120: 21st Century IT Skills
        </p>

        <p>
            © 2026 Edd Lawrence C. Porras | All Rights Reserved
        </p>
    </footer>

</body>
</html>
