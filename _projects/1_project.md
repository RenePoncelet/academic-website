---
layout: page
title: HighTEA
description: A database framework for theory events for high-energy physics
img: assets/img/hightea.png
importance: 1
category: work
related_publications:
---

<img src="../../assets/img/hightea.png" alt="HighTEA logo" style="width:200px;display:block;margin-left:auto;margin-right:auto;">

<p align="justify">
Higher-order corrections, particularly those in Quantum Chromodynamics (QCD), are crucial for precision phenomenology at collider experiments such as the Large Hadron Collider (LHC). The computation of these perturbative corrections is computationally expensive (i.e. they need many CPU core hours), especially for corrections beyond the next-to-leading order. Most numerical codes, particularly those for second-order corrections, produce individual numeric results for pre-defined (differential) cross-sections. Moreover, these results are for pre-defined input parameters such as a parton distribution function (PDF) set or choices for the renormalization and factorization scale. If, for example, an analysis needs new observables or different PDF sets, these computations must be repeated. As these computations are expensive, they can be a bottleneck in phenomenological analyses and cost a lot of human resources.
</p>

<p align="justify">
The HighTEA project aims to overcome this issue by storing intermediate computation results (so-called partially unweighted events) so that users can choose observable definitions, PDFs, and scale choices a posteriori. Further, HighTEA provides a public interface that allows everyone to perform this re-analysis using their preferred observables and input parameters.
</p>

<b> To learn more about the HighTEA project, visit the main <a href="https://www.precision.hep.phy.cam.ac.uk/hightea/">website</a> </b>.


<h2> Related publications </h2>
<div class="publications">
  {% bibliography -f papers -q @*[key=Czakon:2023hls]* %}
</div>
