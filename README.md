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
<table>
    <tr>
      <td align="center">
        <img src="case-study-result/img1-Membrane-at-Initial-Condition.png" width="260"><br>
        <b>Membrane at Initial Condition</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
      <td align="center">
        <img src="case-study-result/img1-Membrane-after-1-second.png" width="260"><br>
        <b>Membrane after 1 second</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
      <td align="center">
        <img src="case-study-result/img1-Membrane-after-5-seconds.png" width="260"><br>
        <b>Membrane after 5 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
    </tr>
    
    <tr>
      <td align="center">
        <img src="case-study-result/img1-Membrane-after-10-seconds.png" width="260"><br>
        <b>Membrane after 10 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
      <td align="center">
        <img src="case-study-result/Membrane after 15 seconds.png" width="260"><br>
        <b>Membrane after 15 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
      <td align="center">
        <img src="case-study-result/Membrane after 20 seconds.png" width="260"><br>
        <b>Membrane after 20 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
    </tr>

    <tr>
      <td align="center">
        <img src="case-study-result/Membrane after 25 seconds.png" width="260"><br>
        <b>Membrane after 25 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
      <td align="center">
        <img src="case-study-result/Membrane after 30 seconds.png" width="260"><br>
        <b>Membrane after 30 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
      <td align="center">
        <img src="case-study-result/Membrane after 35 seconds.png" width="260"><br>
        <b>Membrane after 35 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
    </tr>
    
    <tr>
      <td align="center">
        <img src="case-study-result/Membrane after 40 seconds.png" width="260"><br>
        <b>Membrane after 40 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
      <td align="center">
        <img src="case-study-result/Membrane after 45 seconds.png" width="260"><br>
        <b>Membrane after 45 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
      <td align="center">
        <img src="case-study-result/Membrane after 50 seconds.png" width="260"><br>
        <b>Membrane after 50 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
    </tr>
    
    <tr>
      <td align="center">
        <img src="case-study-result/Membrane after 55 seconds.png" width="260"><br>
        <b>Membrane after 55 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
      <td align="center">
        <img src="case-study-result/Membrane after 59 seconds.png" width="260"><br>
        <b>Membrane after 59 seconds</b><br>
        <sub>Short description of what the figure shows.</sub>
      </td>
    </tr>
</table>













