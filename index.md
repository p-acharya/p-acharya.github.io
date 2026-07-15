---
layout: default
title: Poorvi Acharya — Computational Psycholinguistics
description: >-
  Poorvi Acharya studies how humans and language models learn, process, and
  generalize language — connecting cognitive science, second language
  acquisition, and machine learning.
permalink: /
---

<main class="page">

  {%- comment -%} ===== Hero: research identity first ===== {%- endcomment -%}
  <header class="hero">
    <div class="hero__text">
      <p class="eyebrow">Poorvi Acharya · Computational Psycholinguistics</p>
      <h1 class="hero__headline">
        I study how humans and language models learn, process, and generalize language.
      </h1>
      <p class="hero__lede">
        My work combines cognitive science and machine learning to model second language acquisition, with the dual goal of explaining human language processing and improving the evaluation of LLMs.
      </p>
      <div class="hero__cta">
        <a class="btn-primary" href="{{ '/research/' | relative_url }}">
          Explore the research
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
            stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
            <line x1="5" y1="12" x2="19" y2="12"></line>
            <polyline points="12 5 19 12 12 19"></polyline>
          </svg>
        </a>
      </div>
    </div>
    <figure class="hero__photo">
      <img src="{{ '/images/profile.png' | relative_url }}"
        alt="Poorvi Acharya, standing by Lake Lucerne in Switzerland" />
    </figure>
  </header>

  <hr class="rule" />

  {%- comment -%} ===== Research teaser card → links to Research page ===== {%- endcomment -%}
  <section aria-label="Research overview">
    <a class="card featured teaser" data-accent="p1" href="{{ '/research/' | relative_url }}">
      <div class="card__visual" data-accent="p1">
        <span class="card__index accent-p1">Research</span>
        <div class="card__visual-inner">
          {% include visuals/syntax-tree.html %}
        </div>
      </div>
      <div class="card__body">
        <div class="card__meta">
          <span class="tag accent-p1">3 Projects</span>
          <span class="affiliation">Parsing · Inference · Transfer</span>
        </div>
        <h2 class="card__title">How knowing one language shapes the way you read another</h2>
        <p class="card__hook">
          Bilinguals parse, infer, and err in revealing ways. Because a second language is never acquired in isolation, my work uses computational models to investigate how native language structures shape how we process and produce a new one.
        </p>
        <span class="card__more">
          See all three projects
          <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
            stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
            <line x1="5" y1="12" x2="19" y2="12"></line>
            <polyline points="12 5 19 12 12 19"></polyline>
          </svg>
        </span>
      </div>
    </a>
  </section>

  {%- comment -%} ===== Position + Languages ===== {%- endcomment -%}
  <section class="about-grid about-grid--single">
    <div class="about-bio about-bio--full">
      <h2 class="section-label">Background</h2>
      <p>
        I am a PhD student in Computer Science at <strong>George Mason
        University</strong>, advised by
        <a href="https://antonisa.github.io/" target="_blank" rel="noopener noreferrer">Antonios Anastasopoulos</a>.
        I previously studied Electrical Engineering and Computer Science at
        <strong>UC Berkeley</strong>, and have held visiting summer research
        appointments at <strong>MIT</strong> and <strong>ETH Zürich</strong>.
      </p>
      <p>
        Outside of research, I enjoy learning languages, playing the violin,
        and — more recently — getting into tea.  
      </p>
      <p>
        I got into this field for obvious reasons. Learning languages is somewhere between a hobby and a pathology for me. I speak <a class="lang-link" href="https://en.wikipedia.org/wiki/Kannada" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="kn">ಕನ್ನಡ</span></a>, <a class="lang-link" href="https://en.wikipedia.org/wiki/Hindi" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="hi">हिंदी</span></a>, <a class="lang-link" href="https://en.wikipedia.org/wiki/French_language" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="fr">Français</span></a>, <a class="lang-link" href="https://en.wikipedia.org/wiki/Japanese_language" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="ja">日本語</span></a>, <a class="lang-link" href="https://en.wikipedia.org/wiki/German_language" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="de">Deutsch</span></a>, and <a class="lang-link" href="https://en.wikipedia.org/wiki/Korean_language" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="ko">한국어</span></a>, and have studied <a class="lang-link" href="https://en.wikipedia.org/wiki/Sanskrit" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="sa">संस्कृतम्</span></a>, <a class="lang-link" href="https://en.wikipedia.org/wiki/Latin" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="la">Latin</span></a>, <a class="lang-link" href="https://en.wikipedia.org/wiki/Greek_language" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="el">Ἑλληνική</span></a>, <a class="lang-link" href="https://en.wikipedia.org/wiki/Yiddish" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="yi">ייִדיש</span></a>, and <a class="lang-link" href="https://en.wikipedia.org/wiki/Middle_Persian" target="_blank" rel="noopener noreferrer"><span class="lang-sample" lang="fa-Latn">Middle Persian</span></a>. This turns out to be useful for researching why languages are hard in such different ways.
      </p>
    </div>
  </section>

  {%- comment -%} ===== News as a momentum timeline ===== {%- endcomment -%}
  {% include news.md %}

  <hr class="rule" />

  {%- comment -%} ===== Contact icons (preserved) ===== {%- endcomment -%}
  <div class="contact-icons">
    <a href="mailto:poorvi.acharya@gmail.com" title="Email" aria-label="Email">
      <svg class="contact-icon-svg contact-icon-svg--stroke" viewBox="0 0 24 24" aria-hidden="true" focusable="false" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round">
        <rect x="3" y="5" width="18" height="14" rx="2"></rect>
        <path d="m4 7 8 6 8-6"></path>
      </svg>
    </a>
    <a href="https://twitter.com/poorvi___" title="Twitter" aria-label="Twitter" target="_blank" rel="noopener noreferrer">
      <svg class="contact-icon-svg" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
        <path d="M18.244 2.25h3.308l-7.227 8.26 8.502 11.24H16.17l-5.214-6.817L4.99 21.75H1.68l7.73-8.835L1.254 2.25H8.08l4.713 6.231zm-1.161 17.52h1.833L7.084 4.126H5.117z"/>
      </svg>
    </a>
    <a href="https://bsky.app/profile/pooorvi.bsky.social" title="Bluesky" aria-label="Bluesky" target="_blank" rel="noopener noreferrer">
      <svg class="contact-icon-svg" viewBox="0 0 600 530" aria-hidden="true" focusable="false">
        <path d="m130 37c64 48 133 145 170 222 37-77 106-174 170-222 46-34 120-60 120 26 0 18-10 151-16 173-22 78-101 98-171 86 121 21 152 90 86 159-126 131-181-33-195-75-3-6-4-8-6-8s-3 2-6 8c-14 42-69 206-195 75-66-69-35-138 86-159-70 12-149-8-171-86-6-22-16-155-16-173 0-86 74-60 120-26z"/>
      </svg>
    </a>
    <a href="https://www.linkedin.com/in/poorvi-acharya-824839118/" title="LinkedIn" aria-label="LinkedIn" target="_blank" rel="noopener noreferrer">
      <svg class="contact-icon-svg" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
        <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.225 0z"/>
      </svg>
    </a>
    <a href="https://github.com/p-acharya" title="GitHub" aria-label="GitHub" target="_blank" rel="noopener noreferrer">
      <svg class="contact-icon-svg" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
        <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23A11.509 11.509 0 0 1 12 5.803c1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222 0 1.606-.014 2.898-.014 3.293 0 .322.216.694.825.576C20.565 22.092 24 17.595 24 12.297c0-6.627-5.373-12-12-12"/>
      </svg>
    </a>
    <a href="https://scholar.google.com/citations?hl=en&user=NPvy2gIAAAAJ" title="Google Scholar" aria-label="Google Scholar" target="_blank" rel="noopener noreferrer">
      <svg class="contact-icon-svg contact-icon-svg--stroke" viewBox="0 0 24 24" aria-hidden="true" focusable="false" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round">
        <path d="M12 3 2 8l10 5 10-5-10-5Z"></path>
        <path d="M6 10.5V15c0 1.8 2.7 3.5 6 3.5s6-1.7 6-3.5v-4.5"></path>
      </svg>
    </a>
    <a class="location-icon" href="https://www.google.com/maps/place/Fairfax,+VA" title="Fairfax, VA" aria-label="Location: Fairfax, VA" target="_blank" rel="noopener noreferrer">
      <svg class="contact-icon-svg contact-icon-svg--stroke" viewBox="0 0 24 24" aria-hidden="true" focusable="false" fill="none" stroke="currentColor" stroke-width="1.9" stroke-linecap="round" stroke-linejoin="round">
        <path d="M12 21s6-5.33 6-11a6 6 0 1 0-12 0c0 5.67 6 11 6 11Z"></path>
        <circle cx="12" cy="10" r="2.5"></circle>
      </svg>
    </a>
  </div>
</main>
