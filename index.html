<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ayush Nayak — Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Sans:ital,wght@0,300;0,400;0,500;1,300&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --ink: #0d0d0d;
      --paper: #f5f0e8;
      --cream: #ede8dc;
      --accent: #c94f2c;
      --accent2: #2c7ac9;
      --muted: #7a7268;
      --border: #ccc5b5;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'DM Sans', sans-serif;
      background: var(--paper);
      color: var(--ink);
      overflow-x: hidden;
      cursor: none;
    }

    /* Custom cursor */
    .cursor {
      width: 10px; height: 10px;
      background: var(--accent);
      border-radius: 50%;
      position: fixed; top: 0; left: 0;
      pointer-events: none;
      z-index: 9999;
      transition: transform 0.15s ease;
      mix-blend-mode: multiply;
    }
    .cursor-ring {
      width: 36px; height: 36px;
      border: 1.5px solid var(--accent);
      border-radius: 50%;
      position: fixed; top: 0; left: 0;
      pointer-events: none;
      z-index: 9998;
      transition: transform 0.35s ease, width 0.2s, height 0.2s;
      mix-blend-mode: multiply;
    }

    /* Noise overlay */
    body::before {
      content: '';
      position: fixed; inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.75' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
      pointer-events: none; z-index: 9000;
      opacity: 0.4;
    }

    /* NAV */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1.6rem 4rem;
      position: sticky; top: 0;
      background: var(--paper);
      border-bottom: 1px solid var(--border);
      z-index: 100;
    }
    .nav-logo {
      font-family: 'Syne', sans-serif;
      font-size: 1.1rem;
      font-weight: 800;
      letter-spacing: 0.04em;
      color: var(--ink);
      text-decoration: none;
    }
    .nav-links { display: flex; gap: 2.4rem; list-style: none; }
    .nav-links a {
      font-size: 0.82rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: var(--muted);
      text-decoration: none;
      transition: color 0.2s;
      font-weight: 500;
    }
    .nav-links a:hover { color: var(--accent); }

    /* HERO */
    .hero {
      min-height: 92vh;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 0;
      position: relative;
      overflow: hidden;
    }
    .hero-left {
      padding: 6rem 3.5rem 6rem 4rem;
      display: flex;
      flex-direction: column;
      justify-content: center;
      position: relative;
    }
    .hero-tag {
      font-size: 0.72rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: var(--accent);
      font-weight: 600;
      margin-bottom: 1.8rem;
      display: flex;
      align-items: center;
      gap: 0.6rem;
      opacity: 0;
      animation: fadeUp 0.7s 0.1s ease forwards;
    }
    .hero-tag::before {
      content: '';
      display: inline-block;
      width: 28px; height: 1.5px;
      background: var(--accent);
    }
    h1 {
      font-family: 'Syne', sans-serif;
      font-size: clamp(3.4rem, 5.5vw, 6.2rem);
      font-weight: 800;
      line-height: 1.0;
      letter-spacing: -0.02em;
      opacity: 0;
      animation: fadeUp 0.8s 0.25s ease forwards;
    }
    h1 span { color: var(--accent); }
    .hero-sub {
      margin-top: 1.8rem;
      font-size: 1.05rem;
      line-height: 1.75;
      color: var(--muted);
      max-width: 380px;
      font-weight: 300;
      opacity: 0;
      animation: fadeUp 0.8s 0.45s ease forwards;
    }
    .hero-badges {
      display: flex;
      gap: 0.7rem;
      flex-wrap: wrap;
      margin-top: 2.4rem;
      opacity: 0;
      animation: fadeUp 0.8s 0.6s ease forwards;
    }
    .badge {
      padding: 0.45rem 1rem;
      border: 1.5px solid var(--border);
      border-radius: 100px;
      font-size: 0.78rem;
      font-weight: 500;
      color: var(--ink);
      letter-spacing: 0.04em;
      background: var(--cream);
    }
    .badge.accent { background: var(--accent); color: white; border-color: var(--accent); }

    .hero-cta {
      margin-top: 3rem;
      display: flex;
      gap: 1rem;
      opacity: 0;
      animation: fadeUp 0.8s 0.75s ease forwards;
    }
    .btn {
      padding: 0.85rem 2.2rem;
      font-family: 'Syne', sans-serif;
      font-size: 0.85rem;
      font-weight: 700;
      letter-spacing: 0.06em;
      text-transform: uppercase;
      text-decoration: none;
      border-radius: 4px;
      transition: all 0.22s ease;
      cursor: none;
    }
    .btn-primary {
      background: var(--ink);
      color: var(--paper);
      border: 2px solid var(--ink);
    }
    .btn-primary:hover { background: var(--accent); border-color: var(--accent); }
    .btn-outline {
      background: transparent;
      color: var(--ink);
      border: 2px solid var(--border);
    }
    .btn-outline:hover { border-color: var(--ink); }

    /* HERO RIGHT - photo */
    .hero-right {
      background: var(--cream);
      border-left: 1px solid var(--border);
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      overflow: hidden;
      opacity: 0;
      animation: fadeIn 1s 0.5s ease forwards;
    }
    .photo-frame {
      width: 320px; height: 400px;
      border-radius: 6px;
      overflow: hidden;
      border: 1px solid var(--border);
      position: relative;
      box-shadow: 12px 12px 0 var(--border);
    }
    .photo-frame img {
      width: 100%; height: 100%;
      object-fit: cover;
      display: block;
    }
    .photo-placeholder {
      width: 100%; height: 100%;
      background: linear-gradient(145deg, #ddd9cf, #c8c2b2);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 0.8rem;
      color: var(--muted);
    }
    .photo-placeholder svg { opacity: 0.4; }
    .photo-placeholder p { font-size: 0.78rem; letter-spacing: 0.06em; text-transform: uppercase; opacity: 0.6; }

    /* deco elements */
    .deco-circle {
      position: absolute;
      border-radius: 50%;
      border: 1px solid var(--border);
    }
    .hero-right .deco-circle:nth-child(2) { width: 500px; height: 500px; top: -120px; right: -140px; }
    .hero-right .deco-circle:nth-child(3) { width: 300px; height: 300px; bottom: -80px; left: -80px; border-style: dashed; }

    .scroll-hint {
      position: absolute;
      bottom: 2.5rem;
      left: 4rem;
      font-size: 0.72rem;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      color: var(--muted);
      display: flex;
      align-items: center;
      gap: 0.6rem;
      opacity: 0;
      animation: fadeUp 1s 1.2s ease forwards;
    }
    .scroll-hint::after {
      content: '';
      display: inline-block;
      width: 1px; height: 40px;
      background: var(--muted);
    }

    /* SECTIONS */
    section {
      padding: 7rem 4rem;
      border-top: 1px solid var(--border);
    }
    .section-label {
      font-size: 0.72rem;
      letter-spacing: 0.18em;
      text-transform: uppercase;
      color: var(--accent);
      font-weight: 600;
      margin-bottom: 3rem;
      display: flex;
      align-items: center;
      gap: 0.8rem;
    }
    .section-label::after {
      content: '';
      flex: 1;
      height: 1px;
      background: var(--border);
    }
    h2 {
      font-family: 'Syne', sans-serif;
      font-size: clamp(2rem, 4vw, 3.4rem);
      font-weight: 800;
      line-height: 1.1;
      letter-spacing: -0.02em;
      margin-bottom: 1.2rem;
    }

    /* ABOUT */
    .about-grid {
      display: grid;
      grid-template-columns: 1.1fr 0.9fr;
      gap: 6rem;
      align-items: start;
      margin-top: 3.5rem;
    }
    .about-text p {
      font-size: 1.05rem;
      line-height: 1.85;
      color: var(--muted);
      font-weight: 300;
      margin-bottom: 1.4rem;
    }
    .about-text p strong { color: var(--ink); font-weight: 500; }
    .info-cards { display: flex; flex-direction: column; gap: 1rem; }
    .info-card {
      padding: 1.4rem 1.6rem;
      background: var(--cream);
      border: 1px solid var(--border);
      border-radius: 6px;
    }
    .info-card-label {
      font-size: 0.68rem;
      letter-spacing: 0.14em;
      text-transform: uppercase;
      color: var(--muted);
      margin-bottom: 0.4rem;
    }
    .info-card-value {
      font-family: 'Syne', sans-serif;
      font-size: 1rem;
      font-weight: 700;
    }

    /* SKILLS */
    .skills-wrap { margin-top: 3.5rem; }
    .skill-group { margin-bottom: 3rem; }
    .skill-group-title {
      font-family: 'Syne', sans-serif;
      font-size: 0.9rem;
      font-weight: 700;
      letter-spacing: 0.06em;
      text-transform: uppercase;
      margin-bottom: 1.2rem;
      color: var(--muted);
    }
    .skill-pills { display: flex; flex-wrap: wrap; gap: 0.6rem; }
    .skill-pill {
      padding: 0.5rem 1.2rem;
      border: 1.5px solid var(--border);
      border-radius: 4px;
      font-size: 0.84rem;
      font-weight: 500;
      transition: all 0.2s;
      background: var(--cream);
    }
    .skill-pill:hover {
      border-color: var(--accent);
      background: var(--accent);
      color: white;
      transform: translateY(-2px);
    }
    .skill-pill.tech { border-color: var(--accent2); }
    .skill-pill.tech:hover { background: var(--accent2); border-color: var(--accent2); }

    /* PROJECTS */
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1.5rem;
      margin-top: 3.5rem;
    }
    .project-card {
      background: var(--cream);
      border: 1px solid var(--border);
      border-radius: 6px;
      padding: 2rem;
      position: relative;
      overflow: hidden;
      transition: transform 0.25s ease, box-shadow 0.25s ease;
    }
    .project-card:hover {
      transform: translateY(-6px);
      box-shadow: 0 20px 40px rgba(0,0,0,0.08);
    }
    .project-num {
      font-family: 'Syne', sans-serif;
      font-size: 3.5rem;
      font-weight: 800;
      color: var(--border);
      line-height: 1;
      margin-bottom: 1.2rem;
    }
    .project-title {
      font-family: 'Syne', sans-serif;
      font-size: 1.1rem;
      font-weight: 700;
      margin-bottom: 0.6rem;
    }
    .project-desc {
      font-size: 0.85rem;
      line-height: 1.7;
      color: var(--muted);
      font-weight: 300;
    }
    .project-tag {
      display: inline-block;
      margin-top: 1.2rem;
      font-size: 0.7rem;
      letter-spacing: 0.1em;
      text-transform: uppercase;
      color: var(--accent);
      font-weight: 600;
    }

    /* CONTACT */
    .contact-inner {
      max-width: 640px;
      margin-top: 3.5rem;
    }
    .contact-inner p {
      font-size: 1.05rem;
      line-height: 1.8;
      color: var(--muted);
      font-weight: 300;
      margin-bottom: 2.5rem;
    }
    .contact-links { display: flex; gap: 1rem; flex-wrap: wrap; }

    /* FOOTER */
    footer {
      padding: 2.5rem 4rem;
      border-top: 1px solid var(--border);
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 0.78rem;
      color: var(--muted);
    }
    footer span { font-family: 'Syne', sans-serif; font-weight: 700; color: var(--ink); }

    /* ANIMATIONS */
    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(24px); }
      to   { opacity: 1; transform: translateY(0); }
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to   { opacity: 1; }
    }

    /* Scroll reveal */
    .reveal {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.7s ease, transform 0.7s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* RESPONSIVE */
    @media (max-width: 900px) {
      nav { padding: 1.4rem 1.8rem; }
      .hero { grid-template-columns: 1fr; min-height: auto; }
      .hero-left { padding: 5rem 1.8rem 3rem; }
      .hero-right { min-height: 340px; border-left: none; border-top: 1px solid var(--border); }
      .photo-frame { width: 220px; height: 280px; }
      section { padding: 5rem 1.8rem; }
      .about-grid { grid-template-columns: 1fr; gap: 3rem; }
      .projects-grid { grid-template-columns: 1fr; }
      footer { flex-direction: column; gap: 0.5rem; text-align: center; }
      .scroll-hint { left: 1.8rem; }
    }
  </style>
</head>
<body>

  <!-- Custom Cursor -->
  <div class="cursor" id="cursor"></div>
  <div class="cursor-ring" id="cursor-ring"></div>

  <!-- NAV -->
  <nav>
    <a class="nav-logo" href="#">AN</a>
    <ul class="nav-links">
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section class="hero" style="border-top:none; padding:0;">
    <div class="hero-left">
      <div class="hero-tag">Portfolio — 2026</div>
      <h1>Ayush<br /><span>Nayak.</span></h1>
      <p class="hero-sub">A passionate BCA student crafting digital experiences, learning the art of code, and building tomorrow's solutions.</p>
      <div class="hero-badges">
        <span class="badge accent">BCA Student</span>
        <span class="badge">Srinath University</span>
        <span class="badge">Developer in Progress</span>
      </div>
      <div class="hero-cta">
        <a href="#projects" class="btn btn-primary">View Projects</a>
        <a href="#contact" class="btn btn-outline">Get in Touch</a>
      </div>
    </div>
    <div class="hero-right">
      <div class="deco-circle"></div>
      <div class="deco-circle"></div>
      <div class="photo-frame">
        <img src="data:image/jpeg;base64,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