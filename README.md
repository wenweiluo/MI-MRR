# Morphology Intelligent of Modular Reconfigurable Robot
### Proposed an inner-outer loop optimization (IOLO) framework for modular robots in pursuit-evasion tasks for first time (Ready for submission)
Proposed an inner-outer loop optimization framework for modular robots in pursuit-evasion task for the first time. In the outer evolutionary loop, **elite genetic (EG) algorithm** is applied to evolve the morphology and a robot assessment rule is design to evaluate the optimality of both the morphology and controller in the pursuit-evasion task. In the inner reinforcement learning loop, **PPO algorithm** is applied to learn optimal control strategy for pursuit-evasion task. By utilizing **JAX**, the framework enables **parallel computation on GPUs** to simultaneously optimize the morphology and the controller of the modular robot, **ultimately resulting in an approximately optimal morphology and corresponding controller for the pursuit-evasion task**.  

### The framework of the IOLO algorithm
<div align=center>
<img src="https://private-user-images.githubusercontent.com/59788826/382986082-2e24fec8-21a1-4133-9b3b-12dfd2446ed2.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzM3MzA5NzYsIm5iZiI6MTczMzczMDY3NiwicGF0aCI6Ii81OTc4ODgyNi8zODI5ODYwODItMmUyNGZlYzgtMjFhMS00MTMzLTliM2ItMTJkZmQyNDQ2ZWQyLmpwZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMDklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjA5VDA3NTExNlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTMyMWMzODliOTY1ZGE4MTcyNTg2YzVkMjI3NjFhZWRkZDExZmQ3NjRhNjhkYTI3YTU4NTBkODYxYzUzOTA3OWEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.qbUFOx9FvRaJlJSpesX9M4nSH032d6g1wOZ8xgJW4Iw" width=40%></img>
</div>

### Designed a hierarchical end-to-end planning approach for modular robots to achieve coordinated reconfiguration of multiple modules
Proposed an end-to-end hierarchical planning approach for modular reconfigurable robots, enabling multi-module coordinated reconfiguration. In the higher-level planning, the Kuhn-Munkres algorithm and the Hungarian algorithm are employed to determine the positions of each moving module in both the initial and target configurations. The lower-level planning **utilizes the dynamic A*** **algorithm to achieve collision-free path planning for the moving modules**, allowing them to evade both other robotic modules and spatial obstacles during movement. Compared to conventional path planning algorithms for modular robot reconfiguration, this approach enable all moving modules to move simultaneously and perform the waiting action. The approach significantly enhances the reconfiguration efficiency and reduces the energy consumption. The simulation visualization of self-reconstruction process is ultimately achieved through the establishment of communication between **Python** and **Unity**.

### Schematic diagram of the research content for the hierarchical end-to-end planning approach
<div align=center>
<img src="https://private-user-images.githubusercontent.com/59788826/382977264-73f547fa-9f92-4df7-b363-49b70361dd51.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzM3MzEwNjYsIm5iZiI6MTczMzczMDc2NiwicGF0aCI6Ii81OTc4ODgyNi8zODI5NzcyNjQtNzNmNTQ3ZmEtOWY5Mi00ZGY3LWIzNjMtNDliNzAzNjFkZDUxLmpwZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMDklMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjA5VDA3NTI0NlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTM1YWE3OWIyZDdhODA3M2M3OTAwNmNjMzY1NmVhNzBhZDhlZWE0MDE5ZDc0MzRlYjdmMWE0NDU2OGYyZGY5ZjAmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.yk8EEejeic3ggEHpMJhdgVXReIfF7jGCyKoIIUGw_C8" width=60%></img>
</div>


### Simulation result under the hierarchical end-to-end planning approach
<div align=center>
<video src="https://private-user-images.githubusercontent.com/59788826/380374140-76426007-4dc4-4f2e-a7b6-6b568c6396c0.mp4"></video>
</div>
