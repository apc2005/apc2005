
<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500&family=Sora:wght@400;500;600&display=swap');

  .readme {
    font-family: 'Sora', sans-serif;
    color: var(--color-text-primary);
    max-width: 780px;
    margin: 0 auto;
    padding: 2rem 1.5rem;
    line-height: 1.7;
  }

  .header-band {
    border-left: 3px solid #1D9E75;
    padding: 0.5rem 0 0.5rem 1.25rem;
    margin-bottom: 1.5rem;
  }

  .header-band h1 {
    font-size: 26px;
    font-weight: 600;
    margin: 0 0 4px;
    letter-spacing: -0.3px;
  }

  .header-band .subtitle {
    font-size: 13px;
    color: var(--color-text-secondary);
    font-family: 'JetBrains Mono', monospace;
    margin: 0;
  }

  .bio {
    font-size: 14px;
    color: var(--color-text-secondary);
    margin-bottom: 2rem;
    max-width: 640px;
  }

  .badges {
    display: flex;
    flex-wrap: wrap;
    gap: 8px;
    margin-bottom: 2rem;
  }

  .badge {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    font-size: 11.5px;
    font-family: 'JetBrains Mono', monospace;
    padding: 4px 10px;
    border-radius: 4px;
    border: 0.5px solid var(--color-border-tertiary);
    background: var(--color-background-secondary);
    color: var(--color-text-secondary);
  }

  .badge img { width: 14px; height: 14px; object-fit: contain; }

  .section-title {
    font-size: 11px;
    font-family: 'JetBrains Mono', monospace;
    font-weight: 500;
    color: #1D9E75;
    letter-spacing: 1.5px;
    text-transform: uppercase;
    margin: 2rem 0 0.75rem;
    border-bottom: 0.5px solid var(--color-border-tertiary);
    padding-bottom: 6px;
  }

  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
    gap: 8px;
    margin-bottom: 1rem;
  }

  .skill-card {
    display: flex;
    align-items: center;
    gap: 8px;
    padding: 8px 12px;
    background: var(--color-background-secondary);
    border-radius: var(--border-radius-md);
    border: 0.5px solid var(--color-border-tertiary);
    font-size: 12.5px;
    font-weight: 500;
  }

  .skill-card img { width: 18px; height: 18px; object-fit: contain; }

  .projects-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 10px;
    margin-bottom: 1rem;
  }

  .project-card {
    padding: 14px 16px;
    background: var(--color-background-primary);
    border: 0.5px solid var(--color-border-tertiary);
    border-radius: var(--border-radius-lg);
    cursor: pointer;
    transition: border-color 0.15s;
    text-decoration: none;
    color: inherit;
    display: block;
  }

  .project-card:hover { border-color: #1D9E75; }

  .project-card .proj-title {
    font-size: 13.5px;
    font-weight: 500;
    margin: 0 0 4px;
    display: flex;
    align-items: center;
    gap: 6px;
    color: var(--color-text-primary);
  }

  .project-card .proj-title .gh-icon {
    width: 14px; height: 14px; opacity: 0.5;
  }

  .project-card .proj-desc {
    font-size: 12px;
    color: var(--color-text-secondary);
    margin: 0 0 8px;
    line-height: 1.5;
  }

  .proj-tags { display: flex; flex-wrap: wrap; gap: 4px; }

  .proj-tag {
    font-size: 10px;
    font-family: 'JetBrains Mono', monospace;
    padding: 2px 7px;
    border-radius: 3px;
    background: #E1F5EE;
    color: #0F6E56;
    border: 0.5px solid #9FE1CB;
  }

  .timeline { margin-bottom: 0.5rem; }

  .tl-item {
    display: flex;
    gap: 12px;
    align-items: flex-start;
    padding: 10px 0;
    border-bottom: 0.5px solid var(--color-border-tertiary);
    font-size: 13px;
  }

  .tl-item:last-child { border-bottom: none; }

  .tl-dot {
    width: 8px; height: 8px;
    border-radius: 50%;
    background: #1D9E75;
    margin-top: 5px;
    flex-shrink: 0;
  }

  .tl-main { font-weight: 500; }
  .tl-sub { color: var(--color-text-secondary); font-size: 12px; }

  .contact-row {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 0.5rem;
  }

  .contact-pill {
    display: inline-flex;
    align-items: center;
    gap: 6px;
    padding: 6px 14px;
    border-radius: 20px;
    border: 0.5px solid var(--color-border-secondary);
    font-size: 12.5px;
    background: var(--color-background-secondary);
    color: var(--color-text-primary);
    text-decoration: none;
    cursor: pointer;
  }

  .contact-pill img { width: 14px; height: 14px; }

  .contact-pill:hover { border-color: #1D9E75; }

  @media (max-width: 500px) {
    .projects-grid { grid-template-columns: 1fr; }
  }
</style>

<div class="readme">

  <div class="header-band">
    <h1>Antonio Pérez Carmona</h1>
    <p class="subtitle">// Desarrollador Web · IA & Big Data · Sevilla, España</p>
  </div>

  <p class="bio">
    Desarrollador con especialización en Inteligencia Artificial y Big Data. Mi enfoque se centra en la intersección entre software robusto y análisis avanzado de datos. Orientado al detalle, con curiosidad técnica por comprender la lógica profunda detrás de cada herramienta.
  </p>

  <div class="badges">
    <span class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="">Next.js</span>
    <span class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="">Python</span>
    <span class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="">Java</span>
    <span class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="">PHP</span>
    <span class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="">MySQL</span>
    <span class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="">PostgreSQL</span>
    <span class="badge"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="">Git</span>
  </div>

  <div class="section-title">// stack técnico</div>

  <div class="skills-grid">
    <div class="skill-card"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="">Next.js</div>
    <div class="skill-card"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="">Python</div>
    <div class="skill-card"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="">Java</div>
    <div class="skill-card"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" alt="">PHP</div>
    <div class="skill-card"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="">MySQL</div>
    <div class="skill-card"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="">PostgreSQL</div>
    <div class="skill-card"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" alt="">TensorFlow</div>
    <div class="skill-card"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="">Git</div>
  </div>

  <div class="section-title">// proyectos destacados</div>

  <div class="projects-grid">
    <a class="project-card" href="https://github.com/PabloGonzGar/cv-analyze" target="_blank">
      <div class="proj-title">
        <svg class="gh-icon" viewBox="0 0 16 16" fill="currentColor"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
        CV-Analyzer
      </div>
      <p class="proj-desc">Sistema de clasificación automática de candidatos mediante análisis de afinidad con descripciones de puesto.</p>
      <div class="proj-tags">
        <span class="proj-tag">Python</span>
        <span class="proj-tag">NLP</span>
        <span class="proj-tag">IA</span>
      </div>
    </a>

    <a class="project-card" href="https://github.com/apc2005/VisionCine" target="_blank">
      <div class="proj-title">
        <svg class="gh-icon" viewBox="0 0 16 16" fill="currentColor"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
        VisionCine — TFG
      </div>
      <p class="proj-desc">Plataforma social de cine con APIs externas, perfiles, puntuaciones y listas dinámicas de usuario.</p>
      <div class="proj-tags">
        <span class="proj-tag">PHP</span>
        <span class="proj-tag">APIs</span>
        <span class="proj-tag">MySQL</span>
      </div>
    </a>

    <a class="project-card" href="https://github.com/apc2005/A-Pathfinding" target="_blank">
      <div class="proj-title">
        <svg class="gh-icon" viewBox="0 0 16 16" fill="currentColor"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"/></svg>
        A* Pathfinding
      </div>
      <p class="proj-desc">Implementación de búsqueda de rutas óptimas en cuadrículas con obstáculos. Algoritmos complejos, lógica limpia.</p>
      <div class="proj-tags">
        <span class="proj-tag">Algoritmos</span>
        <span class="proj-tag">Python</span>
      </div>
    </a>
  </div>

  <div class="section-title">// trayectoria</div>

  <div class="timeline">
    <div class="tl-item">
      <div class="tl-dot"></div>
      <div>
        <div class="tl-main">Postgrado en IA y Big Data</div>
        <div class="tl-sub">Campus Cámara de Comercio de Sevilla</div>
      </div>
    </div>
    <div class="tl-item">
      <div class="tl-dot"></div>
      <div>
        <div class="tl-main">Técnico Superior en DAW</div>
        <div class="tl-sub">Desarrollo de Aplicaciones Web</div>
      </div>
    </div>
    <div class="tl-item">
      <div class="tl-dot"></div>
      <div>
        <div class="tl-main">Desarrollo frontend · E-commerce</div>
        <div class="tl-sub">Proyectos de alta escala en sector IT</div>
      </div>
    </div>
    <div class="tl-item">
      <div class="tl-dot"></div>
      <div>
        <div class="tl-main">Gestión logística y cadena de suministro</div>
        <div class="tl-sub">Visión pragmática sobre eficiencia de procesos</div>
      </div>
    </div>
  </div>

  <div class="section-title">// contacto</div>

  <div class="contact-row">
    <a class="contact-pill" href="mailto:antonio.perez.carmona.2005@gmail.com">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" alt="">
      antonio.perez.carmona.2005@gmail.com
    </a>
    <a class="contact-pill" href="https://www.linkedin.com/in/antonio-p%C3%A9rez-carmona-1b7a633a0/" target="_blank">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="#0A66C2"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
      LinkedIn
    </a>
    <span class="contact-pill">
      <svg width="14" height="14" viewBox="0 0 24 24" fill="currentColor"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/></svg>
      Sevilla, España
    </span>
  </div>

</div>
