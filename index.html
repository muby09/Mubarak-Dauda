<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mubarak Dauda — Systems, Security &amp; Data</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Inter:wght@400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --bg:#0B1220;
    --bg-alt:#0E1626;
    --surface:#131C30;
    --surface-2:#172140;
    --border:#24314D;
    --text:#E7ECF5;
    --text-muted:#8FA0BC;
    --text-dim:#5D6C89;
    --accent:#4FD1C5;
    --accent-dim:rgba(79,209,197,0.14);
    --amber:#F2A65A;
    --font-display:'Space Grotesk', sans-serif;
    --font-body:'Inter', sans-serif;
    --font-mono:'JetBrains Mono', monospace;
  }
  *{margin:0;padding:0;box-sizing:border-box;}
  html{scroll-behavior:smooth;}
  body{
    background:var(--bg);
    color:var(--text);
    font-family:var(--font-body);
    line-height:1.6;
    overflow-x:hidden;
  }
  a{color:inherit;text-decoration:none;}
  ::selection{background:var(--accent-dim);color:var(--accent);}

  /* background grid texture */
  .grid-bg{
    position:fixed;inset:0;z-index:0;pointer-events:none;
    background-image:
      linear-gradient(rgba(79,209,197,0.045) 1px, transparent 1px),
      linear-gradient(90deg, rgba(79,209,197,0.045) 1px, transparent 1px);
    background-size:44px 44px;
    mask-image:radial-gradient(ellipse 90% 60% at 50% 0%, black 40%, transparent 90%);
  }

  .wrap{max-width:1080px;margin:0 auto;padding:0 32px;position:relative;z-index:1;}

  /* NAV */
  header{
    position:sticky;top:0;z-index:50;
    backdrop-filter:blur(10px);
    background:rgba(11,18,32,0.75);
    border-bottom:1px solid var(--border);
  }
  nav{display:flex;align-items:center;justify-content:space-between;padding:18px 0;}
  .logo{font-family:var(--font-mono);font-size:14px;color:var(--text);letter-spacing:0.02em;}
  .logo span{color:var(--accent);}
  .nav-links{display:flex;gap:28px;list-style:none;font-family:var(--font-mono);font-size:13px;color:var(--text-muted);}
  .nav-links a:hover{color:var(--accent);}
  .nav-links li{white-space:nowrap;}
  @media(max-width:720px){.nav-links{display:none;}}

  /* HERO */
  .hero{
    padding:110px 0 90px;
    display:grid;grid-template-columns:1.15fr 0.85fr;gap:56px;align-items:center;
  }
  @media(max-width:860px){.hero{grid-template-columns:1fr;padding:70px 0 50px;}}
  .eyebrow{
    font-family:var(--font-mono);font-size:13px;color:var(--accent);
    display:flex;align-items:center;gap:10px;margin-bottom:20px;letter-spacing:0.04em;
  }
  .eyebrow::before{content:'';width:8px;height:8px;border-radius:50%;background:var(--accent);box-shadow:0 0 0 4px var(--accent-dim);animation:pulse 2s infinite;}
  @keyframes pulse{0%,100%{opacity:1;}50%{opacity:0.4;}}
  h1{
    font-family:var(--font-display);
    font-size:clamp(38px,5.5vw,60px);
    font-weight:700;line-height:1.05;letter-spacing:-0.01em;
    margin-bottom:20px;
  }
  h1 .accent{color:var(--accent);}
  .hero-sub{
    font-size:17px;color:var(--text-muted);max-width:520px;margin-bottom:32px;
  }
  .hero-actions{display:flex;gap:14px;flex-wrap:wrap;}
  .btn{
    font-family:var(--font-mono);font-size:13px;padding:12px 22px;border-radius:6px;
    border:1px solid var(--border);transition:all .2s ease;
  }
  .btn-primary{background:var(--accent);color:#06171a;border-color:var(--accent);font-weight:600;}
  .btn-primary:hover{background:#6fe0d5;}
  .btn-ghost{color:var(--text);}
  .btn-ghost:hover{border-color:var(--accent);color:var(--accent);}

  /* Hero network panel (signature element) */
  .netpanel{
    background:var(--surface);border:1px solid var(--border);border-radius:12px;
    padding:22px;font-family:var(--font-mono);
  }
  .netpanel-head{
    display:flex;justify-content:space-between;align-items:center;
    font-size:11px;color:var(--text-dim);margin-bottom:16px;
    border-bottom:1px solid var(--border);padding-bottom:12px;
  }
  .netpanel-head .dots{display:flex;gap:5px;}
  .netpanel-head .dots span{width:7px;height:7px;border-radius:50%;background:var(--border);}
  svg.topology{width:100%;height:auto;display:block;}
  .node-label{font-size:10.5px;fill:var(--text-muted);font-family:var(--font-mono);}
  .node-value{font-size:9px;fill:var(--text-dim);font-family:var(--font-mono);}

  /* SECTIONS */
  section{padding:90px 0;border-bottom:1px solid var(--border);}
  .section-head{margin-bottom:44px;}
  .prompt{
    font-family:var(--font-mono);font-size:12.5px;color:var(--accent);margin-bottom:10px;
  }
  .prompt::before{content:'root@mubarak:~$ ';color:var(--text-dim);}
  h2{
    font-family:var(--font-display);font-size:clamp(26px,3.5vw,34px);font-weight:600;letter-spacing:-0.01em;
  }

  /* ABOUT */
  .about-grid{display:grid;grid-template-columns:1fr 280px;gap:48px;}
  @media(max-width:760px){.about-grid{grid-template-columns:1fr;}}
  .about-text p{color:var(--text-muted);margin-bottom:16px;font-size:15.5px;max-width:600px;}
  .about-text strong{color:var(--text);font-weight:600;}
  .fact-card{background:var(--surface);border:1px solid var(--border);border-radius:10px;padding:20px;}
  .fact-card + .fact-card{margin-top:14px;}
  .fact-card .k{font-family:var(--font-mono);font-size:11px;color:var(--text-dim);text-transform:uppercase;letter-spacing:0.05em;margin-bottom:6px;}
  .fact-card .v{font-size:14.5px;color:var(--text);}

  /* EXPERIENCE */
  .timeline{position:relative;padding-left:28px;}
  .timeline::before{content:'';position:absolute;left:5px;top:6px;bottom:6px;width:1px;background:var(--border);}
  .tl-item{position:relative;padding-bottom:44px;}
  .tl-item:last-child{padding-bottom:0;}
  .tl-item::before{
    content:'';position:absolute;left:-28px;top:4px;width:11px;height:11px;border-radius:50%;
    background:var(--bg);border:2px solid var(--accent);
  }
  .tl-date{font-family:var(--font-mono);font-size:12px;color:var(--accent);margin-bottom:6px;}
  .tl-role{font-family:var(--font-display);font-size:19px;font-weight:600;margin-bottom:2px;}
  .tl-org{color:var(--text-muted);font-size:14px;margin-bottom:14px;}
  .tl-item ul{list-style:none;color:var(--text-muted);font-size:14.5px;}
  .tl-item li{position:relative;padding-left:18px;margin-bottom:8px;}
  .tl-item li::before{content:'▸';position:absolute;left:0;color:var(--text-dim);}

  /* PROJECTS */
  .proj-grid{display:grid;grid-template-columns:1fr 1fr;gap:22px;}
  @media(max-width:760px){.proj-grid{grid-template-columns:1fr;}}
  .proj-card{
    background:var(--surface);border:1px solid var(--border);border-radius:10px;padding:26px;
    transition:border-color .2s ease, transform .2s ease;display:flex;flex-direction:column;
  }
  .proj-card:hover{border-color:var(--accent);transform:translateY(-2px);}
  .proj-card.featured{grid-column:1 / -1;}
  .proj-top{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:12px;}
  .proj-title{font-family:var(--font-display);font-size:19px;font-weight:600;}
  .proj-link{font-family:var(--font-mono);font-size:12px;color:var(--text-dim);border:1px solid var(--border);border-radius:5px;padding:5px 10px;white-space:nowrap;}
  .proj-link:hover{color:var(--accent);border-color:var(--accent);}
  .proj-desc{color:var(--text-muted);font-size:14.5px;margin-bottom:16px;flex:1;}
  .tag-row{display:flex;gap:8px;flex-wrap:wrap;}
  .tag{font-family:var(--font-mono);font-size:11px;color:var(--accent);background:var(--accent-dim);padding:4px 9px;border-radius:4px;}

  /* SKILLS */
  .skill-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:18px;}
  .skill-card{background:var(--surface);border:1px solid var(--border);border-radius:10px;padding:20px;}
  .skill-card h3{font-family:var(--font-mono);font-size:12px;color:var(--amber);text-transform:uppercase;letter-spacing:0.05em;margin-bottom:14px;}
  .skill-card ul{list-style:none;color:var(--text-muted);font-size:14px;}
  .skill-card li{margin-bottom:7px;}

  /* PUBLICATION & LEADERSHIP */
  .split{display:grid;grid-template-columns:1fr 1fr;gap:24px;}
  @media(max-width:760px){.split{grid-template-columns:1fr;}}
  .info-card{background:var(--surface);border:1px solid var(--border);border-radius:10px;padding:26px;}
  .info-card .tag-label{font-family:var(--font-mono);font-size:11px;color:var(--accent);text-transform:uppercase;letter-spacing:0.05em;margin-bottom:12px;}
  .info-card h3{font-family:var(--font-display);font-size:17px;font-weight:600;margin-bottom:10px;line-height:1.35;}
  .info-card p{color:var(--text-muted);font-size:14px;}

  /* CONTACT / FOOTER */
  footer{padding:90px 0 50px;}
  .contact-box{
    background:var(--surface);border:1px solid var(--border);border-radius:14px;
    padding:48px;text-align:center;
  }
  .contact-box h2{margin-bottom:14px;}
  .contact-box p{color:var(--text-muted);margin-bottom:28px;max-width:440px;margin-left:auto;margin-right:auto;}
  .contact-links{display:flex;gap:16px;justify-content:center;flex-wrap:wrap;margin-bottom:44px;}
  .foot-meta{
    display:flex;justify-content:space-between;color:var(--text-dim);font-family:var(--font-mono);font-size:12px;
    flex-wrap:wrap;gap:10px;
  }

  /* reveal on scroll */
  .reveal{opacity:0;transform:translateY(16px);transition:opacity .6s ease, transform .6s ease;}
  .reveal.visible{opacity:1;transform:translateY(0);}

  @media (prefers-reduced-motion: reduce){
    *{animation:none !important;transition:none !important;}
  }
</style>
</head>
<body>

<div class="grid-bg"></div>

<header>
  <div class="wrap">
    <nav>
      <div class="logo">Mubarak<span>.</span>Dauda</div>
      <ul class="nav-links">
        <li><a href="#about">About</a></li>
        <li><a href="#experience">Experience</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </div>
</header>

<div class="wrap">

  <!-- HERO -->
  <section class="hero" style="border-bottom:none;padding-top:100px;">
    <div>
      <div class="eyebrow">SYSTEMS &nbsp;·&nbsp; SECURITY &nbsp;·&nbsp; DATA</div>
      <h1>Mubarak Dauda<br>keeps the <span class="accent">infrastructure</span><br>honest.</h1>
      <p class="hero-sub">Computer Engineering graduate working across IT support, network security, and ERP systems — turning messy operations into infrastructure that runs, and data that people actually trust.</p>
      <div class="hero-actions">
        <a href="#projects" class="btn btn-primary">View Projects</a>
        <a href="#contact" class="btn btn-ghost">Get in Touch</a>
      </div>
    </div>

    <div class="netpanel">
      <div class="netpanel-head">
        <span>status.log</span>
        <div class="dots"><span></span><span></span><span></span></div>
      </div>
      <svg class="topology" viewBox="0 0 260 220" fill="none">
        <!-- connecting lines -->
        <line x1="130" y1="30" x2="55" y2="100" stroke="#24314D" stroke-width="1.5"/>
        <line x1="130" y1="30" x2="205" y2="100" stroke="#24314D" stroke-width="1.5"/>
        <line x1="130" y1="30" x2="55" y2="185" stroke="#24314D" stroke-width="1.5"/>
        <line x1="130" y1="30" x2="205" y2="185" stroke="#24314D" stroke-width="1.5"/>
        <line x1="55" y1="100" x2="55" y2="185" stroke="#24314D" stroke-width="1" stroke-dasharray="3 3"/>
        <line x1="205" y1="100" x2="205" y2="185" stroke="#24314D" stroke-width="1" stroke-dasharray="3 3"/>

        <!-- center node -->
        <circle cx="130" cy="30" r="7" fill="#4FD1C5"/>
        <circle cx="130" cy="30" r="12" fill="none" stroke="#4FD1C5" stroke-width="1" opacity="0.4"/>
        <text x="130" y="16" text-anchor="middle" class="node-label" fill="#E7ECF5">MD</text>

        <!-- 4 nodes -->
        <circle cx="55" cy="100" r="5.5" fill="#0B1220" stroke="#4FD1C5" stroke-width="1.5"/>
        <text x="55" y="122" text-anchor="middle" class="node-label">SYSTEMS</text>
        <text x="55" y="134" text-anchor="middle" class="node-value">LAN · Linux</text>

        <circle cx="205" cy="100" r="5.5" fill="#0B1220" stroke="#F2A65A" stroke-width="1.5"/>
        <text x="205" y="122" text-anchor="middle" class="node-label">SECURITY</text>
        <text x="205" y="134" text-anchor="middle" class="node-value">Vuln · Traffic</text>

        <circle cx="55" cy="185" r="5.5" fill="#0B1220" stroke="#4FD1C5" stroke-width="1.5"/>
        <text x="55" y="207" text-anchor="middle" class="node-label">DATA</text>
        <text x="55" y="219" text-anchor="middle" class="node-value">SQL · Reports</text>

        <circle cx="205" cy="185" r="5.5" fill="#0B1220" stroke="#F2A65A" stroke-width="1.5"/>
        <text x="205" y="207" text-anchor="middle" class="node-label">ERP</text>
        <text x="205" y="219" text-anchor="middle" class="node-value">Odoo · Process</text>
      </svg>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="reveal">
    <div class="section-head">
      <div class="prompt">whoami</div>
      <h2>About</h2>
    </div>
    <div class="about-grid">
      <div class="about-text">
        <p>I spend most of my time in the unglamorous middle of tech — the place where <strong>servers</strong>, <strong>spreadsheets</strong>, and <strong>staff logins</strong> all have to work at the same time. Over the last two years I've kept a company's LAN running, rolled out an ERP system across departments, hunted vulnerabilities in web applications, and turned raw operational data into reports people actually use to make decisions.</p>
        <p>I like problems that sit between infrastructure and business — because that's usually where small failures quietly become expensive ones, and where a little structure goes a long way.</p>
        <p>Outside of work, I've mentored 100+ young people through a national community service program, co-authored an IEEE research paper on GPA prediction, and I'm currently deepening my cybersecurity practice through hands-on labs on HackTheBox and OverTheWire.</p>
      </div>
      <div>
        <div class="fact-card">
          <div class="k">Based in</div>
          <div class="v">Kaduna, Nigeria</div>
        </div>
        <div class="fact-card">
          <div class="k">Education</div>
          <div class="v">B.Sc. Computer Engineering, University of Kyrenia </div>
        </div>
        <div class="fact-card">
          <div class="k">Currently</div>
          <div class="v">IT Assistant & ERP Lead at Technovati Limited</div>
        </div>
      </div>
    </div>
  </section>

  <!-- EXPERIENCE -->
  <section id="experience" class="reveal">
    <div class="section-head">
      <div class="prompt">cat experience.log</div>
      <h2>Experience</h2>
    </div>
    <div class="timeline">
      <div class="tl-item">
        <div class="tl-date">May 2024 — Present</div>
        <div class="tl-role">IT Assistant / Social Media Manager</div>
        <div class="tl-org">Technovati Limited · Kaduna</div>
        <ul>
          <li>Managed and optimized the company website and digital presence; designed visual content to strengthen branding.</li>
          <li>Diagnosed and resolved hardware, software, and network issues; maintained LAN infrastructure and set up video conferencing systems.</li>
          <li>Cleaned and transformed meter installation data into daily, weekly, and monthly reports; tracked progress and supported sales reconciliation.</li>
          <li>Acted as Single Point of Contact for the Odoo ERP rollout — mapped business workflows, defined system requirements, and trained staff across departments.</li>
        </ul>
      </div>
      <div class="tl-item">
        <div class="tl-date">May 2023 — April 2024</div>
        <div class="tl-role">NYSC Corper</div>
        <div class="tl-org">Kaduna Polytechnic · Kaduna</div>
        <ul>
          <li>Delivered lectures and tutorials on computer engineering and network management.</li>
          <li>Prepared course materials and supported students in understanding networking concepts.</li>
        </ul>
      </div>
      <div class="tl-item">
        <div class="tl-date">Sept 2021 — Sept 2022</div>
        <div class="tl-role">Intern</div>
        <div class="tl-org">International Research Centre for AI &amp; IoT, NEU</div>
        <ul>
          <li>Worked on web development and database management tasks.</li>
          <li>Assisted in research and project coordination focused on AI and IoT systems.</li>
        </ul>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="reveal">
    <div class="section-head">
      <div class="prompt">ls ./projects</div>
      <h2>Featured Projects</h2>
    </div>
    <div class="proj-grid">

      <div class="proj-card featured">
        <div class="proj-top">
          <div class="proj-title">Meter Information Management System (MIMS)</div>
          <a href="https://github.com/muby09/MIMS" target="_blank" class="proj-link">github ↗</a>
        </div>
        <div class="proj-desc">A full-lifecycle system for managing meter installations — from scheduling and team-lead requests to inventory and per-customer install records. Built with role-based access for regional admins, installers, data-entry staff, supervisors, and inventory staff, real-time reporting, and NERC-compliant regulatory export.</div>
        <div class="tag-row">
          <span class="tag">Laravel</span><span class="tag">Vue</span><span class="tag">MySQL/SQLite</span><span class="tag">Pest</span>
        </div>
      </div>

      <div class="proj-card">
        <div class="proj-top">
          <div class="proj-title">Vulnerability Assessment</div>
        </div>
        <div class="proj-desc">Conducted a vulnerability assessment on OWASP Juice Shop as part of the 3MTT program, analysed web application weaknesses, and proposed mitigations — plus a secure network architecture built around firewalls and IDS/IPS.</div>
        <div class="tag-row">
          <span class="tag">Wireshark</span><span class="tag">OWASP</span><span class="tag">IDS/IPS</span>
        </div>
      </div>

      <div class="proj-card">
        <div class="proj-top">
          <div class="proj-title">Student Management System</div>
          <a href="https://github.com/muby09/studentsys" target="_blank" class="proj-link">github ↗</a>
        </div>
        <div class="proj-desc">A university course registration system with distinct login paths for students, instructors, advisors, and admins — covering enrollment, grading, and transcript access.</div>
        <div class="tag-row">
          <span class="tag">PHP</span><span class="tag">MySQL</span><span class="tag">HTML/CSS</span>
        </div>
      </div>

      <div class="proj-card featured">
        <div class="proj-top">
          <div class="proj-title">Backend Engineering Challenges — HNG12</div>
          <a href="https://github.com/muby09/fastapi-book-project" target="_blank" class="proj-link">github ↗</a>
        </div>
        <div class="proj-desc">A set of backend challenges from the HNG internship program: a public info API, a number-classification API that returns mathematical properties and a fun fact, and a FastAPI-based book service exploring DevOps-flavored backend work.</div>
        <div class="tag-row">
          <span class="tag">PHP</span><span class="tag">Python</span><span class="tag">FastAPI</span><span class="tag">DevOps</span>
        </div>
      </div>

    </div>
  </section>

  <!-- SKILLS -->
  <section id="skills" class="reveal">
    <div class="section-head">
      <div class="prompt">cat skills.json</div>
      <h2>Skills</h2>
    </div>
    <div class="skill-grid">
      <div class="skill-card">
        <h3>IT & Systems</h3>
        <ul><li>Technical Support</li><li>System Maintenance</li><li>LAN Administration</li><li>Linux</li></ul>
      </div>
      <div class="skill-card">
        <h3>Cybersecurity</h3>
        <ul><li>Network Security</li><li>Vulnerability Assessment</li><li>Web Security</li><li>Traffic Analysis</li></ul>
      </div>
      <div class="skill-card">
        <h3>Data & Analysis</h3>
        <ul><li>Data Cleaning</li><li>Transformation</li><li>Reporting</li><li>Performance Tracking</li></ul>
      </div>
      <div class="skill-card">
        <h3>ERP Systems</h3>
        <ul><li>Odoo Implementation</li><li>Business Process Mapping</li><li>User Training</li></ul>
      </div>
      <div class="skill-card">
        <h3>Tools & Languages</h3>
        <ul><li>Wireshark · Excel · SQL</li><li>PHP · Python</li><li>Vue · Laravel</li></ul>
      </div>
      <div class="skill-card">
        <h3>Other</h3>
        <ul><li>Problem Solving</li><li>Communication</li><li>Training & Documentation</li></ul>
      </div>
    </div>
  </section>

  <!-- PUBLICATION & LEADERSHIP -->
  <section class="reveal">
    <div class="section-head">
      <div class="prompt">cat about --extended</div>
      <h2>Publication &amp; Leadership</h2>
    </div>
    <div class="split">
      <div class="info-card">
        <div class="tag-label">Research Publication · IEEE, 2022</div>
        <a href="https://ieeexplore.ieee.org/document/9898801">A Step Ahead: Students' GPA Prediction Based on Support Vector Machines</a>
        <p>Co-authored research applying support vector machine models to predict student academic performance.</p>
      </div>
      <div class="info-card">
        <div class="tag-label">Leadership · Jan – April 2024</div>
        <h3>President, Digital On-boarders CDS Group</h3>
        <p>Directed group activities and mentored 100+ members. Delivered Google Digital Marketing training to 50+ NEET youth, championing digital literacy and community empowerment.</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <footer id="contact" class="reveal">
    <div class="contact-box">
      <div class="prompt" style="justify-content:center;display:flex;">ping mubarak </div>
      <h2>Let's talk.</h2>
      <p>Open to roles in IT systems, cybersecurity, and Data/ERP-driven operations</p>
      <div class="contact-links">
        <a href="mailto:mmubarak0124@gmail.com" class="btn btn-primary">mmubarak0124@gmail.com</a>
        <a href="tel:+2348183856470" class="btn btn-ghost">+234 818 385 6470</a>
        <a href="https://github.com/muby09" target="_blank" class="btn btn-primary">github.com/muby09</a>
      </div>
      <div class="foot-meta" style="justify-content:center;display:flex">
        <h3 > © 2026 Mubarak Dauda</h3>
      </div>
    </div>
  </footer>

</div>

<script>
  const revealEls = document.querySelectorAll('.reveal');
  const io = new IntersectionObserver((entries)=>{
    entries.forEach(e=>{
      if(e.isIntersecting){ e.target.classList.add('visible'); io.unobserve(e.target); }
    });
  },{threshold:0.12});
  revealEls.forEach(el=>io.observe(el));
</script>

</body>
</html>
