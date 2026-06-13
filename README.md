<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Politique de Confidentialité — Transc100dence</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&family=Playfair+Display:wght@700&display=swap');

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg: #0f0f13;
    --surface: #17171d;
    --border: #2a2a35;
    --accent: #7c5cfc;
    --accent-soft: rgba(124, 92, 252, 0.12);
    --text: #e8e8f0;
    --text-muted: #8888a0;
    --text-dim: #555568;
  }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Inter', sans-serif;
    font-size: 15px;
    line-height: 1.75;
    min-height: 100vh;
  }

  .wrapper {
    max-width: 760px;
    margin: 0 auto;
    padding: 60px 32px 80px;
  }

  /* Header */
  header {
    border-bottom: 1px solid var(--border);
    padding-bottom: 40px;
    margin-bottom: 48px;
    text-align: center;
  }

  .app-badge {
    display: inline-block;
    background: var(--accent-soft);
    border: 1px solid var(--accent);
    color: var(--accent);
    font-size: 11px;
    font-weight: 600;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    padding: 4px 14px;
    border-radius: 20px;
    margin-bottom: 20px;
  }

  h1 {
    font-family: 'Playfair Display', serif;
    font-size: clamp(28px, 5vw, 40px);
    font-weight: 700;
    color: #fff;
    line-height: 1.2;
    margin-bottom: 16px;
  }

  .meta {
    font-size: 13px;
    color: var(--text-muted);
  }

  /* Sections */
  .section {
    margin-bottom: 44px;
  }

  .section-header {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 16px;
  }

  .section-num {
    font-size: 11px;
    font-weight: 600;
    color: var(--accent);
    letter-spacing: 0.1em;
    min-width: 28px;
  }

  h2 {
    font-size: 17px;
    font-weight: 600;
    color: #fff;
    letter-spacing: 0.01em;
  }

  .divider {
    flex: 1;
    height: 1px;
    background: var(--border);
  }

  p {
    text-align: justify;
    color: var(--text);
    margin-bottom: 12px;
  }

  p:last-child { margin-bottom: 0; }

  /* Highlight box */
  .highlight {
    background: var(--accent-soft);
    border-left: 3px solid var(--accent);
    border-radius: 0 8px 8px 0;
    padding: 16px 20px;
    margin: 16px 0;
  }

  .highlight p {
    color: #c8c0f8;
    font-weight: 500;
    margin: 0;
  }

  /* Data list */
  .data-list {
    list-style: none;
    margin: 12px 0;
    padding: 0;
  }

  .data-list li {
    display: flex;
    align-items: flex-start;
    gap: 10px;
    padding: 8px 0;
    border-bottom: 1px solid var(--border);
    color: var(--text);
    font-size: 14px;
  }

  .data-list li:last-child { border-bottom: none; }

  .data-list li::before {
    content: '—';
    color: var(--accent);
    font-weight: 600;
    flex-shrink: 0;
    margin-top: 1px;
  }

  /* Footer */
  footer {
    margin-top: 60px;
    padding-top: 32px;
    border-top: 1px solid var(--border);
    text-align: center;
  }

  .contact-btn {
    display: inline-block;
    background: var(--accent);
    color: #fff;
    text-decoration: none;
    font-size: 14px;
    font-weight: 500;
    padding: 12px 28px;
    border-radius: 8px;
    margin-top: 8px;
    transition: opacity 0.2s;
  }

  .contact-btn:hover { opacity: 0.85; }

  footer p {
    text-align: center;
    color: var(--text-muted);
    font-size: 13px;
    margin-bottom: 12px;
  }

  .legal-note {
    margin-top: 32px;
    font-size: 12px;
    color: var(--text-dim);
    text-align: center;
  }

  @media (max-width: 600px) {
    .wrapper { padding: 40px 20px 60px; }
  }
</style>
</head>
<body>
<div class="wrapper">

  <header>
    <h1>Politique de Confidentialité</h1>
    <p class="meta">Transc100dence &nbsp;·&nbsp; Dernière mise à jour : juin 2026</p>
  </header>

  <!-- 1 -->
  <div class="section">
    <div class="section-header">
      <span class="section-num">01</span>
      <h2>Présentation</h2>
      <div class="divider"></div>
    </div>
    <p>Transc100dence est une application mobile de suivi personnel (semen retention tracker) disponible sur le Google Play Store. La présente politique de confidentialité a pour objet d'informer les utilisateurs de manière transparente sur le traitement — ou l'absence de traitement — de leurs données personnelles.</p>
  </div>

  <!-- 2 -->
  <div class="section">
    <div class="section-header">
      <span class="section-num">02</span>
      <h2>Données collectées</h2>
      <div class="divider"></div>
    </div>
    <div class="highlight">
      <p>Transc100dence ne collecte aucune donnée personnelle. L'application fonctionne intégralement en mode hors ligne (offline).</p>
    </div>
    <p>Toutes les données saisies par l'utilisateur sont stockées exclusivement sur l'appareil local. Aucune information ne transite par un serveur externe ni n'est accessible par les développeurs de l'application.</p>
  </div>

  <!-- 3 -->
  <div class="section">
    <div class="section-header">
      <span class="section-num">03</span>
      <h2>Données stockées localement</h2>
      <div class="divider"></div>
    </div>
    <p>Les éléments suivants peuvent être enregistrés sur votre appareil pour assurer le bon fonctionnement de l'application :</p>
    <ul class="data-list">
      <li>Dates et durées de suivi (streaks)</li>
  <li>Paramètres et préférences de l'application</li>
    </ul>
    <p>Ces données restent sous votre contrôle exclusif et ne quittent jamais votre appareil.</p>
  </div>

  <!-- 4 -->
  <div class="section">
    <div class="section-header">
      <span class="section-num">04</span>
      <h2>Partage de données</h2>
      <div class="divider"></div>
    </div>
    <p>Aucune donnée n'est partagée, vendue, louée ou transmise à des tiers, qu'il s'agisse de partenaires commerciaux, de régies publicitaires ou d'organismes gouvernementaux. Cette absence de partage est structurelle : aucune donnée n'étant collectée, aucune transmission n'est possible.</p>
  </div>

  <!-- 5 -->
  <div class="section">
    <div class="section-header">
      <span class="section-num">05</span>
      <h2>Services tiers et SDK</h2>
      <div class="divider"></div>
    </div>
    <p>L'application n'intègre aucun SDK tiers d'analytique, de publicité ou de suivi comportemental (ex. Firebase Analytics, AdMob, Facebook SDK, Crashlytics, etc.). Aucune bibliothèque externe n'accède à vos données.</p>
  </div>

  <!-- 6 -->
  <div class="section">
    <div class="section-header">
      <span class="section-num">06</span>
      <h2>Permissions Android</h2>
      <div class="divider"></div>
    </div>
    <p>L'application ne demande que les permissions strictement nécessaires à son fonctionnement en mode hors ligne. Aucune permission d'accès réseau (INTERNET) n'est requise ni déclarée dans le manifeste de l'application.</p>
  </div>

  <!-- 7 -->
  <div class="section">
    <div class="section-header">
      <span class="section-num">07</span>
      <h2>Public cible et âge minimum</h2>
      <div class="divider"></div>
    </div>
    <p>Transc100dence est destinée exclusivement aux adultes âgés de <strong style="color:#fff">18 ans et plus</strong>. L'application n'est pas conçue pour, ni destinée à, des enfants de moins de 13 ans. Si vous avez moins de 18 ans, nous vous invitons à ne pas utiliser cette application.</p>
  </div>

  <!-- 8 -->
  <div class="section">
    <div class="section-header">
      <span class="section-num">08</span>
      <h2>Sécurité des données</h2>
      <div class="divider"></div>
    </div>
    <p>Les données étant stockées localement sur votre appareil, leur sécurité dépend directement des mesures de protection de votre terminal Android (verrouillage par code PIN, schéma ou empreinte digitale, chiffrement du stockage activé par défaut sur Android 6.0 et supérieur). Nous vous recommandons de maintenir votre système à jour et de sécuriser l'accès à votre appareil.</p>
  </div>

  <!-- 9 -->
  <div class="section">
    <div class="section-header">
      <span class="section-num">09</span>
      <h2>Suppression des données</h2>
      <div class="divider"></div>
    </div>
    <p>Vous pouvez supprimer l'intégralité de vos données à tout moment en désinstallant l'application depuis votre appareil. Cette action supprime définitivement toutes les données stockées localement. Aucune copie de sauvegarde n'est conservée par nos services.</p>
  </div>

  <!-- 10 -->
  <div class="section">
    <div class="section-header">
      <span class="section-num">10</span>
      <h2>Modifications de la politique</h2>
      <div class="divider"></div>
    </div>
    <p>Toute modification substantielle de la présente politique sera communiquée via une mise à jour de l'application publiée sur le Google Play Store. La date de dernière mise à jour figurant en en-tête de ce document sera actualisée en conséquence. Nous vous encourageons à consulter cette page périodiquement.</p>
  </div>

  <!-- Footer / Contact -->
  <footer>
    <p>Pour toute question relative à cette politique de confidentialité, vous pouvez nous contacter :</p>
    <a class="contact-btn" href="mailto:tenaizyduverger@gmail.com">tenaizyduverger@gmail.com</a>
    <p class="legal-note">© 2026 Transc100dence — Tous droits réservés.</p>
  </footer>

</div>
</body>
</html>
