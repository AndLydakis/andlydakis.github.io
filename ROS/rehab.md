---
title: "Learning Assisted Rehab"
excerpt: "A couple of Learning Based rehabilitation applications, using ROS as the sensor middleware"
collection: portfolio
---

### Lower Limb Wearable for Fall Detection    
ROS node that uses hidden markov models to classify a human's gait phase as swing or stance based on IMU data, 
.foot pressure sensors, infrared and proximity. Based on timeseries data, it evaluates the gait as likely or not to lead to a fall.  
When events that are likely to cause a fall are detected, the system can identify the source of the issue and activate  
the appropriate support component.

[See on Gitbub](https://github.com/AndLydakis/gait_hmm_ros)  

### Upper Limb Personalized Rehabilitation

Using 3 IMUs and EEG sensors worn on the arms of a patient, a physical therapist can demonstrate an exercise and create a 
personalized model for the patient. When practicing the same exercise, the patient can receive a feedback on their performance.  
Using AR, a 3D avatar can demonstrate the exercise for the patient.


[See on Gitbub](https://github.com/AssistiveRoboticsUNH/threespace_ros/tree/master/scripts/canal_surface_test)
