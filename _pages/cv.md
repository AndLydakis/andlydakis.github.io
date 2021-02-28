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
* M.Sc. in Computer Engineering, University of Patras, 2015
* M.Sc. in Computer Science, University of New Hampshire, 2018

Work experience
======
* Oct 2018: **Dyson Technology** - Robotics Engineer
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* May 2018 - Oct. 2018: **Innotec UK** - Robotics Engineer
  * Implemented ROS nodes for RS485 & CANOpen communication protocol for motor control
  * Implemented a visual odometry system for differential drive robots
  * Worked on Motion capture system & IMU integration for human activity detection for a lower limb exoskeleton project

* Sept 2015 - May 2018: **University Of New Hampshire** - Research Assistant
  * Research on Human-Robot Interaction, Learning from Demonstration, Assistive Robotics, Decision Making Under Uncertainty, Reinforcement Learning, Robust Optimization
  * Developed machine learning based robotics applications for upper and lower limb rehabilitation, personalized for individual users, that can be used without expert supervision.
  * Integration Experience with multiple types of robotic platforms: Pioneer 3-DX, Turtlebot, Nao, Neobotix MP400, Cyton Gamma-300 arms, custom robotic rovers.

* June 2013 - August 2015: **NCSR Demokritos** - Research Assistant
  * Developed R.O.S.(Robot Operating System) applications in C++ & Python for autonomous and remote controlled robot navigation, robot vision, interfacing with Android devices, and communication with Raspberry Pi and Arduino controlled devices. Worked with simulators such as Gazebo & Stage. Maintained the lab’s Github repository.
  * Project Assistant in IIT’s International Research-Centered Summer School 2013. The project included recognizing and learning human walking patterns through laser scans and depth imaging, distinguishing humans from other obstacles, face detection and recognition and speaker diarization.
  
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
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
