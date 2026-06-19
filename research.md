---
layout: default
title: Research — Poorvi Acharya
description: >-
  Selected research in computational psycholinguistics: cross-linguistic
  parsing, Chinese vocabulary inference, and L1 transfer detection in L2 writing.
permalink: /research/
---

<main class="page">
  <header class="intro">
    <p class="eyebrow">Research</p>
    <h1>Learning a second language is hard. Learning a third is somehow easier.</h1>
    <p>
      I build computational models of second language processing to understand where the hardest errors come from, and why learning one language can help with another, even when the two are unrelated.
    </p>
  </header>

  <hr class="rule" />

  {%- comment -%} Featured project (large, side-by-side) {%- endcomment -%}
  <section aria-label="Featured research project">
    {% for p in site.data.projects %}{% if p.featured %}
      {% include project-card.html project=p %}
    {% endif %}{% endfor %}
  </section>

  {%- comment -%} Two-up grid {%- endcomment -%}
  <section aria-label="Additional research projects" class="grid-2">
    {% for p in site.data.projects %}{% unless p.featured %}
      {% include project-card.html project=p %}
    {% endunless %}{% endfor %}
  </section>

  <div class="footer-link">
    <a href="{{ '/publications/' | relative_url }}">
      See Publications for citable papers and links
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
        stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
        <line x1="5" y1="12" x2="19" y2="12"></line>
        <polyline points="12 5 19 12 12 19"></polyline>
      </svg>
    </a>
  </div>
</main>
