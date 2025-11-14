<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <title>AI by Elo – IA, contenu & automatisation</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="AI by Elo – IA appliquée au contenu, au marketing et à l’automatisation. Portfolio & services d’Élodie, basée entre Paris et Dubaï." />
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background: #020617;
      color: #e5e7eb;
    }
    a { color: #38bdf8; text-decoration: none; }
    a:hover { text-decoration: underline; }
    header {
      border-bottom: 1px solid #1f2937;
      background: rgba(15,23,42,0.9);
      backdrop-filter: blur(12px);
      position: sticky;
      top: 0;
      z-index: 10;
    }
    .nav {
      max-width: 960px;
      margin: 0 auto;
      padding: 0.75rem 1.5rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-weight: 700;
      letter-spacing: 0.08em;
      text-transform: uppercase;
      font-size: 0.9rem;
    }
    main {
      max-width: 960px;
      margin: 0 auto;
      padding: 3rem 1.5rem 4rem;
    }
    .hero-tag {
      display: inline-block;
      padding: 0.2rem 0.6rem;
      border-radius: 999px;
      background: #0f172a;
      border: 1px solid #1f2937;
      font-size: 0.75rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      margin-bottom: 1rem;
      color: #9ca3af;
    }
    h1 {
      font-size: clamp(2.2rem, 4vw, 3rem);
      margin: 0 0 0.75rem;
    }
    .hero-sub {
      font-size: 1rem;
      max-width: 38rem;
      color: #9ca3af;
      margin-bottom: 1.5rem;
    }
    .hero-badges {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-bottom: 2rem;
    }
    .badge {
      padding: 0.25rem 0.7rem;
      border-radius: 999px;
      border: 1px solid #1f2937;
      font-size: 0.75rem;
      color: #cbd5f5;
      background: #020617;
    }
    .cta-row {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
      margin-bottom: 3rem;
    }
    .btn-primary, .btn-ghost {
      padding: 0.7rem 1.2rem;
      border-radius: 999px;
      font-size: 0.9rem;
      font-weight: 500;
      border: 1px solid transparent;
      cursor: pointer;
      display: inline-flex;
      align-items: center;
      gap: 0.4rem;
    }
