---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* MPhys in Theoretical Physics, University of Sheffield, 2011
* PhD in Physics, University of Sheffield, 2015

Employment
======
* 2021 - present: Research Fellow
  * Leeds Institute of Cardiovascular and Metabolic Medicine, University of Leeds
  * Duties included: Processing cardiac Diffusion Tensor Imaging data
  * Supervisor: Professor Jurgen Schneider 

* 2017 - 2021: Research Associate
  * Department of Computer Science, INSIGNEO Institute for _in silico_ medicine, University of Sheffield
  * Duties included: Calibration of cardiac electrophysiology models
  * Supervisor: Professor Richard Clayton 

* 2015 - 2017: Research Associate
  * Department of Physics and Astronomy, University of Sheffield
  * Duties included: Emulation of complex models with Gaussian process emulators 
  * Supervisor: Professor Nigel Clarke
  
Skills
======
* Uncertainty quantification
  * model sensitivity
  * probabilistic calibration with surrogate models
  * Gaussian processes (including on non-Euclidean domains)
* Processing medical data
  * cardic MRI imaging data
  * surface mesh manipulation
  * electrophysiology data
* Coding and software
  * highly skilled in Python, experienced in Matlab, R, C++
  * version control (git) for large collaborative software (e.g. https://dipy.org/team.html)
  * developing and maintaining research software for teams with varying levels of computer skills

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
