# Simulation video under the proposed end-to-end hierarchical planning approach for modular reconfigurable robots
### Introduction
An end-to-end hierarchical planning approach for modular reconfigurable robots is proposed, enabling multi-module coordinated reconfiguration. In the upper-level planning, the Kuhn-Munkres algorithm and the Hungarian algorithm are employed to determine the positions of each moving module in both the initial and target configurations. The lower-level planning utilizes the dynamic A* algorithm to achieve collision-free path planning for the moving modules, allowing them to evade both friendly robotic modules and other spatial obstacles during movement. Compared to conventional path planning algorithms for modular robot reconfiguration, this approach enable all moving modules to move simultaneously and perform the waiting action. The approach significantly enhances the reconfiguration efficiency and reduces the energy consumption.
### Experimental results
<div align=center>
<video src="https://github.com/wenweiluo/MI-MRR/reconfiguration.mp4"></video>
</div>
