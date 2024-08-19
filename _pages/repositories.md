---
layout: page
permalink: /repositories/
title: Repositories
description: Below I feature an old GitHub account (EndaFlynn1) and my current one (endaflynn198). My old account is mostly sequential scripts and my new account demonstrates the more sophisticated approaches to coding I have developed since I was a college student!
nav: true
nav_order: 4
---

## Projects

---


### HDI Indicators R Package
_[GitHub](https://github.com/endaflynn198/HDI_summary)_

This library applies OOP principles to allow the easy summary and comparison of UN Human Development Indicators data from different countries. See related blog post [here](https://endaflynn198.github.io/blog/2024/HDI_indicators/). 

And you can get a sense of the package by reading the vignette comparing Singapore and Nigeria [here](https://htmlpreview.github.io/?https://github.com/endaflynn198/HDI_summary/blob/main/vignettes/HDIsummary.html)




### Boox Annotation Formatting tool
_[GitHub](https://github.com/endaflynn198/boox-annotation-processing)_

The Boox Annotation Processing repository provides a simple solution for processing Boox annotations. It allows you to convert the annotations into a formatted output that can be easily imported into note-taking and personal knowledge base (PKB) applications like [Obsidian](https://obsidian.md/).

### Asynchronous Downloader
_[GitHub](https://github.com/endaflynn198/asynchronous_downloader_tool)_

This repository contains a simple asynchronous downloader that can be used to download all `.webm` and `.png` files from a website concurrently. This enables the rapid download of large numbers of files which can be useful for scraping image boards, open directories, and similar websites.





## GitHub users

{% if site.data.repositories.github_users %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
{% if site.data.repositories.github_users.size > 1 %}

  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username=user %}
  </div>

---

{% endfor %}
{% endif %}
{% endif %}

## GitHub Repositories

{% if site.data.repositories.github_repos %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
