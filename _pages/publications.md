---
layout: page
permalink: /publications/
title: publications
description: Journal articles and theses in reverse chronological order.
nav: true
nav_order: 4
---

<!-- _pages/publications.md -->

Publications, current through 07/2025. Links point to journal pages, PDFs, or thesis records where available.

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

<h2>Journal Articles</h2>

{% bibliography --query @article %}

<h2>In Progress</h2>

<div class="row">
  <div class="col col-sm-2 abbr">
    <img class="preview z-depth-1 rounded" src="/assets/img/publication_preview/bodiesreg_overview.jpg" width="100%" height="auto" alt="BODIESReg registration pipeline overview" style="max-height: 120px; object-fit: contain;">
  </div>
  <div class="col-sm-8">
    <div class="title">BODIESReg: An open-source pipeline for registering 3D body scans using pose-aligned initialization</div>
    <div class="author">Vikash Chaurasia et al.</div>
    <div class="periodical">Submitted.</div>
    <div class="links">
      <a class="btn btn-sm z-depth-0" href="https://github.com/chaurasiavikash/BODIESReg" target="_blank" rel="noopener noreferrer" role="button">GitHub</a>
    </div>
  </div>
</div>

<p>Vikash Chaurasia and Eliot Fried. <em>Inside-out motion of mobile linkages.</em></p>

<h2>Theses</h2>

{% bibliography --query @phdthesis, @mastersthesis %}

</div>
