---
layout: page
title: STRIPPER
description: SecToR Improved Phase sPacE for real Radiation -- A NNLO QCD subtraction scheme
img: assets/img/sirs.png
importance: 1
category: work
related_publications:
---

<img src="../../assets/img/sirs.png" alt="Logo" style="width:200px;display:block;margin-left:auto;margin-right:auto;">

<p align="justify">
The STRIPPER project is a significant milestone in our quest to better understand Quantum Chromodynamics (QCD). A key aspect of this project is the computation of perturbative corrections, which requires the systematic cancellation between infra-red singularities arising from the loop and real-radiation contributions. STRIPPER, a general scheme for NNLO QCD corrections, is the name of the C++ framework that implements the 4-dimensional version of the scheme. Currently, the STRIPPER code implements the minimal sector-improved residue subtraction method, an improved variant of the 4-dimensional STRIPPER subtraction scheme.
</p>

<p align="justify">
The STRIPPER framework has proven its versatility and practicality in a wide range of cutting-edge applications. From top-quark pair and inclusive jet production to the computation of event shape observables at the LHC, STRIPPER has been instrumental. Its flexibility and robustness make it one of the most valuable frameworks for NNLO QCD computations in the field. The software has many features useful for phenomenology:
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
