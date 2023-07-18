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
* B.S. in Mechanical and Automation Engineering, Hohai University, 2008
* M.S. in Naval and Ocean Engineering, Zhejiang University, 2015
* Ph.D in Mechanical and Aerospace Engineering, University of California, Davis, 2021

Work experience
======
* Spring, Winter 2016: Research Assistant
  * University of California, Davis
  * Duties included: Software development of education robots 
  * Supervisor: [Harry H. Cheng](https://faculty.engineering.ucdavis.edu/cheng/)

* Summer 2017: Research Assistant
  * University of California, Davis
  * Duties included: Motion control of agriculture robotics
  * Supervisor: [Stavros G. Vougioukas](https://faculty.engineering.ucdavis.edu/vougioukas/)

* Fall 2018: Research Assistant
  * University of California, Davis
  * Duties included: Data Driven Simulation of strawberry harvesting activities
  * Supervisor: [Stavros G. Vougioukas](https://faculty.engineering.ucdavis.edu/vougioukas/). 

* Summer 2019: Research Assistant
  * University of California, Davis
  * Duties included: Navigation of crop-transport robots in the strawberry field
  * Supervisor: [Stavros G. Vougioukas](https://faculty.engineering.ucdavis.edu/vougioukas/). 

* March 2021: Post-doctoral Scholar
  * University of California, Davis
  * Duties included: IoT system development for data collection in the harvesting scenario
  * Supervisor: [Stavros G. Vougioukas](https://faculty.engineering.ucdavis.edu/vougioukas/). 

* Feb 2022: Research Scientist
  * MU-robotix
  * Duties included: Robotic system design, PNC of E-tractor

* July 2022: Researcher (PI)
  * Hangzhou Global Innovation and Technology Center
  * Duties included: Picking automation, Automatic system design in Greenhouse


  
Skills
======
* Proficient in [ROS package development](http://wiki.ros.org/) (C++/Python)
* Optimization based path planning and tracking for mobile robot in the orchard;
  * Application of OBCA for headland manuvering of E-tractor;
  * Kinodynamic model based optimal control of E-tractor;
* Experienced in mathematical modeling of vehicle logistics problems; 
  * Online heuristic discrete optimization;
  * Gurobi solver;
  * CPLEX solver;
* Experienced in RTK-GPS based localization solution;
  * Vehicle Model based state estimation with other sensor data; 
  * Sensor fusion of IMU and Odometry (visual odometry/wheel odometry); 
* Experienced in navigation of mobile robots in the agricultrural field;
  * Software-based Ackerman steering control; 
  * Path planning (Dubins, RRT);
  * Path tracking (Pure-pursuit, MPC);

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

Patent (provisional)
=====================
1. A Crop-Transport robotic aided harvesting vehicle system method and devices.
2. Crop-transport robots and instrumented picking carts acting as harvest-aids during manual harvesting.