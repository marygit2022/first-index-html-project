<!DOCTYPE html>
<html>
<head>
    <title>My First Project</title>
</head>
<body>
    <h1>Hello GitHub Pages!</h1>
</body>
</html>

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Molecular Techniques Project — Maryam</title>
  <meta name="description" content="Molecular Techniques Project — Project page for laboratory protocols, code and results. Author: Maryam." />
  <meta property="og:title" content="Molecular Techniques Project — Maryam" />
  <meta property="og:description" content="Brief overview of molecular techniques used (PCR, qPCR, cloning, CRISPR concepts), code and links to GitHub repository." />
  <meta property="og:type" content="website" />
  <style>
    :root{--bg:#f6fbff;--card:#ffffff;--muted:#536272;--accent:#0b6ea8;--accent-2:#1fa2a6}
    *{box-sizing:border-box}
    body{font-family:Inter,ui-sans-serif,system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial;line-height:1.5;color:#112; background:linear-gradient(180deg,var(--bg),#ffffff);margin:0;padding:24px}
    .container{max-width:980px;margin:0 auto}
    header{display:flex;align-items:center;gap:16px;margin-bottom:18px}
    .logo{width:68px;height:68px;border-radius:10px;background:linear-gradient(135deg,var(--accent),var(--accent-2));display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;font-size:20px}
    h1{margin:0;font-size:28px}
    p.lead{margin:6px 0 18px;color:var(--muted)}
    .grid{display:grid;grid-template-columns:1fr 320px;gap:20px}
    .card{background:var(--card);border-radius:12px;padding:18px;box-shadow:0 6px 18px rgba(15,23,42,0.06)}
    .hero-image{width:100%;height:200px;border-radius:8px;object-fit:cover;background:#e6f4fb;display:block}
    .skills{display:flex;flex-wrap:wrap;gap:8px;margin-top:10px}
    .skill{background:#eef8ff;color:var(--accent);padding:6px 10px;border-radius:999px;font-weight:600;font-size:13px}
    a.btn{display:inline-block;padding:10px 14px;border-radius:10px;background:var(--accent);color:#fff;text-decoration:none;font-weight:600}
    .small{font-size:13px;color:var(--muted)}
    ul.meta{padding-left:18px;margin:10px 0}
    footer{margin-top:22px;color:var(--muted);font-size:13px}
    pre.code{background:#0f1724;color:#e6eef6;padding:12px;border-radius:8px;overflow:auto;font-size:13px}
    @media (max-width:900px){.grid{grid-template-columns:1fr} .card{padding:14px}}
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="logo">M</div>
      <div>
        <h1>Molecular Techniques Project</h1>
        <p class="lead">A concise project page presenting laboratory methods, code and resources — authored by Maryam (M.Sc. candidate in Microbial Biotechnology).</p>
      </div>
    </header>

    <div class="grid">
      <main>
        <article class="card">
          <img class="hero-image" src="data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='1200' height='600' viewBox='0 0 1200 600'><rect width='1200' height='600' fill='%23e6f4fb'/><g transform='translate(80,80)'><circle cx='100' cy='60' r='40' fill='%230b6ea8' opacity='0.12'/><rect x='180' y='40' rx='8' ry='8' width='360' height='220' fill='%231fa2a6' opacity='0.08'/><path d='M20 420 C160 360 340 460 480 420 C620 380 840 460 1080 420 V600 H0 Z' fill='%23dff7fb' /></g><text x='40' y='320' font-family='Arial' font-size='28' fill='%230b6ea8'>Molecular Techniques & Code</text></svg>" alt="project illustration">

          <h2>About</h2>
          <p class="small">This repository combines experimental protocols and code examples related to molecular techniques used in the project. The focus is on experimental methods (PCR, qPCR, cloning concepts, CRISPR theory), basic data analysis scripts and a starter notebook for bioinformatics work in Python.</p>

          <h3>What you'll find here</h3>
          <ul>
            <li>Laboratory protocols and notes (markdown files)</li>
            <li>Example scripts: data processing, qPCR analysis and plotting</li>
            <li>A starter Jupyter notebook for sequence analysis</li>
            <li>README with usage instructions and how to reproduce results</li>
          </ul>

          <h3>Key files</h3>
          <pre class="code">README.md
index.html
notebooks/analysis.ipynb
scripts/qPCR_analysis.py
protocols/PCR_protocol.md</pre>

          <h3>How to run</h3>
          <ol>
            <li>Clone the repository: <code>git clone https://github.com/marygit2022/molecular-techniques-project-.git</code></li>
            <li>Open the Jupyter notebooks (if any) or run Python scripts from <code>scripts/</code></li>
            <li>See README for environment and dependencies</li>
          </ol>

          <h3>Notes for reviewers</h3>
          <p class="small">This project is intended as a demonstration of laboratory familiarity and basic bioinformatics skills. If you'd like the data or specific protocol details removed before sharing publicly, please let me know.</p>

        </article>

        <article class="card" style="margin-top:16px">
          <h3>Contact & Links</h3>
          <p class="small">GitHub repository: <a href="https://github.com/marygit2022/molecular-techniques-project-" target="_blank">github.com/marygit2022/molecular-techniques-project-</a></p>
          <p class="small">If you want this page customized (colors, sections, add CV, publications or images), tell me and I will update the page.</p>
        </article>
      </main>

      <aside>
        <div class="card">
          <h4>Project summary</h4>
          <p class="small">Author: <strong>Maryam</strong><br>Degree: M.Sc. (Microbial Biotechnology) — Term 2</p>

          <h4 style="margin-top:12px">Skills & Techniques</h4>
          <div class="skills">
            <div class="skill">PCR</div>
            <div class="skill">Real-Time PCR (qPCR)</div>
            <div class="skill">Primer design</div>
            <div class="skill">Cloning (conceptual)</div>
            <div class="skill">CRISPR (theory)</div>
            <div class="skill">Cell culture (theory)</div>
            <div class="skill">Animal work (theory)</div>
            <div class="skill">Python (bioinformatics)</div>
            <div class="skill">Git / version control</div>
          </div>

          <h4 style="margin-top:12px">Quick actions</h4>
          <p><a class="btn" href="https://github.com/marygit2022/molecular-techniques-project-" target="_blank">Open repository</a></p>
          <p style="margin-top:8px" class="small">Downloadable files and notebooks are available inside the repository.</p>
        </div>

        <div class="card" style="margin-top:12px">
          <h4>For admissions</h4>
          <p class="small">Suggested text to include in applications: <em>"This project demonstrates hands-on familiarity with molecular techniques (PCR, qPCR), primer design, and introductory bioinformatics using Python. Code and protocols are available in the linked repository."</em></p>
        </div>
      </aside>
    </div>

    <footer class="container small">
      <p>Page generated for: Maryam — <a href="https://github.com/marygit2022" target="_blank">marygit2022</a></p>
    </footer>
  </div>
</body>
</html>
