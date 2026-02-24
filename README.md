

<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fiche Projet : Mantasoa l'Incontournable</title>
    <style>
        
.btn-floating {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background-color: var(--accent-color);
    color: violet;
    padding: 12px 20px;
    border-radius: 10px; 
    text-decoration: none;
    display: flex;
    align-items: center;
    gap: 10px;
    font-weight: bold;
    box-shadow: 0 4px 15px rgba(0,0,0,0.3);
    z-index: 1000; 
    transition: transform 0.3s, background-color 0.3s;
}

.btn-floating:hover {
    background-color: #ff5733; 
    transform: scale(1.5);   
    color: white
}

@media (max-width: 600px) {
    .btn-floating span { display-none;}/* Sary famantarana fotsiny no hita amin'ny finday */
    .btn-floating {padding: 15px;
    }

        :root {
            --primary-color: #2c3e50;
            --accent-color: #27ae60;
            --text-color: #333;
            --bg-color: #f4f7f6;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                line-height: 1.6;
            color: var(--text-color);
            background-color: var(--bg-color);h1 {
    background-color: var(--primary-color); /* Loko manga */
    color: white;             /* Loko fotsy ny soratra mba hovakiana tsara */
    padding: 15px 20px;       /* Elanelana eo anelanelan'ny soratra sy ny sisiny */
    border-radius: 10px;      /* Manodidina kely ny zorony */
    display: inline-block;    /* Tsy mameno ny sakany manontolo fa araka ny soratra ihany */
    margin-bottom: 20px;}
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            
        } 
        header {
            text-align: center;
            border-bottom: 3px solid var(--accent-color);
            padding-bottom: 20px;
            margin-bottom: 30px;
        }

        h1 { color: var(--primary-color); margin: 0; font-size: 2.5em; }
        h2 { color: var(--accent-color); border-left: 5px solid var(--accent-color); padding-left: 15px; margin-top: 40px; }

        .image-placeholder {
            width: 100%;
            height: 400px;
            background: #e0e0e0;
            margin: 20px 0;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
            font-style: italic;
            color: #666;
            border: 1px solid #ddd;
        }

        .image-placeholder img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .content-section {
            margin-bottom: 30px;
            text-align: justify;
        }

        .grid-container {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin-top: 20px;
        }

        .card {
            background: #f9f9f9;
            padding: 20px;
            border-radius: 8px;
            border-top: 4px solid var(--accent-color);
        }

        blockquote {
            background: #f0fff4;
            border-left: 10px solid var(--accent-color);
            margin: 1.5em 10px;
            padding: 1em 20px;
            font-style: italic;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            font-size: 0.9em;
            color: #777;
        }
      </style>
</header>
<body>

    <header>
        <h1>Mantasoa: Histoire & Nature</h1>
        <p>Un sanctuaire unique à Madagascar, entre héritage industriel et sérénité lacustre.</p>
    </header>

      <img src="sary0.jpg" style="width:120%; border-radius:30px; display:block; margin: 25px 0;">
        
    </div>

    <section class="content-section">
        <h2>1. Un Voyage Temporel : L'Héritage de Jean Laborde</h2>
        <p>
            Ce qui distingue Mantasoa de toute autre destination à Madagascar, c'est son <strong>patrimoine historique industriel</strong>. 
            Dans les années 1830, sous le règne de la reine Ranavalona Ière, l'aventurier français Jean Laborde y a construit une véritable cité industrielle.
        </p>
        <ul>
            <li><strong>La Cité Industrielle :</strong> Les vestiges des hauts fourneaux et des tanneries témoignent du génie de l'époque.</li>
            <li><strong>La Maison de Jean Laborde :</strong> Un chef-d'œuvre architectural en bois devenu un musée incontournable.</li>
        </ul>
    </section>

    <img src="sary.jpg" style="width:120%; border-radius:25px; display:block; margin: 25px 0;">

    </div>

    <section class="content-section">
        <h2>2. Un Cadre Naturel Envoûtant</h2>
        <p>
            Le lac de Mantasoa, avec ses <strong>2 000 hectares</strong>, offre un paysage digne d'une carte postale. 
            C'est un lieu où le silence n'est rompu que par le clapotis de l'eau et le chant des oiseaux.
        </p>
        <blockquote>
            "La magie de Mantasoa réside dans son ambiance nostalgique et romantique. C'est un lieu où le temps semble s'être arrêté."
        </blockquote>
    </section>

    <img src="sar.jpg" style="width:120%; border-radius:25px; display:block; margin: 25px 0;">
        [Image de personnes pratiquant du kayak ou du jet-ski sur le lac]
    </div>

    <section class="content-section">
        <h2>3. Activités & Gastronomie</h2>
        <div class="grid-container">
            <div class="card">
                <h3>Sensations & Loisirs</h3>
                <p>Ski nautique, pédalo, et randonnées équestres dans les forêts de pins pour les plus aventureux.</p>
            </div>
            <div class="card">
                <h3>Saveurs Locales</h3>
                <p>Dégustation de <strong>Foie Gras</strong> artisanal et de poisson frais du lac (carpes et tilapias).</p>
            </div>
        </div>
    </section>

    <img src="say..jpg" style="width:120%; border-radius:25px; display:block; margin: 25px 0;">
    </div>

    <section class="content-section">
        <h2>4. Le Prestige Moderne</h2>
        <p>
            Saviez-vous que Mantasoa est également le berceau du <strong>caviar malgache</strong> ? 
            C'est ici que l'un des premiers caviars d'Afrique est produit, apportant une valeur prestigieuse à ce site historique.
        </p>
    </section>

    <footer>
        <p>Fiche Projet  2026 - Exploration Madagascar</p>
    </footer>
</div>
 <a href="javascript:history.back()" class="btn-floating" 
        <svg width="30" height="30" viewBox="0 0 24 24" fill="none"  
         <line x1="19" y1="12" x2="5" y2="12"></line>
            <polyline points="12 19 5 12 12 5"></polyline>
        </svg>
        <span>🏠 RETOUR </span>
    </a>
</body>
</html> 
