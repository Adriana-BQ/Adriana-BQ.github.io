---
layout: page
permalink: /publications/
title: publications
description: Also on <a href="https://orcid.org/0000-0001-5187-7505">ORCID</a>, <a href="https://inspirehep.net/authors?q=Bariego-Quintana">INSPIRE-HEP</a> and <a href="https://ui.adsabs.harvard.edu/search/q=author%3A%22Bariego-Quintana%2C%20A.%22">NASA ADS</a>.
nav: true
nav_order: 3
---

<!--
  You do not edit the list of papers here — the two lists below are generated from:
      _bibliography/papers.bib   → "Dark matter at galactic scales"
      _bibliography/km3net.bib   → "KM3NeT Collaboration"
  Move a paper between sections by moving its entry between those two files.
  Rename a section by editing the <h2> text below.
-->

<style>
  .pub-section {
    margin-top: 2.6rem;
  }
  .pub-section:first-of-type {
    margin-top: 1.4rem;
  }
  .pub-section-head {
    display: flex;
    align-items: baseline;
    gap: 1rem;
    flex-wrap: wrap;
    padding-bottom: 0.4rem;
    border-bottom: 2px solid currentColor;
    margin-bottom: 0.5rem;
  }
  .pub-section-head h2 {
    margin: 0;
  }
  .pub-section-note {
    font-size: 0.9rem;
    opacity: 0.75;
    margin: 0.4rem 0 0.8rem;
  }
</style>

{% include bib_search.liquid %}

<div class="pub-section">
  <div class="pub-section-head">
    <h2>Dark matter at galactic scales</h2>
  </div>
  <p class="pub-section-note">
    REPLACE — one line describing this line of work, e.g. “Stellar-stream torsion, halo shape and
    galactic rotation curves.” Delete this paragraph if you would rather it went straight into the list.
  </p>
  <div class="publications">
  {% bibliography %}
  </div>
</div>

<div class="pub-section">
  <div class="pub-section-head">
    <h2>KM3NeT Collaboration</h2>
  </div>
  <p class="pub-section-note">
    Papers signed by the full KM3NeT Collaboration author list. My own contributions are in the
    dark matter and neutrino-oscillation analyses — REPLACE or delete this sentence.
  </p>
  <div class="publications">
  {% bibliography -f km3net %}
  </div>
</div>
