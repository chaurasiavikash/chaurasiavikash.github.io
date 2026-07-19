---
layout: page
permalink: /research/
title: research
description: Research themes and selected projects.
nav: true
nav_order: 2
---

<div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1.25rem;">
  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem;">
    <img src="/images/helicoid_mobius_webpage.png" alt="Helicoid deforming into a Mobius band" style="width: 100%; height: 180px; object-fit: contain; margin-bottom: 0.75rem;">
    <h3 style="margin-top: 0;">Isometric folding of helicoids into Mobius bands</h3>
    <p>In this work, we ask when an unstretchable circular helicoid can fold into a Mobius band without changing its metric. We reduce the surface geometry to conditions on the band midline and its frame, then use those conditions to design helicoid templates. The construction gives stable Mobius bands with prescribed odd numbers of half twists.</p>
    <p><a href="https://link.springer.com/article/10.1007/s10659-023-10008-x" target="_blank" rel="noopener noreferrer">Paper</a> &middot; <a href="/gallery/">Gallery</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem;">
    <img src="/images/knot_eversion_rev2.jpg" alt="Knotted band eversion states" style="width: 100%; height: 180px; object-fit: contain; margin-bottom: 0.75rem;">
    <h3 style="margin-top: 0;">Everting motions of Mobius and orientable bands</h3>
    <p>In this project, we construct continuous eversion paths for Mobius and orientable binormal scrolls while preserving metric and bending energy. We track the full motion, not just the starting and ending shapes. The examples connect classical curve geometry with foldable, shape-changing structures.</p>
    <p><a href="https://link.springer.com/article/10.1007/s00332-025-10164-5" target="_blank" rel="noopener noreferrer">Paper</a> &middot; <a href="https://chaurasiavikash.github.io/mobius_visualization/" target="_blank" rel="noopener noreferrer">Mobius demo</a> &middot; <a href="https://chaurasiavikash.github.io/bates_visualization/" target="_blank" rel="noopener noreferrer">Orientable demo</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem;">
    <img src="/images/curves_on_sphere.png" alt="Charged elastic loops on a sphere" style="width: 100%; height: 180px; object-fit: contain; margin-bottom: 0.75rem;">
    <h3 style="margin-top: 0;">Charged elastic loops on a sphere</h3>
    <p>In this work, we formulate the equilibrium problem for charged elastic loops constrained to lie on a sphere. We balance bending energy with intra-loop and inter-loop electrostatic interactions. We then analyze how loop length and charge density select unstable modes and equilibrium shapes.</p>
    <p><a href="https://www.sciencedirect.com/science/article/pii/S0022509619305411" target="_blank" rel="noopener noreferrer">Paper</a> &middot; <a href="/gallery/">Gallery</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem;">
    <img src="/images/charge_hetero_covid.jpg" alt="Coronavirus particle model with charge heterogeneity" style="width: 100%; height: 180px; object-fit: contain; margin-bottom: 0.75rem;">
    <h3 style="margin-top: 0;">Virus-shape modeling and hydrodynamics</h3>
    <p>For these projects, we represented virus particles as rigid cores decorated with rigid bead-rod spike proteins, then minimized interaction energies to obtain particle shapes.</p>
    <ul style="padding-left: 1.2rem; margin-bottom: 0.75rem;">
      <li><a href="https://pubs.aip.org/aip/pof/article-abstract/35/3/037125/2882155/Coronavirus-peplomer-charge-heterogeneity" target="_blank" rel="noopener noreferrer">Charge heterogeneity</a>: how nonuniform spike charges alter spike arrangements and hydrodynamic response.</li>
      <li><a href="https://pubs.aip.org/aip/pof/article/33/3/033115/1064042" target="_blank" rel="noopener noreferrer">Spike shape</a>: how triangular spike geometry changes particle shape and transport properties.</li>
      <li><a href="https://pubs.aip.org/aip/pof/article/34/6/063101/2846764" target="_blank" rel="noopener noreferrer">Pleomorphism</a>: how spherical, prolate, and oblate cores change virus-particle hydrodynamics.</li>
    </ul>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem;">
    <img src="/images/surface_tension.png" alt="Surface tension imbalance on partly submerged bodies" style="width: 100%; height: 180px; object-fit: contain; margin-bottom: 0.75rem;">
    <h3 style="margin-top: 0;">Surface tension imbalance</h3>
    <p>In this project, we analyzed partly submerged bodies separating surfactant-laden and surfactant-free liquid interfaces. We quantified how surface tension imbalance changes vertical support and creates horizontal forces. The same mechanics appears in Marangoni propulsion and surface-pressure measurement.</p>
    <p><a href="https://www.cambridge.org/core/journals/journal-of-fluid-mechanics/article/effect-of-a-surface-tension-imbalance-on-a-partly-submerged-cylinder/F2C597292793A3785BB87FFAD484DF0D" target="_blank" rel="noopener noreferrer">Paper</a></p>
  </section>

  <section style="border: 1px solid var(--global-divider-color); border-radius: 8px; padding: 1rem;">
    <img src="/images/bodiesreg_overview.jpg" alt="BODIESReg registration pipeline overview" style="width: 100%; height: 180px; object-fit: contain; margin-bottom: 0.75rem;">
    <h3 style="margin-top: 0;">BODIESReg for 3D body-scan registration</h3>
    <p>BODIESReg is an open-source pipeline for registering 3D body scans to parametric body models. We estimate the scan pose before surface fitting, so the optimizer starts from a pose-aligned mesh rather than a default template pose. The pipeline runs end-to-end in automatic mode, supports batch processing, and includes interactive tools for difficult scans.</p>
    <ul style="padding-left: 1.2rem; margin-bottom: 0.75rem;">
      <li>Targets biomechanical model personalization from 3D body surface scans.</li>
      <li>Uses pose-aligned initialization before Chamfer-distance minimization.</li>
      <li>Achieved mean surface-fit errors below 10 mm for successful registrations.</li>
    </ul>
    <p><a href="https://github.com/chaurasiavikash/BODIESReg" target="_blank" rel="noopener noreferrer">GitHub repository</a></p>
  </section>
</div>
