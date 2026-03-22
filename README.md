# Ironing Board Mechanism: Kinematic & Dynamic Analysis 👔⚙️

[![Simulation](https://img.shields.io/badge/Simulation-MATLAB-orange.svg)](https://www.mathworks.com/products/matlab.html)
[![Domain](https://img.shields.io/badge/Domain-Mechanisms_%26_Dynamics-blue.svg)]()
[![Universidad de Sevilla](https://img.shields.io/badge/Academic-Universidad_de_Sevilla-red?style=flat-square&logo=university&logoColor=white)](https://www.us.es/)

A complete kinematic and dynamic analysis of a multi-bar linkage system representing a folding ironing board. 

Developed for the **Mechanisms (Mecanismos)** course during the 3rd year of the Bachelor's Degree in Aerospace Engineering at Universidad de Sevilla (2021-2022).

---

## 🎥 Mechanism Animation

![Ironing Board Motion](media/ironing_board.gif)

---

## 📌 Project Overview

Everyday objects often hide complex mechanical systems. This project breaks down the folding mechanism of an ironing board into a rigorous 2D multi-bar linkage problem. The study encompasses the full mathematical modeling of the system, from basic mobility analysis to the calculation of the required motor torque using advanced energy methods.

### 🎯 Key Objectives & Scope

#### 1. Kinematic Analysis
* **Mobility:** Calculation of the system's Degrees of Freedom (DoF) using Gruebler's equation: $G = 3(N-1) - 2g - h$.
* **Loop Closure:** Formulation of the vector loop equations to map the mechanism's geometry.
* **Singularity Analysis:** Identification of singular configurations (dead centers) within the workspace.
* **Motion Profiles:** Plotting the time evolution of position, velocity, and acceleration for the Center of Gravity (CoG) and angular coordinates of each bar.

#### 2. Dynamic Analysis
* **Newtonian Formulation:** Extraction of internal reaction forces at the joints and calculation of the required driving torque.
* **Lagrangian Formulation:** Validation of the dynamic behavior using the Euler-Lagrange energy approach.
* **Energy Balance:** Graphical evolution of the system's kinetic energy ($T$), potential energy ($V$), and the mechanical work ($W_m$) executed by the motor over a full operational cycle.

## 📂 Repository Contents

* **`docs/`**: Contains the full project report (`Report.pdf`) with the complete mathematical derivations, and the presentation slides.
* **`media/`**: Contains the animated `.gif` showing the mechanism in motion.
* **`src/`** *(Coming soon)*: MATLAB scripts used to solve the kinematic loops, compute the dynamic matrices, and generate the plots and animations.

## 👨‍💻 Authors

* **Irene Mena Ballesteros**
* **Alejandro Rivera Míguez**
* **Pablo Sánchez Mora**
* **Narciso Valverde González**

---

Professor: **Joaquin Ojeda Granja**  
Bachelor in Aerospace Engineering | Universidad de Sevilla

---
*Disclaimer: This is an academic project. The code and models provided are intended for educational demonstration of mechanical linkage analysis.*
