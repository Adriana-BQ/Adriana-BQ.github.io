---
layout: page
permalink: /projects/
title: Projects
description: Three lines of work on dark matter — one experimental, one theoretical, one finished.
nav: true
nav_order: 2
---
{% include custom_style.liquid %}
<!--
  STRUCTURE
  Each research programme is one <div class="prog"> block: a heading with dates and
  affiliation, a one-line summary, then "In progress" and/or "Completed" lists.
  Copy a whole block to add a programme; copy one <li> to add a project.
  Thumbnails are optional — delete the <img> line and the programme still lays out.
  NEVER leave a blank line inside a block: Kramdown ends raw HTML at the first blank
  line and prints the rest as visible text.
-->
<div class="prog">
  <div class="prog-head">
    <img class="prog-thumb" src="{{ '/assets/img/projects/topic1.jpg' | relative_url }}" alt="">
    <div class="prog-headtext">
      <h2 class="prog-title">Indirect dark matter searches with KM3NeT</h2>
      <p class="prog-meta">March 2023 – present · IFIC (CSIC – Universitat de València)</p>
    </div>
  </div>
  <p class="prog-summary">Looking for dark matter in neutrino telescope data: if dark matter annihilates or decays, the neutrinos it produces should reach the detectors on the Mediterranean seabed. I work on the analyses that turn that idea into a limit.</p>
  <div class="prog-group">
    <h3 class="prog-label">In progress</h3>
    <ul class="prog-list">
      <li><span class="prog-item-title">WIMP dark matter searches toward the Galactic Centre with KM3NeT/ORCA.</span> Searching ORCA data for the neutrino signature of dark matter annihilation in the Galactic Centre. <span class="prog-cite">Presented at ICRC 2025 — <a href="https://doi.org/10.22323/1.501.0469">PoS ICRC2025, 469</a></span></li>
      <li><span class="prog-item-title">Boosted dark matter searches with KM3NeT/ORCA.</span> Extending the ORCA dark matter programme to boosted dark matter scenarios. <span class="prog-cite">With Aaron Vincent's group, Queen's University</span></li>
    </ul>
  </div>
</div>
<div class="prog">
  <div class="prog-head">
    <img class="prog-thumb" src="{{ '/assets/img/projects/topic2.jpg' | relative_url }}" alt="">
    <div class="prog-headtext">
      <h2 class="prog-title">Effective theories in high energy physics</h2>
      <p class="prog-meta">August 2020 – present · IPARCOS (Universidad Complutense de Madrid) · with Felipe J. Llanes-Estrada</p>
    </div>
  </div>
  <p class="prog-summary">What shape is the dark matter around a galaxy? Rather than assuming a halo profile and fitting to it, this work asks what the observations on their own can say about the geometry of the mass distribution.</p>
  <div class="prog-group">
    <h3 class="prog-label">In progress</h3>
    <ul class="prog-list">
      <li><span class="prog-item-title">Formation of the spiral feature in Milky Way angular-momentum space.</span> N-body simulations of the Galaxy. <span class="prog-cite">With Jorge Peñarrubia, Royal Observatory Edinburgh</span></li>
      <li><span class="prog-item-title">Dark matter halo shapes from gravitational lensing.</span> Constraining halo geometry with lensing observables. <span class="prog-cite">With Abigail Belarde</span></li>
    </ul>
  </div>
  <div class="prog-group">
    <h3 class="prog-label">Completed</h3>
    <ul class="prog-list">
      <li><span class="prog-item-title">No Keplerian taper in far-out SPARC rotation curves.</span> Statistical test of 175 rotation curves for a Keplerian decline at large radii; the data are compatible with no taper at all. <span class="prog-cite"><a href="https://doi.org/10.1016/j.newast.2026.102537">New Astronomy 126, 102537 (2026)</a></span></li>
      <li><span class="prog-item-title">Dark matter halo shape of the Milky Way from stellar-stream torsion.</span> Introduced stream torsion as a local, model-independent probe of halo asphericity. <span class="prog-cite"><a href="https://doi.org/10.1051/0004-6361/202347502">A&amp;A 687, A46 (2024)</a></span></li>
      <li><span class="prog-item-title">Prolate dark matter haloes from SPARC rotation curves.</span> Fitted 175 rotation curves with multipole halo distributions; prolate haloes are strongly preferred over spherical ones. <span class="prog-cite"><a href="https://doi.org/10.1103/PhysRevD.107.083524">Phys. Rev. D 107, 083524 (2023)</a></span></li>
    </ul>
  </div>
</div>
<div class="prog">
  <div class="prog-head">
    <img class="prog-thumb" src="{{ '/assets/img/projects/topic3.jpg' | relative_url }}" alt="">
    <div class="prog-headtext">
      <h2 class="prog-title">Direct dark matter detection and neutrinos</h2>
      <p class="prog-meta">September 2021 – September 2022 · IFT (CSIC – Universidad Autónoma de Madrid)</p>
    </div>
  </div>
  <p class="prog-summary">Beyond-Standard-Model scenarios for direct detection experiments, and what they imply for the neutrino signals those experiments will eventually have to contend with.</p>
  <div class="prog-group">
    <h3 class="prog-label">Completed</h3>
    <ul class="prog-list">
      <li><span class="prog-item-title">Measuring the sterile neutrino mass in spallation source and direct detection experiments.</span> <span class="prog-cite"><a href="https://doi.org/10.1007/JHEP12(2023)096">JHEP 12 (2023) 096</a></span></li>
    </ul>
  </div>
</div>