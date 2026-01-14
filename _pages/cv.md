---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download my full CV [here](/images/profile.png).

Education
======
* 10/2018 - 07/2022 &nbsp; &nbsp; Ph.D. Computational Geodynamics at University of Mainz, Germany
* 10/2015 - 04/2018 &nbsp; &nbsp; M.Sc. Geoscience at University of Mainz, Germany
* 10/2012 - 03/2016 &nbsp; &nbsp; B.Sc. Geosceince at University of Mainz, Germany

Work experience
======
* 09/2025 - 10/2025 &nbsp; &nbsp; 3-week research stay at ETH Zürich, Switzerland
  * Code development

* 10/2022 - present &nbsp; &nbsp; Postdoctoral Researcher at University of Bayreuth, Germany
  * Code development and execution
  * Thermal runaway as a driver of deep earthquakes
  * Scaling laws for the occurence and intensity of thermal runaway
  * Supervision of two Ph.D. students

* 08/2022 - 09/2022 &nbsp; &nbsp; Postdoctoral Researcher at University of Mainz, Germany
  * Code execution
  * Geodynamic models of magmatic intrusion

* 10/2018 - 07/2022 &nbsp; &nbsp; Ph.D. Student at University of Mainz, Germany
  * Code execution
  * Geodynamic models of magmatic system dynamics
  * Data-driven inversion for subsurface processes
  * Parameterizing complex 3D geometries

* 04/2018 - 09/2018 &nbsp; &nbsp; Research Assistant at University of Mainz, Germany
  * Code execution
  * Geodynamic models of folding

* 04/2012 - 09/2013 &nbsp; &nbsp; Rubel & Partner, Wörrstadt, Germany
  * Geotechnical field work
  * Internship and minor job later on

Supervision
======
* Tatjana Weiler, PhD thesis
  * 12/2023 - present
  * “Modelling of deep earthquake generation in the Hindu Kush”
  * Co-supervisor
* Danielle Silva Souza, PhD thesis
  * 12/2023 - present
  * “Experimental investigation of Antigorite dehydration reactions under deformation”
  * Mentor
* Hao Liu, PhD thesis
  * 10/2023 - present
  * “Geodynamic modelling of the Changbai magmatic system”
  * External advisor
* Muhammad Ilham Hamadi, Master thesis
  * 04/2024 - 10/2024
  * “Postseismic relaxation due to thermally activated ductile deformation”
  * Main supervisor
* Zornitsa Kunchova, Master thesis
  * 06/2022 - 05/2023
  * “Modelling of magmatic systems underneath the Klyuchevskoy group of volcanoes, Kamchatka”
  * Co-supervisor
* Elisabeth Walter, Bachelor thesis
  * 10/2021 - 02/2022
  * “Geophysical Modelling of Magma Induced Uplift at Campi Flegrei, Italy”
  * Co-supervisor

Skills
======
* Languages
  * English, C2
  * German, native speaker
* Programming
  * Julia (daily for 4 years)
  * Matlab (daily for 5 years)
  * Python (weekly for 2.5 years)
  * C/C++, Bash (occasionally for 7 years)
* Open-source software development
  * DEDLoc (Julia)
    * 1D and 2D GPU-compatible thermomechanical code
    * Developed from scratch 
  * LaMEM (C)
    * Highly-parallelized CPU thermomechanical code
    * Added several features to the existing software
  * geomIO (Matlab)
    * Software for the creation of 3D geometries from vector-graphics drawings
    * Added the possibility to automatically create variations for the volumes
  * GeophysicalModelGenerator (Julia)
    * Software to jointly visualize and analyze different geophyiscal data sets
    * Added a few features such as forward modeling of gravity anomalies

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

Invited talks and seminars
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>