---
title: "Research & Work"
layout: splash
classes: wide


feature_row_1:
  - image_path: /assets/images/Experimental.png
    title: "Paper1"
    excerpt: >
      <b>M. Papadakis</b>, J. A. Olsen, I. Poulakakis, and K. Alexis, "Modeling and In-flight Torso Attitude Stabilization
      of a Jumping Quadruped", in <i> International Symposium of Robotics Research </i>, Long Beach, California, USA, 2024 
      <br> <br> 
      <b>Abstract:</b> This paper addresses the modeling and attitude control of jumping quadrupeds in low-gravity environments. First, a convex decomposition procedure is presented to generate high-accuracy and low-cost collision geometries for quadrupeds performing agile maneuvers. A hierarchical control architecture is then investigated, separating torso orientation tracking from the generation of suitable, collision-free, corresponding leg motions. Nonlinear Model Predictive Controllers (NMPCs) are utilized in both layers of the controller. To compute the necessary leg motions, a torque allocation strategy is employed that leverages the symmetries of the system to avoid self-collisions and simplify the respective NMPC. To plan periodic trajectories online, a Finite State Machine (FSM)-based weight switching strategy is also used. The proposed controller is first evaluated in simulation, where 90 degree rotations in roll, pitch, and yaw are stabilized in 6.3, 2.4, and 5.5 seconds, respectively. The performance of the controller is further experimentally demonstrated by stabilizing constant and changing orientation references. Overall, this work provides a framework for the development of advanced model-based attitude controllers for jumping legged systems. 
    url: "https://arxiv.org/pdf/2409.14567"
    btn_label: "Paper"
    url2: "https://www.youtube.com/watch?v=term0jZLbjM"
    btn_label2: "Video"
    url3: "https://michalispapadakis.github.io/mpc_olympus/"
    btn_label3: "Publication Site"

---
<h1 align = "center"> University Projects </h1>


<h2 align = "center"> Mechanical Engineering Projects </h2>


{% include feature_row id = "feature_row_1" type = "left" %}
