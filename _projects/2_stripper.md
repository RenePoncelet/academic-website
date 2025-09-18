---
layout: page
title: STRIPPER
description: SecToR Improved Phase sPacE for real Radiation -- A NNLO QCD subtraction scheme
img: assets/img/project-sirs-wp.png
importance: 1
category: work
related_publications:
---

<img src="../../assets/img/project-sirs-wp.png" alt="Logo" style="width:200px;display:block;margin-left:auto;margin-right:auto;">

<p align="justify">
This project is a significant milestone in our quest to better understand Quantum Chromodynamics (QCD). A key aspect is the computation of perturbative corrections, particularly the handling of infra-red singularities arising from the loop and real-radiation contributions. Infra-red divergencies occur if particles approach collinear configurations to other massless particles as the angle approaches zero. Alternatively, they can go in the soft limit, where the momentum of the particles is small. Both result in mathematical poles, which need to be handled appropriately.
</p>

<p align="justify">
To strip these poles from calculations, the C++ framework STRIPPER implements systematic cancellations between these and virtual singularities. It provides a general scheme for NNLO QCD corrections. Currently, the code implements the minimal sector-improved residue subtraction method, an improved variant of the prvious 4-dimensional subtraction scheme.
</p>

<p align="justify">
The framework has proven its versatility and practicality in various cutting-edge applications. From top-quark pair and inclusive jet production to the computation of event shape observables at the LHC, STRIPPER has been instrumental. Its flexibility and robustness make it one of the most valuable frameworks for NNLO QCD computations in the field. The software has many features useful for phenomenology:
<ul>
<li> Particle decays in the narrow-width approximation (NWA), including higher-order corrections. </li>
<li> Polarized intermediated boson states </li>
<li> Interface to fastNLO to generate input for PDF fits </li>
<li> Interfaces to one-loop matrix element providers </li>
<li> Fragmentation into hadrons </li>
</ul>
</p>

<h2> Related publications </h2>
<div class="publications">
  {% bibliography -f papers -q @*[key=Czakon:2021mjy]* %}
  {% bibliography -f papers -q @*[key=Czakon:2019tmo]* %}
  {% bibliography -f papers -q @*[key=Behring:2018cvx]* %}
  {% bibliography -f papers -q @*[key=Poncelet:2018vdr]* %}
</div>
