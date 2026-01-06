---
layout: archive
title: ""
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

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
