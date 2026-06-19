---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

<section class="research-page" aria-label="Research portfolio">
  <main class="page">
    <header class="intro">
      <p class="eyebrow">Research</p>
      <h1>How experience with one language reshapes the mind&apos;s grip on another.</h1>
      <p>
        I work at the intersection of computational linguistics and
        psycholinguistics, asking how bilingual readers parse, infer, and err.
        Three threads run through my work. Each pairs careful experimental design
        with scalable computational tools.
      </p>
    </header>

    <hr class="rule" />

    <section aria-label="Featured research project">
      {% for p in site.data.research.projects %}{% if p.featured %}
        {% include research/project-card.html project=p %}
      {% endif %}{% endfor %}
    </section>

    <section aria-label="Additional research projects" class="grid-2">
      {% for p in site.data.research.projects %}{% unless p.featured %}
        {% include research/project-card.html project=p %}
      {% endunless %}{% endfor %}
    </section>

    <div class="footer-link">
      <a href="/publications/">
        See Publications for citable papers and links
        <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
          stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
          <line x1="5" y1="12" x2="19" y2="12"></line>
          <polyline points="12 5 19 12 12 19"></polyline>
        </svg>
      </a>
    </div>
  </main>
</section>