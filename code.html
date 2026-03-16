<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DS Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=Space+Mono:ital,wght@0,400;0,700;1,400&family=Outfit:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --bg: #0a0a0f;
    --surface: #111118;
    --surface2: #1a1a26;
    --border: #2a2a3d;
    --accent: #7c6aff;
    --accent2: #ff6a9e;
    --accent3: #6affd4;
    --text: #e8e8f0;
    --muted: #7a7a9a;
    --card: #13131e;
    --glow: rgba(124,106,255,0.15);
  }
  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }
  html { scroll-behavior: smooth; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: 'Outfit', sans-serif;
    font-weight: 400;
    font-size: 17px;
    overflow-x: hidden;
    cursor: none;
  }

  /* CURSOR */
  #cursor { position: fixed; width:14px; height:14px; background:var(--accent); border-radius:50%; pointer-events:none; z-index:99999; transform:translate(-50%,-50%); transition: width 0.2s, height 0.2s, background 0.2s; mix-blend-mode: exclusion; }
  #cursor-ring { position:fixed; width:40px; height:40px; border:1px solid rgba(124,106,255,0.5); border-radius:50%; pointer-events:none; z-index:99998; transform:translate(-50%,-50%); transition: all 0.12s ease; }

  /* NOISE OVERLAY */
  body::before {
    content:''; position:fixed; inset:0; pointer-events:none; z-index:9999;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.035'/%3E%3C/svg%3E");
    opacity: 0.4;
  }

  /* NAV */
  nav {
    position: fixed; top:0; left:0; right:0; z-index:1000;
    display:flex; align-items:center; justify-content:space-between;
    padding: 20px 60px;
    border-bottom: 1px solid rgba(42,42,61,0.5);
    background: rgba(10,10,15,0.85);
    backdrop-filter: blur(20px);
  }
  .nav-logo { font-family:'DM Serif Display', serif; font-size:1.5rem; color:var(--accent); letter-spacing:-0.02em; }
  .nav-links { display:flex; gap:32px; align-items:center; }
  .nav-links a { color:var(--muted); text-decoration:none; font-size:0.92rem; letter-spacing:0.08em; text-transform:uppercase; transition:color 0.2s; }
  .nav-links a:hover { color:var(--text); }
  .admin-btn {
    background: transparent;
    border: 1px solid var(--accent);
    color: var(--accent);
    padding: 9px 22px;
    font-family:'Space Mono', monospace;
    font-size:0.82rem;
    cursor: none;
    transition: all 0.2s;
    letter-spacing: 0.05em;
  }
  .admin-btn:hover { background:var(--accent); color:#fff; }

  /* HERO */
  #hero {
    min-height: 100vh;
    display: flex; align-items: center;
    padding: 120px 60px 80px;
    position: relative;
    overflow: hidden;
  }
  .hero-grid {
    position:absolute; inset:0; pointer-events:none; opacity:0.06;
    background-image: linear-gradient(rgba(124,106,255,0.8) 1px, transparent 1px),
                      linear-gradient(90deg, rgba(124,106,255,0.8) 1px, transparent 1px);
    background-size: 60px 60px;
  }
  .hero-orb1 { position:absolute; width:600px; height:600px; border-radius:50%; background: radial-gradient(circle, rgba(124,106,255,0.12) 0%, transparent 70%); top:-100px; right:-100px; pointer-events:none; animation: drift1 8s ease-in-out infinite; }
  .hero-orb2 { position:absolute; width:400px; height:400px; border-radius:50%; background: radial-gradient(circle, rgba(106,255,212,0.08) 0%, transparent 70%); bottom:-50px; left:200px; pointer-events:none; animation: drift2 10s ease-in-out infinite; }
  @keyframes drift1 { 0%,100%{transform:translate(0,0)} 50%{transform:translate(-20px,30px)} }
  @keyframes drift2 { 0%,100%{transform:translate(0,0)} 50%{transform:translate(20px,-20px)} }

  .hero-content { position:relative; max-width:900px; }
  .hero-tag { font-family:'Space Mono', monospace; font-size:0.85rem; color:var(--accent3); letter-spacing:0.15em; text-transform:uppercase; margin-bottom:24px; display:flex; align-items:center; gap:12px; }
  .hero-tag::before { content:''; width:40px; height:1px; background:var(--accent3); }
  .hero-name { font-family:'DM Serif Display', serif; font-size: clamp(3.2rem, 8vw, 7.5rem); line-height:0.95; letter-spacing:-0.03em; margin-bottom:16px; }
  .hero-name span { color:var(--accent); font-style:italic; }
  .hero-title { font-family:'Space Mono', monospace; font-size:clamp(0.95rem, 1.6vw, 1.1rem); color:var(--muted); margin-bottom:32px; letter-spacing:0.05em; }
  .hero-bio { font-size:1.2rem; line-height:1.9; color: rgba(232,232,240,0.82); max-width:620px; margin-bottom:48px; }
  .hero-actions { display:flex; gap:16px; flex-wrap:wrap; }
  .btn-primary { background:var(--accent); color:#fff; border:none; padding:15px 34px; font-family:'Space Mono', monospace; font-size:0.88rem; cursor:none; transition:all 0.2s; letter-spacing:0.05em; position:relative; overflow:hidden; }
  .btn-primary::after { content:''; position:absolute; inset:0; background:linear-gradient(90deg, transparent, rgba(255,255,255,0.1), transparent); transform:translateX(-100%); transition:transform 0.4s; }
  .btn-primary:hover::after { transform:translateX(100%); }
  .btn-outline { background:transparent; color:var(--text); border:1px solid var(--border); padding:15px 34px; font-family:'Space Mono', monospace; font-size:0.88rem; cursor:none; transition:all 0.2s; letter-spacing:0.05em; }
  .btn-outline:hover { border-color:var(--accent); color:var(--accent); }
  .hero-stats { display:flex; gap:48px; margin-top:64px; padding-top:48px; border-top:1px solid var(--border); }
  .stat-num { font-family:'DM Serif Display', serif; font-size:2.8rem; color:var(--accent); }
  .stat-label { font-size:0.88rem; color:var(--muted); letter-spacing:0.08em; text-transform:uppercase; margin-top:4px; }

  /* SECTIONS */
  section { padding: 100px 60px; }
  .section-header { margin-bottom:60px; display:flex; align-items:baseline; gap:24px; }
  .section-num { font-family:'Space Mono', monospace; font-size:0.85rem; color:var(--accent); }
  .section-title { font-family:'DM Serif Display', serif; font-size: clamp(2.2rem, 4vw, 3.2rem); }
  .section-line { flex:1; height:1px; background: linear-gradient(90deg, var(--border), transparent); }

  /* ABOUT */
  #about { background: var(--surface); }
  .about-grid { display:grid; grid-template-columns:1fr 1fr; gap:80px; align-items:start; }
  .about-img-wrap { position:relative; }
  .about-img-placeholder {
    width:100%; aspect-ratio:3/4; background:var(--surface2);
    border:1px solid var(--border);
    display:flex; flex-direction:column; align-items:center; justify-content:center;
    gap:12px; color:var(--muted); font-size:0.85rem; position:relative; overflow:hidden;
  }
  .about-img-placeholder img { width:100%; height:100%; object-fit:cover; position:absolute; inset:0; }
  .img-overlay { position:absolute; inset:0; background:linear-gradient(to top, rgba(10,10,15,0.8) 0%, transparent 50%); }
  .about-img-placeholder .upload-hint { position:relative; z-index:2; text-align:center; }
  .about-text h3 { font-family:'DM Serif Display', serif; font-size:2rem; margin-bottom:24px; }
  .about-text p { color:rgba(232,232,240,0.82); line-height:2; margin-bottom:20px; font-size:1.05rem; }
  .skills-wrap { margin-top:40px; }
  .skills-label { font-family:'Space Mono', monospace; font-size:0.78rem; color:var(--accent3); letter-spacing:0.15em; text-transform:uppercase; margin-bottom:16px; }
  .skills-grid { display:flex; flex-wrap:wrap; gap:8px; }
  .skill-tag { background:var(--surface2); border:1px solid var(--border); color:var(--text); padding:7px 16px; font-size:0.88rem; font-family:'Space Mono', monospace; transition:all 0.2s; }
  .skill-tag:hover { border-color:var(--accent); color:var(--accent); }

  /* PROJECTS */
  .projects-grid { display:grid; grid-template-columns: repeat(auto-fill, minmax(340px, 1fr)); gap:1px; background:var(--border); }
  .project-card {
    background: var(--card);
    padding: 40px;
    transition: all 0.3s;
    position:relative;
    overflow:hidden;
  }
  .project-card::before { content:''; position:absolute; top:0; left:0; right:0; height:2px; background:linear-gradient(90deg, var(--accent), var(--accent2)); transform:scaleX(0); transform-origin:left; transition:transform 0.3s; }
  .project-card:hover { background:var(--surface2); }
  .project-card:hover::before { transform:scaleX(1); }
  .project-tag { font-family:'Space Mono', monospace; font-size:0.72rem; color:var(--accent3); letter-spacing:0.12em; text-transform:uppercase; margin-bottom:16px; }
  .project-title { font-family:'DM Serif Display', serif; font-size:1.65rem; margin-bottom:12px; line-height:1.2; }
  .project-desc { font-size:1rem; color:var(--muted); line-height:1.8; margin-bottom:24px; }
  .project-tech { display:flex; flex-wrap:wrap; gap:6px; margin-bottom:24px; }
  .tech-pill { background:rgba(124,106,255,0.1); border:1px solid rgba(124,106,255,0.2); color:var(--accent); padding:4px 12px; font-size:0.78rem; font-family:'Space Mono', monospace; }
  .project-links { display:flex; gap:16px; }
  .project-links a { font-family:'Space Mono', monospace; font-size:0.72rem; color:var(--muted); text-decoration:none; letter-spacing:0.05em; transition:color 0.2s; display:flex; align-items:center; gap:6px; }
  .project-links a:hover { color:var(--text); }
  .project-img { width:100%; height:180px; object-fit:cover; margin-bottom:24px; background:var(--surface2); display:block; }

  /* CERTIFICATIONS */
  #certifications { background: var(--surface); }
  .certs-grid { display:grid; grid-template-columns: repeat(auto-fill, minmax(280px, 1fr)); gap:24px; }
  .cert-card {
    background:var(--card);
    border:1px solid var(--border);
    padding:32px;
    transition:all 0.3s;
    position:relative;
  }
  .cert-card:hover { border-color:var(--accent); transform:translateY(-4px); }
  .cert-logo { width:48px; height:48px; background:var(--surface2); border:1px solid var(--border); display:flex; align-items:center; justify-content:center; margin-bottom:20px; font-size:1.5rem; }
  .cert-issuer { font-family:'Space Mono', monospace; font-size:0.78rem; color:var(--accent3); letter-spacing:0.12em; text-transform:uppercase; margin-bottom:8px; }
  .cert-name { font-size:1.05rem; font-weight:500; margin-bottom:8px; line-height:1.4; }
  .cert-date { font-family:'Space Mono', monospace; font-size:0.8rem; color:var(--muted); margin-bottom:16px; }
  .cert-link { font-family:'Space Mono', monospace; font-size:0.8rem; color:var(--accent); text-decoration:none; letter-spacing:0.05em; }
  .cert-link:hover { text-decoration:underline; }
  .cert-badge { position:absolute; top:20px; right:20px; background:rgba(106,255,212,0.1); border:1px solid rgba(106,255,212,0.3); color:var(--accent3); font-family:'Space Mono', monospace; font-size:0.65rem; padding:3px 8px; letter-spacing:0.08em; }

  /* EXPERIENCE */
  .timeline { position:relative; padding-left:40px; }
  .timeline::before { content:''; position:absolute; left:0; top:0; bottom:0; width:1px; background:linear-gradient(to bottom, var(--accent), var(--border)); }
  .timeline-item { position:relative; margin-bottom:56px; }
  .timeline-dot { position:absolute; left:-46px; top:4px; width:12px; height:12px; background:var(--accent); border-radius:50%; box-shadow:0 0 20px var(--accent); }
  .timeline-date { font-family:'Space Mono', monospace; font-size:0.82rem; color:var(--accent3); letter-spacing:0.1em; margin-bottom:8px; }
  .timeline-role { font-family:'DM Serif Display', serif; font-size:1.6rem; margin-bottom:4px; }
  .timeline-company { font-size:1rem; color:var(--muted); margin-bottom:16px; }
  .timeline-desc { font-size:1rem; color:rgba(232,232,240,0.78); line-height:1.9; }
  .timeline-tags { display:flex; flex-wrap:wrap; gap:6px; margin-top:16px; }

  /* CONTACT */
  #contact { background:var(--surface); }
  .contact-grid { display:grid; grid-template-columns:1fr 1fr; gap:80px; }
  .contact-info h3 { font-family:'DM Serif Display', serif; font-size:2.1rem; margin-bottom:20px; }
  .contact-info p { color:var(--muted); line-height:1.9; margin-bottom:32px; font-size:1.05rem; }
  .contact-links { display:flex; flex-direction:column; gap:16px; }
  .contact-link { display:flex; align-items:center; gap:16px; padding:18px 22px; background:var(--card); border:1px solid var(--border); text-decoration:none; color:var(--text); transition:all 0.2s; font-size:1rem; }
  .contact-link:hover { border-color:var(--accent); background:rgba(124,106,255,0.05); }
  .contact-link-icon { width:36px; height:36px; background:rgba(124,106,255,0.15); display:flex; align-items:center; justify-content:center; font-size:1.1rem; flex-shrink:0; }
  .contact-link-label { font-family:'Space Mono', monospace; font-size:0.75rem; color:var(--muted); }

  /* BOOKS */
  #books { background: var(--bg); }
  .books-grid { display:grid; grid-template-columns: repeat(auto-fill, minmax(200px, 1fr)); gap:24px; }
  .book-card {
    background: var(--card);
    border: 1px solid var(--border);
    transition: all 0.3s;
    position: relative;
    overflow: hidden;
    cursor: default;
  }
  .book-card:hover { border-color: var(--accent); transform: translateY(-6px); box-shadow: 0 20px 40px rgba(0,0,0,0.4); }
  .book-cover {
    width: 100%; aspect-ratio: 2/3; background: var(--surface2);
    display: flex; align-items: center; justify-content: center;
    font-size: 3rem; position: relative; overflow: hidden;
  }
  .book-cover img { width:100%; height:100%; object-fit:cover; position:absolute; inset:0; }
  .book-cover-placeholder { position:relative; z-index:1; text-align:center; }
  .book-spine { position:absolute; left:0; top:0; bottom:0; width:6px; background: linear-gradient(to bottom, var(--accent), var(--accent2)); }
  .book-info { padding: 16px; }
  .book-title { font-family:'DM Serif Display', serif; font-size:1.1rem; margin-bottom:4px; line-height:1.3; }
  .book-author { font-family:'Space Mono', monospace; font-size:0.75rem; color:var(--muted); margin-bottom:10px; }
  .book-status { display:inline-block; font-family:'Space Mono', monospace; font-size:0.68rem; letter-spacing:0.08em; padding:3px 8px; }
  .book-status.reading { background:rgba(124,106,255,0.12); border:1px solid rgba(124,106,255,0.3); color:var(--accent); }
  .book-status.read { background:rgba(106,255,212,0.1); border:1px solid rgba(106,255,212,0.3); color:var(--accent3); }
  .book-status.wishlist { background:rgba(255,106,158,0.1); border:1px solid rgba(255,106,158,0.3); color:var(--accent2); }
  .book-rating { display:flex; gap:2px; margin-top:8px; font-size:0.85rem; }
  .book-note { font-size:0.9rem; color:rgba(232,232,240,0.65); line-height:1.7; margin-top:8px; font-style:italic; }
  .books-filter { display:flex; gap:8px; flex-wrap:wrap; margin-bottom:32px; }
  .filter-btn { background:transparent; border:1px solid var(--border); color:var(--muted); padding:6px 16px; font-family:'Space Mono', monospace; font-size:0.68rem; cursor:none; transition:all 0.2s; letter-spacing:0.05em; }
  .filter-btn.active, .filter-btn:hover { border-color:var(--accent); color:var(--accent); background:rgba(124,106,255,0.08); }

  /* FORGOT PASSWORD */
  #forgot-modal { display:none; }
  .forgot-link { font-family:'Space Mono', monospace; font-size:0.68rem; color:var(--muted); background:none; border:none; cursor:none; text-decoration:underline; margin-top:12px; display:block; text-align:center; transition:color 0.2s; }
  .forgot-link:hover { color:var(--accent); }
  .security-q { font-family:'Space Mono', monospace; font-size:0.72rem; color:var(--accent3); margin-bottom:16px; padding:12px; background:rgba(106,255,212,0.05); border:1px solid rgba(106,255,212,0.15); }

  /* FOOTER */
  footer { padding:40px 60px; border-top:1px solid var(--border); display:flex; justify-content:space-between; align-items:center; }
  .footer-text { font-family:'Space Mono', monospace; font-size:0.72rem; color:var(--muted); }

  /* ===== ADMIN PANEL ===== */
  #admin-overlay {
    position:fixed; inset:0; z-index:10000;
    background:rgba(0,0,0,0.7); backdrop-filter:blur(8px);
    display:none; align-items:center; justify-content:center;
  }
  #admin-overlay.open { display:flex; }

  /* LOGIN MODAL */
  #login-modal {
    background:var(--surface);
    border:1px solid var(--border);
    padding:48px;
    width:100%; max-width:400px;
    position:relative;
  }
  .modal-close { position:absolute; top:16px; right:16px; background:none; border:none; color:var(--muted); font-size:1.2rem; cursor:none; }
  .modal-close:hover { color:var(--text); }
  .login-title { font-family:'DM Serif Display', serif; font-size:1.8rem; margin-bottom:8px; }
  .login-sub { font-family:'Space Mono', monospace; font-size:0.72rem; color:var(--accent); margin-bottom:32px; }
  .form-group { margin-bottom:20px; }
  .form-group label { display:block; font-family:'Space Mono', monospace; font-size:0.7rem; color:var(--muted); letter-spacing:0.1em; text-transform:uppercase; margin-bottom:8px; }
  .form-control { width:100%; background:var(--bg); border:1px solid var(--border); color:var(--text); padding:12px 16px; font-family:'Outfit', sans-serif; font-size:0.9rem; outline:none; transition:border-color 0.2s; }
  .form-control:focus { border-color:var(--accent); }
  .login-error { color:var(--accent2); font-family:'Space Mono', monospace; font-size:0.72rem; margin-bottom:16px; display:none; }

  /* ADMIN PANEL */
  #admin-panel {
    background:var(--bg);
    width:100%; max-width:900px;
    max-height:90vh;
    overflow-y:auto;
    position:relative;
    border:1px solid var(--border);
    display:none;
  }
  #admin-panel::-webkit-scrollbar { width:4px; }
  #admin-panel::-webkit-scrollbar-track { background:var(--bg); }
  #admin-panel::-webkit-scrollbar-thumb { background:var(--border); }

  .panel-header { padding:24px 32px; border-bottom:1px solid var(--border); display:flex; align-items:center; justify-content:space-between; position:sticky; top:0; background:var(--bg); z-index:10; }
  .panel-title { font-family:'DM Serif Display', serif; font-size:1.5rem; }
  .panel-tabs { display:flex; gap:0; border-bottom:1px solid var(--border); overflow-x:auto; }
  .panel-tab { padding:14px 24px; font-family:'Space Mono', monospace; font-size:0.72rem; color:var(--muted); background:none; border:none; cursor:none; letter-spacing:0.08em; text-transform:uppercase; transition:all 0.2s; border-bottom:2px solid transparent; white-space:nowrap; }
  .panel-tab.active { color:var(--accent); border-bottom-color:var(--accent); }
  .panel-tab:hover { color:var(--text); }
  .panel-body { padding:32px; }
  .tab-section { display:none; }
  .tab-section.active { display:block; }

  /* ADMIN FORM */
  .admin-form-row { display:grid; grid-template-columns:1fr 1fr; gap:16px; }
  .item-list { display:flex; flex-direction:column; gap:12px; margin-bottom:32px; }
  .item-card {
    background:var(--surface);
    border:1px solid var(--border);
    padding:20px 24px;
    display:flex; align-items:center; justify-content:space-between;
    gap:16px;
  }
  .item-card-info { flex:1; min-width:0; }
  .item-card-title { font-weight:500; font-size:0.95rem; margin-bottom:4px; white-space:nowrap; overflow:hidden; text-overflow:ellipsis; }
  .item-card-sub { font-size:0.8rem; color:var(--muted); font-family:'Space Mono', monospace; }
  .item-actions { display:flex; gap:8px; flex-shrink:0; }
  .btn-edit { background:rgba(124,106,255,0.1); border:1px solid rgba(124,106,255,0.3); color:var(--accent); padding:6px 14px; font-family:'Space Mono', monospace; font-size:0.68rem; cursor:none; transition:all 0.2s; }
  .btn-edit:hover { background:rgba(124,106,255,0.2); }
  .btn-delete { background:rgba(255,106,158,0.1); border:1px solid rgba(255,106,158,0.3); color:var(--accent2); padding:6px 14px; font-family:'Space Mono', monospace; font-size:0.68rem; cursor:none; transition:all 0.2s; }
  .btn-delete:hover { background:rgba(255,106,158,0.2); }
  .add-form { background:var(--surface); border:1px solid var(--border); padding:24px; }
  .add-form-title { font-family:'Space Mono', monospace; font-size:0.72rem; color:var(--accent3); letter-spacing:0.12em; text-transform:uppercase; margin-bottom:20px; }
  .btn-add { background:var(--accent3); color:#0a0a0f; border:none; padding:10px 24px; font-family:'Space Mono', monospace; font-size:0.75rem; cursor:none; font-weight:700; letter-spacing:0.05em; transition:all 0.2s; margin-top:16px; }
  .btn-add:hover { opacity:0.85; }
  .btn-save { background:var(--accent); color:#fff; border:none; padding:10px 24px; font-family:'Space Mono', monospace; font-size:0.75rem; cursor:none; letter-spacing:0.05em; transition:all 0.2s; margin-top:16px; }
  .btn-save:hover { opacity:0.85; }
  .section-divider { height:1px; background:var(--border); margin:32px 0; }
  .profile-preview { width:100px; height:100px; background:var(--surface2); border:2px solid var(--border); border-radius:50%; overflow:hidden; display:flex; align-items:center; justify-content:center; font-size:2.5rem; margin-bottom:16px; }
  .profile-preview img { width:100%; height:100%; object-fit:cover; }
  textarea.form-control { resize:vertical; min-height:80px; }
  .color-row { display:flex; gap:12px; flex-wrap:wrap; margin-bottom:16px; }
  .color-btn { width:36px; height:36px; border:2px solid transparent; cursor:none; border-radius:4px; transition:all 0.2s; }
  .color-btn.active { border-color:white; transform:scale(1.15); }
  .theme-label { font-family:'Space Mono', monospace; font-size:0.7rem; color:var(--muted); margin-bottom:8px; }
  .success-toast { position:fixed; bottom:32px; right:32px; background:var(--accent3); color:#0a0a0f; padding:14px 24px; font-family:'Space Mono', monospace; font-size:0.75rem; z-index:99999; transform:translateY(80px); opacity:0; transition:all 0.3s; pointer-events:none; }
  .success-toast.show { transform:translateY(0); opacity:1; }

  /* RESPONSIVE */
  @media (max-width:768px) {
    nav { padding:16px 20px; }
    section { padding:60px 20px; }
    #hero { padding:100px 20px 60px; }
    .about-grid, .contact-grid { grid-template-columns:1fr; }
    .hero-stats { flex-wrap:wrap; gap:24px; }
    .admin-form-row { grid-template-columns:1fr; }
    .panel-body { padding:20px; }
    footer { flex-direction:column; gap:16px; text-align:center; }
    .nav-links { display:none; }
  }

  /* ANIMATIONS */
  .fade-up { opacity:0; transform:translateY(30px); transition:opacity 0.6s, transform 0.6s; }
  .fade-up.visible { opacity:1; transform:translateY(0); }
</style>
</head>
<body>

<!-- CUSTOM CURSOR -->
<div id="cursor"></div>
<div id="cursor-ring"></div>

<!-- SUCCESS TOAST -->
<div class="success-toast" id="toast">✓ Changes saved</div>

<!-- NAV -->
<nav>
  <div class="nav-logo" id="nav-logo">Portfolio</div>
  <div class="nav-links">
    <a href="#about">About</a>
    <a href="#projects">Projects</a>
    <a href="#certifications">Certs</a>
    <a href="#experience">Experience</a>
    <a href="#books">Books</a>
    <a href="#contact">Contact</a>
  </div>
  <button class="admin-btn" onclick="openAdmin()">⚙ Admin</button>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-grid"></div>
  <div class="hero-orb1"></div>
  <div class="hero-orb2"></div>
  <div class="hero-content">
    <div class="hero-tag" id="hero-tag">Aspiring Data Scientist &amp; ML Enthusiast</div>
    <h1 class="hero-name">
      <span id="hero-firstname">Nikhilesh</span><br>
      <span id="hero-lastname">Mewara</span>
    </h1>
    <div class="hero-title" id="hero-subtitle">// Learning, building, and growing — one dataset at a time</div>
    <p class="hero-bio" id="hero-bio">I'm passionate about turning data into meaningful stories. Currently deepening my skills in machine learning, statistics, and data engineering — building projects that solve real problems and showcase what data can do.</p>
    <div class="hero-actions">
      <button class="btn-primary" id="hero-cta1" onclick="scrollTo(document.getElementById('projects'))">View Projects</button>
      <button class="btn-outline" id="hero-cta2" onclick="scrollTo(document.getElementById('contact'))">Get in Touch</button>
    </div>
    <div class="hero-stats">
      <div><div class="stat-num" id="stat1-num">5+</div><div class="stat-label" id="stat1-label">Projects Built</div></div>
      <div><div class="stat-num" id="stat2-num">3+</div><div class="stat-label" id="stat2-label">Certifications</div></div>
      <div><div class="stat-num" id="stat3-num">∞</div><div class="stat-label" id="stat3-label">Curiosity</div></div>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="section-header fade-up">
    <span class="section-num">01</span>
    <h2 class="section-title">About Me</h2>
    <div class="section-line"></div>
  </div>
  <div class="about-grid">
    <div class="about-img-wrap fade-up">
      <div class="about-img-placeholder" id="about-img-container">
        <img id="about-img" src="" alt="" style="display:none;">
        <div class="img-overlay"></div>
        <div class="upload-hint">
          <div style="font-size:3rem;margin-bottom:8px;">👤</div>
          <div>Photo appears here</div>
        </div>
      </div>
    </div>
    <div class="about-text fade-up">
      <h3 id="about-heading">Curious about data,<br><em>driven to learn.</em></h3>
      <p id="about-p1">I'm an aspiring data scientist with a strong foundation in Python, statistics, and machine learning fundamentals. I enjoy exploring datasets, building models, and learning how data can drive smarter decisions.</p>
      <p id="about-p2">When I'm not working on projects, I'm taking online courses, reading about new ML techniques, and participating in Kaggle competitions to sharpen my skills.</p>
      <div class="skills-wrap">
        <div class="skills-label">Core Skills</div>
        <div class="skills-grid" id="skills-container"></div>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects" style="background:var(--bg);">
  <div class="section-header fade-up">
    <span class="section-num">02</span>
    <h2 class="section-title">Projects</h2>
    <div class="section-line"></div>
  </div>
  <div class="projects-grid" id="projects-container"></div>
</section>

<!-- CERTIFICATIONS -->
<section id="certifications">
  <div class="section-header fade-up">
    <span class="section-num">03</span>
    <h2 class="section-title">Certifications</h2>
    <div class="section-line"></div>
  </div>
  <div class="certs-grid" id="certs-container"></div>
</section>

<!-- EXPERIENCE -->
<section id="experience" style="background:var(--bg);">
  <div class="section-header fade-up">
    <span class="section-num">04</span>
    <h2 class="section-title">Experience</h2>
    <div class="section-line"></div>
  </div>
  <div class="timeline" id="experience-container"></div>
</section>

<!-- BOOKS -->
<section id="books">
  <div class="section-header fade-up">
    <span class="section-num">05</span>
    <h2 class="section-title">Reading List</h2>
    <div class="section-line"></div>
  </div>
  <div class="books-filter" id="books-filter">
    <button class="filter-btn active" onclick="filterBooks('all', this)">All</button>
    <button class="filter-btn" onclick="filterBooks('reading', this)">Currently Reading</button>
    <button class="filter-btn" onclick="filterBooks('read', this)">Read</button>
    <button class="filter-btn" onclick="filterBooks('wishlist', this)">Wishlist</button>
  </div>
  <div class="books-grid" id="books-container"></div>
</section>

<!-- CONTACT -->
<section id="contact" style="background:var(--surface);">
  <div class="section-header fade-up">
    <span class="section-num">06</span>
    <h2 class="section-title">Contact</h2>
    <div class="section-line"></div>
  </div>
  <div class="contact-grid">
    <div class="contact-info fade-up">
      <h3 id="contact-heading">Let's <em style="color:var(--accent)">connect</em> and grow together.</h3>
      <p id="contact-desc">I'm actively looking for internship opportunities, collaborations on data projects, and mentorship. Always happy to connect with fellow learners and professionals!</p>
      <div class="contact-links" id="contact-links-container"></div>
    </div>
    <div class="fade-up" style="display:flex;align-items:center;justify-content:center;">
      <div style="font-family:'DM Serif Display',serif; font-size:6rem; opacity:0.05; line-height:1; text-align:center;">&lt;/&gt;</div>
    </div>
  </div>
</section>

<footer>
  <div class="footer-text" id="footer-text">© 2026 Nikhilesh Mewara — Aspiring Data Scientist</div>
  <div class="footer-text">Built with passion & precision</div>
</footer>

<!-- ===== ADMIN OVERLAY ===== -->
<div id="admin-overlay">
  <!-- LOGIN -->
  <div id="login-modal">
    <button class="modal-close" onclick="closeAdmin()">✕</button>
    <div class="login-title">Admin Access</div>
    <div class="login-sub">// Portfolio Control Panel</div>
    <div class="form-group">
      <label>Password</label>
      <input type="password" class="form-control" id="admin-password" placeholder="Enter admin password" onkeyup="if(event.key==='Enter')doLogin()">
    </div>
    <div class="login-error" id="login-error">Incorrect password.</div>
    <button class="btn-primary" style="width:100%;text-align:center;" onclick="doLogin()">Access Panel</button>
    <button class="forgot-link" onclick="showForgot()">Forgot password?</button>
  </div>

  <!-- FORGOT PASSWORD -->
  <div id="forgot-modal" style="background:var(--surface);border:1px solid var(--border);padding:48px;width:100%;max-width:420px;position:relative;">
    <button class="modal-close" onclick="closeForgot()">✕</button>
    <div class="login-title">Reset Password</div>
    <div class="login-sub">// Answer the security question</div>
    <div class="security-q" id="security-question-display">What is the default admin password of this portfolio?</div>
    <div class="form-group">
      <label>Your Answer</label>
      <input type="text" class="form-control" id="forgot-answer" placeholder="Type your answer..." onkeyup="if(event.key==='Enter')checkForgotAnswer()">
    </div>
    <div class="login-error" id="forgot-error" style="display:none;">Wrong answer. Hint: it's the original default password.</div>
    <button class="btn-primary" style="width:100%;text-align:center;margin-bottom:12px;" onclick="checkForgotAnswer()">Verify Answer</button>
    <button class="forgot-link" onclick="closeForgot()">← Back to Login</button>
  </div>

  <!-- RESET PASSWORD (shown after correct answer) -->
  <div id="reset-modal" style="background:var(--surface);border:1px solid var(--border);padding:48px;width:100%;max-width:420px;position:relative;display:none;">
    <div class="login-title">New Password</div>
    <div class="login-sub">// Set your new admin password</div>
    <div class="form-group">
      <label>New Password</label>
      <input type="password" class="form-control" id="reset-new-pass" placeholder="Enter new password">
    </div>
    <div class="form-group">
      <label>Confirm Password</label>
      <input type="password" class="form-control" id="reset-confirm-pass" placeholder="Confirm new password">
    </div>
    <div class="login-error" id="reset-error" style="display:none;">Passwords do not match.</div>
    <button class="btn-primary" style="width:100%;text-align:center;" onclick="doResetPassword()">Set New Password</button>
  </div>

  <!-- PANEL -->
  <div id="admin-panel">
    <div class="panel-header">
      <div class="panel-title">Admin Panel</div>
      <div style="display:flex;gap:12px;align-items:center;">
        <span style="font-family:'Space Mono',monospace;font-size:0.68rem;color:var(--accent3);">● LIVE EDITING</span>
        <button class="modal-close" style="position:static;" onclick="closeAdmin()">✕</button>
      </div>
    </div>
    <div class="panel-tabs">
      <button class="panel-tab active" onclick="switchTab('profile')">Profile</button>
      <button class="panel-tab" onclick="switchTab('hero')">Hero</button>
      <button class="panel-tab" onclick="switchTab('skills')">Skills</button>
      <button class="panel-tab" onclick="switchTab('projects')">Projects</button>
      <button class="panel-tab" onclick="switchTab('certifications')">Certs</button>
      <button class="panel-tab" onclick="switchTab('experience')">Experience</button>
      <button class="panel-tab" onclick="switchTab('contact')">Contact</button>
      <button class="panel-tab" onclick="switchTab('books')">Books</button>
      <button class="panel-tab" onclick="switchTab('theme')">Theme</button>
    </div>
    <div class="panel-body">

      <!-- PROFILE TAB -->
      <div class="tab-section active" id="tab-profile">
        <div class="add-form-title">Personal Information</div>
        <div style="display:flex;align-items:flex-start;gap:24px;margin-bottom:24px;flex-wrap:wrap;">
          <div style="display:flex;flex-direction:column;align-items:center;gap:12px;">
            <div class="profile-preview"><img id="profile-img-preview" src="" alt="" style="display:none;"><span id="profile-emoji">👤</span></div>
            <label id="upload-label" style="background:var(--accent3);color:#0a0a0f;border:none;padding:8px 18px;font-family:'Space Mono',monospace;font-size:0.72rem;cursor:pointer;font-weight:700;letter-spacing:0.05em;transition:opacity 0.2s;display:inline-block;" onmouseover="this.style.opacity=0.85" onmouseout="this.style.opacity=1">
              📁 Choose Photo
              <input type="file" id="photo-file-input" accept="image/*" style="display:none;" onchange="handlePhotoUpload(this)">
            </label>
            <div id="upload-filename" style="font-family:'Space Mono',monospace;font-size:0.65rem;color:var(--muted);text-align:center;max-width:120px;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;"></div>
          </div>
          <div style="flex:1;min-width:220px;">
            <div style="font-family:'Space Mono',monospace;font-size:0.7rem;color:var(--muted);letter-spacing:0.1em;text-transform:uppercase;margin-bottom:8px;">OR PASTE IMAGE URL</div>
            <input type="text" class="form-control" id="p-photo" placeholder="https://..." oninput="previewProfilePhoto(this.value)">
            <div style="font-family:'Space Mono',monospace;font-size:0.65rem;color:var(--muted);margin-top:8px;line-height:1.6;">
              Upload from device <em>or</em> paste a URL from<br>Imgur, LinkedIn, GitHub, etc.
            </div>
          </div>
        </div>
        <div class="admin-form-row">
          <div class="form-group"><label>First Name</label><input type="text" class="form-control" id="p-firstname" value="Nikhilesh"></div>
          <div class="form-group"><label>Last Name</label><input type="text" class="form-control" id="p-lastname" value="Mewara"></div>
        </div>
        <div class="form-group"><label>Role / Tagline</label><input type="text" class="form-control" id="p-role" value="Aspiring Data Scientist &amp; ML Enthusiast"></div>
        <div class="form-group"><label>Subtitle Line</label><input type="text" class="form-control" id="p-subtitle" value="// Learning, building, and growing — one dataset at a time"></div>
        <div class="form-group"><label>Bio (Hero)</label><textarea class="form-control" id="p-bio">I'm passionate about turning data into meaningful stories. Currently deepening my skills in machine learning, statistics, and data engineering — building projects that solve real problems and showcase what data can do.</textarea></div>
        <div class="section-divider"></div>
        <div class="add-form-title">About Section</div>
        <div class="form-group"><label>About Heading</label><input type="text" class="form-control" id="p-about-heading" value="Curious about data, driven to learn."></div>
        <div class="form-group"><label>About Paragraph 1</label><textarea class="form-control" id="p-about-p1">I'm an aspiring data scientist with a strong foundation in Python, statistics, and machine learning fundamentals. I enjoy exploring datasets, building models, and learning how data can drive smarter decisions.</textarea></div>
        <div class="form-group"><label>About Paragraph 2</label><textarea class="form-control" id="p-about-p2">When I'm not working on projects, I'm taking online courses, reading about new ML techniques, and participating in Kaggle competitions to sharpen my skills.</textarea></div>
        <div class="section-divider"></div>
        <div class="add-form-title">Stats</div>
        <div class="admin-form-row">
          <div class="form-group"><label>Stat 1 Number</label><input type="text" class="form-control" id="p-stat1n" value="5+"></div>
          <div class="form-group"><label>Stat 1 Label</label><input type="text" class="form-control" id="p-stat1l" value="Projects Built"></div>
        </div>
        <div class="admin-form-row">
          <div class="form-group"><label>Stat 2 Number</label><input type="text" class="form-control" id="p-stat2n" value="3+"></div>
          <div class="form-group"><label>Stat 2 Label</label><input type="text" class="form-control" id="p-stat2l" value="Certifications"></div>
        </div>
        <div class="admin-form-row">
          <div class="form-group"><label>Stat 3 Number</label><input type="text" class="form-control" id="p-stat3n" value="∞"></div>
          <div class="form-group"><label>Stat 3 Label</label><input type="text" class="form-control" id="p-stat3l" value="Curiosity"></div>
        </div>
        <button class="btn-save" onclick="saveProfile()">Save Profile</button>
      </div>

      <!-- HERO TAB -->
      <div class="tab-section" id="tab-hero">
        <div class="add-form-title">Hero Section Text</div>
        <div class="form-group"><label>Hero CTA Button 1 Text</label><input type="text" class="form-control" id="h-cta1" value="View Projects"></div>
        <div class="form-group"><label>Hero CTA Button 2 Text</label><input type="text" class="form-control" id="h-cta2" value="Get in Touch"></div>
        <div class="form-group"><label>Footer Text</label><input type="text" class="form-control" id="h-footer" value="© 2026 Nikhilesh Mewara — Aspiring Data Scientist"></div>
        <button class="btn-save" onclick="saveHero()">Save Hero</button>
      </div>

      <!-- SKILLS TAB -->
      <div class="tab-section" id="tab-skills">
        <div class="add-form-title">Current Skills</div>
        <div class="item-list" id="skills-admin-list"></div>
        <div class="add-form">
          <div class="add-form-title">Add Skill</div>
          <div class="form-group"><label>Skill Name</label><input type="text" class="form-control" id="new-skill" placeholder="e.g. TensorFlow, Python, SQL..."></div>
          <button class="btn-add" onclick="addSkill()">+ Add Skill</button>
        </div>
      </div>

      <!-- PROJECTS TAB -->
      <div class="tab-section" id="tab-projects">
        <div class="add-form-title">Current Projects</div>
        <div class="item-list" id="projects-admin-list"></div>
        <div class="add-form">
          <div class="add-form-title">Add / Edit Project</div>
          <input type="hidden" id="edit-project-id" value="">
          <div class="admin-form-row">
            <div class="form-group"><label>Title</label><input type="text" class="form-control" id="proj-title" placeholder="Project Title"></div>
            <div class="form-group"><label>Category Tag</label><input type="text" class="form-control" id="proj-tag" placeholder="e.g. NLP / Computer Vision"></div>
          </div>
          <div class="form-group"><label>Description</label><textarea class="form-control" id="proj-desc" placeholder="What this project does..."></textarea></div>
          <div class="form-group"><label>Technologies (comma separated)</label><input type="text" class="form-control" id="proj-tech" placeholder="Python, TensorFlow, scikit-learn"></div>
          <div class="admin-form-row">
            <div class="form-group"><label>GitHub URL</label><input type="text" class="form-control" id="proj-github" placeholder="https://github.com/..."></div>
            <div class="form-group"><label>Demo URL</label><input type="text" class="form-control" id="proj-demo" placeholder="https://demo.com/..."></div>
          </div>
          <div class="form-group"><label>Image URL (optional)</label><input type="text" class="form-control" id="proj-img" placeholder="https://..."></div>
          <button class="btn-add" onclick="saveProject()">+ Save Project</button>
        </div>
      </div>

      <!-- CERTIFICATIONS TAB -->
      <div class="tab-section" id="tab-certifications">
        <div class="add-form-title">Current Certifications</div>
        <div class="item-list" id="certs-admin-list"></div>
        <div class="add-form">
          <div class="add-form-title">Add / Edit Certification</div>
          <input type="hidden" id="edit-cert-id" value="">
          <div class="admin-form-row">
            <div class="form-group"><label>Certification Name</label><input type="text" class="form-control" id="cert-name" placeholder="e.g. AWS ML Specialty"></div>
            <div class="form-group"><label>Issuing Organization</label><input type="text" class="form-control" id="cert-issuer" placeholder="e.g. Amazon Web Services"></div>
          </div>
          <div class="admin-form-row">
            <div class="form-group"><label>Date</label><input type="text" class="form-control" id="cert-date" placeholder="e.g. Nov 2023"></div>
            <div class="form-group"><label>Badge Emoji</label><input type="text" class="form-control" id="cert-emoji" placeholder="🏆"></div>
          </div>
          <div class="form-group"><label>Credential URL</label><input type="text" class="form-control" id="cert-url" placeholder="https://..."></div>
          <button class="btn-add" onclick="saveCert()">+ Save Certification</button>
        </div>
      </div>

      <!-- EXPERIENCE TAB -->
      <div class="tab-section" id="tab-experience">
        <div class="add-form-title">Work Experience</div>
        <div class="item-list" id="exp-admin-list"></div>
        <div class="add-form">
          <div class="add-form-title">Add / Edit Experience</div>
          <input type="hidden" id="edit-exp-id" value="">
          <div class="admin-form-row">
            <div class="form-group"><label>Role / Title</label><input type="text" class="form-control" id="exp-role" placeholder="e.g. Senior Data Scientist"></div>
            <div class="form-group"><label>Company</label><input type="text" class="form-control" id="exp-company" placeholder="e.g. Google"></div>
          </div>
          <div class="form-group"><label>Duration</label><input type="text" class="form-control" id="exp-date" placeholder="e.g. Jan 2022 — Present"></div>
          <div class="form-group"><label>Description</label><textarea class="form-control" id="exp-desc" placeholder="What you did..."></textarea></div>
          <div class="form-group"><label>Skills Used (comma separated)</label><input type="text" class="form-control" id="exp-skills" placeholder="Python, PyTorch, AWS"></div>
          <button class="btn-add" onclick="saveExp()">+ Save Experience</button>
        </div>
      </div>

      <!-- CONTACT TAB -->
      <div class="tab-section" id="tab-contact">
        <div class="add-form-title">Contact Info</div>
        <div class="form-group"><label>Section Heading</label><input type="text" class="form-control" id="c-heading" value="Let's connect and grow together."></div>
        <div class="form-group"><label>Section Description</label><textarea class="form-control" id="c-desc">I'm actively looking for internship opportunities, collaborations on data projects, and mentorship. Always happy to connect with fellow learners and professionals!</textarea></div>
        <div class="section-divider"></div>
        <div class="add-form-title">Contact Links</div>
        <div class="item-list" id="contact-admin-list"></div>
        <div class="add-form">
          <div class="add-form-title">Add Contact Link</div>
          <div class="admin-form-row">
            <div class="form-group"><label>Label</label><input type="text" class="form-control" id="cl-label" placeholder="e.g. LinkedIn"></div>
            <div class="form-group"><label>Value / Handle</label><input type="text" class="form-control" id="cl-value" placeholder="e.g. linkedin.com/in/..."></div>
          </div>
          <div class="admin-form-row">
            <div class="form-group"><label>URL</label><input type="text" class="form-control" id="cl-url" placeholder="https://..."></div>
            <div class="form-group"><label>Icon (emoji)</label><input type="text" class="form-control" id="cl-icon" placeholder="💼"></div>
          </div>
          <button class="btn-add" onclick="saveContactLink()">+ Add Link</button>
        </div>
        <button class="btn-save" style="margin-top:24px;" onclick="saveContact()">Save Contact</button>
      </div>

      <!-- BOOKS TAB -->
      <div class="tab-section" id="tab-books">
        <div class="add-form-title">Book Collection</div>
        <div class="item-list" id="books-admin-list"></div>
        <div class="add-form">
          <div class="add-form-title">Add / Edit Book</div>
          <input type="hidden" id="edit-book-id" value="">
          <div class="admin-form-row">
            <div class="form-group"><label>Title</label><input type="text" class="form-control" id="book-title" placeholder="Book Title"></div>
            <div class="form-group"><label>Author</label><input type="text" class="form-control" id="book-author" placeholder="Author Name"></div>
          </div>
          <div class="admin-form-row">
            <div class="form-group">
              <label>Status</label>
              <select class="form-control" id="book-status">
                <option value="read">Read ✓</option>
                <option value="reading">Currently Reading</option>
                <option value="wishlist">Wishlist</option>
              </select>
            </div>
            <div class="form-group">
              <label>Rating (1-5 stars)</label>
              <select class="form-control" id="book-rating">
                <option value="5">★★★★★</option>
                <option value="4">★★★★☆</option>
                <option value="3">★★★☆☆</option>
                <option value="2">★★☆☆☆</option>
                <option value="1">★☆☆☆☆</option>
                <option value="0">No rating</option>
              </select>
            </div>
          </div>
          <div class="form-group"><label>Cover Image URL (optional)</label><input type="text" class="form-control" id="book-cover" placeholder="https://..."></div>
          <div class="form-group"><label>Short Note / Takeaway</label><textarea class="form-control" id="book-note" placeholder="What did you learn or love about this book?"></textarea></div>
          <button class="btn-add" onclick="saveBook()">+ Save Book</button>
        </div>
      </div>

      <!-- THEME TAB -->
      <div class="tab-section" id="tab-theme">
        <div class="add-form-title">Accent Color</div>
        <div class="theme-label">Primary Accent</div>
        <div class="color-row" id="color-primary">
          <div class="color-btn active" style="background:#7c6aff" data-color="#7c6aff" onclick="setColor('accent',this)"></div>
          <div class="color-btn" style="background:#6a9fff" data-color="#6a9fff" onclick="setColor('accent',this)"></div>
          <div class="color-btn" style="background:#ff6a9e" data-color="#ff6a9e" onclick="setColor('accent',this)"></div>
          <div class="color-btn" style="background:#ff9a6a" data-color="#ff9a6a" onclick="setColor('accent',this)"></div>
          <div class="color-btn" style="background:#6affd4" data-color="#6affd4" onclick="setColor('accent',this)"></div>
          <div class="color-btn" style="background:#ffd46a" data-color="#ffd46a" onclick="setColor('accent',this)"></div>
          <div class="color-btn" style="background:#e86a6a" data-color="#e86a6a" onclick="setColor('accent',this)"></div>
        </div>
        <div class="theme-label" style="margin-top:16px;">Secondary Accent</div>
        <div class="color-row" id="color-secondary">
          <div class="color-btn active" style="background:#ff6a9e" data-color="#ff6a9e" onclick="setColor('accent2',this)"></div>
          <div class="color-btn" style="background:#6affd4" data-color="#6affd4" onclick="setColor('accent2',this)"></div>
          <div class="color-btn" style="background:#ffd46a" data-color="#ffd46a" onclick="setColor('accent2',this)"></div>
          <div class="color-btn" style="background:#7c6aff" data-color="#7c6aff" onclick="setColor('accent2',this)"></div>
          <div class="color-btn" style="background:#6a9fff" data-color="#6a9fff" onclick="setColor('accent2',this)"></div>
        </div>
        <div class="section-divider"></div>
        <div class="add-form-title">Background Theme</div>
        <div style="display:flex;gap:12px;flex-wrap:wrap;">
          <button class="btn-edit" onclick="setBg('#0a0a0f','#111118')">Dark (Default)</button>
          <button class="btn-edit" onclick="setBg('#080810','#0f0f18')">Deep Dark</button>
          <button class="btn-edit" onclick="setBg('#0a100a','#0f180f')">Forest Dark</button>
          <button class="btn-edit" onclick="setBg('#100a0a','#18100f')">Crimson Dark</button>
          <button class="btn-edit" onclick="setBg('#0a0a18','#0f0f24')">Midnight Blue</button>
        </div>
        <div class="section-divider"></div>
        <div class="add-form-title">Change Admin Password</div>
        <div class="admin-form-row">
          <div class="form-group"><label>New Password</label><input type="password" class="form-control" id="new-pass"></div>
          <div class="form-group"><label>Confirm</label><input type="password" class="form-control" id="confirm-pass"></div>
        </div>
        <button class="btn-save" onclick="changePassword()">Update Password</button>
      </div>

    </div>
  </div>
</div>

<script>
// ===== PASSWORD PERSISTENCE via localStorage =====
const PASS_KEY = 'ds_portfolio_admin_pw';
const SECURITY_ANSWER = 'admin123'; // the answer to the security question

function getSavedPassword() {
  try { return localStorage.getItem(PASS_KEY) || 'admin123'; } catch(e) { return 'admin123'; }
}
function savePasswordToStorage(pw) {
  try { localStorage.setItem(PASS_KEY, pw); } catch(e) {}
}

// ===== DATA STORE =====
let DATA = {
  get password() { return getSavedPassword(); },
  set password(v) { savePasswordToStorage(v); },
  skills: ['Python','SQL','Pandas','NumPy','Matplotlib','scikit-learn','TensorFlow','Jupyter','Git','Statistics','Excel','Tableau'],
  projects: [
    { id:1, title:'House Price Prediction', tag:'ML / Regression', desc:'Built a regression model to predict house prices using feature engineering and ensemble methods, achieving a strong RMSE on the Kaggle dataset.', tech:['Python','scikit-learn','Pandas','Seaborn'], github:'https://github.com', demo:'', img:'' },
    { id:2, title:'Exploratory Data Analysis — Sales Dataset', tag:'EDA / Visualization', desc:'In-depth EDA of a retail sales dataset uncovering seasonal trends, top-performing categories, and actionable insights using Python and Matplotlib.', tech:['Python','Pandas','Matplotlib','Seaborn'], github:'https://github.com', demo:'', img:'' },
    { id:3, title:'Movie Recommendation System', tag:'ML / Recommender', desc:'Collaborative filtering-based recommendation system using cosine similarity to suggest movies based on user ratings.', tech:['Python','scikit-learn','NumPy','Jupyter'], github:'https://github.com', demo:'', img:'' },
  ],
  certifications: [
    { id:1, name:'Python for Data Science and AI', issuer:'IBM / Coursera', date:'2024', emoji:'🐍', url:'', badge:'Earned' },
    { id:2, name:'Machine Learning Specialization', issuer:'Andrew Ng / Coursera', date:'2024', emoji:'🤖', url:'', badge:'Earned' },
    { id:3, name:'Data Analysis with Python', issuer:'freeCodeCamp', date:'2023', emoji:'📊', url:'', badge:'Earned' },
  ],
  experience: [
    { id:1, role:'Data Science Intern (Virtual)', company:'Self-initiated Projects', date:'2024 — Present', desc:'Building a personal portfolio of data science projects covering regression, classification, EDA, and visualization to develop hands-on skills.', skills:['Python','scikit-learn','Pandas','Jupyter'] },
    { id:2, role:'Kaggle Competitor', company:'Kaggle', date:'2023 — Present', desc:'Participating in beginner and intermediate Kaggle competitions to practice real-world data science workflows and learn from the community.', skills:['Python','Feature Engineering','EDA','Ensemble Methods'] },
  ],
  books: [
    { id:1, title:'The Elements of Statistical Learning', author:'Hastie, Tibshirani, Friedman', status:'read', rating:5, cover:'', note:'The bible of statistical ML. Dense but worth every page.' },
    { id:2, title:'Designing Data-Intensive Applications', author:'Martin Kleppmann', status:'read', rating:5, cover:'', note:'Essential for understanding data systems at scale.' },
    { id:3, title:'Python Machine Learning', author:'Sebastian Raschka', status:'reading', rating:4, cover:'', note:'Incredibly practical with great code examples throughout.' },
    { id:4, title:'Storytelling with Data', author:'Cole Nussbaumer Knaflic', status:'read', rating:4, cover:'', note:'Completely changed how I approach data visualization.' },
    { id:5, title:'The Alignment Problem', author:'Brian Christian', status:'wishlist', rating:0, cover:'', note:'On my list — AI alignment and safety deep dive.' },
  ],
  contactLinks: [
    { id:1, label:'Email', value:'nikkumewara2003@gmail.com', url:'mailto:nikkumewara2003@gmail.com', icon:'✉️' },
    { id:2, label:'LinkedIn', value:'linkedin.com/in/nikhilesh-mewara-111nk333', url:'https://www.linkedin.com/in/nikhilesh-mewara-111nk333', icon:'💼' },
    { id:3, label:'GitHub', value:'github.com/nk019', url:'https://github.com/nk019', icon:'🐙' },
    { id:4, label:'Kaggle', value:'kaggle.com/nikhileshmewara', url:'https://www.kaggle.com/nikhileshmewara', icon:'🏆' },
  ]
};

// ===== CURSOR =====
const cursor = document.getElementById('cursor');
const ring = document.getElementById('cursor-ring');
document.addEventListener('mousemove', e => {
  cursor.style.left = e.clientX + 'px'; cursor.style.top = e.clientY + 'px';
  setTimeout(()=>{ ring.style.left = e.clientX+'px'; ring.style.top = e.clientY+'px'; }, 80);
});
document.addEventListener('mousedown', () => { cursor.style.transform='translate(-50%,-50%) scale(0.7)'; });
document.addEventListener('mouseup', () => { cursor.style.transform='translate(-50%,-50%) scale(1)'; });

// ===== RENDER =====
function renderAll() {
  renderSkills();
  renderProjects();
  renderCerts();
  renderExperience();
  renderBooks();
  renderContactLinks();
}

function renderSkills() {
  const c = document.getElementById('skills-container');
  c.innerHTML = DATA.skills.map(s => `<div class="skill-tag">${s}</div>`).join('');
  renderSkillsAdmin();
}
function renderSkillsAdmin() {
  const c = document.getElementById('skills-admin-list');
  c.innerHTML = DATA.skills.map((s,i) => `
    <div class="item-card">
      <div class="item-card-info"><div class="item-card-title">${s}</div></div>
      <div class="item-actions"><button class="btn-delete" onclick="deleteSkill(${i})">✕ Remove</button></div>
    </div>`).join('');
}

function renderProjects() {
  const c = document.getElementById('projects-container');
  c.innerHTML = DATA.projects.map(p => `
    <div class="project-card fade-up visible">
      ${p.img ? `<img src="${p.img}" class="project-img" alt="">` : ''}
      <div class="project-tag">${p.tag}</div>
      <div class="project-title">${p.title}</div>
      <div class="project-desc">${p.desc}</div>
      <div class="project-tech">${p.tech.map(t=>`<span class="tech-pill">${t}</span>`).join('')}</div>
      <div class="project-links">
        ${p.github ? `<a href="${p.github}" target="_blank">↗ GitHub</a>` : ''}
        ${p.demo ? `<a href="${p.demo}" target="_blank">⬡ Live Demo</a>` : ''}
      </div>
    </div>`).join('');
  renderProjectsAdmin();
}
function renderProjectsAdmin() {
  const c = document.getElementById('projects-admin-list');
  c.innerHTML = DATA.projects.map(p => `
    <div class="item-card">
      <div class="item-card-info">
        <div class="item-card-title">${p.title}</div>
        <div class="item-card-sub">${p.tag}</div>
      </div>
      <div class="item-actions">
        <button class="btn-edit" onclick="editProject(${p.id})">✎ Edit</button>
        <button class="btn-delete" onclick="deleteProject(${p.id})">✕ Delete</button>
      </div>
    </div>`).join('');
}

function renderCerts() {
  const c = document.getElementById('certs-container');
  c.innerHTML = DATA.certifications.map(ct => `
    <div class="cert-card fade-up visible">
      <div class="cert-badge">${ct.badge||'Active'}</div>
      <div class="cert-logo">${ct.emoji||'🏅'}</div>
      <div class="cert-issuer">${ct.issuer}</div>
      <div class="cert-name">${ct.name}</div>
      <div class="cert-date">${ct.date}</div>
      ${ct.url ? `<a href="${ct.url}" target="_blank" class="cert-link">View Credential →</a>` : ''}
    </div>`).join('');
  renderCertsAdmin();
}
function renderCertsAdmin() {
  const c = document.getElementById('certs-admin-list');
  c.innerHTML = DATA.certifications.map(ct => `
    <div class="item-card">
      <div class="item-card-info">
        <div class="item-card-title">${ct.name}</div>
        <div class="item-card-sub">${ct.issuer} · ${ct.date}</div>
      </div>
      <div class="item-actions">
        <button class="btn-edit" onclick="editCert(${ct.id})">✎ Edit</button>
        <button class="btn-delete" onclick="deleteCert(${ct.id})">✕ Delete</button>
      </div>
    </div>`).join('');
}

function renderExperience() {
  const c = document.getElementById('experience-container');
  c.innerHTML = DATA.experience.map(e => `
    <div class="timeline-item fade-up visible">
      <div class="timeline-dot"></div>
      <div class="timeline-date">${e.date}</div>
      <div class="timeline-role">${e.role}</div>
      <div class="timeline-company">${e.company}</div>
      <div class="timeline-desc">${e.desc}</div>
      <div class="timeline-tags">${e.skills.map(s=>`<span class="tech-pill">${s}</span>`).join('')}</div>
    </div>`).join('');
  renderExpAdmin();
}
function renderExpAdmin() {
  const c = document.getElementById('exp-admin-list');
  c.innerHTML = DATA.experience.map(e => `
    <div class="item-card">
      <div class="item-card-info">
        <div class="item-card-title">${e.role}</div>
        <div class="item-card-sub">${e.company} · ${e.date}</div>
      </div>
      <div class="item-actions">
        <button class="btn-edit" onclick="editExp(${e.id})">✎ Edit</button>
        <button class="btn-delete" onclick="deleteExp(${e.id})">✕ Delete</button>
      </div>
    </div>`).join('');
}

// ===== BOOKS =====
let currentBookFilter = 'all';
function starsHTML(n) {
  if(!n || n==0) return '';
  return '★'.repeat(n) + '☆'.repeat(5-n);
}
function renderBooks(filter) {
  if(filter !== undefined) currentBookFilter = filter;
  const f = currentBookFilter;
  const list = f === 'all' ? DATA.books : DATA.books.filter(b=>b.status===f);
  const c = document.getElementById('books-container');
  c.innerHTML = list.map(b => `
    <div class="book-card fade-up visible">
      <div class="book-cover">
        <div class="book-spine"></div>
        ${b.cover ? `<img src="${b.cover}" alt="">` : `<div class="book-cover-placeholder">📚</div>`}
      </div>
      <div class="book-info">
        <div class="book-title">${b.title}</div>
        <div class="book-author">${b.author}</div>
        <span class="book-status ${b.status}">${b.status==='reading'?'● Reading':b.status==='read'?'✓ Read':'♡ Wishlist'}</span>
        ${b.rating ? `<div class="book-rating" style="color:var(--accent3);">${starsHTML(parseInt(b.rating))}</div>` : ''}
        ${b.note ? `<div class="book-note">"${b.note}"</div>` : ''}
      </div>
    </div>`).join('');
  renderBooksAdmin();
}
function filterBooks(f, btn) {
  currentBookFilter = f;
  document.querySelectorAll('.filter-btn').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  renderBooks(f);
}
function renderBooksAdmin() {
  const c = document.getElementById('books-admin-list');
  c.innerHTML = DATA.books.map(b => `
    <div class="item-card">
      <div class="item-card-info">
        <div class="item-card-title">${b.title}</div>
        <div class="item-card-sub">${b.author} · ${b.status}</div>
      </div>
      <div class="item-actions">
        <button class="btn-edit" onclick="editBook(${b.id})">✎ Edit</button>
        <button class="btn-delete" onclick="deleteBook(${b.id})">✕ Delete</button>
      </div>
    </div>`).join('');
}
let bookCounter = 10;
function saveBook() {
  const editId = document.getElementById('edit-book-id').value;
  const obj = {
    id: editId ? parseInt(editId) : ++bookCounter,
    title: document.getElementById('book-title').value,
    author: document.getElementById('book-author').value,
    status: document.getElementById('book-status').value,
    rating: parseInt(document.getElementById('book-rating').value),
    cover: document.getElementById('book-cover').value,
    note: document.getElementById('book-note').value,
  };
  if(!obj.title) return;
  if(editId) { const idx=DATA.books.findIndex(b=>b.id===parseInt(editId)); DATA.books[idx]=obj; }
  else DATA.books.push(obj);
  ['book-title','book-author','book-cover','book-note'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('edit-book-id').value='';
  renderBooks();
  showToast('Book saved');
}
function editBook(id) {
  const b = DATA.books.find(x=>x.id===id);
  document.getElementById('edit-book-id').value=id;
  document.getElementById('book-title').value=b.title;
  document.getElementById('book-author').value=b.author;
  document.getElementById('book-status').value=b.status;
  document.getElementById('book-rating').value=b.rating||0;
  document.getElementById('book-cover').value=b.cover||'';
  document.getElementById('book-note').value=b.note||'';
  document.querySelector('#tab-books .add-form').scrollIntoView({behavior:'smooth'});
}
function deleteBook(id) { DATA.books=DATA.books.filter(b=>b.id!==id); renderBooks(); showToast('Book removed'); }

function renderContactLinks() {
  const c = document.getElementById('contact-links-container');
  c.innerHTML = DATA.contactLinks.map(cl => `
    <a href="${cl.url}" target="_blank" class="contact-link">
      <div class="contact-link-icon">${cl.icon}</div>
      <div>
        <div class="contact-link-label">${cl.label}</div>
        <div>${cl.value}</div>
      </div>
    </a>`).join('');
  renderContactAdmin();
}
function renderContactAdmin() {
  const c = document.getElementById('contact-admin-list');
  c.innerHTML = DATA.contactLinks.map(cl => `
    <div class="item-card">
      <div class="item-card-info">
        <div class="item-card-title">${cl.icon} ${cl.label}</div>
        <div class="item-card-sub">${cl.value}</div>
      </div>
      <div class="item-actions">
        <button class="btn-delete" onclick="deleteContactLink(${cl.id})">✕ Remove</button>
      </div>
    </div>`).join('');
}

// ===== ADMIN =====
function openAdmin() {
  document.getElementById('admin-overlay').classList.add('open');
  document.getElementById('login-modal').style.display='block';
  document.getElementById('admin-panel').style.display='none';
  document.getElementById('forgot-modal').style.display='none';
  document.getElementById('reset-modal').style.display='none';
}
function closeAdmin() {
  document.getElementById('admin-overlay').classList.remove('open');
  document.getElementById('admin-password').value='';
  document.getElementById('login-error').style.display='none';
  document.getElementById('forgot-error').style.display='none';
  document.getElementById('reset-error').style.display='none';
}
function doLogin() {
  const pw = document.getElementById('admin-password').value;
  const err = document.getElementById('login-error');
  if(pw === DATA.password) {
    err.style.display='none';
    document.getElementById('login-modal').style.display='none';
    document.getElementById('admin-panel').style.display='block';
    loadProfileForm();
  } else {
    err.textContent = 'Incorrect password.';
    err.style.display='block';
  }
}

// ===== FORGOT PASSWORD =====
function showForgot() {
  document.getElementById('login-modal').style.display='none';
  document.getElementById('forgot-modal').style.display='block';
  document.getElementById('forgot-answer').value='';
  document.getElementById('forgot-error').style.display='none';
}
function closeForgot() {
  document.getElementById('forgot-modal').style.display='none';
  document.getElementById('reset-modal').style.display='none';
  document.getElementById('login-modal').style.display='block';
}
function checkForgotAnswer() {
  const ans = document.getElementById('forgot-answer').value.trim().toLowerCase();
  if(ans === SECURITY_ANSWER.toLowerCase()) {
    document.getElementById('forgot-modal').style.display='none';
    document.getElementById('reset-modal').style.display='block';
    document.getElementById('reset-new-pass').value='';
    document.getElementById('reset-confirm-pass').value='';
    document.getElementById('reset-error').style.display='none';
  } else {
    document.getElementById('forgot-error').style.display='block';
  }
}
function doResetPassword() {
  const np = document.getElementById('reset-new-pass').value;
  const cp = document.getElementById('reset-confirm-pass').value;
  const err = document.getElementById('reset-error');
  if(!np) { err.textContent='Please enter a new password.'; err.style.display='block'; return; }
  if(np !== cp) { err.textContent='Passwords do not match.'; err.style.display='block'; return; }
  DATA.password = np;
  document.getElementById('reset-modal').style.display='none';
  document.getElementById('login-modal').style.display='block';
  showToast('Password reset! Login with your new password.');
}

function switchTab(name) {
  document.querySelectorAll('.panel-tab').forEach((t)=>{ t.classList.toggle('active', t.getAttribute('onclick').includes("'"+name+"'")); });
  document.querySelectorAll('.tab-section').forEach(s=>{ s.classList.toggle('active', s.id==='tab-'+name); });
}

function showToast(msg='Changes saved') {
  const t = document.getElementById('toast');
  t.textContent = '✓ '+msg;
  t.classList.add('show');
  setTimeout(()=>t.classList.remove('show'), 2800);
}

// ===== PROFILE =====
function loadProfileForm() {
  document.getElementById('p-firstname').value = document.getElementById('hero-firstname').textContent;
  document.getElementById('p-lastname').value = document.getElementById('hero-lastname').textContent;
}
function handlePhotoUpload(input) {
  const file = input.files[0];
  if (!file) return;
  const reader = new FileReader();
  reader.onload = function(e) {
    const dataUrl = e.target.result;
    // Update preview in admin
    const img = document.getElementById('profile-img-preview');
    const em = document.getElementById('profile-emoji');
    img.src = dataUrl; img.style.display = 'block'; em.style.display = 'none';
    // Clear URL field since we're using file
    document.getElementById('p-photo').value = '';
    // Show filename
    document.getElementById('upload-filename').textContent = file.name;
    // Update about section photo
    const aboutImg = document.getElementById('about-img');
    const hint = document.querySelector('.upload-hint');
    aboutImg.src = dataUrl; aboutImg.style.display = 'block';
    if (hint) hint.style.display = 'none';
    // Store dataUrl so saveProfile can use it
    window._uploadedPhotoDataUrl = dataUrl;
    showToast('Photo loaded! Click Save Profile to apply.');
  };
  reader.readAsDataURL(file);
}

function previewProfilePhoto(url) {
  if (!url) return;
  window._uploadedPhotoDataUrl = null;
  document.getElementById('upload-filename').textContent = '';
  const img = document.getElementById('profile-img-preview');
  const em = document.getElementById('profile-emoji');
  img.src = url; img.style.display = 'block'; em.style.display = 'none';
  const aboutImg = document.getElementById('about-img');
  const hint = document.querySelector('.upload-hint');
  aboutImg.src = url; aboutImg.style.display = 'block';
  if (hint) hint.style.display = 'none';
}
function saveProfile() {
  // Apply photo — prefer uploaded file, then URL field
  const photoSrc = window._uploadedPhotoDataUrl || document.getElementById('p-photo').value;
  if (photoSrc) {
    const aboutImg = document.getElementById('about-img');
    const hint = document.querySelector('.upload-hint');
    aboutImg.src = photoSrc; aboutImg.style.display = 'block';
    if (hint) hint.style.display = 'none';
  }
  document.getElementById('hero-firstname').textContent = document.getElementById('p-firstname').value;
  document.getElementById('hero-lastname').textContent = document.getElementById('p-lastname').value;
  document.getElementById('hero-tag').innerHTML = document.getElementById('p-role').value;
  document.getElementById('hero-subtitle').textContent = document.getElementById('p-subtitle').value;
  document.getElementById('hero-bio').textContent = document.getElementById('p-bio').value;
  document.getElementById('about-heading').innerHTML = document.getElementById('p-about-heading').value;
  document.getElementById('about-p1').textContent = document.getElementById('p-about-p1').value;
  document.getElementById('about-p2').textContent = document.getElementById('p-about-p2').value;
  document.getElementById('stat1-num').textContent = document.getElementById('p-stat1n').value;
  document.getElementById('stat1-label').textContent = document.getElementById('p-stat1l').value;
  document.getElementById('stat2-num').textContent = document.getElementById('p-stat2n').value;
  document.getElementById('stat2-label').textContent = document.getElementById('p-stat2l').value;
  document.getElementById('stat3-num').textContent = document.getElementById('p-stat3n').value;
  document.getElementById('stat3-label').textContent = document.getElementById('p-stat3l').value;
  document.getElementById('nav-logo').textContent = document.getElementById('p-firstname').value + ' ' + document.getElementById('p-lastname').value;
  showToast('Profile saved');
}
function saveHero() {
  document.getElementById('hero-cta1').textContent = document.getElementById('h-cta1').value;
  document.getElementById('hero-cta2').textContent = document.getElementById('h-cta2').value;
  document.getElementById('footer-text').textContent = document.getElementById('h-footer').value;
  showToast('Hero saved');
}

// ===== SKILLS =====
function addSkill() {
  const val = document.getElementById('new-skill').value.trim();
  if(!val) return;
  DATA.skills.push(val);
  document.getElementById('new-skill').value = '';
  renderSkills();
  showToast('Skill added');
}
function deleteSkill(i) { DATA.skills.splice(i,1); renderSkills(); showToast('Skill removed'); }

// ===== PROJECTS =====
let projCounter = 10;
function saveProject() {
  const editId = document.getElementById('edit-project-id').value;
  const obj = {
    id: editId ? parseInt(editId) : ++projCounter,
    title: document.getElementById('proj-title').value,
    tag: document.getElementById('proj-tag').value,
    desc: document.getElementById('proj-desc').value,
    tech: document.getElementById('proj-tech').value.split(',').map(t=>t.trim()).filter(Boolean),
    github: document.getElementById('proj-github').value,
    demo: document.getElementById('proj-demo').value,
    img: document.getElementById('proj-img').value,
  };
  if(!obj.title) return;
  if(editId) { const idx = DATA.projects.findIndex(p=>p.id===parseInt(editId)); DATA.projects[idx]=obj; }
  else DATA.projects.push(obj);
  ['proj-title','proj-tag','proj-desc','proj-tech','proj-github','proj-demo','proj-img'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('edit-project-id').value='';
  renderProjects();
  showToast('Project saved');
}
function editProject(id) {
  const p = DATA.projects.find(x=>x.id===id);
  document.getElementById('edit-project-id').value=id;
  document.getElementById('proj-title').value=p.title;
  document.getElementById('proj-tag').value=p.tag;
  document.getElementById('proj-desc').value=p.desc;
  document.getElementById('proj-tech').value=p.tech.join(', ');
  document.getElementById('proj-github').value=p.github;
  document.getElementById('proj-demo').value=p.demo;
  document.getElementById('proj-img').value=p.img;
  document.querySelector('#tab-projects .add-form').scrollIntoView({behavior:'smooth'});
}
function deleteProject(id) { DATA.projects=DATA.projects.filter(p=>p.id!==id); renderProjects(); showToast('Project removed'); }

// ===== CERTS =====
let certCounter = 10;
function saveCert() {
  const editId = document.getElementById('edit-cert-id').value;
  const obj = {
    id: editId ? parseInt(editId) : ++certCounter,
    name: document.getElementById('cert-name').value,
    issuer: document.getElementById('cert-issuer').value,
    date: document.getElementById('cert-date').value,
    emoji: document.getElementById('cert-emoji').value||'🏅',
    url: document.getElementById('cert-url').value,
    badge: 'Active'
  };
  if(!obj.name) return;
  if(editId) { const idx=DATA.certifications.findIndex(c=>c.id===parseInt(editId)); DATA.certifications[idx]=obj; }
  else DATA.certifications.push(obj);
  ['cert-name','cert-issuer','cert-date','cert-emoji','cert-url'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('edit-cert-id').value='';
  renderCerts();
  showToast('Certification saved');
}
function editCert(id) {
  const c = DATA.certifications.find(x=>x.id===id);
  document.getElementById('edit-cert-id').value=id;
  document.getElementById('cert-name').value=c.name;
  document.getElementById('cert-issuer').value=c.issuer;
  document.getElementById('cert-date').value=c.date;
  document.getElementById('cert-emoji').value=c.emoji;
  document.getElementById('cert-url').value=c.url;
  document.querySelector('#tab-certifications .add-form').scrollIntoView({behavior:'smooth'});
}
function deleteCert(id) { DATA.certifications=DATA.certifications.filter(c=>c.id!==id); renderCerts(); showToast('Certification removed'); }

// ===== EXPERIENCE =====
let expCounter = 10;
function saveExp() {
  const editId = document.getElementById('edit-exp-id').value;
  const obj = {
    id: editId ? parseInt(editId) : ++expCounter,
    role: document.getElementById('exp-role').value,
    company: document.getElementById('exp-company').value,
    date: document.getElementById('exp-date').value,
    desc: document.getElementById('exp-desc').value,
    skills: document.getElementById('exp-skills').value.split(',').map(s=>s.trim()).filter(Boolean)
  };
  if(!obj.role) return;
  if(editId) { const idx=DATA.experience.findIndex(e=>e.id===parseInt(editId)); DATA.experience[idx]=obj; }
  else DATA.experience.push(obj);
  ['exp-role','exp-company','exp-date','exp-desc','exp-skills'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('edit-exp-id').value='';
  renderExperience();
  showToast('Experience saved');
}
function editExp(id) {
  const e = DATA.experience.find(x=>x.id===id);
  document.getElementById('edit-exp-id').value=id;
  document.getElementById('exp-role').value=e.role;
  document.getElementById('exp-company').value=e.company;
  document.getElementById('exp-date').value=e.date;
  document.getElementById('exp-desc').value=e.desc;
  document.getElementById('exp-skills').value=e.skills.join(', ');
  document.querySelector('#tab-experience .add-form').scrollIntoView({behavior:'smooth'});
}
function deleteExp(id) { DATA.experience=DATA.experience.filter(e=>e.id!==id); renderExperience(); showToast('Experience removed'); }

// ===== CONTACT =====
let clCounter = 10;
function saveContact() {
  document.getElementById('contact-heading').innerHTML = document.getElementById('c-heading').value;
  document.getElementById('contact-desc').textContent = document.getElementById('c-desc').value;
  showToast('Contact saved');
}
function saveContactLink() {
  const obj = {
    id: ++clCounter,
    label: document.getElementById('cl-label').value,
    value: document.getElementById('cl-value').value,
    url: document.getElementById('cl-url').value,
    icon: document.getElementById('cl-icon').value||'🔗'
  };
  if(!obj.label) return;
  DATA.contactLinks.push(obj);
  ['cl-label','cl-value','cl-url','cl-icon'].forEach(id=>document.getElementById(id).value='');
  renderContactLinks();
  showToast('Link added');
}
function deleteContactLink(id) { DATA.contactLinks=DATA.contactLinks.filter(c=>c.id!==id); renderContactLinks(); showToast('Link removed'); }

// ===== THEME =====
function setColor(varName, btn) {
  const color = btn.getAttribute('data-color');
  document.documentElement.style.setProperty('--'+varName, color);
  btn.closest('.color-row').querySelectorAll('.color-btn').forEach(b=>b.classList.remove('active'));
  btn.classList.add('active');
  showToast('Color updated');
}
function setBg(bg, surface) {
  document.documentElement.style.setProperty('--bg', bg);
  document.documentElement.style.setProperty('--surface', surface);
  showToast('Theme updated');
}
function changePassword() {
  const np = document.getElementById('new-pass').value;
  const cp = document.getElementById('confirm-pass').value;
  if(!np) return;
  if(np !== cp) { showToast('Passwords do not match!'); return; }
  DATA.password = np;
  document.getElementById('new-pass').value='';
  document.getElementById('confirm-pass').value='';
  showToast('Password updated & saved!');
}

// ===== SCROLL ANIMATIONS =====
const observer = new IntersectionObserver((entries) => {
  entries.forEach(e => { if(e.isIntersecting) e.target.classList.add('visible'); });
}, { threshold: 0.1 });
document.querySelectorAll('.fade-up').forEach(el => observer.observe(el));

// ===== INIT =====
renderAll();
</script>
</body>
</html>
