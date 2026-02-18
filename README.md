# moses-thundercat-landing
Landing page for my coaching
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moses Thundercat - Street Workout Mastery</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700;900&display=swap" rel="stylesheet">
    <style>
        :root {
            --primary: #FF6B35;
            --secondary: #FF8C42;
            --dark: #1A1A1A;
            --light: #F8F9FA;
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Montserrat', sans-serif; line-height: 1.6; color: var(--dark); scroll-behavior: smooth; }
        
        header { 
            position: fixed; top: 0; width: 100%; background: rgba(26, 26, 26, 0.95); 
            padding: 15px 0; z-index: 1000; backdrop-filter: blur(5px);
        }
        .nav-container { max-width: 1200px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; padding: 0 20px; }
        .logo { color: white; font-weight: 900; font-size: 1.2rem; text-transform: uppercase; letter-spacing: 2px; }

        .hero { 
            height: 90vh; background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1526506118085-60ce8714f8c5?auto=format&fit=crop&q=80&w=1200');
            background-size: cover; background-position: center;
            display: flex; align-items: center; justify-content: center; text-align: center; color: white; padding-top: 60px;
        }
        .hero-content h1 { font-size: clamp(2.5rem, 8vw, 4.5rem); font-weight: 900; line-height: 1.1; margin-bottom: 20px; }
        .hero-content p { font-size: 1.4rem; margin-bottom: 30px; font-weight: 300; max-width: 800px; margin-left: auto; margin-right: auto; }

        .cta-btn { 
            background: linear-gradient(45deg, var(--primary), var(--secondary)); 
            color: white; padding: 20px 40px; font-size: 1.1rem; font-weight: 700;
            text-decoration: none; border-radius: 50px; display: inline-block;
            transition: 0.3s; border: none; cursor: pointer; text-transform: uppercase;
        }
        .cta-btn:hover { transform: scale(1.05); box-shadow: 0 10px 20px rgba(255, 107, 53, 0.4); }

        .black-title { color: #000000 !important; font-weight: 900; }

        .step-section { padding: 80px 20px; text-align: center; }
        .container { max-width: 1100px; margin: 0 auto; }
        
        /* SECTION PROBLÈME OPTIMISÉE */
        .problem-section { background: #fff; }
        .problem-intro { font-size: 1.2rem; color: #666; max-width: 700px; margin: 0 auto 40px; }
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 30px; margin-top: 40px; }
        .card { background: var(--light); padding: 40px; border-radius: 20px; text-align: left; transition: 0.3s; border-bottom: 4px solid transparent; }
        .card:hover { border-bottom: 4px solid var(--primary); transform: translateY(-5px); }
        .card h3 { font-size: 1.5rem; margin-bottom: 15px; display: flex; align-items: center; gap: 10px; }
        .card p { color: #444; font-size: 1rem; }

        .form-wrapper { background: white; padding: 20px; border-radius: 20px; box-shadow: 0 20px 40px rgba(0,0,0,0.1); margin-top: 40px; }

        /* OFFER BOX */
        .offer-box { 
            background: var(--primary); color: white; padding: 60px 40px; border-radius: 30px; 
            margin: 50px 0; box-shadow: 0 20px 50px rgba(255, 107, 53, 0.3);
        }
        .offer-box ul { list-style: none; margin: 30px auto; max-width: 500px; text-align: left; }
        .offer-box li { margin-bottom: 15px; font-size: 1.1rem; display: flex; align-items: center; gap: 10px; }

        @media (max-width: 768px) {
            .hero-content h1 { font-size: 2.2rem; }
            iframe { height: 800px; }
        }
    </style>
</head>
<body>

    <header>
        <div class="nav-container">
            <div class="logo">Moses Thundercat</div>
            <a href="#consultation" class="cta-btn" style="padding: 10px 20px; font-size: 0.8rem;">DÉMARRER</a>
        </div>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>REPRENDS LE CONTRÔLE</h1>
            <p>De la réathlétisation à la force explosive. Un accompagnement d'élite pour transformer ton corps durablement.</p>
            <a href="#eval" class="cta-btn">Évaluer mon potentiel →</a>
        </div>
    </section>

    <section class="step-section problem-section">
        <div class="container">
            <h2 style="font-size: 2.5rem; margin-bottom: 10px;">Le constat est frustrant, n'est-ce pas ?</h2>
            <p class="problem-intro">Arrêter l'entraînement est facile, mais reprendre sans guide est un champ de mines.</p>
            
            <div class="grid">
                <div class="card">
                    <h3>⚡ Le sentiment d'impuissance</h3>
                    <p>Tu sens que ton corps est "rouillé". L'énergie n'est plus la même, ton tonus musculaire s'est évaporé et chaque séance devient un combat contre la fatigue plutôt qu'une progression.</p>
                </div>
                <div class="card">
                    <h3>📉 Le syndrome de la régression</h3>
                    <p>Tes records en tractions et dips ne sont plus que des souvenirs. Repartir de zéro après une pause est un défi mental immense quand on sait ce qu'on a déjà accompli par le passé.</p>
                </div>
                <div class="card">
                    <h3>💪 La peur du "faux mouvement"</h3>
                    <p>Tu veux reprendre sérieusement, mais la peur de la blessure te freine. Sans un protocole de réathlétisation strict, tu risques de casser la machine avant même d'avoir retrouvé ton niveau.</p>
                </div>
            </div>
        </div>
    </section>

    <section class="step-section" id="eval" style="background: var(--light);">
        <div class="container">
            <h2 class="black-title" style="font-size: 2.2rem;">🔍 Évalue ton Niveau en 2min</h2>
            <p>Remplis ce formulaire pour que je puisse analyser tes blocages avant notre premier échange.</p>
            <div class="form-wrapper">
                <iframe src="https://docs.google.com/forms/d/e/1FAIpQLScXViLuyhrHyF50-1W_3VEQCfcExyTZhXcu9e2-j3IROx71sw/viewform?embedded=true" width="100%" height="600" frameborder="0">Chargement...</iframe>
            </div>
        </div>
    </section>

    <section class="step-section" id="consultation">
        <div class="container">
            <div class="offer-box">
                <h2 class="black-title" style="font-size: 2.8rem; margin-bottom: 10px;">🎁 Offre Exclusive</h2>
                <h3 style="font-size: 1.8rem; font-weight: 400; opacity: 0.9;">Accompagnement Mastery : 2 mois de suivi intensif</h3>
                
                <div style="font-size: 3.5rem; margin: 30px 0; font-weight: 900;">97 CHF <span style="font-size: 1.2rem; text-decoration: line-through; opacity: 0.7; font-weight: 300;">(Valeur : 497 CHF)</span></div>
                
                <ul>
                    <li>✅ <strong>Programmation Dynamique :</strong> Adaptée à ton évolution chaque semaine.</li>
                    <li>✅ <strong>Réathlétisation Sécurisée :</strong> Protocole anti-blessure personnalisé.</li>
                    <li>✅ <strong>Analyse Vidéo :</strong> Correction de ta forme pour maximiser la force.</li>
                    <li>✅ <strong>Support WhatsApp 7j/7 :</strong> Je réponds à toutes tes questions en direct.</li>
                </ul>

                <a href="https://calendly.com/mosiahahouansou/30min" class="cta-btn" style="background: #000; color: #fff; font-size: 1.3rem;">Réserver mon suivi intensif</a>
                
                <p style="margin-top: 30px; font-weight: bold; font-style: italic;">🚨 Attention : Seulement 5 places disponibles pour garantir un suivi de haute qualité.</p>
            </div>
        </div>
    </section>

    <footer style="background: #111; color: #555; padding: 40px 20px; text-align: center;">
        <p>&copy; 2026 Moses Thundercat. Programme de réathlétisation et force explosive.</p>
    </footer>

</body>
</html>
