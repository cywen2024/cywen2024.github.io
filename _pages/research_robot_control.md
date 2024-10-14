---
layout: page
permalink: /research_robot_control/
title: Control Algorithms
description: Control algorithms for UAV and UUV.
nav: false
---

# Neural Network MPC for quadrotor (NNMPC)
A dynamic model that considers both linear and complex nonlinear effects extensively benefits the model-based controller development. However, predicting a detailed aerodynamic model with good accuracy for unmanned aerial vehicles (UAVs) is challenging due to their irregular shape and low Reynolds number behavior. This work proposes an approach to model the full translational dynamics of a quadrotor UAV by a feedforward neural network, which is adopted as the prediction model in a model predictive controller (MPC) for precise position control. The raw flight data are collected by tracking various pre-designed trajectories with PX4 autopilot. The neural network model is trained to predict the linear accelerations from the flight log. The neural network-based model predictive controller is then implemented with the automatic control and dynamic optimization toolkit (ACADO) to achieve real-time online optimization. Software in the loop (SITL) simulation and indoor flight experiments are conducted to verify the controller performance. The results indicate that the proposed controller leads to a 40% reduction in the average trajectory tracking error compared to the traditional PID controller.
<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; background: #000;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.youtube.com/embed/KYH02a_53fs?si=IAb4Sbq0zLYQAZO9" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
<p></p>




# UUV Control
This research addresses the trajectory tracking problem of an unmanned underwater vehicle (UUV) within 4 degrees of freedom (DOF) subject to external disturbances and measurement noise. An adaptive control framework consisting of an adaptive model predictive control (MPC) and an error- state extended state observer (ESESO) is proposed. The MPC is utilized to stabilize the system while the ESESO is proposed to estimate both the state and the lump disturbance. In contrast to most conventional ESOs, we explicitly formulate a sensor-fusion problem by tracking the error state of the observer. The ESESO feeds back the filtered state to the MPC to achieve the adaptability of the closed-loop system. The stability analysis in the Lyapunov sense for both ESESO and adaptive MPC is conducted, whose asymptotic stability is shown. Sufficient simulation via a semi-physical experiment is conducted to validate the effectiveness and superiority of the proposed control framework.

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; background: #000;">
  <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://pattylo.github.io/assets/img/eseso_mpc.png" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
