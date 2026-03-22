<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SysNet Pro — Administration Systèmes & Réseaux</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@300;400;700&family=Syne:wght@400;600;800&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #080c10;
    --bg2: #0d1218;
    --bg3: #111820;
    --border: #1e2d3d;
    --accent: #00d4ff;
    --accent2: #0066cc;
    --accent3: #00ff88;
    --text: #c8d8e8;
    --text-dim: #5a7a9a;
    --text-bright: #e8f4ff;
    --mono: 'JetBrains Mono', monospace;
    --display: 'Syne', sans-serif;
    --radius: 4px;
    --glow: 0 0 20px rgba(0, 212, 255, 0.15);
  }
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  html { scroll-behavior: smooth; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--mono);
    font-size: 14px;
    line-height: 1.7;
    overflow-x: hidden;
  }
  body::before {
    content: '';
    position: fixed; inset: 0;
    background-image:
      linear-gradient(rgba(0,212,255,0.025) 1px, transparent 1px),
      linear-gradient(90deg, rgba(0,212,255,0.025) 1px, transparent 1px);
    background-size: 40px 40px;
    pointer-events: none; z-index: 0;
  }
  body::after {
    content: '';
    position: fixed; inset: 0;
    background: repeating-linear-gradient(0deg, transparent, transparent 2px, rgba(0,0,0,0.03) 2px, rgba(0,0,0,0.03) 4px);
    pointer-events: none; z-index: 1;
  }

  /* NAV */
  nav {
    position: fixed; top: 0; width: 100%; z-index: 100;
    background: rgba(8,12,16,0.92);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid var(--border);
    padding: 0 2rem;
    display: flex; align-items: center; justify-content: space-between;
    height: 60px;
  }
  .nav-logo {
    font-family: var(--display); font-weight: 800; font-size: 1.1rem;
    color: var(--text-bright); letter-spacing: -0.02em;
    display: flex; align-items: center; gap: 10px; text-decoration: none;
  }
  .nav-logo span { color: var(--accent); }
  .logo-dot {
    width: 8px; height: 8px;
    background: var(--accent3); border-radius: 50%;
    animation: pulse 2s infinite;
  }
  @keyframes pulse {
    0%, 100% { opacity: 1; box-shadow: 0 0 0 0 rgba(0,255,136,0.4); }
    50% { opacity: 0.7; box-shadow: 0 0 0 6px rgba(0,255,136,0); }
  }
  .nav-links { display: flex; gap: 2rem; list-style: none; }
  .nav-links a {
    color: var(--text-dim); text-decoration: none;
    font-size: 12px; letter-spacing: 0.08em; text-transform: uppercase;
    transition: color 0.2s;
  }
  .nav-links a:hover { color: var(--accent); }
  .nav-cta {
    background: transparent; border: 1px solid var(--accent);
    color: var(--accent) !important; padding: 6px 16px;
    border-radius: var(--radius); transition: all 0.2s !important;
  }
  .nav-cta:hover { background: var(--accent) !important; color: var(--bg) !important; }

  /* HERO */
  .hero {
    position: relative; min-height: 100vh;
    display: flex; align-items: center;
    padding: 80px 2rem 4rem; z-index: 2; overflow: hidden;
  }
  .hero-content { max-width: 900px; margin: 0 auto; width: 100%; }
  .hero-tag {
    display: inline-flex; align-items: center; gap: 8px;
    background: rgba(0,212,255,0.08); border: 1px solid rgba(0,212,255,0.2);
    color: var(--accent); font-size: 11px; letter-spacing: 0.12em;
    text-transform: uppercase; padding: 5px 14px; border-radius: 2px;
    margin-bottom: 2rem; animation: fadeUp 0.6s ease both;
  }
  .hero-tag::before { content: '//'; opacity: 0.5; }
  .hero-title {
    font-family: var(--display); font-weight: 800;
    font-size: clamp(2.4rem, 6vw, 4.5rem);
    line-height: 1.05; color: var(--text-bright);
    letter-spacing: -0.03em; margin-bottom: 1.5rem;
    animation: fadeUp 0.6s 0.1s ease both;
  }
  .hero-title em {
    font-style: normal; color: var(--accent); position: relative;
  }
  .hero-title em::after {
    content: ''; position: absolute; bottom: 4px; left: 0; right: 0;
    height: 3px; background: var(--accent); opacity: 0.3; border-radius: 2px;
  }
  .hero-sub {
    font-size: 15px; color: var(--text-dim); max-width: 600px;
    line-height: 1.8; margin-bottom: 2.5rem;
    animation: fadeUp 0.6s 0.2s ease both;
  }
  .hero-stats {
    display: flex; gap: 3rem; margin-bottom: 3rem;
    animation: fadeUp 0.6s 0.3s ease both;
  }
  .stat-item { display: flex; flex-direction: column; gap: 4px; }
  .stat-value {
    font-family: var(--display); font-size: 2rem;
    font-weight: 800; color: var(--text-bright); line-height: 1;
  }
  .stat-label { font-size: 11px; color: var(--text-dim); text-transform: uppercase; letter-spacing: 0.08em; }
  .hero-actions { display: flex; gap: 1rem; animation: fadeUp 0.6s 0.4s ease both; }
  .btn-primary {
    background: var(--accent); color: var(--bg);
    font-family: var(--mono); font-size: 13px; font-weight: 700;
    padding: 14px 28px; border: none; border-radius: var(--radius);
    cursor: pointer; text-decoration: none;
    display: inline-flex; align-items: center; gap: 8px;
    transition: all 0.2s; letter-spacing: 0.02em;
  }
  .btn-primary:hover {
    background: #00b8d9; transform: translateY(-2px);
    box-shadow: 0 8px 30px rgba(0,212,255,0.3);
  }
  .btn-outline {
    background: transparent; color: var(--text);
    font-family: var(--mono); font-size: 13px;
    padding: 14px 28px; border: 1px solid var(--border);
    border-radius: var(--radius); cursor: pointer;
    text-decoration: none; display: inline-flex; align-items: center; gap: 8px;
    transition: all 0.2s;
  }
  .btn-outline:hover { border-color: var(--accent); color: var(--accent); background: rgba(0,212,255,0.05); }

  /* TERMINAL */
  .hero-terminal {
    position: absolute; right: -40px; top: 50%; transform: translateY(-50%);
    width: 460px; background: var(--bg2); border: 1px solid var(--border);
    border-radius: 8px; overflow: hidden;
    box-shadow: 0 30px 80px rgba(0,0,0,0.6), var(--glow);
    animation: fadeUp 0.8s 0.5s ease both; opacity: 0.85;
  }
  .terminal-bar {
    background: var(--bg3); padding: 10px 16px;
    display: flex; align-items: center; gap: 8px;
    border-bottom: 1px solid var(--border);
  }
  .terminal-dot { width: 10px; height: 10px; border-radius: 50%; }
  .td-red { background: #ff5f57; } .td-yellow { background: #ffbd2e; } .td-green { background: #28c840; }
  .terminal-title { font-size: 11px; color: var(--text-dim); margin-left: 6px; }
  .terminal-body { padding: 16px 20px; font-size: 12px; line-height: 2; }
  .t-prompt { color: var(--accent3); } .t-cmd { color: var(--text-bright); }
  .t-out { color: var(--text-dim); } .t-ok { color: var(--accent3); } .t-warn { color: #ffbd2e; }
  .t-cursor {
    display: inline-block; width: 7px; height: 14px;
    background: var(--accent); vertical-align: middle;
    animation: blink 1s step-end infinite;
  }
  @keyframes blink { 0%,100%{opacity:1} 50%{opacity:0} }

  /* SECTIONS */
  section { position: relative; z-index: 2; }
  .section-inner { max-width: 1100px; margin: 0 auto; padding: 6rem 2rem; }
  .section-label {
    font-size: 11px; color: var(--accent); text-transform: uppercase;
    letter-spacing: 0.15em; margin-bottom: 1rem;
    display: flex; align-items: center; gap: 10px;
  }
  .section-label::before { content: ''; display: block; width: 24px; height: 1px; background: var(--accent); }
  .section-title {
    font-family: var(--display); font-size: clamp(1.8rem, 4vw, 2.8rem);
    font-weight: 800; color: var(--text-bright);
    letter-spacing: -0.02em; line-height: 1.15; margin-bottom: 1rem;
  }
  .section-desc { color: var(--text-dim); max-width: 560px; font-size: 14px; line-height: 1.8; margin-bottom: 3rem; }

  /* SERVICES */
  #prestations { background: var(--bg2); border-top: 1px solid var(--border); border-bottom: 1px solid var(--border); }
  .services-grid {
    display: grid; grid-template-columns: repeat(auto-fill, minmax(320px, 1fr));
    gap: 1px; background: var(--border);
    border: 1px solid var(--border); border-radius: 6px; overflow: hidden;
  }
  .service-card {
    background: var(--bg2); padding: 2rem;
    position: relative; transition: background 0.2s; cursor: default;
  }
  .service-card:hover { background: var(--bg3); }
  .service-card::before {
    content: ''; position: absolute; top: 0; left: 0;
    width: 3px; height: 0; background: var(--accent); transition: height 0.3s ease;
  }
  .service-card:hover::before { height: 100%; }
  .service-icon { font-size: 1.6rem; margin-bottom: 1rem; display: block; }
  .service-category { font-size: 10px; text-transform: uppercase; letter-spacing: 0.12em; color: var(--text-dim); margin-bottom: 0.5rem; }
  .service-title { font-family: var(--display); font-size: 1rem; font-weight: 600; color: var(--text-bright); margin-bottom: 0.8rem; }
  .service-desc { font-size: 12px; color: var(--text-dim); line-height: 1.7; margin-bottom: 1rem; }
  .service-tags { display: flex; flex-wrap: wrap; gap: 6px; }
  .tag { font-size: 10px; padding: 3px 8px; border-radius: 2px; border: 1px solid var(--border); color: var(--text-dim); letter-spacing: 0.05em; }

  /* PROCESS */
  .process-steps { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; margin-top: 3rem; }
  .step { position: relative; padding-left: 1.5rem; border-left: 1px solid var(--border); }
  .step-num {
    position: absolute; left: -14px; top: 0;
    width: 28px; height: 28px; background: var(--bg);
    border: 1px solid var(--accent); color: var(--accent);
    font-size: 11px; font-weight: 700;
    display: flex; align-items: center; justify-content: center; border-radius: 2px;
  }
  .step-title { font-family: var(--display); font-size: 0.95rem; font-weight: 600; color: var(--text-bright); margin-bottom: 0.5rem; margin-top: 4px; padding-left: 1rem; }
  .step-desc { font-size: 12px; color: var(--text-dim); padding-left: 1rem; line-height: 1.7; }

  /* CONTACT */
  #contact { background: var(--bg); }
  .contact-grid { display: grid; grid-template-columns: 1fr 1.3fr; gap: 4rem; align-items: start; }
  .contact-info h3 { font-family: var(--display); font-size: 1.1rem; font-weight: 600; color: var(--text-bright); margin-bottom: 1rem; }
  .contact-info p { color: var(--text-dim); font-size: 13px; line-height: 1.8; margin-bottom: 2rem; }
  .contact-detail { display: flex; align-items: center; gap: 12px; padding: 12px 0; border-bottom: 1px solid var(--border); font-size: 13px; color: var(--text); }
  .contact-detail-icon { font-size: 1.1rem; width: 32px; }

  /* FORM */
  .form-card { background: var(--bg2); border: 1px solid var(--border); border-radius: 6px; padding: 2.5rem; }
  .form-title { font-family: var(--display); font-size: 1.2rem; font-weight: 700; color: var(--text-bright); margin-bottom: 0.5rem; }
  .form-subtitle { font-size: 12px; color: var(--text-dim); margin-bottom: 2rem; }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
  .form-group { display: flex; flex-direction: column; gap: 6px; margin-bottom: 1.2rem; }
  .form-group label { font-size: 11px; text-transform: uppercase; letter-spacing: 0.08em; color: var(--text-dim); }
  .form-group input, .form-group select, .form-group textarea {
    background: var(--bg); border: 1px solid var(--border);
    color: var(--text); font-family: var(--mono); font-size: 13px;
    padding: 10px 14px; border-radius: var(--radius); outline: none;
    transition: border-color 0.2s; width: 100%;
  }
  .form-group input::placeholder, .form-group textarea::placeholder { color: var(--text-dim); opacity: 0.5; }
  .form-group input:focus, .form-group select:focus, .form-group textarea:focus {
    border-color: var(--accent); box-shadow: 0 0 0 3px rgba(0,212,255,0.08);
  }
  .form-group select option { background: var(--bg2); }
  .form-group textarea { resize: vertical; min-height: 100px; }
  .form-checkboxes { display: grid; grid-template-columns: 1fr 1fr; gap: 8px; margin-bottom: 1.5rem; }
  .checkbox-item { display: flex; align-items: center; gap: 8px; font-size: 12px; color: var(--text); cursor: pointer; }
  .checkbox-item input[type="checkbox"] { width: 16px; height: 16px; accent-color: var(--accent); cursor: pointer; }
  .form-submit {
    width: 100%; background: var(--accent); color: var(--bg);
    font-family: var(--mono); font-size: 13px; font-weight: 700;
    padding: 14px; border: none; border-radius: var(--radius);
    cursor: pointer; letter-spacing: 0.04em; transition: all 0.2s;
  }
  .form-submit:hover { background: #00b8d9; transform: translateY(-1px); box-shadow: 0 6px 20px rgba(0,212,255,0.25); }
  .form-success { display: none; text-align: center; padding: 2rem; }
  .form-success .success-icon { font-size: 3rem; margin-bottom: 1rem; }
  .form-success h3 { font-family: var(--display); color: var(--accent3); margin-bottom: 0.5rem; }
  .form-success p { color: var(--text-dim); font-size: 13px; }

  /* FOOTER */
  footer {
    position: relative; z-index: 2;
    border-top: 1px solid var(--border); background: var(--bg2);
    padding: 2rem; display: flex; align-items: center;
    justify-content: space-between; flex-wrap: wrap; gap: 1rem;
  }
  .footer-left { font-size: 12px; color: var(--text-dim); }
  .footer-left strong { color: var(--text); }
  .footer-right { font-size: 11px; color: var(--text-dim); }
  .footer-right span { color: var(--accent3); }

  @keyframes fadeUp { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }

  @media (max-width: 900px) {
    .hero-terminal { display: none; }
    .hero-stats { gap: 2rem; }
    .contact-grid { grid-template-columns: 1fr; }
    .form-row { grid-template-columns: 1fr; }
    .form-checkboxes { grid-template-columns: 1fr; }
    .nav-links { display: none; }
  }
  ::-webkit-scrollbar { width: 6px; }
  ::-webkit-scrollbar-track { background: var(--bg); }
  ::-webkit-scrollbar-thumb { background: var(--border); border-radius: 3px; }
  ::-webkit-scrollbar-thumb:hover { background: var(--accent2); }
</style>
</head>
<body>

<nav>
  <a href="#" class="nav-logo">
    <div class="logo-dot"></div>
    Sys<span>Net</span>Pro
  </a>
  <ul class="nav-links">
    <li><a href="#prestations">Prestations</a></li>
    <li><a href="#processus">Processus</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#contact" class="nav-cta">Demander un devis</a></li>
  </ul>
</nav>

<section class="hero">
  <div class="hero-content">
    <div class="hero-tag">Administrateur Systèmes & Réseaux</div>
    <h1 class="hero-title">
      Votre infrastructure,<br>
      entre <em>de bonnes mains</em>
    </h1>
    <p class="hero-sub">
      Expert en administration systèmes Linux/Windows et architectures réseau.
      Je prends en charge la conception, la sécurisation et la maintenance
      de vos infrastructures IT — en toute autonomie.
    </p>
    <div class="hero-stats">
      <div class="stat-item">
        <span class="stat-value">24/7</span>
        <span class="stat-label">Disponibilité</span>
      </div>
      <div class="stat-item">
        <span class="stat-value">100%</span>
        <span class="stat-label">Engagement</span>
      </div>
      <div class="stat-item">
        <span class="stat-value">CDI+</span>
        <span class="stat-label">Expérience terrain</span>
      </div>
    </div>
    <div class="hero-actions">
      <a href="#contact" class="btn-primary">→ Demander un devis</a>
      <a href="#prestations" class="btn-outline">Voir les prestations</a>
    </div>
  </div>

  <div class="hero-terminal">
    <div class="terminal-bar">
      <div class="terminal-dot td-red"></div>
      <div class="terminal-dot td-yellow"></div>
      <div class="terminal-dot td-green"></div>
      <span class="terminal-title">admin@sysnetpro ~ </span>
    </div>
    <div class="terminal-body">
      <div><span class="t-prompt">❯</span> <span class="t-cmd">ping 192.168.1.1</span></div>
      <div class="t-ok">64 bytes from gateway: icmp_seq=1 ttl=64</div>
      <div class="t-ok">64 bytes from gateway: icmp_seq=2 ttl=64</div>
      <br>
      <div><span class="t-prompt">❯</span> <span class="t-cmd">systemctl status nginx</span></div>
      <div class="t-ok">● nginx.service — Active: active (running)</div>
      <br>
      <div><span class="t-prompt">❯</span> <span class="t-cmd">check-backup --last</span></div>
      <div class="t-out">→ Backup completed: 2026-03-22 02:00</div>
      <div class="t-ok">✓ All systems nominal</div>
      <br>
      <div><span class="t-prompt">❯</span> <span class="t-cmd">Get-ADUser -Filter * | Measure</span></div>
      <div class="t-out">Count : 247 users synced</div>
      <br>
      <div><span class="t-prompt">❯</span> <span class="t-cmd">scan-vuln --target all</span></div>
      <div class="t-warn">⚠ 3 patches pending — scheduling...</div>
      <div class="t-ok">✓ No critical CVE detected</div>
      <br>
      <div><span class="t-prompt">❯</span> <span class="t-cursor"></span></div>
    </div>
  </div>
</section>

<section id="prestations">
  <div class="section-inner">
    <div class="section-label">Expertises</div>
    <h2 class="section-title">Mes prestations</h2>
    <p class="section-desc">Un spectre complet de services IT — de l'infrastructure au poste utilisateur, en passant par la sécurité et l'automatisation.</p>

    <div class="services-grid">

      <div class="service-card">
        <span class="service-icon">🪟</span>
        <div class="service-category">Systèmes</div>
        <div class="service-title">Administration Windows Server</div>
        <p class="service-desc">Installation, configuration et maintenance de serveurs Windows. Gestion des rôles AD, DNS, DHCP, GPO, RDS, WSUS et plus encore.</p>
        <div class="service-tags">
          <span class="tag">Windows Server 2019/2022</span><span class="tag">Active Directory</span><span class="tag">GPO</span><span class="tag">WSUS</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">🐧</span>
        <div class="service-category">Systèmes</div>
        <div class="service-title">Administration Linux</div>
        <p class="service-desc">Déploiement et administration de serveurs Linux. Services web, bases de données, messagerie et sécurisation système.</p>
        <div class="service-tags">
          <span class="tag">Debian/Ubuntu</span><span class="tag">RHEL/CentOS</span><span class="tag">Nginx/Apache</span><span class="tag">Shell scripting</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">⚙️</span>
        <div class="service-category">Infrastructure</div>
        <div class="service-title">Virtualisation</div>
        <p class="service-desc">Mise en place et gestion de plateformes de virtualisation. Optimisation des ressources et haute disponibilité.</p>
        <div class="service-tags">
          <span class="tag">VMware vSphere/ESXi</span><span class="tag">Hyper-V</span><span class="tag">Proxmox</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">🌐</span>
        <div class="service-category">Réseau</div>
        <div class="service-title">Architecture & Configuration Réseau</div>
        <p class="service-desc">Conception et déploiement d'architectures réseau LAN/WAN. Configuration de switches, routeurs et équipements actifs.</p>
        <div class="service-tags">
          <span class="tag">Cisco IOS</span><span class="tag">VLANs</span><span class="tag">OSPF/BGP</span><span class="tag">QoS</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">🔒</span>
        <div class="service-category">Sécurité</div>
        <div class="service-title">Firewall & Sécurité périmétrique</div>
        <p class="service-desc">Configuration et maintien de pare-feu. Segmentation réseau, filtrage applicatif et politiques de sécurité adaptées.</p>
        <div class="service-tags">
          <span class="tag">pfSense/OPNsense</span><span class="tag">FortiGate</span><span class="tag">Cisco ASA</span><span class="tag">iptables</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">🔐</span>
        <div class="service-category">Réseau / Sécurité</div>
        <div class="service-title">VPN & Accès distant</div>
        <p class="service-desc">Mise en place de solutions VPN site-à-site et nomade pour sécuriser les accès distants de vos collaborateurs.</p>
        <div class="service-tags">
          <span class="tag">OpenVPN</span><span class="tag">WireGuard</span><span class="tag">IPSec</span><span class="tag">SSL-VPN</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">💾</span>
        <div class="service-category">Continuité</div>
        <div class="service-title">Sauvegarde & Plan de reprise</div>
        <p class="service-desc">Conception et mise en œuvre de stratégies de sauvegarde (règle 3-2-1). Tests de restauration et documentation PRA/PCA.</p>
        <div class="service-tags">
          <span class="tag">Veeam Backup</span><span class="tag">Bacula</span><span class="tag">rsync</span><span class="tag">PRA/PCA</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">☁️</span>
        <div class="service-category">Cloud</div>
        <div class="service-title">Cloud & Infrastructure hybride</div>
        <p class="service-desc">Migration, déploiement et administration de services cloud. Architectures hybrides on-premise/cloud adaptées à votre budget.</p>
        <div class="service-tags">
          <span class="tag">Microsoft Azure</span><span class="tag">AWS</span><span class="tag">Office 365</span><span class="tag">Azure AD</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">📊</span>
        <div class="service-category">Supervision</div>
        <div class="service-title">Monitoring & Supervision</div>
        <p class="service-desc">Déploiement de solutions de supervision pour anticiper les pannes. Tableaux de bord, alertes et rapports de disponibilité.</p>
        <div class="service-tags">
          <span class="tag">Zabbix</span><span class="tag">Nagios/Centreon</span><span class="tag">Grafana</span><span class="tag">PRTG</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">🤖</span>
        <div class="service-category">Automatisation</div>
        <div class="service-title">Automatisation & Scripting</div>
        <p class="service-desc">Automatisation de tâches répétitives et déploiement d'infrastructures. Scripts et outils DevOps adaptés à votre environnement.</p>
        <div class="service-tags">
          <span class="tag">PowerShell</span><span class="tag">Bash</span><span class="tag">Ansible</span><span class="tag">Python</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">📧</span>
        <div class="service-category">Collaboration</div>
        <div class="service-title">Messagerie & Collaboration</div>
        <p class="service-desc">Administration de serveurs de messagerie et plateformes collaboratives. Migration, sécurisation et anti-spam.</p>
        <div class="service-tags">
          <span class="tag">Exchange</span><span class="tag">Office 365</span><span class="tag">Postfix</span><span class="tag">Zimbra</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">🛡️</span>
        <div class="service-category">Sécurité</div>
        <div class="service-title">Audit & Cybersécurité</div>
        <p class="service-desc">Audit de sécurité, analyse des risques, recommandations et mise en conformité. Sensibilisation des équipes.</p>
        <div class="service-tags">
          <span class="tag">Audit SI</span><span class="tag">ANSSI / ISO 27001</span><span class="tag">RGPD</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">🎧</span>
        <div class="service-category">Support</div>
        <div class="service-title">Support & Helpdesk N2/N3</div>
        <p class="service-desc">Prise en charge des incidents complexes, résolution et documentation. Intervention sur site ou à distance selon vos besoins.</p>
        <div class="service-tags">
          <span class="tag">GLPI</span><span class="tag">TeamViewer</span><span class="tag">RDP</span><span class="tag">Astreinte</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">📡</span>
        <div class="service-category">Réseau</div>
        <div class="service-title">Infrastructure Wi-Fi entreprise</div>
        <p class="service-desc">Audit, conception et déploiement d'infrastructures Wi-Fi. Couverture optimisée, sécurité WPA3 et authentification 802.1X.</p>
        <div class="service-tags">
          <span class="tag">Ubiquiti UniFi</span><span class="tag">Cisco Meraki</span><span class="tag">802.1X / RADIUS</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">📞</span>
        <div class="service-category">Téléphonie</div>
        <div class="service-title">Téléphonie IP (ToIP / VoIP)</div>
        <p class="service-desc">Mise en place et administration de systèmes de téléphonie sur IP. Migration PABX vers IPBX, trunk SIP et postes IP.</p>
        <div class="service-tags">
          <span class="tag">Asterisk</span><span class="tag">FreePBX</span><span class="tag">3CX</span><span class="tag">SIP/RTP</span>
        </div>
      </div>

      <div class="service-card">
        <span class="service-icon">🐳</span>
        <div class="service-category">DevOps / Infra</div>
        <div class="service-title">Conteneurisation & DevOps</div>
        <p class="service-desc">Déploiement et gestion d'applications conteneurisées. Pipelines CI/CD et environnements reproductibles.</p>
        <div class="service-tags">
          <span class="tag">Docker</span><span class="tag">Docker Compose</span><span class="tag">Kubernetes</span><span class="tag">GitLab CI</span>
        </div>
      </div>

    </div>
  </div>
</section>

<section id="processus">
  <div class="section-inner">
    <div class="section-label">Comment ça marche</div>
    <h2 class="section-title">Un processus clair<br>du devis à la livraison</h2>
    <p class="section-desc">Chaque mission commence par une analyse de vos besoins. Voici comment je travaille.</p>
    <div class="process-steps">
      <div class="step">
        <div class="step-num">01</div>
        <div class="step-title">Prise de contact</div>
        <p class="step-desc">Vous décrivez votre besoin via le formulaire. Je vous réponds sous 24h pour fixer un échange.</p>
      </div>
      <div class="step">
        <div class="step-num">02</div>
        <div class="step-title">Analyse & audit</div>
        <p class="step-desc">J'audite votre infrastructure existante et identifie les points d'amélioration prioritaires.</p>
      </div>
      <div class="step">
        <div class="step-num">03</div>
        <div class="step-title">Devis détaillé</div>
        <p class="step-desc">Vous recevez un devis transparent avec le périmètre exact, le délai et le tarif.</p>
      </div>
      <div class="step">
        <div class="step-num">04</div>
        <div class="step-title">Exécution</div>
        <p class="step-desc">Je réalise la mission avec un reporting régulier. Intervention sur site ou à distance.</p>
      </div>
      <div class="step">
        <div class="step-num">05</div>
        <div class="step-title">Livraison & suivi</div>
        <p class="step-desc">Documentation complète livrée. Suivi post-mission inclus pour assurer la stabilité.</p>
      </div>
    </div>
  </div>
</section>

<section id="contact">
  <div class="section-inner">
    <div class="section-label">Contact</div>
    <h2 class="section-title">Parlons de votre projet</h2>
    <div class="contact-grid">
      <div class="contact-info">
        <h3>Besoin d'un expert IT ?</h3>
        <p>Que ce soit pour un projet ponctuel, une mission longue durée ou un contrat de maintenance, je vous propose une solution adaptée à votre contexte et votre budget.</p>
        <p>Interventions en région Centre-Val de Loire et à distance partout en France.</p>
        <div class="contact-detail"><span class="contact-detail-icon">📧</span><span>contact@sysnetpro.fr</span></div>
        <div class="contact-detail"><span class="contact-detail-icon">📞</span><span>+33 6 XX XX XX XX</span></div>
        <div class="contact-detail"><span class="contact-detail-icon">📍</span><span>Châteauroux — Déplacements France entière</span></div>
        <div class="contact-detail"><span class="contact-detail-icon">⏱️</span><span>Réponse sous 24h ouvrées</span></div>
      </div>

      <div class="form-card">
        <div class="form-title">Demande de devis</div>
        <div class="form-subtitle">// Remplissez ce formulaire — je vous recontacte rapidement</div>
        <form id="quoteForm" onsubmit="submitForm(event)">
          <div class="form-row">
            <div class="form-group"><label>Prénom *</label><input type="text" placeholder="Jean" required></div>
            <div class="form-group"><label>Nom *</label><input type="text" placeholder="Dupont" required></div>
          </div>
          <div class="form-group"><label>Email *</label><input type="email" placeholder="jean.dupont@entreprise.fr" required></div>
          <div class="form-row">
            <div class="form-group"><label>Société</label><input type="text" placeholder="Mon Entreprise SARL"></div>
            <div class="form-group"><label>Téléphone</label><input type="tel" placeholder="+33 6 XX XX XX XX"></div>
          </div>
          <div class="form-group">
            <label>Type de prestation *</label>
            <select required>
              <option value="" disabled selected>-- Sélectionnez une prestation --</option>
              <option>Administration Windows Server / Active Directory</option>
              <option>Administration Linux</option>
              <option>Virtualisation (VMware / Hyper-V / Proxmox)</option>
              <option>Architecture & Configuration Réseau</option>
              <option>Firewall & Sécurité périmétrique</option>
              <option>VPN & Accès distant</option>
              <option>Sauvegarde & Plan de reprise (PRA/PCA)</option>
              <option>Cloud & Infrastructure hybride</option>
              <option>Monitoring & Supervision</option>
              <option>Automatisation & Scripting</option>
              <option>Messagerie & Collaboration</option>
              <option>Audit & Cybersécurité</option>
              <option>Support & Helpdesk N2/N3</option>
              <option>Infrastructure Wi-Fi entreprise</option>
              <option>Téléphonie IP (ToIP/VoIP)</option>
              <option>Conteneurisation & DevOps</option>
              <option>Autre / Multiple prestations</option>
            </select>
          </div>
          <div class="form-group"><label>Type d'intervention</label></div>
          <div class="form-checkboxes">
            <label class="checkbox-item"><input type="checkbox"> Mission ponctuelle</label>
            <label class="checkbox-item"><input type="checkbox"> Contrat de maintenance</label>
            <label class="checkbox-item"><input type="checkbox"> Intervention sur site</label>
            <label class="checkbox-item"><input type="checkbox"> Télémaintenance</label>
          </div>
          <div class="form-group">
            <label>Décrivez votre besoin *</label>
            <textarea placeholder="Décrivez votre infrastructure actuelle, le problème rencontré ou le projet à réaliser..." required></textarea>
          </div>
          <button type="submit" class="form-submit">→ Envoyer la demande de devis</button>
        </form>
        <div class="form-success" id="formSuccess">
          <div class="success-icon">✅</div>
          <h3>Demande envoyée !</h3>
          <p>Je vous recontacte sous 24h ouvrées. Merci pour votre confiance.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<footer>
  <div class="footer-left">
    <strong>SysNetPro</strong> — Administration Systèmes & Réseaux<br>
    Micro-entreprise · SIRET : XXXXXXXX · © 2026
  </div>
  <div class="footer-right">Fait avec <span>♥</span> & beaucoup de café ☕</div>
</footer>

<script>
  function submitForm(e) {
    e.preventDefault();
    document.getElementById('quoteForm').style.display = 'none';
    document.getElementById('formSuccess').style.display = 'block';
  }
  const obs = new IntersectionObserver((entries) => {
    entries.forEach(e => {
      if (e.isIntersecting) e.target.style.animation = 'fadeUp 0.5s ease both';
    });
  }, { threshold: 0.1 });
  document.querySelectorAll('.service-card, .step').forEach(el => obs.observe(el));
</script>
</body>
</html>
