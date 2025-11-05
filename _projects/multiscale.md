---
layout: page
title: Multiscale processes
description: Higher orders for higher multiplicity cross-sections
img: assets/img/project-2to3-wp.png
importance: 5
category: work
related_publications:
---

<img src="../../assets/img/project-2to3.png" alt="Contributions to three jet production through NNLO QCD" style="width:400px;display:block;margin-left:auto;margin-right:auto;">

<!--
%<p align="justify">
%Multi-jet and photon production are a staple of Standard Model phenomenology,  at the Large Hadron Collider. As more and more data is collected at the Large Hadron Collider and experimental analysis techniques improve, it is possible to measure processes with higher precision. This is also true for higher multiplicity processes with many produced particles or jets, for example three-jet production. Indeed, the experimental precision for many processes with three or more identified objects is already much higher than how precise the current 'industry standard', NLO QCD predictions, can currently calculate what data to expect for the Standard Model. 
%The next level of precision are NNLO QCD predictions. They are often needed to reach similar precision as experimental data and to describe this data accurately and theoretically. These processes offer many phenomenological applications, such as extracting, and thus being able to look at, specific relevant values or process functions within these calculations, such as the strong coupling constant, or functions of photon fragmentation. They also improve estimates of how much background noise is captured alongside data.
%</p>

%<p align="justify">
The additional corrections at higher-order that differentiate NNLO from NLO QCD are an enormous challenge to compute. It is one of the edges of precision phenomenology. The demands on the efficiency and stability of the numerical computations are high. We use the STRIPPER framework for this. It uses a mathematical knack and sophisticated implementation to strip away parts of the calculations that can create computation problems, without compromising the reliability of the results. It has been used to compute several production processes found at the LHC where from two particles, three particles or jets are created. These are all the ones where any particles are photons, which have no mass. Jets, though they are many particles, can be surprisingly well described by an approximation without mass. All of the described processes are thus massless two-to-three productions.
%<ul>
%<li> Three-photon </li>
%<li> Photon-pair plus jet </li>
%<li> Photon plus jet pair </li>
%<li> Three-jet </li>
%</ul>

%We work on constantly improving the STRIPPER framework to further increase computational efficiency. We also work to compute the necessary two-loop amplitudes, which are the defining step in the additional corrections at NNLO.
%</p>

---
-->

<p align="justify">
Multi-jet and photon production are a staple of Standard Model phenomenology at the Large Hadron Collider. As more and more data is collected at the Large Hadron Collider and experimental analysis techniques improve, measuring higher multiplicity processes, for example, three-jet production, with higher precision, is possible. Indeed, the experimental precision for many processes with three or more identified objects is already much higher than that of NLO QCD predictions, which are the 'industry standard'. NNLO QCD predictions are often needed to reach experimental precision and to describe the data accurately and theoretically. These processes offer many phenomenological applications, such as extracting the strong coupling constant, improving background estimates, and extracting photon fragmentation functions.
</p>

<p align="justify">
Computing the higher-order corrections for these processes is an enormous challenge and one of the edges of precision phenomenology. The demands on the efficiency and stability of the numerical computations are high. The STRIPPER framework has been used to compute all massless two-to-three production processes at the LHC:
<ul>
<li> Three-photon </li>
<li> Photon-pair plus jet </li>
<li> Photon plus jet pair </li>
<li> Three-jet </li>
</ul>
We work on computing the necessary two-loop amplitudes and constantly improving the STRIPPER framework to further increase computational efficiency.
</p>


<h2> Related publications </h2>
<div class="publications">
  {% bibliography -f papers -q @*[key=Badger:2024mir]* %}
  {% bibliography -f papers -q @*[key=Badger:2023mgf]* %}
  {% bibliography -f papers -q @*[key=Alvarez:2023fhi]* %}
  {% bibliography -f papers -q @*[key=Hartanto:2022ypo]* %}
  {% bibliography -f papers -q @*[key=Hartanto:2022qhh]* %}
  {% bibliography -f papers -q @*[key=Czakon:2021mjy]* %}
  {% bibliography -f papers -q @*[key=Chawdhry:2021hkp]* %}
  {% bibliography -f papers -q @*[key=Chawdhry:2021mkw]* %}
  {% bibliography -f papers -q @*[key=Chawdhry:2020for]* %}
  {% bibliography -f papers -q @*[key=Chawdhry:2019bji]* %}
</div>
