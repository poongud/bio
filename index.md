---
layout: null
title: "Poongudivanan Natarajan"
description: "Software Architect | Adobe Commerce | Cloud | Composable Commerce | AI"
---

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root {
  --bg: #07111f;
  --bg2: #0b1628;
  --card: #0d1a2d;
  --card2: #101e33;
  --border: #263750;
  --text: #f5f7fb;
  --muted: #a9b4c5;

  --purple: #a855f7;
  --blue: #38bdf8;
  --green: #34d399;
  --orange: #f59e0b;
  --pink: #e879f9;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  background:
    radial-gradient(circle at 15% 5%, rgba(126,34,206,.18), transparent 28%),
    radial-gradient(circle at 85% 15%, rgba(37,99,235,.12), transparent 25%),
    var(--bg);
  color: var(--text);
  font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
               Helvetica, Arial, sans-serif;
  line-height: 1.6;
}

a {
  color: inherit;
  text-decoration: none;
}

.container {
  width: min(1180px, 92%);
  margin: auto;
}

/* NAV */

nav {
  position: sticky;
  top: 0;
  z-index: 100;
  background: rgba(7,17,31,.92);
  backdrop-filter: blur(14px);
  border-bottom: 1px solid var(--border);
}

.nav-inner {
  min-height: 72px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 30px;
}

.brand {
  display: flex;
  align-items: center;
  gap: 12px;
}

.logo {
  width: 44px;
  height: 44px;
  border: 2px solid var(--purple);
  border-radius: 10px;
  display: grid;
  place-items: center;
  font-weight: 800;
  color: #d8b4fe;
  background: rgba(168,85,247,.08);
}

.brand strong {
  display: block;
}

.brand small {
  color: var(--muted);
}

.nav-links {
  display: flex;
  gap: 26px;
  font-size: 14px;
}

.nav-links a {
  color: #dbe4f0;
}

.nav-links a:hover {
  color: var(--purple);
}

/* HERO */

.hero {
  padding: 75px 0 65px;
  border-bottom: 1px solid var(--border);
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.15fr .85fr;
  gap: 70px;
  align-items: center;
}

.hello {
  font-size: 22px;
  font-weight: 700;
}

h1 {
  margin: 8px 0 8px;
  font-size: clamp(46px, 7vw, 76px);
  line-height: .98;
  letter-spacing: -2px;
}

.gradient-text {
  display: block;
  background: linear-gradient(90deg, #a855f7, #6366f1);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.subtitle {
  font-size: 20px;
  color: #d2d8e4;
  max-width: 650px;
}

.hero-meta {
  margin-top: 22px;
  color: #d0d7e2;
}

.buttons {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-top: 28px;
}

.btn {
  display: inline-block;
  padding: 12px 20px;
  border-radius: 8px;
  border: 1px solid #52617a;
  font-weight: 700;
  transition: .2s ease;
}

.btn-primary {
  border: none;
  background: linear-gradient(90deg, #7c3aed, #a855f7);
}

.btn:hover {
  transform: translateY(-2px);
  filter: brightness(1.12);
}

/* HERO PROFILE */

.profile-side {
  text-align: center;
}

.avatar {
  width: 225px;
  height: 225px;
  margin: auto;
  border-radius: 50%;
  border: 3px solid #6366f1;
  background:
    linear-gradient(135deg, rgba(168,85,247,.25), rgba(59,130,246,.15));
  display: grid;
  place-items: center;
  box-shadow: 0 0 50px rgba(99,102,241,.18);
}

.avatar span {
  font-size: 70px;
  font-weight: 800;
  color: #c4b5fd;
}

.quote {
  margin: 30px auto 0;
  max-width: 480px;
  color: #d9dfeb;
  font-style: italic;
  text-align: left;
  border-left: 3px solid var(--purple);
  padding-left: 20px;
}

/* SECTIONS */

section {
  padding: 58px 0;
  border-bottom: 1px solid rgba(38,55,80,.75);
}

.section-title {
  font-size: 27px;
  margin: 0 0 25px;
}

.about-grid {
  display: grid;
  grid-template-columns: 1.1fr .9fr;
  gap: 45px;
}

.about-copy {
  color: #cbd5e1;
}

.highlight {
  color: #c084fc;
  font-weight: 700;
  font-size: 18px;
}

.stats {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  border: 1px solid var(--border);
  border-radius: 10px;
  overflow: hidden;
}

.stat {
  min-height: 145px;
  display: grid;
  place-items: center;
  text-align: center;
  padding: 20px;
  background: rgba(13,26,45,.65);
  border: 1px solid rgba(38,55,80,.55);
}

.stat-icon {
  font-size: 30px;
}

.stat strong {
  display: block;
  font-size: 21px;
  color: var(--purple);
}

/* CARDS */

.cards {
  display: grid;
  grid-template-columns: repeat(5,1fr);
  gap: 16px;
}

.card {
  background: linear-gradient(145deg, var(--card), rgba(13,26,45,.65));
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 25px 20px;
  text-align: center;
  transition: transform .2s ease, border-color .2s ease;
}

.card:hover {
  transform: translateY(-5px);
}

.card-icon {
  font-size: 30px;
  margin-bottom: 10px;
}

.card h3 {
  font-size: 17px;
  margin: 5px 0 12px;
}

.card p {
  color: var(--muted);
  font-size: 14px;
}

.purple { border-color: #6d3aa5; }
.purple h3 { color: #c084fc; }

.blue { border-color: #235a88; }
.blue h3 { color: #60a5fa; }

.cyan { border-color: #16719a; }
.cyan h3 { color: #38bdf8; }

.green { border-color: #24745f; }
.green h3 { color: #34d399; }

.orange { border-color: #8c5b09; }
.orange h3 { color: #fbbf24; }

/* CERTIFICATIONS */

.two-columns {
  display: grid;
  grid-template-columns: 1.1fr .9fr;
  gap: 25px;
}

.panel {
  background: rgba(13,26,45,.55);
  border: 1px solid var(--border);
  border-radius: 10px;
  padding: 25px;
}

.cert-grid {
  display: grid;
  grid-template-columns: repeat(2,1fr);
  gap: 12px;
}

.cert {
  padding: 15px;
  border: 1px solid var(--border);
  border-radius: 8px;
  background: var(--card);
}

.cert strong {
  display: block;
}

.cert small {
  color: var(--muted);
}

/* TECH */

.tags {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.tag {
  border: 1px solid #36506f;
  background: #0b1728;
  padding: 7px 13px;
  border-radius: 6px;
  font-size: 13px;
}

.tag:nth-child(4n+1) { border-color: #28765e; }
.tag:nth-child(4n+2) { border-color: #276a98; }
.tag:nth-child(4n+3) { border-color: #74459a; }
.tag:nth-child(4n+4) { border-color: #8b5e13; }

/* EXPLORING */

.explore-grid {
  display: grid;
  grid-template-columns: repeat(7,1fr);
  gap: 12px;
}

.explore {
  background: var(--card);
  border: 1px solid var(--border);
  border-radius: 8px;
  padding: 18px 10px;
  text-align: center;
  font-size: 13px;
  font-weight: 600;
}

.explore span {
  display: block;
  font-size: 25px;
  margin-bottom: 8px;
}

/* CTA */

.cta {
  margin: 55px auto 25px;
  padding: 30px;
  border: 1px solid #36235e;
  border-radius: 12px;
  background:
    linear-gradient(100deg,
      rgba(88,28,135,.30),
      rgba(30,41,59,.45),
      rgba(76,29,149,.24));
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 30px;
}

.cta h3 {
  margin: 0 0 10px;
}

.cta-quote {
  color: #c084fc;
  font-size: 18px;
  font-style: italic;
}

.social {
  color: #c4b5fd;
}

footer {
  padding: 15px 0 40px;
  color: #7f8da3;
  font-size: 13px;
  display: flex;
  justify-content: space-between;
}

/* RESPONSIVE */

@media (max-width: 900px) {
  .hero-grid,
  .about-grid,
  .two-columns {
    grid-template-columns: 1fr;
  }

  .cards {
    grid-template-columns: repeat(2,1fr);
  }

  .explore-grid {
    grid-template-columns: repeat(2,1fr);
  }

  .profile-side {
    order: -1;
  }

  .avatar {
    width: 170px;
    height: 170px;
  }

  .nav-links {
    display: none;
  }

  .cta {
    flex-direction: column;
    align-items: flex-start;
  }
}

@media (max-width: 550px) {
  .cards,
  .cert-grid,
  .stats,
  .explore-grid {
    grid-template-columns: 1fr;
  }

  h1 {
    font-size: 43px;
  }
}

.tamil-name {
  margin: 10px 0 18px;
  font-size: clamp(22px, 3vw, 30px);
  font-weight: 600;
  color: #c4b5fd;
  letter-spacing: 0.3px;
}
</style>
</head>

<body>

<nav>
  <div class="container nav-inner">

    <div class="brand">
      <div class="logo">PN</div>
      <div>
        <strong>Poongudivanan Natarajan</strong>
        <small>Software Architect</small>
      </div>
    </div>

    <div class="nav-links">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#focus">Focus</a>
      <a href="#skills">Skills</a>
      <a href="#certifications">Certifications</a>
      <a href="#connect">Connect</a>
    </div>

  </div>
</nav>


<!-- HERO -->

<header class="hero" id="home">
<div class="container hero-grid">

  <div>
    <div class="hello">👋 Hi, I'm</div>

    <h1>
      Poongudivanan
      <span class="gradient-text">Natarajan</span>
    </h1>
    <div class="tamil-name">பூங்குடிவாணன் நடராஜன்</div>
    <div class="subtitle">
      Software Architect | Adobe Commerce | Cloud |
      Composable Commerce | AI
    </div>

    <div class="hero-meta">
      📍 Bengaluru, India &nbsp;&nbsp;
      💼 Adobe
      <br><br>
      🚀 Building scalable digital commerce platforms and exploring
      the future of AI-powered software architecture
    </div>

    <div class="buttons">
      <a class="btn btn-primary"
         href="https://github.com/poongud">
         ◉ View on GitHub
      </a>

      <a class="btn"
         href="https://www.linkedin.com/in/poongudivanan/">
         in &nbsp; Connect on LinkedIn
      </a>
    </div>
  </div>


  <div class="profile-side">
    
    <img class="avatar" src="https://media.licdn.com/dms/image/v2/C5603AQERL2CrFN-_bw/profile-displayphoto-shrink_800_800/profile-displayphoto-shrink_800_800/0/1650297964136?e=1790208000&v=beta&t=A7X-iVwa0F_lwkOeX08l9cr8SsdwB-oGhoHOXQihzcQ">
    <div class="quote">
      “Good architecture isn't about using the newest technology.
      It's about making the right trade-offs for the problem you're solving.”
    </div>

  </div>

</div>
</header>


<!-- ABOUT -->

<section id="about">
<div class="container">

<h2 class="section-title">👨‍💻 About Me</h2>

<div class="about-grid">

<div class="about-copy">

<p>
I'm a <strong>Software Architect and Digital Commerce Technology Leader</strong>
with <strong>12+ years of experience</strong> designing, developing,
and scaling enterprise software and digital commerce solutions.
</p>

<p>
My core expertise is around
<strong>Adobe Commerce / Magento architecture</strong>,
cloud-native systems, APIs, integrations, and scalable commerce platforms.
</p>

<p>
Today, I'm particularly interested in the intersection of:
</p>

<p class="highlight">
Commerce × Cloud × Composable Architecture ×
Generative AI × Agentic Systems
</p>

<p>
I enjoy solving complex engineering problems, evaluating architectural
trade-offs, experimenting with emerging technologies, and sharing what
I learn with the developer community.
</p>

</div>


<div class="stats">

<div class="stat">
<div>
<div class="stat-icon">💼</div>
<strong>12+</strong>
Years of Experience
</div>
</div>

<div class="stat">
<div>
<div class="stat-icon">⌨️</div>
<strong style="color:#60a5fa">Architect</strong>
By Role
</div>
</div>

<div class="stat">
<div>
<div class="stat-icon">☁️</div>
<strong style="color:#38bdf8">Cloud</strong>
AWS
</div>
</div>

<div class="stat">
<div>
<div class="stat-icon">👥</div>
<strong style="color:#34d399">Community</strong>
Speaker & Contributor
</div>
</div>

</div>

</div>
</div>
</section>


<!-- FOCUS -->

<section id="focus">
<div class="container">

<h2 class="section-title">🎯 What I Focus On</h2>

<div class="cards">

<div class="card purple">
<div class="card-icon">🛒</div>
<h3>Digital Commerce</h3>
<p>
Designing scalable and maintainable commerce platforms using
Adobe Commerce / Magento, APIs, integrations, and modern commerce architecture.
</p>
</div>

<div class="card blue">
<div class="card-icon">🏗️</div>
<h3>Software Architecture</h3>
<p>
Designing systems focused on scalability, extensibility,
reliability, performance, and long-term maintainability.
</p>
</div>

<div class="card cyan">
<div class="card-icon">☁️</div>
<h3>Cloud Architecture</h3>
<p>
Building cloud-based solutions using modern infrastructure,
distributed systems, APIs, and integration patterns.
</p>
</div>

<div class="card green">
<div class="card-icon">🧩</div>
<h3>Composable Commerce</h3>
<p>
Exploring independent applications, services,
API-first platforms, and composable digital experiences.
</p>
</div>

<div class="card orange">
<div class="card-icon">🤖</div>
<h3>AI & Agentic Systems</h3>
<p>
Experimenting with Generative AI, AI agents,
LLM-powered developer tools, automation,
and intelligent commerce experiences.
</p>
</div>

</div>
</div>
</section>


<!-- CERTIFICATIONS -->

<section id="certifications">
<div class="container">

<div class="two-columns">

<div>

<h2 class="section-title">🏅 Certifications</h2>

<div class="panel cert-grid">

<div class="cert">
<strong>🔴 Adobe Certified Master</strong>
<small>Adobe Commerce Architect</small>
</div>

<div class="cert">
<strong>🔴 Adobe Certified Expert</strong>
<small>Magento Commerce Developer</small>
</div>

<div class="cert">
<strong>☁️ AWS Certified</strong>
<small>Solutions Architect – Associate</small>
</div>

<div class="cert">
<strong>🏅 SwiftOtter Certification</strong>
<small>Challenge Achiever</small>
</div>

</div>
</div>


<div>

<h2 class="section-title">🎓 Education</h2>

<div class="panel">

<h3>The University of Texas at Austin</h3>

<p>
Executive / Professional Education
</p>

<p style="color:var(--muted)">
2024 – 2025 &nbsp; • &nbsp;
Academic Performance: <strong>3.88</strong>
</p>

</div>

</div>

</div>
</div>
</section>


<!-- TECHNOLOGY -->

<section id="skills">
<div class="container">

<h2 class="section-title">⌨️ Technology & Architecture</h2>

<div class="tags">

<span class="tag">Adobe Commerce</span>
<span class="tag">Magento 2</span>
<span class="tag">PHP</span>
<span class="tag">TypeScript</span>
<span class="tag">Node.js</span>
<span class="tag">REST API</span>
<span class="tag">GraphQL</span>
<span class="tag">AWS</span>
<span class="tag">Microservices</span>
<span class="tag">Docker</span>
<span class="tag">Kubernetes</span>
<span class="tag">Event-Driven</span>
<span class="tag">Serverless</span>
<span class="tag">CI/CD</span>
<span class="tag">Linux</span>
<span class="tag">MySQL</span>
<span class="tag">ElasticSearch</span>
<span class="tag">Redis</span>
<span class="tag">AI / LLM</span>
<span class="tag">RAG</span>
<span class="tag">MCP</span>
<span class="tag">Agentic AI</span>

</div>

</div>
</section>


<!-- EXPLORING -->

<section>
<div class="container">

<h2 class="section-title">🚀 What I'm Exploring</h2>

<div class="explore-grid">

<div class="explore">
<span>🤖</span>
AI Agents for Software Engineering
</div>

<div class="explore">
<span>🧠</span>
Agentic AI Architectures
</div>

<div class="explore">
<span>🛒</span>
AI-powered Commerce
</div>

<div class="explore">
<span>🧩</span>
Composable Commerce
</div>

<div class="explore">
<span>☁️</span>
Cloud-native Commerce Architecture
</div>

<div class="explore">
<span>🔌</span>
API Mesh & Integration
</div>

<div class="explore">
<span>💡</span>
AI-assisted Developer Workflows
</div>

</div>

</div>
</section>


<!-- CONNECT -->

<div class="container" id="connect">

<div class="cta">

<div>
<h3>Let's build the future of Commerce, Cloud and AI together!</h3>

<div class="social">
<a href="https://www.linkedin.com/in/poongudivanan/">LinkedIn</a>
&nbsp; | &nbsp;
<a href="https://github.com/poongud">GitHub</a>
</div>
</div>

<div>
<div class="cta-quote">
“Build. Learn. Architect. Share.”
</div>

<div style="color:var(--muted)">
Exploring the future of Commerce, Cloud and AI.
</div>
</div>

</div>


<footer>

<div>
© 2026 Poongudivanan Natarajan.
Built with ❤️ using GitHub Pages.
</div>

<div>
Stay curious. Keep building. 🚀
</div>

</footer>

</div>

</body>
</html>
