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
University of Science and Technology of China (USTC), Hefei, China
B.S. in Applied Physics, 2024 (expected)
Condensed Matter Physics track, Yan Jici Talent Program in Physics (Honor Class)
**Major GPA: 3.82/4.30 (Ranked Top 10 out of 84 in the field of Condensed Matter Physics)**
Coursework: Thermodynamics and Statistical Physics A (99), Solid State Physics (95), Physics of Semiconductor
(94), Computational Physics A (92), Computational Method (91), Theoretical Mechanics A (90)

* **Outstanding Award in Atomic Physics Seminar** (Honoring USTC researchers who presented exceptional seminar presentations on topics related to atomic physics, 2022)
* Outstanding Student Scholarship - Bronze Award of USTC (2021)
* Endeavour Award of USTC (2021)
* **Annual Scholarship of Yan Jici Physics Science and Technology Excellence Class** (2020)

;* M.S. in Jekyll, GitHub University, 2014
;* Ph.D in Version Control Theory, GitHub University, 2018 (expected)

Research Experience
======
**Summer Researcher** | The O’Hern Group in Yale School of Engineering & Applied Science &ensp; Jul.2023 - Now
**Riverbed DEM Simulation, supervised by Prof. Corey O’Hern from Yale University** &ensp; CT, USA
* Simulated a 3D riverbed system using 400 bi-disperse particles with periodic boundary conditions, and studied
how the bed’s properties are changed due to different prestress history exerted by flow
* Optimized the simulation by introducing particle-particle elastic force, damping force, fluid’s dragging force, and
buoyancy force, to make the system more realistic
* Prepared different sedimented configurations of the bed, applied flow characterized by different Reynolds
numbers and Shield numbers, identified the critical combination of parameters to make a static riverbed mobile,
and reproduced Shield’s curve
* Prestress the beds with under-critical parameters to study new Shield’s curve again, and investigate the effect of
prestress history on bed’s anisotropy and resistance to applied flow (in progress)
* Utilize **C++** to develop the simulation, leveraging standard algorithms for DEM like *Verlet list* and *velocity Verlet
integration*

&nbsp;
**Undergraduate Researcher | Laboratory of Soft Matter Physics** &ensp; Apr. 2022 - Now
**Soft Matter Molecular Dynamics Simulation, supervised by Prof. Ning Xu from USTC** &ensp; Hefei, China
* Simulated the evolution of a system consisting of 256 short-range interacting particles using molecular dynamics methods, and investigated its macroscopic properties, such as pressure and moduli
* Determined the equilibrium state of the system with **Python** programming, solved the zero-temperature minimum energy configuration and the Jamming point by implementing the *FIRE* algorithm from an initial infinite temperature configuration, and calculated the critical scaling near the Jamming point
* Encapsulated the simulation code to obtain a simulation module for easy transplantation and reuse, optimized the algorithm using the *Verlet neighbor list*, and improved the computational efficiency for large-scale matrices using *Numpy* library functions
* Utilize the *Numba* module to pre-compile functions, thereby enhancing code execution efficiency by over 90%, with stabilization’s time cost drop from 10s to less than 0.8s

&nbsp;
**Summer Researcher | GREAT Summer Research Program of UC Davis** &ensp; Jul. 2022 - Aug. 2022
**Supervised by Prof. Dong Yu from UC Davis** &ensp; Online
* Constructed a model of solar cells using the finite element method, and successfully solved complex partial
differential equations regarding the potential and carrier distribution within the device.
* Utilized **COMSOL** to predict the impact of external bias voltage on the temporal evolution and spatial variation of the electric field and carrier density inside the device
* Simulated the ion migration in hybrid halide perovskite MAPbBr3, and evaluated its impact on the energy conversion efficiency
  
Course Project
======
**Generation and Detection of Vortex Beam | Team Leader and took charge of all the simulation work** &ensp; Oct. 2022 - Mar. 2023
* Studied the generation and propagation of vortex beams by reviewing the literature
* Used spatial light moderator to prepare vortex beams in modes with different topological charge numbers
* Designed optical path to observe optical vortex’s behavior, observed the interference phenomenon between optical
vortices and plane waves or spherical waves, and analyzed the geometric structure of the interference pattern
* Used **COMSOL** to visualize wave front of vortex beam and used Python to predict interference patterns and
compare them with experimental results
* **Achievement**: Received the Special Prize **(Top 10%)** in the USTC’s 18th University Physics Innovative Experimental Research Paper Competition for my paper titled "Generation of Vortex Beams"


<!-- Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub -->
  
Skills and Interests
======
* **Technical & Computational**
  * C, C++ (proficient)
  * Python (proficient)
  * Linux (skilled) in use of Slurm & LSF workload manager and bash scripts
  * Fortran (skilled)
  * COMSOL Multiphysics (familiar)
  * Wolfram Mathematica (familiar)
  * etc.
* **Language**
  * English (fluent, **TOFEL 111-Speaking 26**)
  * Chinese (native)
* **Interests**
  * Playing tennis
  * playing the piano
  * avidly exploring emerging technologies

<!-- Publications
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
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
