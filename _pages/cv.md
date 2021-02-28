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
* M.Sc. in Computer Engineering, University of Patras, 2012
* M.Sc. in Computer Science, University of New Hampshire, 2014

Work experience
======
* Oct 2018: 
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* May 2018 - Oct. 2018: Robotics Engineer
  * InnotecUK
  * Implemented ROS nodes for RS485 & CANOpen communication protocol for motor control
  * Implemented a visual odometry system for differential drive robots
  * Worked on Motion capture system & IMU integration for human activity detection for a lower limb exoskeleton project
  
Skills
======
* Robotics / Simulation
  * ROS
  * Gazebo, VREP, Unity
  * NVIDIA Isaac
* Extensive Experience
  * C++
  * Python (scikit, pandas, numpy)
  * R
* Deep Learning
  * Keras, PyTorch
* CI/CD
  * Git, Docker, K8s, familiar with Jenkins, TravisCI, AWS, Google Cloud
* Working Knowledge
  * C, Java, SQL, JavaScript
* Web
  * Node, React, Django, PostgreSQL, familiar with Redis
* Exposure To:
  * Scala, Kotlin, Perl


Publications
======
  <ul>{% for post in site.publications reversed %}
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
  
