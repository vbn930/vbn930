# Dohun Lee

I'm an M.Sc. Computer Science student at the University of Stuttgart, interested in computer vision and motion estimation. My background is in C++ networking, real-time simulation and Python automation. At Rennteam's Driverless Perception team, I'm currently studying LiDAR motion compensation.

[LinkedIn](https://www.linkedin.com/in/dohun-lee-304971313/) · [Email](mailto:st205052@stud.uni-stuttgart.de)

## Selected projects

### [Realtime-Consistency-Sim](https://github.com/vbn930/Realtime-Consistency-Sim)

**C++ · Unreal Engine 5 · UDP · Python**

A simulation of client-side state reconstruction under latency and packet loss. I implemented snapshot buffering, interpolation and constant-velocity dead reckoning, with CSV telemetry.

The offline Python benchmark compares reconstruction methods over repeated seeds and examines the trade-off between position error and smoothness. Its replay results are separate from the Unreal measurements.

[Benchmark and findings](https://github.com/vbn930/Realtime-Consistency-Sim/tree/master/benchmark) · [Research report](https://github.com/vbn930/Realtime-Consistency-Sim/blob/master/Docs/Research_Report.pdf)

### [SelfDriving-Simulator](https://github.com/vbn930/SelfDriving-Simulator)

**Python · PyTorch · OpenCV · Unity**

A solo learning/reproduction project based on NVIDIA's end-to-end driving paper. I built a modified Dave-2-style CNN that predicts steering and throttle from camera images and vehicle speed, then connected inference to Unity over TCP. Evaluation is simulation-only.

<a href="https://www.youtube.com/watch?v=v07TapYTM1Y"><img src="https://img.youtube.com/vi/v07TapYTM1Y/mqdefault.jpg" width="320" alt="Watch the Unity driving demo for the Dave-2-style PyTorch model"></a>

[Watch the driving demo](https://www.youtube.com/watch?v=v07TapYTM1Y)

### [VisionCursor](https://github.com/vbn930/vision-cursor)

**Python · OpenCV · MediaPipe · PyAutoGUI**

A webcam interface that maps hand landmarks to cursor movement and clicks. I implemented geometric gesture rules and gesture-transition handling, with separate vision and OS-input modules.

### [Discord RPG](https://github.com/Dungeon-RPG-Discord-Game-Server)

**C# · .NET 8 · Azure · Docker**

A solo cloud systems design project with separate Discord interaction and game-state services. It uses authenticated REST communication and Cosmos DB persistence; active player state is held in process-local memory.

[Game-state service](https://github.com/Dungeon-RPG-Discord-Game-Server/game-state-service) · [Discord service](https://github.com/Dungeon-RPG-Discord-Game-Server/discord-message-receiver)

## Tools I use

Python, C++17/20, C# · PyTorch, OpenCV, MediaPipe · Unreal Engine, Unity  
Linux, Git, Docker · TCP/UDP sockets, REST APIs · Pandas, NumPy

## Background

- **Computer Networks I TA, DigiPen** · Sep–Dec 2025. Supported students with C/C++ networking assignments and helped the instructor design and develop assignments.
- **Freelance Python automation** · Mar–Aug 2024. Built product-monitoring and catalog-data tools, including Discord notifications and Excel export.
- **Computer Operations Sergeant, Republic of Korea Air Force** · Nov 2021–Aug 2023. Maintained network equipment and servers; handled security updates on isolated internal networks.

## Education

- **University of Stuttgart** · M.Sc. Computer Science, Oct 2026–present.
- **DigiPen Institute of Technology** · B.S. Computer Science in Real-Time Interactive Simulation, Apr 2026. Cum Laude.
- **Keimyung University** · B.E. DigiPen Game Engineering, Aug 2026. Dual-degree pathway.
