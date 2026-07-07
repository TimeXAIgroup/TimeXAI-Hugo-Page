---
title: Resources
type: landing

sections:
  # ======================
  # INTRO
  # ======================
  - block: markdown
    content:
      title: "Research Software, Datasets & Interactive Demos"
      text: |
        We develop open and interactive research resources that make
        artificial intelligence methods more accessible, transparent,
        and reproducible. This page provides access to software, datasets,
        web tools, and interactive demonstrations developed by the Applied AI Lab.
    design:
      columns: '1'
      css_class: resources-intro-section
      spacing:
        padding: ['70px', '20px', '45px', '20px']

  # ======================
  # RESOURCES
  # ======================
  - block: markdown
    content:
      text: |
        <div class="research-resources">

        <article class="research-resource-card">
        <div class="research-resource-card__image">
        <img src="/static/uploads/cnn-3d-demo.png" alt="Interactive 3D visualization of a one-dimensional convolutional neural network" loading="lazy" decoding="async" />
        </div>

        <div class="research-resource-card__body">
        <p class="research-resource-card__type">Interactive Demo</p>
        <h2>Interactive 3D Visualization of a 1D CNN</h2>

        <p>
        Explore activations, learned filters, and network connections
        in an interactive visualization of a one-dimensional convolutional
        neural network.
        </p>

        <p class="research-resource-card__meta">
        Related project: <a href="/research/project_timexai/">TimeXAI</a>
        </p>

        <a class="research-resource-card__link" href="https://timexaigroup.github.io/nn-vis-ts/cnn/3d.html" target="_blank" rel="noopener noreferrer">
        Open interactive demo ↗
        </a>
        </div>
        </article>

        <article class="research-resource-card">
        <div class="research-resource-card__image">
        <img src="/static/uploads/eduxai.png" alt="EduXAI interactive web application" loading="lazy" decoding="async" />
        </div>

        <div class="research-resource-card__body">
        <p class="research-resource-card__type">Web Tool</p>
        <h2>EduXAI</h2>

        <p>
        Interactive web application for exploring concepts and methods
        in explainable artificial intelligence.
        </p>

        <p class="research-resource-card__meta">
        Developed by the Applied AI Lab
        </p>

        <a class="research-resource-card__link" href="https://xai.mnd.thm.de/" target="_blank" rel="noopener noreferrer">
        Open web tool ↗
        </a>
        </div>
        </article>

        </div>
    design:
      columns: '1'
      css_class: resources-grid-section
      spacing:
        padding: ['30px', '20px', '80px', '20px']
---
