---
layout: page
permalink: /research_robot_planning/
title: UAV Path Planning Algorithms
description: Path planning algorithms for autonomous path planning.
nav: false
---

# Velocity Planner
A demo of the velocity planner related to our paper "Real-time Identification and Avoidance of Simultaneous Static and Dynamic Obstacles on Point Cloud for UAVs Navigation", accepted in Robotics and Autonomous Systems [J]. The algorithm is not exactly the same as that in the paper. We generate the trajectory segments in close-form and assemble the segments into a complete trajectory to the local goal. Both the computing time and flight smoothness are improved. Also, when the velocity candidates generated from the "forbidden pyramids" are all found infeasible, we try some random velocities instead of reducing the number of obstacles to be considered.

<div style="display: flex; justify-content: center; align-items: center; background: transparent;">
  <div style="position: relative; width: 640px; height: 380px; overflow: hidden;">
    <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="../assets/video/plan_demo_fake.gif" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
<div style="text-align: center; margin-top: 10px;">
  Figure 1. Simulation Path Planning
</div>
<p></p>


# Dyanmic Object Tracking Path Planning

Object tracking and motion estimation in 3D space:
Traditional object tracking and classifcation by dynamic or static by velocity, often leads to wrong due to the error in velocity estimation:
In this work, we propose a universal framework for object detecting, tracking, and motion estimating based on PIV method.

<div style="display: flex; justify-content: center; align-items: center; background: transparent;">
  <div style="position: relative; width: 640px; height: 380px; overflow: hidden;">
    <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="../assets/video/tracking_3d_noyolo.gif" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
<div style="text-align: center; margin-top: 10px;">
  Figure 2. Dyanmic Object Tracking Path Planning
</div>
<p></p>
