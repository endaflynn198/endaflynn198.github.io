---
layout: page
permalink: /repositories/
title: Projects
description: Selected data-science, automation, and educational projects by Enda Flynn.
nav: true
nav_order: 1
---

<div class="portfolio-callout">
  <h2>Built to solve a clear problem</h2>
  <p>These projects are deliberately varied, but they share the same approach: understand the user’s real need, make the analysis reproducible, and package the result so somebody else can use it.</p>
  <div class="portfolio-actions">
    <a class="primary" href="https://github.com/endaflynn198">Browse all GitHub repositories</a>
  </div>
</div>

<div class="project-list">
  <article class="project-case" id="human-development-indicators-toolkit">
    <div class="project-topline">
      <div>
        <span class="project-number">Project 01</span>
        <h2>Human Development Indicators toolkit</h2>
      </div>
      <div class="portfolio-actions">
        <a class="secondary" href="https://github.com/endaflynn198/HDI_summary">R package</a>
        <a class="secondary" href="https://github.com/endaflynn198/hdi_shiny_app">Shiny app</a>
      </div>
    </div>
    <div class="project-details">
      <div>
        <h3>Problem</h3>
        <p>UN development data is broad and valuable, but comparing indicators between countries requires repeated filtering, summarising, and visualisation work.</p>
      </div>
      <div>
        <h3>Approach</h3>
        <p>I built an object-oriented R package for repeatable summaries and comparisons, then used it as the analytical layer for an interactive Shiny application.</p>
      </div>
      <div>
        <h3>What it demonstrates</h3>
        <p>Package design, documentation, reusable analysis, reactive applications, and translating a dataset into a coherent user workflow.</p>
      </div>
    </div>
    <div class="skill-tags">
      <span>R</span><span>OOP</span><span>Shiny</span><span>Documentation</span><span>Data visualisation</span>
    </div>
    <div class="portfolio-actions">
      <a class="primary" href="/blog/2024/HDI_indicators/">Read the package article</a>
      <a class="secondary" href="https://htmlpreview.github.io/?https://github.com/endaflynn198/HDI_summary/blob/main/vignettes/HDIsummary.html">Open the vignette</a>
    </div>
  </article>

  <article class="project-case" id="asynchronous-downloader">
    <div class="project-topline">
      <div>
        <span class="project-number">Project 04</span>
        <h2>Asynchronous downloader</h2>
      </div>
      <div class="portfolio-actions">
        <a class="secondary" href="https://github.com/endaflynn198/asynchronous_downloader_tool">View repository</a>
      </div>
    </div>
    <div class="project-details">
      <div>
        <h3>Problem</h3>
        <p>Downloading a large collection of media files sequentially wastes time and makes an otherwise simple collection task unnecessarily slow.</p>
      </div>
      <div>
        <h3>Approach</h3>
        <p>The utility discovers supported files and downloads them concurrently, turning a repetitive browser workflow into a reusable script.</p>
      </div>
      <div>
        <h3>What it demonstrates</h3>
        <p>Asynchronous Python, web requests, concurrency, and packaging a performance improvement into a straightforward tool.</p>
      </div>
    </div>
    <div class="skill-tags">
      <span>Python</span><span>Async IO</span><span>Web scraping</span><span>Performance</span>
    </div>
  </article>

  <article class="project-case" id="boox-annotation-processing">
    <div class="project-topline">
      <div>
        <span class="project-number">Project 02</span>
        <h2>Boox Annotation Processing</h2>
      </div>
      <div class="portfolio-actions">
        <a class="secondary" href="https://github.com/endaflynn198/boox-annotation-processing">View repository</a>
      </div>
    </div>
    <div class="project-details">
      <div>
        <h3>Problem</h3>
        <p>Annotations exported from a Boox e-reader are awkward to reuse in a personal knowledge base and require repetitive manual formatting.</p>
      </div>
      <div>
        <h3>Approach</h3>
        <p>The tool parses the exported content, applies consistent formatting, and produces clean Markdown ready for applications such as Obsidian.</p>
      </div>
      <div>
        <h3>What it demonstrates</h3>
        <p>Practical Python automation, text processing, command-line workflows, and designing a small tool around a concrete everyday need.</p>
      </div>
    </div>
    <div class="skill-tags">
      <span>Python</span><span>Text processing</span><span>Markdown</span><span>Automation</span>
    </div>
  </article>

  <article class="project-case" id="r-learning-resources">
    <div class="project-topline">
      <div>
        <span class="project-number">Project 03</span>
        <h2>R learning resources</h2>
      </div>
      <div class="portfolio-actions">
        <a class="secondary" href="https://github.com/endaflynn198/r-resources">View repository</a>
      </div>
    </div>
    <div class="project-details">
      <div>
        <h3>Problem</h3>
        <p>Technical examples often show isolated functions without explaining the analytical reasoning, diagnostics, and communication around them.</p>
      </div>
      <div>
        <h3>Approach</h3>
        <p>I created reproducible Quarto reports combining explanation, mathematics, source code, and output for topics including clustering and regression.</p>
      </div>
      <div>
        <h3>What it demonstrates</h3>
        <p>Statistical communication, literate programming, reproducibility, and an educational approach that connects theory with implementation.</p>
      </div>
    </div>
    <div class="skill-tags">
      <span>R</span><span>Quarto</span><span>Statistics</span><span>Teaching</span><span>Reproducibility</span>
    </div>
  </article>
</div>
