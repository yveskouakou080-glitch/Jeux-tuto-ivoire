<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Jeux-tuto-ivoire - Accès Premium</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(145deg, #f2f4f8 0%, #e6e9f0 100%);
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 20px;
        }
        .card {
            background: white;
            padding: 2rem 1.5rem 2.5rem;
            border-radius: 32px;
            box-shadow: 0 20px 40px -12px rgba(0,0,0,0.2);
            max-width: 420px;
            width: 100%;
            text-align: center;
        }
        .logo {
            font-size: 3.5rem;
            margin-bottom: 0.2rem;
        }
        h1 {
            font-size: 2rem;
            color: #0b1a33;
            margin-bottom: 0.2rem;
        }
        .sub {
            color: #4a5a72;
            margin-bottom: 1rem;
            font-size: 1rem;
        }
        .price {
            background: #f0f4fe;
            display: inline-block;
            padding: 0.4rem 2.5rem;
            border-radius: 60px;
            font-size: 2rem;
            font-weight: 700;
            color: #0047ab;
            margin: 0.5rem 0 1.5rem;
        }
        .features {
            text-align: left;
            margin: 1.5rem 0;
            padding: 0 0.5rem;
        }
        .features li {
            list-style: none;
            padding: 0.6rem 0;
            font-size: 1rem;
            color: #1f2a3f;
            border-bottom: 1px solid #f0f2f5;
        }
        .features li:last-child { border-bottom: none; }
        .features li::before {
            content: "✅ ";
        }
        .btn-wave {
            display: inline-block;
            background: #0066e6;
            color: white;
            padding: 1rem 2rem;
            border-radius: 60px;
            font-weight: 700;
            font-size: 1.2rem;
            text-decoration: none;
            box-shadow: 0 6px 14px rgba(0,102,230,0.35);
            transition: 0.25s;
            width: 100%;
            margin-top: 0.5rem;
            border: none;
            cursor: pointer;
        }
        .btn-wave:hover {
            background: #004bb5;
            transform: translateY(-2px);
            box-shadow: 0 10px 20px rgba(0,102,230,0.4);
        }
        .btn-wave:active { transform: translateY(0); }
        .secure {
            margin-top: 1.5rem;
            font-size: 0.8rem;
            color: #6b7d98;
        }
        .whatsapp-link {
            display: inline-block;
            margin-top: 0.8rem;
            background: #25D366;
            color: white !important;
            padding: 0.7rem 1.5rem;
            border-radius: 60px;
            font-weight: 600;
            text-decoration: none;
            font-size: 0.95rem;
            transition: 0.3s;
            width: 100%;
        }
        .whatsapp-link:hover {
            background: #1da851;
            transform: scale(1.02);
        }
        .footer {
            margin-top: 1.5rem;
            padding-top: 1rem;
            border-top: 1px solid #e4eaf2;
            font-size: 0.7rem;
            color: #8a9bb0;
        }
    </style>
</head>
<body>

<div class="card">
    <div class="logo">🎮</div>
    <h1>Jeux-tuto-ivoire</h1>
    <p class="sub">Accès illimité aux jeux <br />24h/24, 7j/7</p>

    <div class="price">500 FCFA</div>

    <ul class="features">
        <li>Jeux premium sans limite</li>
        <li>Nouveautés chaque semaine</li>
        <li>Support client réactif</li>
    </ul>

    <!-- LIEN WAVE OFFICIEL -->
    <a href="https://pay.wave.com/m/M_ci_ipFvpaqcjLsy/c/ci/?amount=500" class="btn-wave">
        💳 Payer avec Wave
    </a>

    <p class="secure">🔒 Paiement sécurisé via Wave Business</p>

    <!-- BOUTON WHATSAPP AVEC VOTRE NUMÉRO -->
    <a href="https://wa.me/2250150882462" class="whatsapp-link">
        📱 Envoyer la capture sur WhatsApp
    </a>

    <div class="footer">© Jumivoire 2026</div>
</div>

</body>
</html>
