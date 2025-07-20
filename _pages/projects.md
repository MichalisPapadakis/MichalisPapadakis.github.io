---
title: "Research & Work"
layout: splash
classes: wide


feature_row_1:
  - image_path: /assets/images/Task2.png
    title: "Simulation Frameworks for prototype robotic leg"
    excerpt: >
      The purpose of this project was to develop two simulation frameworks for a robotic leg: one in ROS with Gazebo and one in Simscape. I modeled the leg in SolidWorks, created its URDF, and set up the complete ROS-based framework. I carried out the full kinematic (FK, IK, differential kinematics) and dynamic analysis, and modeled the contact forces. To validate the frameworks, I created a generic program to derive Euler-Lagrange equations for multibody systems and built an analytical dynamic model of the leg. Both frameworks were tested on static and dynamic control tasks. This project was my first ROS-based project.
    url: "assets/project_pdfs/LegSimulationFrameworks.pdf"
    btn_label: "Report"

feature_row_2:
  - image_path: /assets/images/ComputationalProject.png
    title: "Planning and control of double integrator in uneven terrain using Potential Fields"
    excerpt: >
      The scope of this computation project was the motion planning of a two-dimensional double intergrator which moves under the influence of a conservative field, and specifically the gravitational potential field. The first part of the project included the creation of navigation functions in simple circular spaces. The next step was the modelling of the relevant dynamics, using different techniques. Having modelled the external dynamics, a controller was designed, using Artificial Harmonic Potential Fields (AHPF) in order to drive the system to the desired destination. The final part of the project included the investigation of the controller cost.
    url: "assets/project_pdfs/Computational_Project_Papadakis.pdf"
    btn_label: "Report (greek)"

feature_row_3:
  - image_path: /assets/images/IntelligentManufacturing.png
    title: "Intelligent Manufacturing"
    excerpt: >
      These projects, part of the Intelligent Manufacturing course,  focus on optimizing and automating aspects of advanced manufacturing. The first project developed and optimized neural networks to predict surface roughness and mechanical properties (strength and strain) of 3D-printed parts using Python’s scikit-learn. The second project built on this by using evolutionary algorithms (PyGAD) to find optimal 3D printing parameters that minimize roughness and maximize strength, analyzing simultaneously the impact of different hyperparameters. The third project created an application for automatic defect detection and classification in hot-rolled parts. It used morphological analysis and image processing (MATLAB toolbox) to enhance images and extract relevant features, which were then used to train a neural network classifier in Python. Together, these projects show how AI and optimization can be used in the manufacturing sector.
    url: "assets/project_pdfs/ManufacturingNN.pdf"
    btn_label: "Report 1 (greek)"
    url2: "assets/project_pdfs/ManufacturingGA.pdf"
    btn_label2: "Report 2 (greek)"
    url3: "assets/project_pdfs/ManufacturingCV.pdf"
    btn_label3: "Report 3 (greek)"

feature_row_4:
  - image_path: /assets/images/Grad.jpg
    title: "Gradient Based Optimization"
    excerpt: >
      In this project for the Optimization Methods course, I explored different techniques for computing derivatives for gradient-based optimization. The first part focused on an inverse design problem for the boundary layer height over a flat plate in incompressible flow. The objective was to adjust the fluid’s viscosity and edge velocity so the boundary layer height matches a desired distribution. I implemented and compared direct differentiation and both continuous and discrete adjoint methods for this task. In the second part, I tested complex differentiation and automatic differentiation on a simpler problem to study their implementation and accuracy.
    url: "assets/project_pdfs/Optimization_Grad.pdf"
    btn_label: "Report (greek)"

feature_row_5:
  - image_path: /assets/images/TransprtationSystems.png
    title: "Automatic truck loading system"
    excerpt: >
      This group project, part of the Transport and Lifting Machines course, involved designing an automatic truck loading system for marble dust at a quarry. I was responsible for the capacity sizing of the entire installation to ensure it met operational specifications. I designed the initial discharge hopper, built to handle impact loads from unloading trucks. My main focus was the detailed design of the storage silo, modeled in SolidWorks using sheet metal parts. I performed FEA static analysis to test its strength and applied iterative improvements, adding reinforcements based on simulation results to ensure sufficient structural strength under full load.
    url: "assets/project_pdfs/Transportation&LiftingSystems.pdf"
    btn_label: "Report (greek)"

feature_row_6:
  - image_path: /assets/images/DRM3.jpg
    title: "Dynamic Analysis of Rotating Shaft"
    excerpt: >
      In this project for the Dynamics of Rotating Machines course, I analyzed a rotating shaft using the finite element method. First, I studied its steady-state response under different operating conditions, accounting for the nonlinear behavior of hydrodynamic bearings. Then, I examined its transient response to observe how the nonlinear bearings affect its dynamic behavior. I ensured a high-quality elements for accurate results and extracted key operating characteristics through numerical analysis.
    url: "assets/project_pdfs/DRM_HM3.pdf"
    btn_label: "Report 1 (greek)"
    url2: "assets/project_pdfs/DRM_HM4.pdf"
    btn_label2: "Report 2 (greek)"
---
<br>
<h1 align = "center"> University Projects </h1>


<h2 align = "center"> Mechanical Engineering Projects </h2>

<!-- Below, the major project of my undergraduate studies are presented.

--- -->

{% include feature_row id = "feature_row_1" type = "left" %}
{% include feature_row id = "feature_row_2" type = "left" %}
{% include feature_row id = "feature_row_3" type = "left" %}
{% include feature_row id = "feature_row_4" type = "left" %}
{% include feature_row id = "feature_row_5" type = "left" %}
{% include feature_row id = "feature_row_6" type = "left" %}
