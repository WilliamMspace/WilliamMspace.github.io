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
* M.S. in Physics, California State University Los Angeles, May 2027 (expected)
* B.A. in Engineering Physics, Augustana College, 2024

Research Experience
======
* Dec 2024 - Present: LIGO Scientific Collaboration
  * PI: Dr. Harry Themann
  * Analyzing public LIGO data on GW250114 to perform tests of general relativity by testing the
    consistency of the inspiral-merger-ringdown consistency andHawking area law.
  * Used LIGO data to constrain black holes source properties - using GWpy and PyCBC to create         nested sampling runs in order to estimate parameters of merging black hole binaries 

* June 2025 - July 2025: Visiting Collaborator - 2025 MACRO Summer Program (Virtual)
  * PI: Dr. John Cannon
  * Investigated the presence of radio variability in the eclipsing cataclysmic variable LX Serpens using the NRAO high-performance computing cluster.
  
Skills
======
* Python(SciPy,Matplotlib,Numpy,Astropy,GWpy,PyCBC); C++, Shell/Scripting(Bash,Nano,Linux/Ubuntu); MATLAB
  
* SPDC design, 3d printing, mechanical design (Onshape, Autodesk Inventor), basic CNC and Arduino

* HPC Job Scheduling, Interferometric Calibration (basic familiarity)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* SPS Associate Zone Councilor
* Augustana College APS_IDEA Inclusion Diversity Equity Alliance
* Augustana Society of Physics Students
  * Chapter President
  * John Deere Planetarium Astro-Night Host   
