---
layout: page
permalink: /projects/
title: Projects
description: Click any project to read what it is about.
nav: true
nav_order: 2
---
{% include custom_style.liquid %}
<!--
  STRUCTURE
  Two levels of heading: status (## In progress / ## Completed), then theme (###).
  Each project is one <details class="proj"> box. Closed it shows the title and a
  meta line; clicking opens the description.
  To add one, copy a whole <details> ... </details> block.
  NEVER leave a blank line inside a block — Kramdown ends raw HTML at the first
  blank line and prints the rest of the page as visible text.
-->
## In progress
### Dark matter: model-driven searches
<div class="proj-grid">
<details class="proj">
  <summary><span class="proj-name">WIMP searches toward the Galactic Centre</span><span class="proj-meta">KM3NeT/ORCA · IFIC (CSIC – Universitat de València) · 2023 – present</span></summary>
  <div class="proj-body">
    <p>If dark matter accumulates in the centre of the Galaxy and annihilates there, some of what comes out should be neutrinos. I search KM3NeT/ORCA data for that signal: an excess of neutrinos pointing back at the Galactic Centre, with an energy spectrum set by the dark matter mass rather than by any astrophysical source.</p>
    <p class="proj-cite">Presented at ICRC 2025 — <a href="https://doi.org/10.22323/1.501.0469">PoS ICRC2025, 469</a></p>
  </div>
</details>
<details class="proj">
  <summary><span class="proj-name">Boosted dark matter searches</span><span class="proj-meta">KM3NeT/ORCA · with Aaron Vincent's group, Queen's University</span></summary>
  <div class="proj-body">
    <p>Standard WIMP searches assume dark matter in the halo is slow. Boosted scenarios do not: they predict a relativistic dark matter flux, which leaves a different signature in a neutrino telescope. This project extends the ORCA dark matter programme to cover them.</p>
    <p class="proj-cite">REPLACE — one sentence on the specific scenario or observable, if you want it here.</p>
  </div>
</details>
</div>
### Dark matter: data-driven approach
<div class="proj-grid">
<details class="proj">
  <summary><span class="proj-name">The spiral feature in Milky Way angular-momentum space</span><span class="proj-meta">N-body simulations · with Jorge Peñarrubia, Royal Observatory Edinburgh</span></summary>
  <div class="proj-body">
    <p>Stars in the Milky Way trace a spiral pattern when plotted in angular-momentum space. This project uses N-body simulations of the Galaxy to work out how that feature forms and what it can tell us about the potential it formed in.</p>
    <p class="proj-cite">REPLACE — add a line on the expected result, or delete this line.</p>
  </div>
</details>
<details class="proj">
  <summary><span class="proj-name">Halo shapes from gravitational lensing</span><span class="proj-meta">with Abigail Belarde</span></summary>
  <div class="proj-body">
    <p>A third, independent handle on the same question the rotation-curve and stellar-stream work asks: lensing observables constrain the geometry of the mass distribution without assuming a halo profile.</p>
    <p class="proj-cite">REPLACE — add a line on the method or dataset, or delete this line.</p>
  </div>
</details>
</div>
## Completed
### Dark matter: data-driven approach
<div class="proj-grid">
<details class="proj">
  <summary><span class="proj-name">No Keplerian taper in far-out SPARC rotation curves</span><span class="proj-meta">New Astronomy 126, 102537 (2026) · IPARCOS-UCM · with F. J. Llanes-Estrada</span></summary>
  <div class="proj-body">
    <p>If a galaxy's mass ran out where its light does, rotation velocities would fall off in a Keplerian way at large radii. We tested 175 SPARC rotation curves for exactly that decline and found the data compatible with no taper at all. The Milky Way is the odd one out: it declines by about 20%, which suggests our own Galaxy may not be typical.</p>
    <p class="proj-cite"><a href="https://doi.org/10.1016/j.newast.2026.102537">Published version</a> · <a href="https://arxiv.org/abs/2507.12120">arXiv:2507.12120</a></p>
  </div>
</details>
<details class="proj">
  <summary><span class="proj-name">Milky Way halo shape from stellar-stream torsion</span><span class="proj-meta">A&amp;A 687, A46 (2024) · IPARCOS-UCM · with F. J. Llanes-Estrada</span></summary>
  <div class="proj-body">
    <p>A stellar stream would stay on a single plane if the halo's gravitational field were spherically symmetric. We introduced the torsion of the stream — its rate of twist out of that plane — as a local, model-independent measure of how aspherical the halo is. Simulations confirm central forces give negligible torsion; Milky Way streams at large galactocentric distances show far more than a spherical halo can produce.</p>
    <p class="proj-cite"><a href="https://doi.org/10.1051/0004-6361/202347502">Published version</a> · <a href="https://arxiv.org/abs/2307.07402">arXiv:2307.07402</a></p>
  </div>
</details>
<details class="proj">
  <summary><span class="proj-name">Prolate dark matter haloes from SPARC rotation curves</span><span class="proj-meta">Phys. Rev. D 107, 083524 (2023) · IPARCOS-UCM · with F. J. Llanes-Estrada, O. Manzanilla Carretero</span></summary>
  <div class="proj-body">
    <p>Flat rotation curves follow naturally from a dark matter distribution elongated perpendicular to the galactic plane. Fitting SPARC rotation curves with multipole density distributions gives markedly better fits for prolate haloes than spherical ones, and the fitted ellipticities exceed what cosmological simulations produce. If the Milky Way resembles this population, the local dark matter density may be overestimated by a factor of two — which matters directly for direct-detection limits.</p>
    <p class="proj-cite"><a href="https://doi.org/10.1103/PhysRevD.107.083524">Published version</a> · <a href="https://arxiv.org/abs/2204.06384">arXiv:2204.06384</a></p>
  </div>
</details>
</div>
### Neutrino phenomenology
<div class="proj-grid">
<details class="proj">
  <summary><span class="proj-name">Measuring the sterile neutrino mass in spallation source and direct detection experiments</span><span class="proj-meta">JHEP 12 (2023) 096 · IFT (CSIC – Universidad Autónoma de Madrid) · 2021 – 2022</span></summary>
  <div class="proj-body">
    <p>Beyond-Standard-Model work on how a sterile neutrino would show up in two very different experimental settings — a spallation neutron source and a direct dark matter detector — and what mass range each could reach.</p>
    <p class="proj-cite"><a href="https://doi.org/10.1007/JHEP12(2023)096">Published version</a> · <a href="https://arxiv.org/abs/2307.05176">arXiv:2307.05176</a></p>
  </div>
</details>
</div>