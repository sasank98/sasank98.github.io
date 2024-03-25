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
* Masters in Robotics and Automation, Northeastern University, May 2024 (expected)
* Bachelors in Mechanical Engineering, Manipal Academy of Higher Education, July 2020

Work experience
======
* __Computer Vision Teaching Assistant, Khoury College of Computer Science__
    * Conducted Weekly office hours to help with doubts and errors in C++ code or in Projects
    * Graded assignments, projects and exams, provided feedback to students to improve their understanding
* __Autonomy Systems and Machine Learning Co-op, Danfoss Autonomy__
    * Adapted LIO-SAM for a 6-axis IMU using additional GPS and conducted system testing to identify off-road failure modes
    * Performed system integration and testing along with FMEAs on third party SLAM companies for our specific off-road applications
    * Developed C++ code to provide ethernet communication between a SLAM controller and Danfoss controller
    * Implemented an additional decoder on unimatch network to parallelly compute Optic Flow, Stereo Disparity, and 3D detection
    * Achieved a 9.87 AP3D on Object detection task without fine-tuning the encoder of the unimatch network
    * Performed 3D-object detection using YOLO-v8 and DBSCAN on the colored pointcloud generated from LiDAR camera fusion
    * Leveraged synthetic data from Nvidia-IsaacSim to train YOLO-v8, achieved 0.45 mAP for real-world forklift detection
    * Pruned YOLO-v7 model to make it lighter and deployed on Adlink camera to detect Fruits, Trees and People in a farm

* __Research Assistant, Manipal Academy of Higher Education__
  * Added additional Pressure sensor to existing test-rig and acquired dynamic pressure and position readings using Matlab
  * Used the Data acquisition system to acquire the dynamics and stability of a water-lubricated hydrodynamic bearing
  * Created a 3D dynamic CFD model in Ansys and optimized it for stability using the collected bearing data

* __Structural Design and Manufacturing Engineer, Formula Manipal__
  * Performed dynamic simulation of a racecar on track in Matlab and used the data to design Suspension-links and Rims of the car
  * 3D-printed and added composite reinforcement to Intake-Manifold, achieving 50%+ weight reduction compared to prior versions
  * Designed and manufactured Carbon-fiber Seat, and Aero-package and won second place for design in Formula Bharat 2019
  
Skills
======
* Programming
  * C++, ROS, MATLAB, Python, Linux, LaTeX, 
* Robotics
  * Computer vision, Probabilistic Robotics, SLAM, Robot Perception, Reinforcement Learning, Motion Planning, Control Theory, CAD
* Libraries
  * Eigen, GTSAM, PCL (Point Cloud Library), OpenCV

Achievements
======

  * Secured 3rd place in FSAE Bharat 2019 and 2nd place in the design event of the competition
  * Appeared for GATE-2021 and secured an All India Rank of 523 out of 120594 students in Mechanical engineering
  
<!-- Talks
======

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> 
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
* Currently signed in to 43 different slack teams -->
