<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Paul Abiodun — IT Support Specialist & Portfolio</title>
  <meta name="description" content="Paul Abiodun — IT Support Specialist. Portfolio showing work, experience, skills and contact details.">
  <link rel="icon" href="favicon.png">
  <style>
    /* Minimal, modern, responsive portfolio - single-file template */
    :root{
      --bg:#ffffff; --card:#f8fafb; --muted:#64748b; --accent:#0fb9b1; --text:#0f172a; --glass: rgba(15,23,42,0.03);
      --maxw:1100px; --radius:12px; --gap:20px; font-family: Inter, ui-sans-serif, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    *{box-sizing:border-box}
    html,body{height:100%;margin:0;background:linear-gradient(180deg,#ffffff,#f3f7f7);color:var(--text)}
    a{color:var(--accent);text-decoration:none}
    .wrap{max-width:var(--maxw);margin:24px auto;padding:24px}

    /* header */
    header{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:60px;height:60px;border-radius:14px;border:3px solid var(--accent);overflow:hidden}
    .logo img{width:100%;height:100%;object-fit:cover;display:block}
    .nav{display:flex;gap:14px;align-items:center}
    .btn{background:var(--accent);color:white;padding:10px 14px;border-radius:10px}

    /* hero */
    .hero{display:grid;grid-template-columns:1fr 380px;gap:24px;align-items:center;margin-top:18px}
    .headline h1{font-size:34px;margin:0 0 8px}
    .headline p{margin:0;color:var(--muted)}
    .cta{margin-top:18px;display:flex;gap:12px}

    /* card */
    .card{background:var(--card);padding:18px;border-radius:var(--radius);box-shadow:0 6px 18px rgba(11,28,33,0.04)}

    /* skills/projects */
    .skills{display:flex;flex-wrap:wrap;gap:10px}
    .skill{background:var(--glass);padding:8px 12px;border-radius:999px;color:var(--text);font-size:13px}

    .projects{display:grid;grid-template-columns:repeat(2,1fr);gap:16px;margin-top:12px}
    .project{padding:14px;border-radius:10px;background:white;display:flex;flex-direction:column;gap:8px;border:1px solid rgba(15,23,42,0.04)}
    .project img{width:100%;height:140px;object-fit:cover;border-radius:8px}
    .meta{font-size:13px;color:var(--muted)}

    /* two-column lower sections */
    .columns{display:grid;grid-template-columns:2fr 1fr;gap:var(--gap);margin-top:18px}
    .contact .field{display:flex;flex-direction:column;margin-bottom:12px}
    .field input,.field textarea{padding:10px;border-radius:8px;border:1px solid rgba(15,23,42,0.06);font-size:14px}
    .field textarea{min-height:120px;resize:vertical}

    footer{margin-top:28px;padding:18px;text-align:center;color:var(--muted);font-size:14px}

    /* responsive */
    @media (max-width:980px){.hero{grid-template-columns:1fr} .projects{grid-template-columns:1fr} .columns{grid-template-columns:1fr} }

    /* small nav mobile */
    @media (max-width:640px){.nav{display:none}}

  </style>
</head>
<body>
  <div class="wrap" id="page">
    <header>
      <div class="brand">
        <div class="logo card"><img src="profile.png" alt="Paul Abiodun"></div>
        <div>
          <div style="font-weight:700">Paul Abiodun</div>
          <div style="color:var(--muted);font-size:14px">IT Support Specialist — Liverpool</div>
        </div>
      </div>
      <nav class="nav" aria-label="Main Navigation">
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="https://pabiodun.github.io/PaulA-CV/">Resume</a>
        <a href="#contact" class="btn">Contact</a>
      </nav>
    </header>

    <section class="hero">
      <div>
        <div class="headline">
          <h1>IT Support Specialist — helping people and systems run smoothly</h1>
          <p>10+ years supporting enterprise banking systems, endpoint management, AD provisioning, application testing and user training. Based in Liverpool, UK — available for remote and onsite roles.</p>
        </div>

        <div class="card" style="margin-top:16px">
          <div style="display:flex;align-items:center;justify-content:space-between;gap:12px">
            <div>
              <div style="font-size:13px;color:var(--muted)">Email</div>
              <div style="font-weight:600">paulaxcity@yahoo.com</div>
            </div>
            <div>
              <div style="font-size:13px;color:var(--muted)">Phone</div>
              <div style="font-weight:600">+44 (0) 772 150 2616</div>
            </div>
          </div>

          <div style="margin-top:14px">
            <div style="font-size:13px;color:var(--muted)">Core skills</div>
            <div class="skills" style="margin-top:10px">
              <div class="skill">Active Directory</div>
              <div class="skill">ServiceNow / Ticketing</div>
              <div class="skill">Windows & macOS</div>
              <div class="skill">Endpoint Management</div>
              <div class="skill">App Testing (Banking)</div>
              <div class="skill">Scripting (Bash)</div>
            </div>
          </div>
        </div>

        <div id="projects" style="margin-top:16px">
          <h3>Selected Projects</h3>
          <div class="projects">
            <article class="project">
              <img src="assets/project-1.png" alt="Onboarding Automation">
              <div style="font-weight:700">Onboarding Automation</div>
              <div class="meta">Cut setup time by 30% through scripted checklists and Intune provisioning.</div>
            </article>

            <article class="project">
              <img src="assets/project-2.png" alt="Knowledge Base">
              <div style="font-weight:700">Knowledge Base & KB Articles</div>
              <div class="meta">Authored documentation that reduced repeat tickets by 18%.</div>
            </article>

          </div>
        </div>

      </div>

      <aside style="width:100%">
        <div class="card">
          <h3 id="about">About</h3>
          <p style="color:var(--muted)">Dedicated and customer-focused IT Support Specialist with extensive experience in banking environments. Strong troubleshooting skills, excellent customer service, and a track record of improving operational efficiency.</p>

          <h3 style="margin-top:14px">Experience</h3>
          <div style="font-weight:700">Instiq Professional Services</div>
          <div class="meta">IT Support Specialist — Apr 2021 – Present (Lagos & UK)</div>
          <div style="height:10px"></div>
          <div style="font-weight:700">Polaris Bank Ltd</div>
          <div class="meta">IT Support Engineer — Aug 2011 – Mar 2021 (Lagos)</div>
        </div>

        <div class="card" style="margin-top:16px">
          <h3>Download Resume</h3>
          <p class="meta">PDF copy of full CV, print-friendly.</p>
          <a href="https://pabiodun.github.io/PaulA-CV/" class="btn" download>Download CV (PDF)</a>
        </div>

      </aside>
    </section>

    <div class="columns">
      <div>
        <section class="card">
          <h3>Full Experience</h3>
          <p class="meta">(Selected roles and responsibilities)</p>
          <ul>
            <li>First-line support, ticket triage and SLAs for enterprise users.</li>
            <li>Active Directory management, provisioning and access control.</li>
            <li>Application testing and API endpoint checks for banking apps (TME, SRG, ROA).</li>
            <li>Endpoint management, imaging and deployments (SCCM / Intune).</li>
            <li>Monitoring, backups, and disaster recovery participation.</li>
          </ul>
        </section>

        <section class="card" style="margin-top:12px">
          <h3>Education & Certifications</h3>
          <ul>
            <li>B.Sc. Computer Science — ESPAM Formation University (2020)</li>
            <li>OND Computer Engineering — Federal Polytechnic Ede (2008)</li>
            <li>Microsoft Azure Fundamentals — 2023</li>
          </ul>
        </section>
      </div>

      <aside>
        <div class="card contact" id="contact">
          <h3>Contact</h3>
          <form action="mailto:paulaxcity@yahoo.com" method="post" enctype="text/plain">
            <div class="field"><label for="name">Your name</label><input id="name" name="name" required></div>
            <div class="field"><label for="email">Email</label><input id="email" name="email" type="email" required></div>
            <div class="field"><label for="message">Message</label><textarea id="message" name="message" required></textarea></div>
            <div style="text-align:right"><button class="btn" type="submit">Send</button></div>
          </form>
        </div>

        <div class="card" style="margin-top:14px">
          <h3>Skills & Tools</h3>
          <div class="skills">
            <div class="skill">ServiceNow</div>
            <div class="skill">Active Directory</div>
            <div class="skill">Office 365</div>
            <div class="skill">SCCM / Intune</div>
            <div class="skill">Service Desk</div>
            <div class="skill">API Testing</div>
          </div>
        </div>
      </aside>
    </div>

    <footer>
      © Paul Abiodun — Built with a lightweight HTML template. Hosted on GitHub Pages.
    </footer>
  </div>

  <script>
    // small helper: smooth scroll for internal links
    document.querySelectorAll('a[href^="#"]').forEach(a=>{
      a.addEventListener('click', e=>{
        e.preventDefault();
        const t = document.querySelector(a.getAttribute('href'));
        if(t) t.scrollIntoView({behavior:'smooth',block:'start'});
      });
    });
  </script>
</body>
</html>
