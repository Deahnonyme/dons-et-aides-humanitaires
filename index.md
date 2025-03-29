---
title: "🌐Accueil"
order: 0
in_menu: true
---
<div class="sidebar" id="sidebar">
    <button class="toggle-btn" onclick="toggleSidebar()">☰</button>
    <h2>Menu</h2>
    <a href="/page1">Page 1</a>
    <a href="/page2">Page 2</a>
    <a href="/page3">Page 3</a>
    <a href="/contact">Contact</a>
</div>

<div class="content">
    <h1>Bienvenue sur mon blog</h1>
    <p>Explorez mes pages à gauche pour en savoir plus.</p>
</div>

<style>
    body {
        margin: 0;
        font-family: Georgia, serif;
        display: flex;
    }

    .sidebar {
        width: 250px;
        height: 100vh;
        background-color: #b86ad2; /* Violet pervenche */
        color: white;
        padding: 20px;
        position: fixed;
        left: 0;
        top: 0;
        display: flex;
        flex-direction: column;
        transition: width 0.3s ease;
    }

    .sidebar a {
        color: white;
        text-decoration: none;
        font-size: 18px;
        margin: 10px 0;
        padding: 10px;
        background-color: #9c58b6; /* Violet plus clair */
        border-radius: 5px;
        transition: background 0.3s;
    }

    .sidebar a:hover {
        background-color: #7f3c89; /* Assombrissement au survol */
    }

    .toggle-btn {
        background-color: #9c58b6;
        color: white;
        border: none;
        font-size: 20px;
        padding: 10px;
        cursor: pointer;
        position: absolute;
        top: 10px;
        left: 10px;
    }

    .toggle-btn:hover {
        background-color: #7f3c89;
    }

    .content {
        margin-left: 270px; /* Décale le contenu pour ne pas passer sous la barre latérale */
        padding: 20px;
    }

    .collapsed {
        width: 0;
        padding: 0;
    }

    .collapsed a {
        display: none;
    }

    .collapsed h2 {
        display: none;
    }
</style>

<script>
    function toggleSidebar() {
        var sidebar = document.getElementById("sidebar");
        sidebar.classList.toggle("collapsed");
    }
</script>





**Dons et aides Humanitaires** est un site qui a pour objectif de réunir des cagnottes, des comptes qui publient des informations diverses ou d'autres liens utiles afin de les rendre plus facilement trouvables et accessibles.

Il est important de les partager un maximum dans le but d'informer sur ce qu'il se passe dans le monde, notamment les conflits tels que les guerres actuelles que les médias ne montrent que rarement, si ce n'est jamais. L'entraide est une question de survie pour de très nombreuses personnes.

N'hésite pas à partager le lien du site pour donner un coup de pouce contre l'invisibilisation de nos besoins et de nos luttes ! 