# Inverse Jacobian Kinematics with CoppeliaSim Simulation  
*Modern Robotics – Course 2: Robot Kinematics (Coursera Project)*

## 📌 Overview
This project implements inverse Jacobian-based kinematics for a 6-DOF robotic manipulator, inspired by **Course 2: Robot Kinematics** from the **Modern Robotics Specialization by Northwestern University** on Coursera. The simulation is visualized using **CoppeliaSim**, integrating theoretical calculations with practical robotic motion.

## 🛠️ Tools & Technologies
- Python 3  
- [Modern Robotics Library (Python)](https://github.com/NxRLab/ModernRobotics)  
- CoppeliaSim (V-REP)  
- NumPy  
- Matplotlib (for visualizing convergence if applicable)

## 📚 Project Highlights
- Computed the **Jacobian matrix** for a spatial 6R manipulator.
- Implemented **Inverse Jacobian** method using iterative Newton-Raphson for inverse kinematics.
- Verified results using simulation in **CoppeliaSim**, with a robot model that tracks end-effector targets in space.
- Plotted convergence graphs to analyze performance of the IK algorithm.

## 🎯 Key Features
- Custom `IKinBodyIterates` function to show each Newton-Raphson iteration.
- Transformation matrix comparisons: `T_sd` (desired) vs. `T_sb` (achieved).
- Integration with CoppeliaSim via remote API or movement script.

## 🧠 Learning Outcomes
- Practical understanding of forward/inverse kinematics.
- Working knowledge of screw axis representations and spatial velocity.
- Real-world application of Jacobian pseudo-inverse in IK control.
- Simulation workflow using CoppeliaSim for robotics validation.

## ⚠️ Disclaimer
This is **my personal submission** and **does not include any official Coursera solutions or proprietary content**. It is shared to showcase my learning experience and for educational purposes only, in accordance with Coursera’s Honor Code.


## 📬 Contact
For questions or collaboration:  
**Homayra Mobesshira Hemu** – homayrahemu186@gmail.com  
GitHub: Homayra Mobesshira Hemu(https://github.com/44981)
