<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile - Théo Vinicius</title>
    <style>
        :root {
            --bg-color: #0d1117;
            --text-main: #c9d1d9;
            --text-muted: #8b949e;
            --border-color: #30363d;
            --link-color: #58a6ff;
            --btn-bg: #21262d;
            --btn-border: rgba(240, 246, 252, 0.1);
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
        }

        .container {
            display: flex;
            max-width: 1200px;
            width: 100%;
            gap: 30px;
        }

        /* Sidebar */
        .sidebar {
            width: 296px;
            flex-shrink: 0;
        }

        .profile-pic {
            width: 296px;
            height: 296px;
            border-radius: 50%;
            border: 2px solid var(--border-color);
            background-color: #161b22;
            /* Você pode colocar o link da sua foto do GitHub aqui no background-image */
            background-image: url('https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png'); 
            background-size: cover;
            background-position: center;
        }

        .names { margin-top: 16px; }
        .names h1 { font-size: 24px; margin: 0; line-height: 1.25; }
        .names h2 { font-size: 20px; color: var(--text-muted); font-weight: 300; margin: 0 0 16px 0; }

        .btn-follow {
            width: 100%;
            padding: 5px 16px;
            font-size: 14px;
            font-weight: 500;
            color: var(--text-main);
            background-color: var(--btn-bg);
            border: 1px solid var(--btn-border);
            border-radius: 6px;
            cursor: pointer;
            margin-bottom: 16px;
        }

        .bio { font-size: 14px; margin-bottom: 16px; line-height: 1.5; }
        
        .details-list { list-style: none; padding: 0; margin: 0; font-size: 14px; color: var(--text-muted); }
        .details-list li { padding-top: 4px; display: flex; align-items: center; gap: 8px;}

        /* Main Content */
        .main-content {
            flex-grow: 1;
        }

        .banner {
            width: 100%;
            height: 200px;
            background: linear-gradient(to right, #161b22, #0d1117);
            border-radius: 6px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            border: 1px solid var(--border-color);
            margin-bottom: 20px;
        }

        .banner h2 { font-family: 'Courier New', Courier, monospace; margin: 5px; color: #fff;}
        .banner p { color: var(--link-color); font-family: 'Courier New', Courier, monospace; margin: 5px;}
        
        .about-text { font-size: 15px; line-height: 1.6; margin-bottom: 30px; }

        .section-title { text-align: center; margin: 30px 0 20px; font-size: 18px; border-bottom: 1px solid var(--border-color); padding-bottom: 10px;}

        /* Tech Stack */
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin-bottom: 30px;
        }
        .tech-badge {
            background: #161b22;
            border: 1px solid var(--border-color);
            padding: 8px 15px;
            border-radius: 4px;
            font-size: 14px;
            font-weight: 600;
            color: var(--link-color);
        }

        /* Projects Grid */
        .projects-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 15px;
        }

        .project-card {
            background-color: #0d1117;
            border: 1px solid var(--border-color);
            border-radius: 6px;
            padding: 15px;
        }

        .project-card h3 { margin-top: 0; font-size: 16px; color: var(--text-main); }
        .project-card p { font-size: 14px; color: var(--text-muted); line-height: 1.4;}

        /* Badges de Certificação */
        .cert-badge {
            display: inline-block;
            background-color: #238636;
            color: white;
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 12px;
            margin-right: 5px;
            margin-top: 10px;
        }

    </style>
</head>
<body>

<div class="container">
    <aside class="sidebar">
        <div class="profile-pic"></div>
        <div class="names">
            <h1>Théo Vinicius</h1>
            <h2>Comparetti Lima Silva</h2>
        </div>
        <button class="btn-follow">Follow</button>
        <div class="bio">
            Estudante de Gestão em TI. Em transição de carreira para Suporte Técnico e Help Desk. 🚀
        </div>
        <ul class="details-list">
            <li>📍 São Paulo, Brasil</li>
            <li>💼 +3 anos de experiência em Atendimento</li>
            <li>⚽ Vai Corinthians!</li>
            <li>🎮 PS5 Player</li>
        </ul>
    </aside>

    <main class="main-content">
        <div class="banner">
            <h2>Olá, eu sou o Théo! 👋</h2>
            <p>> Futuro Especialista em Suporte de TI</p>
        </div>

        <p class="about-text">
            Atualmente estou no 4º semestre de Gestão em Tecnologia da Informação, com formatura prevista para meados do ano! 🎓 Tenho uma sólida base em comunicação, graças a mais de 3 anos de experiência em atendimento direto ao público, e agora estou focando minhas energias na área de Suporte Técnico e Help Desk 💻.<br><br>
            Estou em constante aprendizado, tirando certificações e construindo projetos práticos para consolidar meus conhecimentos em programação e gestão de dados.
        </p>
        
        <div>
            <span class="cert-badge">Google IT Support Professional (Em andamento)</span>
            <span class="cert-badge">Power BI - SENAI (Concluído)</span>
        </div>

        <h3 class="section-title">Tecnologias e Ferramentas</h3>
        <div class="tech-stack">
            <span class="tech-badge">Java</span>
            <span class="tech-badge">Python</span>
            <span class="tech-badge">SQL</span>
            <span class="tech-badge">HTML</span>
            <span class="tech-badge">Power BI</span>
        </div>

        <h3 class="section-title">Projetos em Destaque</h3>
        <div class="projects-grid">
            <div class="project-card">
                <h3>📦 EPI Manager</h3>
                <p>Sistema desenvolvido para a empresa Sustentare focado no gerenciamento e controle de Equipamentos de Proteção Individual.</p>
                <span class="tech-badge" style="font-size: 11px; padding: 3px 6px;">Java</span>
                <span class="tech-badge" style="font-size: 11px; padding: 3px 6px;">HTML</span>
            </div>
            <div class="project-card">
                <h3>👕 Projeto Revestir</h3>
                <p>Desenvolvimento de um sistema com foco social para organização e gerenciamento de doações de roupas.</p>
                <span class="tech-badge" style="font-size: 11px; padding: 3px 6px;">Gestão de Projetos</span>
            </div>
        </div>
    </main>
</div>

</body>
</html>
