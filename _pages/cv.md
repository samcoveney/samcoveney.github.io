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
  * Duties included: Developing novel techniques for processing cardiac Diffusion Tensor Imaging data
  * Supervisor: Professor Jurgen Schneider 

* 2017 - 2021: Research Associate
  * Department of Computer Science, INSIGNEO Institute for _in silico_ medicine, University of Sheffield
  * Duties included: Calibration of cardiac electrophysiology models
  * Supervisor: Professor Richard Clayton 

* 2015 - 2017: Research Associate
  * Department of Physics and Astronomy, University of Sheffield
  * Duties included: Emulation of complex models with Gaussian Process emulators 
  * Supervisor: Professor Nigel Clarke
  
Skills
======
* Gaussian process emulators
    * surrogate models
    * probabilistic calibration
    * interpolation on non-Euclidean domains
* Processing medical data
  * MRI imaging data
  * electrophysiology catheter measurements 
* Research Software
    * Python 
    * R

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
