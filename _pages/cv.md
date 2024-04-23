---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download
======
My academic CV in PDF format can be accessed <a href="/files/CV-Qisheng_Pan.pdf" target="_blank">here</a>.

<br>

Education
======
* Ph.D in Computational Biology, University of Queensland, Australia, 2022 - 2025 (expected)
* M.S. in Bioinformatics, University of Melbourne, 2019 - 2021
* B.S. in Biotechnology, South China Normal University, 2015 - 2019

<br>

Skills
======
* Programming: Python, R, Linux, JavaScript
* Software: BLAST, MODELLER, PyMol, AutoDock Vina, GALAXY, etc.
* Machine learning: Random Forest, Neural Network, Feature selection, etc. 

<br>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

<br>

Collaboration
======
* <a href="https://www.rmit.edu.au/contact/staff-contacts/academic-staff/b/boer-dr-jennifer" target="_blank">Jeniffer Boer</a> and <a href="https://www.rmit.edu.au/contact/staff-contacts/academic-staff/p/plebanski-magdalena" target="_blank">Magdalena Plebanski</a>, Royal Melbourne Institute of Technology, Australia 2022 - 2023 
  * Investigating the variants of the Spike protein in Omicron SARS-CoV-2 virus 
* Researcher across Australia, on-going, 2023 - now
  * Charactersing the effect of mutations reported in clinical screening

<br>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

<br>

Mentorship
======
* Georgina Becerra Parra, Undergraduate project, 2022
* Dana Jessen-Howard, Master's project, 2023
* Joshua Khoo, Master's project, 2024

<br>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


