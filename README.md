# Hitesh_Patial
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Hitesh Patial — Portfolio</title>
  <meta name="description" content="Portfolio of Hitesh Patial — BCA student interested in software development and cloud computing." />
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#9aa4b2; --accent:#6ee7b7;
      --glass: rgba(255,255,255,0.03);
      font-family: Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;background:linear-gradient(180deg,#091027 0%, #071020 100%);color:#e6eef6;line-height:1.5}
    .wrap{max-width:960px;margin:36px auto;padding:28px;background:linear-gradient(180deg, rgba(255,255,255,0.03), rgba(255,255,255,0.01));border-radius:14px;box-shadow:0 8px 30px rgba(2,6,23,.6)}
    header{display:flex;gap:20px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:12px;background:linear-gradient(135deg,var(--accent),#60a5fa);display:flex;align-items:center;justify-content:center;font-weight:700;color:#022;letter-spacing:1px}
    h1{margin:0;font-size:1.6rem}
    p.lead{margin:6px 0 0;color:var(--muted)}

    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px;margin-top:22px}
    .card{background:var(--card);padding:18px;border-radius:12px}
    .meta{display:flex;flex-direction:column;gap:8px}
    .meta a{color:var(--accent);text-decoration:none;font-weight:600}
    .section-title{font-size:0.98rem;margin:0 0 10px;color:#d7e7f2}

    ul.skills{display:flex;flex-wrap:wrap;gap:8px;padding:0;margin:0;list-style:none}
    ul.skills li{background:var(--glass);padding:8px 10px;border-radius:999px;font-size:.9rem;color:var(--muted)}

    .projects{display:flex;flex-direction:column;gap:12px}
    .project{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:12px;border-radius:10px}
    .project h4{margin:0 0 6px}
    .project p{margin:0;color:var(--muted);font-size:.95rem}

    .achievements{display:flex;flex-direction:column;gap:8px}
    .achievement{background:var(--glass);padding:10px;border-radius:8px;color:var(--muted);font-size:.95rem}

    footer{margin-top:18px;color:var(--muted);font-size:.9rem}

    /* responsive */
    @media (max-width:820px){.grid{grid-template-columns:1fr} .avatar{width:76px;height:76px}}
  </style>
</head>
<body>
  <main class="wrap">
    <header>
      <div class="avatar">HP</div>
      <div>
        <h1>Hitesh Patial</h1>
        <p class="lead">BCA student at Chandigarh University — interested in software development & cloud computing</p>
        <div style="margin-top:8px;color:var(--muted);font-size:.95rem">Chandigarh, India &middot; <a href="mailto:hiteshpatial403@gmail.com">hiteshpatial403@gmail.com</a> &middot; <a href="tel:+917876882007">+91 78768 82007</a></div>
      </div>
    </header>

    <div class="grid">
      <section class="card">
        <h3 class="section-title">Objective</h3>
        <p>As a BCA student (2024–2027) at Chandigarh University, I am building strong foundations in software development and cloud computing. I seek internships and projects that let me apply C++ and database knowledge while growing hands-on cloud skills.</p>

        <h3 class="section-title" style="margin-top:16px">Education</h3>
        <div class="meta">
          <div><strong>BCA</strong> — Chandigarh University (2024 &ndash; 2027)</div>
        </div>

        <h3 class="section-title" style="margin-top:16px">Skills</h3>
        <ul class="skills">
          <li>C++ (OOP)</li>
          <li>Database Management</li>
          <li>Cloud Computing</li>
          <li>HTML</li>
          <li>CSS (Beginner)</li>
        </ul>

        <h3 class="section-title" style="margin-top:16px">Projects</h3>
        <div class="projects">
          <div class="project">
            <h4>Library Management System</h4>
            <p>Built in C++ using classes and file handling to manage books, members, issue/return and persist data to files.</p>
          </div>
          <div class="project">
            <h4>Cloud Computing Presentation</h4>
            <p>Explored public, private and hybrid cloud models and prepared a slide deck summarizing differences and use-cases.</p>
          </div>
        </div>

        <h3 class="section-title" style="margin-top:16px">Achievements</h3>
        <div class="achievements">
          <div class="achievement">Participated in university-level technical events.</div>
          <div class="achievement">Attended coding workshops to improve problem solving and practical coding skills.</div>
        </div>

      </section>

      <aside class="card">
        <h3 class="section-title">Contact</h3>
        <div style="color:var(--muted);margin-bottom:12px">You can reach me at:</div>
        <div style="display:flex;flex-direction:column;gap:8px">
          <div><strong>Email:</strong> <a href="mailto:hiteshpatial403@gmail.com">hiteshpatial403@gmail.com</a></div>
          <div><strong>Phone:</strong> <a href="tel:+917876882007">+91 78768 82007</a></div>
          <div><strong>Location:</strong> Chandigarh, India</div>
        </div>

        <h3 class="section-title" style="margin-top:14px">Quick Links</h3>
        <div style="color:var(--muted);font-size:.95rem;display:flex;flex-direction:column;gap:8px">
          <a href="#" onclick="alert('When you upload this to GitHub, create a repo named hitesh-patial-portfolio and push this index.html')">Create GitHub repo (hint)</a>
          <a href="#" onclick="copyToClipboard()">Copy contact info</a>
        </div>

        <script>
          function copyToClipboard(){
            const text = `Hitesh Patial
Email: hiteshpatial403@gmail.com
Phone: +91 78768 82007`;
            navigator.clipboard?.writeText(text).then(()=>alert('Contact copied to clipboard'));
          }
        </script>

        <h3 class="section-title" style="margin-top:14px">Notes</h3>
        <div style="color:var(--muted);font-size:.9rem">This single-file HTML is ready to be the main page of a GitHub repository. Rename to <code>index.html</code> and push to the root of your repo.</div>
      </aside>
    </div>

    <footer>
      <div>Generated for <strong>Hitesh Patial</strong>. You can edit any section directly in this file.</div>
    </footer>
  </main>
</body>
</html>
