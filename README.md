# Morphology Intelligent of Modular Reconfigurable Robot
### Designed a hierarchical end-to-end planning approach for modular robots to achieve coordinated reconfiguration of multiple modules
An end-to-end hierarchical planning approach for modular reconfigurable robots is proposed, enabling multi-module coordinated reconfiguration. In the upper-level planning, the Kuhn-Munkres algorithm and the Hungarian algorithm are employed to determine the positions of each moving module in both the initial and target configurations. The lower-level planning utilizes the dynamic A* algorithm to achieve collision-free path planning for the moving modules, allowing them to evade both friendly robotic modules and other spatial obstacles during movement. Compared to conventional path planning algorithms for modular robot reconfiguration, this approach enable all moving modules to move simultaneously and perform the waiting action. The approach significantly enhances the reconfiguration efficiency and reduces the energy consumption. The simulation visualization of self-reconstruction process is ultimately achieved through the establishment of communication between Python and Unity.

### Schematic diagram of the research content
<div align=center>
<img src="https://private-user-images.githubusercontent.com/59788826/382977264-73f547fa-9f92-4df7-b363-49b70361dd51.jpg"></img>
</div>

### Simulation results
<div align=center>
<video src="https://private-user-images.githubusercontent.com/59788826/380374140-76426007-4dc4-4f2e-a7b6-6b568c6396c0.mp4"></video>
</div>

