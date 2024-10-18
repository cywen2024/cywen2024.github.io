---
layout: page
permalink: /research_fluid_highSpeedFlow/
title: High Speed Flow
description: High speed flow research.
nav: false
---

The space-time conservation element and solution element (CE/SE) method is a unique computational fluid dynamics (CFD) algorithm. It differs substantially in both concept and methodology from conventional method. The space and time are treated unified and the discrete scheme is derived from the original space-time integral form of the governing conservation laws. It can be proved that the discrete scheme satisfies both local and global flux conservations in space and time. Our group has implemented CE/SE method on general hybrid meshes (consisting of both triangular and quadrilateral elements) and extended it to high-order versions including third and fourth order. In our recent efforts, a family of upwind CE/SE schemes is also developed to further improve its accuracy and robustness. We also apply our in-house CE/SE in the research of: (1) hypersonic non-equilibrium flows; (2) detonation waves; and (3) two-phase compressible flows.

<div style="display: flex; justify-content: center; align-items: center; background: transparent;">
  <div style="position: relative; width: 550px; height: 200px; overflow: hidden;">
    <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="../assets/img/highSpeedFlow/hypervelocity_sphere.png" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
<div style="text-align: center; margin-top: 10px;">
  Figure 1.  Hypervelocity non-equilibrium flows over spheres 
</div>

<p></p>
<div style="display: flex; justify-content: center; align-items: center; background: transparent;">
  <div style="position: relative; width: 330px; height: 180px; overflow: hidden;">
    <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.polyu.edu.hk/researchgrp/cywen/images/HighSpeedFlow/tmp77EB-large.png" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
<div style="text-align: center; margin-top: 10px;">
  Figure 2.  3D detonation propagation in a rectangular duct 
</div>

<p></p>


<div style="display: flex; justify-content: center; align-items: center; background: transparent;">
  <div style="position: relative; width: 595px; height: 391px; overflow: hidden;">
    <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="https://www.polyu.edu.hk/researchgrp/cywen/images/HighSpeedFlow/GIF1-underwater_explosion.gif" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
<div style="text-align: center; margin-top: 10px;">
  Figure 3. Underwater explosion
</div>

<p></p>

The disagreement between numerical simulated detonation cell size (Figure 1.) and the experimental measured data has been recognized a long-lasting problem under resolved. In present study, our group developed an averaged temperature model in order to involve the impact of vibrational non-equilibrium on the prediction of detonation cell size. This distinct conception preliminarily succeeds in narrowing the disparity between numerical results and experimental observation (Figure 2.). Compared to the measured cell size provided in literature, the disparity in cell width has been greatly narrowed down to a factor of 1.3.

<div style="display: flex; justify-content: center; align-items: center; background: transparent;">
  <div style="position: relative; width: 550px; height: 520px; overflow: hidden;">
    <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="../assets/img/highSpeedFlow/stoichiometric.jpg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
<div style="text-align: center; margin-top: 10px;">
  Figure 4. (a) Pressure, (b) temperature, (c) OH field and  (d) numerical soot foil for detonation (stoichiometric H2-O2 diluted with 70% Ar,initial pressure of 0.4 atm, temperature of 300 K)
</div>

<div style="display: flex; justify-content: center; align-items: center; background: transparent;">
  <div style="position: relative; width: 550px; height: 500px; overflow: hidden;">
    <iframe style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" src="../assets/img/highSpeedFlow/stoichiometric2.jpg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</div>
<div style="text-align: center; margin-top: 10px;">
  Figure 5. (a) Vibrational equilibrium (b) Vibrational non-equilibrium and (c) Two temperature model (stoichiometric H2-O2 diluted with 70% Ar, initial pressure of 0.4 atm, temperature of 300 K)
</div>