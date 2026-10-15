# GonTa-tech.github.io
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Illia — Junior Tester & AI Testing Learner</title>
    <style>
        :root {
            --bg-color: #0d1117;
            --card-bg: #161b22;
            --text-primary: #c9d1d9;
            --text-secondary: #8b949e;
            --accent-color: #58a6ff;
            --accent-hover: #1f6feb;
            --border-color: #30363d;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-primary);
            line-height: 1.6;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            width: 100%;
            max-width: 800px;
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 40px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.4);
        }

        header {
            margin-bottom: 30px;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 20px;
        }

        h1 {
            font-size: 2.5rem;
            color: #ffffff;
            margin-bottom: 8px;
        }

        .subtitle {
            font-size: 1.2rem;
            color: var(--accent-color);
            font-weight: 500;
        }

        section {
            margin-bottom: 30px;
        }

        h2 {
            font-size: 1.4rem;
            color: #ffffff;
            margin-bottom: 12px;
            border-left: 3px solid var(--accent-color);
            padding-left: 10px;
        }

        p {
            color: var(--text-secondary);
            margin-bottom: 10px;
        }

        .projects-list {
            list-style: none;
        }

        .project-item {
            background-color: var(--bg-color);
            border: 1px solid var(--border-color);
            border-radius: 8px;
            padding: 16px;
            margin-bottom: 12px;
            transition: border-color 0.2s ease;
        }

        .project-item:hover {
            border-color: var(--accent-color);
        }

        .project-title {
            font-weight: 600;
            color: #ffffff;
            margin-bottom: 4px;
        }

        .project-desc {
            font-size: 0.95rem;
            color: var(--text-secondary);
            margin-bottom: 8px;
        }

        a {
            color: var(--accent-color);
            text-decoration: none;
            font-weight: 500;
        }

        a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.85rem;
            color: var(--text-secondary);
            border-top: 1px solid var(--border-color);
            padding-top: 20px;
        }
    </style>
</head>
<body>

    <div class="container">
        <header>
            <h1>Cześć, jestem Illia</h1>
            <div class="subtitle">Junior Tester &middot; AI Testing Learner</div>
        </header>

        <section>
            <h2>O mnie</h2>
            <p>Jestem już doświadczonym na starcie ścieżki junior testerem, który nie osiada na laurach. Obecnie aktywnie poszerzam swoją wiedzę i rozwijam się w kierunku testowania Sztucznej Inteligencji (AI).</p>
        </section>

        <section>
            <h2>Projekty</h2>
            <ul class="projects-list">
                <li class="project-item">
                    <div class="project-title">Testy w Postmanie</div>
                    <div class="project-desc">Praktyczna weryfikacja statusów odpowiedzi oraz struktury JSON dla wybranych endpointów API.</div>
                </li>
                <li class="project-item">
                    <div class="project-title">Analiza systemów WMS</div>
                    <div class="project-desc">Badanie koncepcji systemów klasy WMS (aplikacji magazynowych) ze szczególnym uwzględnieniem ich mocnych i słabych stron.</div>
                </li>
                <li class="project-item">
                    <div class="project-title">Warsztaty i Inne Projekty</div>
                    <div class="project-desc">Prace realizowane w ramach dodatkowych zadań i wyzwań programistyczno-testowych.</div>
                    <a href="https://GonTa-tech.github.io/kolo-warsztaty/" target="_blank" rel="noopener noreferrer">Zobacz projekt warsztatowy &rarr;</a>
                </li>
            </ul>
        </section>

        <footer>
            <p>&copy; 2026 Illia. Tworzone z pasją do jakości oprogramowania.</p>
        </footer>
    </div>

</body>
</html>
