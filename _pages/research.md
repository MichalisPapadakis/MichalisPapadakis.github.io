---
title: "Research & Work"
layout: splash
classes: wide

intro:
  - title: "Research Interests"
    excerpt: >
      "My research interests lie at the intersection of <b>dynamics</b>, <b>control theory</b>, 
      and <b>optimization</b>, aiming to answer the following question: How can we enable robots 
      to move and perform dynamic tasks in their environment efficiently, safely, and robustly? 
      Specifically, I am interested in <b>optimal</b>, <b>nonlinear control</b> and <b>learning-based 
      techniques</b>, focusing on informed formulations that capture essential dynamics and leverage 
      system properties while remaining mathematically well-conditioned for tractability in 
      <b>real-world applications</b>."

#################################################### 
# This style is good to have research themes grouped
# TODO: add feature projects
#################################################### 

# feature_row_1:
#   - image_path: ../assets/images/safety_gait_tiles.png
#     url : "/_pages/research_projects/machine_learning_control/"
#     btn_label: "Machine Learning for Nonlinear Control"
#     btn_class: btn btn--default btn--large
#   - image_path: ../assets/images/hardware_trot_on_stones_wide_compressed.png
#     url : "/_pages/research_projects/model_predictive_control/"
#     btn_label: "Model Predictive Nonlinear Control"
#     btn_class: btn btn--default btn--large
#   - image_path: ../assets/images/sampled_data_clf_controller_profiles.png
#     url : "/_pages/research_projects/discrete_event_control/"
#     btn_label: "Discrete-Event Control"
#     btn_class: btn btn--default btn--large

# {% include feature_row id="feature_row_1" %}


feature_row_1:
  - image_path: /assets/images/ThesisThumbnail.png
    title: "Modeling and In-flight Torso Attitude Stabilization of a Jumping Quadruped"
    excerpt: >
      <b>M. Papadakis</b>, J. A. Olsen, I. Poulakakis, and K. Alexis, "Modeling and In-flight Torso Attitude Stabilization
      of a Jumping Quadruped", in <i> International Symposium of Robotics Research </i>, Long Beach, California, USA, 2024 
      <br> <br> 
      <b>Abstract:</b> This paper addresses the modeling and attitude control of jumping quadrupeds in low-gravity environments. First, a convex decomposition procedure is presented to generate high-accuracy and low-cost collision geometries for quadrupeds performing agile maneuvers. A hierarchical control architecture is then investigated, separating torso orientation tracking from the generation of suitable, collision-free, corresponding leg motions. Nonlinear Model Predictive Controllers (NMPCs) are utilized in both layers of the controller. To compute the necessary leg motions, a torque allocation strategy is employed that leverages the symmetries of the system to avoid self-collisions and simplify the respective NMPC. To plan periodic trajectories online, a Finite State Machine (FSM)-based weight switching strategy is also used. The proposed controller is first evaluated in simulation, where 90 degree rotations in roll, pitch, and yaw are stabilized in 6.3, 2.4, and 5.5 seconds, respectively. The performance of the controller is further experimentally demonstrated by stabilizing constant and changing orientation references. Overall, this work provides a framework for the development of advanced model-based attitude controllers for jumping legged systems. 
      <br> <br>
      <b>Tools</b>: ROS1, Drake, Acados, Matlab, C++, Python, URDF
    url: "assets/paper_materials/olympus_mpc2024/OlympusMPC.pdf"
    btn_label: "Paper"
    url2: "https://www.youtube.com/watch?v=term0jZLbjM"
    btn_label2: "Video"
    url3: "https://michalispapadakis.github.io/mpc_olympus/"
    btn_label3: "Publication Site"

feature_row_2:
  - image_path: /assets/images/IKH_user.jpg
    title: "Robotic Welding"
    excerpt: >
      As a junior robotics engineer at [iKnowHow](https://www.iknowhow.com/), I worked on an robotic welding platform designed for low volume welds without manual programming or CAD file input. The system utilizes a 3D scanner, a seam tracker and a VR headset and interfaces with a common welding machine. 
      <br>
      I improved the existing pipeline (e.g. cleaner mesh reconstruction using [Open3D](https://www.open3d.org/), added telemetry using [DataTamer](https://github.com/PickNikRobotics/data_tamer), sped up and increased the robustness of the toolchanging process, various enhancements and bugfixes for the seam tracker driver), integrated new components (ros2 modbus driver) and improved the welding pipeline by implementing a servoing controller using [moveit servo](https://moveit.picknik.ai/humble/doc/examples/realtime_servo/realtime_servo_tutorial.html). I also assisted in the development and integration of the VR UI and the deployment of a voice-based interface by creating a public REST server. Finally, to validate system performance and meet project related KPIs, I carried out several integration tests and experiments, and I showcased the platform at various events.
      <br> <br>
      <b>Tools</b>: ROS2, MoveIt, ros2_control, C++, REST, Unity (for VR)
    url: "https://voxreality.eu/welde/"
    btn_label: "Project Site"
    url2: "https://www.linkedin.com/showcase/weld-e"
    btn_label2: "Project Updates"
    url3: "https://www.linkedin.com/posts/weld-e_introducing-weld-e-activity-7356624634294714368-w7XE"
    btn_label3: "Project Video"
---

{% include feature_row id="intro" type="center" %}


{% include feature_row id = "feature_row_1" type = "left" %}
{% include feature_row id = "feature_row_2" type = "left" %}


<h1 align = "center"> Publications </h1>

<h2 align = "center"> Conference Papers </h2>

<p>
<b>M. Papadakis</b>, J. A. Olsen, I. Poulakakis, and K. Alexis, "Modeling and In-flight Torso Attitude Stabilization
of a Jumping Quadruped", in <i> International Symposium of Robotics Research </i>, Long Beach, California, USA, 2024
&nbsp;|&nbsp;
<a href="https://michalispapadakis.github.io/mpc_olympus/" target="_blank">Site</a>
&nbsp;|&nbsp;
<a href="https://www.youtube.com/watch?v=term0jZLbjM" target="_blank">Video</a>
&nbsp;|&nbsp;
<a href="https://arxiv.org/abs/2409.14567" target="_blank">Paper</a>
</p>




