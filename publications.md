---
layout: default
title: Publications — Poorvi Acharya
description: >-
  Citable papers, preprints, and links by Poorvi Acharya in computational
  psycholinguistics and second language acquisition.
permalink: /publications/
---

<main class="page page--narrow">
  <header class="intro">
    <p class="eyebrow">Publications</p>
    <h1>Citable papers, preprints, and links.</h1>
    <p>
      You can also find my articles on
      <a href="https://scholar.google.com/citations?hl=en&user=NPvy2gIAAAAJ" target="_blank" rel="noopener noreferrer">Google Scholar</a>.
    </p>
  </header>

  <ol class="pub-list">
    {% for pub in site.data.publications %}
    <li class="pub-item">
      <div class="pub-meta">
        <div class="accent-p1">{{ pub.venue }}</div>
        <div>{{ pub.year }}</div>
      </div>
      <div class="pub-body">
        <h2 class="pub-title">
          {% if pub.url %}
          <a href="{{ pub.url | relative_url }}"{% if pub.url contains '://' %} target="_blank" rel="noopener noreferrer"{% endif %}>{{ pub.title }}</a>
          {% else %}
          {{ pub.title }}
          {% endif %}
        </h2>
        <p class="pub-authors">
          {{ pub.authors }}{% if pub.note %} · {{ pub.note }}{% endif %}
        </p>
      </div>
    </li>
    {% endfor %}
  </ol>

  <div class="footer-link">
    <a href="{{ '/research/' | relative_url }}" class="footer-link--back">
      <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
        stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
        <line x1="19" y1="12" x2="5" y2="12"></line>
        <polyline points="12 19 5 12 12 5"></polyline>
      </svg>
      Back to research projects
    </a>
  </div>
</main>
