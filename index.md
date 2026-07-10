---
layout: default
title: Marco Montagna, MD PhD
---

<div class="home-layout">
<header class="top-ribbon" aria-label="Section navigation">
  <div class="ribbon-name">Marco Montagna, MD PhD</div>
  <nav class="ribbon-nav" aria-label="Primary">
    <a href="#about">About</a>
    <a href="#research">Research Focus</a>
    <a href="{{ '/publications/' | relative_url }}">Publications</a>
    <a href="{{ '/education/' | relative_url }}">Education</a>
    <a href="{{ '/teaching/' | relative_url }}">Teaching</a>
    <a href="{{ '/talks/' | relative_url }}">Talks</a>
  </nav>
</header>

<div class="site-grid">
  <aside class="profile-panel" aria-label="Profile">
    <img class="profile-photo" src="{{ '/assets/small.jpg' | relative_url }}" alt="Portrait of Marco Montagna">
    <h1>Marco Montagna, MD PhD</h1>
    <p class="subtitle">Clinical Academic / Clinical Data Scientist</p>
    <p class="profile-blurb">
      AI-Team, School of Medicine, Vita-Salute San Raffaele University
    </p>
    <ul class="profile-links">
      <li>
        <a href="mailto:mm2917@cam.ac.uk" aria-label="Email">
          <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M3 6h18v12H3V6zm2 2v.5l7 4.5 7-4.5V8l-7 4.5L5 8z"/></svg>
          <span>Email</span>
        </a>
      </li>
      <li>
        <a href="https://www.linkedin.com/in/marco-montagna-md" aria-label="LinkedIn">
          <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M6.7 8.7a1.7 1.7 0 1 1 0-3.4 1.7 1.7 0 0 1 0 3.4zM5.2 10h3V19h-3v-9zm5 0h2.9v1.2h.1c.4-.7 1.4-1.4 2.8-1.4 3 0 3.5 2 3.5 4.5V19h-3v-4.1c0-1 0-2.2-1.4-2.2s-1.6 1-1.6 2.1V19h-3v-9z"/></svg>
          <span>LinkedIn</span>
        </a>
      </li>
      <li>
        <a href="https://github.com/montagnam/" aria-label="GitHub">
          <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 .5a12 12 0 0 0-3.8 23.4c.6.1.8-.3.8-.6v-2.2c-3.4.7-4.1-1.4-4.1-1.4-.6-1.3-1.4-1.7-1.4-1.7-1.1-.8.1-.8.1-.8 1.2.1 1.9 1.3 1.9 1.3 1.1 1.9 2.8 1.3 3.5 1 .1-.8.4-1.3.8-1.6-2.7-.3-5.6-1.4-5.6-6a4.7 4.7 0 0 1 1.3-3.3 4.4 4.4 0 0 1 .1-3.2s1-.3 3.4 1.3a11.7 11.7 0 0 1 6.2 0c2.4-1.6 3.4-1.3 3.4-1.3a4.4 4.4 0 0 1 .1 3.2 4.7 4.7 0 0 1 1.3 3.3c0 4.6-2.9 5.7-5.6 6 .4.3.9 1 .9 2v3c0 .3.2.7.8.6A12 12 0 0 0 12 .5z"/></svg>
          <span>GitHub</span>
        </a>
      </li>
      <li>
        <a href="https://orcid.org/0000-0002-0907-7640" aria-label="ORCID">
          <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M12 2a10 10 0 1 0 10 10A10 10 0 0 0 12 2zm-3.3 4h1.8v12H8.7V6zm3.3 0h2.8c2.2 0 3.9 1.6 3.9 3.8 0 2.2-1.6 3.8-3.9 3.8h-1V18H12V6zm1.8 1.7v4.3h1c1.2 0 2-.9 2-2.1 0-1.3-.8-2.2-2-2.2h-1z"/></svg>
          <span>ORCID</span>
        </a>
      </li>
      <li>
        <a href="{{ '/assets/CV.pdf' | relative_url }}" aria-label="Curriculum Vitae">
          <svg viewBox="0 0 24 24" aria-hidden="true"><path d="M6 2h9l5 5v15H6V2zm8 1.5V8h4.5L14 3.5zM8 12h8v1.5H8V12zm0 3h8v1.5H8V15z"/></svg>
          <span>CV</span>
        </a>
      </li>
    </ul>
  </aside>

  <section class="content-panel">
    <main class="one-page">
      <section id="about" class="section-block">
        <h2>About</h2>
        <p>
          I am a consultant and machine learning researcher with a dual background in Internal Medicine and Computer Science, currently appointed as a postdoctoral researcher at Vita-Salute San Raffaele University, Milan, and visiting researcher at the University of Cambridge.
        </p>
        <p>
          My work bridges medicine and computational methods, focusing on reproducible pipelines for the acquisition, preprocessing and use of routinely collected data from electronic medical records for risk prediction modelling and clinical decision support according to expected health trajectories.
        </p>
        <p>
           I hold experience in teaching at undergraduate/graduate level, authoring and editing peer-reviewed articles, and am used to engage with various stakeholders, including clinicians, researchers and industry partners.
        </p>
      </section>

      <section id="research" class="section-block">
        <h2>Research Focus</h2>
        <ul>
          <li>Real-world clinical data integration across EHRs, registries, and laboratory systems.</li>
          <li>Reproducible data preprocessing pipelines for longitudinal healthcare datasets.</li>
          <li>Machine learning for classification and survival analysis in multimorbidity.</li>
          <li>Model interpretability and clinical translation using robust validation frameworks.</li>
          <li>Trusted Research Environment workflows based on FAIR principles and medical ontologies.</li>
        </ul>
      </section>
    </main>

    <footer class="site-footnote">
      <p>Last updated: July 2026</p>
    </footer>
  </section>
</div>
</div>

<script>
  (function () {
    function isDesktop() {
      return window.matchMedia("(min-width: 901px)").matches;
    }

    function getPanel() {
      return document.querySelector(".content-panel");
    }

    document.addEventListener(
      "wheel",
      function (event) {
        if (!isDesktop()) {
          return;
        }

        var panel = getPanel();
        if (!panel) {
          return;
        }

        var canScrollDown = panel.scrollTop + panel.clientHeight < panel.scrollHeight;
        var canScrollUp = panel.scrollTop > 0;
        var wantsDown = event.deltaY > 0;
        var wantsUp = event.deltaY < 0;

        if ((wantsDown && canScrollDown) || (wantsUp && canScrollUp)) {
          panel.scrollTop += event.deltaY;
          event.preventDefault();
        }
      },
      { passive: false }
    );
  })();
</script>
