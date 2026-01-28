# *Dynamic-Based Modelling of Surface and Volumetric Objects*

## Project Aim
To develop a **prototype application** for the **real-time modelling of membranes and elastic solids**
under applied forces.


## Overview
This project implements a physics‑informed C++ simulation of dynamic B‑spline surfaces
and deformable solids, enabling parameter‑driven, time‑dependent analysis of structural response under applied forces. </br>

The dynamics of the membranes are formulated using **Lagrangian mechanics**, where the
equations of motion are expressed in terms of B-spline control points. This formulation
leads to a system of **partial differential equations (PDEs)**, which is solved numerically
using the **finite difference method (FDM)**. 
The solver is implemented in **C++**, built upon an existing numerical computation library.

## Key Features
- Dynamic B-spline surface modelling
- Lagrange-based formulation of membrane dynamics
- Numerical Partial Differential Equation solver via Finite Difference Method
- Parameter-driven simulation (density, damping, tension)
- Time-dependent membrane deformation
- C++ implementation with numerical libraries

## Technical Keywords
- B-Spline Curves & Surfaces  
- Lagrangian Dynamics  
- Partial Differential Equations (PDEs)  
- Finite Difference Method (FDM)  
- C++

## Results – Case Studies
<p float="left">
  <img src="case-study-result/image1 - Membrane at Initial Condition.png" width="240" />
  <img src="case-study-result/image2 - Membrane after 1 second.png" width="240" />
  <img src="case-study-result/image3 - Membrane after 5 seconds.png" width="240" />
  <img src="case-study-result/image4 - Membrane after 10 seconds.png" width="240" />
</p>
<p float="left">
  <img src="case-study-result/image5 - Membrane after 15 seconds.png" width="240" />
  <img src="case-study-result/image6 - Membrane after 20 seconds.png" width="240" />
  <img src="case-study-result/image7 - Membrane after 25 seconds.png" width="240" />
</p>
<p float="left">
  <img src="case-study-result/image8 - Membrane after 30 seconds.png" width="240" />
  <img src="case-study-result/image9 - Membrane after 35 seconds.png" width="240" />
  <img src="case-study-result/image10 - Membrane after 40 seconds.png" width="240" />
  <img src="case-study-result/image11 - Membrane after 45 seconds.png" width="240" />
</p>
<p float="left">
  <img src="case-study-result/image12 - Membrane after 50 seconds.png" width="240" />
  <img src="case-study-result/image13 - Membrane after 55 seconds.png" width="240" />
  <img src="case-study-result/image14 - Membrane after 59 seconds.png" width="240" />
</p>













