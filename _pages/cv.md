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
* B.S. in Mechanical and Automation Engineering, Hohai University, 2012
* M.S. in Naval and Ocean Engineering, Zhejiang University, 2015
* Ph.D in Mechanical and Aerospace Engineering, University of California, Davis, 2021

Work experience
======
* 2017-2019: Research Assistant
  * University of California, Davis
  * Duties included: Crop-transport robots system in strawberry harvesting
  * Supervisor: [Stavros G. Vougioukas](https://faculty.engineering.ucdavis.edu/vougioukas/)

* 2020-2021: Research Assistant
  * University of California, Davis
  * Duties included: Co-bot for Grapebot harvesting
  * Supervisor: [Stavros G. Vougioukas](https://faculty.engineering.ucdavis.edu/vougioukas/). 

* March 2021: Post-doctoral Scholar
  * University of California, Davis
  * Duties included: IoT system development for data collection in the harvesting scenario
  * Supervisor: [Stavros G. Vougioukas](https://faculty.engineering.ucdavis.edu/vougioukas/). 

* Feb 2022: Research Scientist
  * MU-robotix
  * Duties included: Robotic system design, Planning and Control of E-tractor

* July 2022: Researcher (PI)
  * HIC-ZJU & ZJU
  * Duties included: Research on agricultural robotics

  
Skills
======
* Proficient in [ROS/ROS2 package development](http://wiki.ros.org/) (C++/Python)
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
  
<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

Patent (provisional)
=====================
1. Vougioukas, Stavros, Chen Peng, and Dennis L. Sadowski. "Robotic crop transport." U.S. Patent Application No. 17/752,335.