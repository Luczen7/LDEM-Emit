<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Profil GitHub</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/your-code.js" crossorigin="anonymous"></script>
</head>
<body>

    <nav class="navbar">
        <div class="nav-left">
            <svg height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true" fill="white"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
            <input type="text" placeholder="Search or jump to..." class="search-input">
            <a href="#">Pull requests</a>
            <a href="#">Issues</a>
            <a href="#">Marketplace</a>
        </div>
    </nav>

    <div class="container">
        <aside class="sidebar">
            <div class="avatar"></div>
            <h1 class="name">Nom d'Utilisateur</h1>
            <p class="username">user_github</p>
            <p class="bio">Passionné de développement web et d'IA. 🚀</p>
            <button class="edit-btn">Edit profile</button>
            <div class="stats">
                <span><strong>120</strong> followers</span> · <span><strong>45</strong> following</span>
            </div>
        </aside>

        <main class="content">
            <nav class="tab-nav">
                <a href="#" class="active">Overview</a>
                <a href="#">Repositories <span class="counter">12</span></a>
                <a href="#">Projects</a>
            </nav>

            <div class="repo-grid">
                <div class="repo-card">
                    <a href="#" class="repo-title">mon-super-projet</a>
                    <p class="repo-desc">Une application incroyable développée avec HTML et CSS.</p>
                    <div class="repo-footer">
                        <span class="lang-circle"></span> HTML
                    </div>
                </div>
                <div class="repo-card">
                    <a href="#" class="repo-title">portfolio-2026</a>
                    <p class="repo-desc">Mon portfolio personnel mis à jour.</p>
                    <div class="repo-footer">
                        <span class="lang-circle css"></span> CSS
                    </div>
                </div>
            </div>
        </main>
    </div>

</body>
</html>
