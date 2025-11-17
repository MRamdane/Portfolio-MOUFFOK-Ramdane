<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio de Ramdane Mouffok | Géographie et Aménagement du Territoire</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #121212;
            color: #ffffff;
            line-height: 1.6;
        }
        
        .background-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            opacity: 0.4;
            background: linear-gradient(rgba(20, 10, 40, 0.8), rgba(15, 5, 35, 0.9));
        }
        
        .bg-map {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: url('https://storageprdv2inwink.blob.core.windows.net/cu-fb334c69-7028-457e-8e00-a4e0fdbfc692-public/assets/Fond-SIG2022-1920.jpg');
            background-size: cover;
            background-position: center;
            opacity: 0.6;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        header {
            padding: 3rem 0;
            text-align: center;
            position: relative;
        }
        
        .header-content {
            position: relative;
            z-index: 2;
        }
        
        h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: #4dd0e1;
            text-shadow: 0 0 15px rgba(77, 208, 225, 0.7);
        }
        
        h2 {
            font-size: 2rem;
            margin-bottom: 1.5rem;
            color: #4dd0e1;
            border-bottom: 2px solid #4dd0e1;
            padding-bottom: 0.5rem;
            text-shadow: 0 0 10px rgba(77, 208, 225, 0.5);
        }
        
        h3 {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
            color: #81d4fa;
        }
        
        .subtitle {
            font-size: 1.5rem;
            color: #b2ebf2;
            margin-bottom: 1.5rem;
        }
        
        .profile {
            background-color: rgba(30, 20, 60, 0.7);
            border-radius: 10px;
            padding: 2rem;
            margin-bottom: 2rem;
            backdrop-filter: blur(5px);
            border: 1px solid #4dd0e1;
            box-shadow: 0 0 15px rgba(77, 208, 225, 0.3);
        }
        
        .profile p {
            font-size: 1.1rem;
            line-height: 1.6;
        }
        
        .grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
        }
        
        @media (max-width: 768px) {
            .grid {
                grid-template-columns: 1fr;
            }
        }
        
        .card {
            background-color: rgba(30, 20, 60, 0.7);
            border-radius: 10px;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            backdrop-filter: blur(5px);
            border: 1px solid #4dd0e1;
            box-shadow: 0 0 15px rgba(77, 208, 225, 0.3);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 0 25px rgba(77, 208, 225, 0.5);
        }
        
        .card h3 {
            display: flex;
            justify-content: space-between;
            margin-bottom: 1rem;
        }
        
        .card .date {
            color: #80deea;
            font-size: 0.9rem;
        }
        
        .card ul {
            list-style-position: inside;
            margin-left: 1rem;
        }
        
        .card ul li {
            margin-bottom: 0.5rem;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 0.5rem;
            margin-top: 1rem;
        }
        
        .skill {
            background-color: rgba(77, 208, 225, 0.2);
            border: 1px solid #4dd0e1;
            border-radius: 50px;
            padding: 0.5rem 1rem;
            font-size: 0.9rem;
            transition: all 0.3s;
        }
        
        .skill:hover {
            background-color: rgba(77, 208, 225, 0.5);
            transform: scale(1.05);
        }
        
        .contact {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-top: 2rem;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 1rem;
            margin-right: 1rem;
        }
        
        footer {
            text-align: center;
            padding: 2rem 0;
            margin-top: 2rem;
            font-size: 0.9rem;
            color: #b2ebf2;
        }
        
        .language-container {
            display: flex;
            flex-direction: column;
            gap: 0.5rem;
            margin-top: 1rem;
        }
        
        .language {
            display: flex;
            flex-direction: column;
        }
        
        .language-name {
            margin-bottom: 0.25rem;
        }
        
        .language-level {
            height: 8px;
            background-color: rgba(77, 208, 225, 0.2);
            border-radius: 4px;
            overflow: hidden;
        }
        
        .language-progress {
            height: 100%;
            background-color: #4dd0e1;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <div class="background-container">
        <div class="bg-map"></div>
    </div>
    
    <div class="container">
        <header>
            <div class="header-content">
                <h1>RAMDANE MOUFFOK</h1>
                <p class="subtitle">Géograpie | Aménagement du Territoire | SIG | IT | IA</p>
            
                <div class="contact">
                    <div class="contact-item">
                        <span>📧 https://www.linkedin.com/in/mouffok/</span>
                    </div>
                    <div class="contact-item">
                        <span>📍Londres, Royaume-Uni</span>
                    </div>
                    <div class="contact-item">
                        <span>📍Paris, France</span>
                    </div>
                </div>
            </div>
        </header>
        
        <section class="profile">
            <h2>Profil</h2>
            <p>Géographe et aménageur du territoire, je mets à profit ma maîtrise de l’analyse et de la transformation de données pour accompagner les collectivités territoriales dans une gestion stratégique et durable de leur territoire. Mon expertise me permet d’identifier des opportunités d’optimisation, de soutenir la planification urbaine et rurale, et d’améliorer la cohérence des projets d’aménagement. Par ailleurs, je pourrai également travailler avec les entreprises pour exploiter des données, leur permettant d’accroître leur efficacité, d’optimiser leurs investissements et de maximiser leurs bénéfices. Mon objectif : transformer les données en leviers concrets pour un développement territorial équilibré et une croissance économique durable.</p>
        </section>
        
        <div class="grid">
            <section>
                <h2>Formation</h2>
                
                <div class="card">
                    <h3>
                        <span>Master en Géographie et Aménagement du Territoire</span>
                    </h3>
                    <p>Spécialité Homme Environnement et Territoire à USTHB Alger</p>
                </div>
                
                <div class="card">
                    <h3>
                        <span>Licence en Géographie et Aménagement</span>
                    </h3>
                    <p>Université d'Avignon</p>
                </div>
                
                <div class="card">
                    <h3>
                        <span>Licence en Géographie et Aménagement du Territoire</span>
                    </h3>
                    <p>Université des Sciences et de la Technologie Houari Boumediene</p>
                </div>
                
                <div class="card">
                    <h3>
                        <span>Baccalauréat en Sciences Expérimentales</span>
                    </h3>
                </div>
                
                <h2>Compétences</h2>
                
                <div class="card">
                    <h3>Compétences Techniques</h3>
                    <div class="skills">
                        <div class="skill">Microsoft Office</div>
                        <div class="skill">Videor/RELEX/TourSolver</div>
                        <div class="skill">HTML/CSS/JS</div>
                        <div class="skill">Python</div>
                        <div class="skill">SQL</div>
                        <div class="skill">ArcGIS</div>
                        <div class="skill">QGIS</div>
                        <div class="skill">Sphinx</div>
                        <div class="skill">Flourish</div>
                        <div class="skill">Jira</div>
                        <div class="skill">Confluence</div>
                        <div class="skill">Postman</div>
                        <div class="skill">Swagger</div>
                        <div class="skill">Squash</div>
                    </div>
                </div>
                
                <div class="card">
                    <h3>Langues</h3>
                    <div class="language-container">
                        <div class="language">
                            <span class="language-name">Français</span>
                            <div class="language-level">
                                <div class="language-progress" style="width: 100%;"></div>
                            </div>
                        </div>
                        <div class="language">
                            <span class="language-name">Arabe</span>
                            <div class="language-level">
                                <div class="language-progress" style="width: 100%;"></div>
                            </div>
                        </div>
                        <div class="language">
                            <span class="language-name">Anglais</span>
                            <div class="language-level">
                                <div class="language-progress" style="width: 80%;"></div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            
            <section>
                <h2>Expérience Professionnelle</h2>
                
                <div class="card">
                    <h3>
                        <span>Co-fondateur et associé, SAS MFPS</span>
                    </h3>
                    <ul>
                        <li>Stratégie commerciale et marketing</li>
                        <li>Gestion des stocks et approvisionnements</li>
                        <li>Suivi et analyse des performances</li>
                        <li>Gestion des risques et conformité</li>
                    </ul>
                </div>
                
                <div class="card">
                    <h3>
                        <span>Responsable de magasin, Franprix Groupe Casino</span>
                    </h3>
                    <ul>
                        <li>Gestion du magasin franchisé Franprix</li>
                        <li>Management des collaborateurs</li>
                        <li>Mise en place de nouvelles méthodes de travail</li>
                    </ul>
                </div>
                
                <div class="card">
                    <h3>
                        <span>Consultant dans un Bureau d'Études Technique</span>
                    </h3>
                    <ul>
                        <li>Réalisation de cartes et plans de situation</li>
                        <li>Aide à l'amélioration des plans directeurs et schémas nationaux</li>
                        <li>Télétravail et prestations à distance</li>
                    </ul>
                </div>
                
                <div class="card">
                    <h3>
                        <span>Gérant, SARL SEA FOOD</span>
                    </h3>
                    <ul>
                        <li>Gestion des stocks</li>
                        <li>Ventes, achats et facturation</li>
                        <li>Poste à temps partiel en parallèle des études</li>
                    </ul>
                </div>
                
                <h2>Stages et Projets de Terrain</h2>
                
                <div class="card">
                    <h3>
                        <span>Stage de terrain à Ghardaïa</span>
                    </h3>
                    <ul>
                        <li>Analyse des politiques urbaines</li>
                        <li>Analyse d'images satellites et de données climatiques avec SIG</li>
                    </ul>
                </div>
                
                <div class="card">
                    <h3>
                        <span>Stage de terrain à Bousaâda</span>
                    </h3>
                    <ul>
                        <li>Étude de la ville et ses plans d'aménagement</li>
                        <li>Étude des enjeux de la Steppe avec des SIG</li>
                    </ul>
                </div>
                
                <div class="card">
                    <h3>
                        <span>Stage de terrain à Djelfa</span>
                    </h3>
                    <ul>
                        <li>Étude de la ville et ses infrastructures</li>
                        <li>Étude des zones éparses</li>
                        <li>Étude des enjeux de la poussée du désert avec des SIG</li>
                    </ul>
                </div>
            </section>
        </div>
        
        <footer>
            <p>© 2025 Ramdane Mouffok | All rights reserved.</p>
        </footer>
    </div>
</body>
</html>
