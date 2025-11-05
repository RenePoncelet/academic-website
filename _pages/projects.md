---
layout: page
title: projects
permalink: /projects/
description: Precision Standard Model Phenomenonogy
nav: true
nav_order: 3
display_categories: [work]
horizontal: false
---

---
<h2>
What even is Standard Model Phenomenology?
</h2>

<p align="justify">
When protons are sped up and directed at each other in the Large Hadron Collider, they hit each other with massive energy. This high energy leads the colliding parts of the protons to create other particles. These again bounce or hit each other, interact, or decay into other particles, and sometimes whole jets, or showers of particles.
These are detected in sensitive equipment and analysed with sophisticated tools and mathematics. Which particles can be found, how often, their direction and speed, all these characteristics are used to find out what happens during and after these collisions. What pattern can only be explained with a specific process happening between collision and detection ? What particles existed and fell apart again into a shower of others? Which ones bounced off of each other giving speed in different directions? 
The characteristics of what particles are detected and how often they can be seen allows many deductions about what particles can exist and how they interact. This tells us much about how the very physical structure of the universe looks.
Experimentalist particle physicists measure this data, interpret the signals in detectors to categorise different particles, and analyse certain patterns. Theoretical particle physicists take what we know about the underlying principles of interactions and build models out of this to describe by what mechanics of particles and forces we could come to see the world that we do encounter. They both check if they describe what we already know, and they also calculate predictions of what we expect to see in certain experiments.
The scientific field at the interaction of the measured data and theoretical models is called phenomenology. It looks at the phenomena that occur in a collision and endeavours to describe them in mathematical terms so they can be included in models.
The Standard Model is one such a model. Experiments aim to test this with each new experimental scope that becomes available and change the model if it ever ceases to fully explain the physics we see. However, it is called "Standard", because it is the simplest model that can describe all the things that could be seen in any experiments with fundamental particles so far.
</p>
---


<!-- pages/projects.md -->
<div class="projects">
{% if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_projects = site.projects | where: "category", category %}
  {% assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}

{% else %}

<!-- Display projects without categories -->

{% assign sorted_projects = site.projects | sort: "importance" %}

  <!-- Generate cards for each project -->

{% if page.horizontal %}

  <div class="container">
    <div class="row row-cols-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="grid">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
{% endif %}
</div>
