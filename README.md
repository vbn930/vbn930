# Hi, I'm Dohun Lee 👋

### Software Engineer | C++ · Python · Real-Time Systems · Simulation · Robotics & AI

I am an incoming **M.Sc. Computer Science student at the University of Stuttgart**, with a B.S. in **Computer Science in Real-Time Interactive Simulation** from **DigiPen Institute of Technology**.

My background is primarily in **C++, real-time systems, networking, simulation, and graphics**, with additional hands-on experience in **Python automation, computer vision, and machine learning**.

I am currently interested in applying this systems background to:

- Robotics & Autonomous Systems
- Robot Perception
- Computer Vision
- Simulation & Digital Twins
- Real-Time / Distributed Systems

---

## 🛠 Tech Stack

### Languages

![C++](https://img.shields.io/badge/C++17%2F20-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)

### Systems & Software

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

`TCP/IP` · `UDP` · `Socket Programming` · `REST APIs` · `Distributed Systems`

### Simulation & Graphics

![Unreal Engine](https://img.shields.io/badge/Unreal_Engine-313131?style=flat-square&logo=unrealengine&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)

`Real-Time Simulation` · `Physics` · `Computer Graphics` · `GLSL`

### AI & Computer Vision

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

`CNNs` · `Computer Vision` · `MediaPipe` · `Pandas` · `NumPy`

---

# 🚀 Featured Projects

## Realtime-Consistency-Sim
### Networked Mobile-Robot State Estimation

**C++17 · Unreal Engine 5 · UDP Networking · Python · Pandas**

A real-time networked simulation for studying mobile-robot state consistency under degraded network conditions.

- Built a **server-authoritative simulation** using a custom UDP networking layer.
- Implemented timestamped state buffering and trajectory interpolation.
- Implemented **constant-velocity dead reckoning** for temporary packet loss.
- Added smooth state reconciliation after network recovery.
- Tested behavior under configurable **latency and packet loss**.
- Logged simulation telemetry and analyzed results with Python, Pandas, and Matplotlib.

[Repository](https://github.com/vbn930/Realtime-Consistency-Sim) ·
[Research Report](https://github.com/vbn930/Realtime-Consistency-Sim/blob/master/Docs/Research_Report.pdf)

---

## SelfDriving-Simulator
### End-to-End Autonomous Driving

**Python · PyTorch · OpenCV · Unity 3D · CNN**

An implementation of NVIDIA's end-to-end learning approach for autonomous driving, evaluated in a Unity simulation environment.

- Built a modified **Dave-2-style CNN** for predicting steering and throttle.
- Used front-camera images together with vehicle speed as model inputs.
- Developed the training pipeline with PyTorch `Dataset`, `DataLoader`, MSE loss, and Adam.
- Implemented image preprocessing and horizontal-flip augmentation using OpenCV.
- Evaluated the trained model through autonomous driving in Unity.

[Repository](https://github.com/vbn930/SelfDriving-Simulator) ·
[Demo](https://www.youtube.com/watch?v=v07TapYTM1Y)

---

## Discord RPG
### Cloud-Native Game Server

**C# · .NET 8 · Azure · REST · Cosmos DB · Docker · OpenTelemetry**

A cloud-native backend for a Discord-based multiplayer RPG.

- Designed two independently deployable services for Discord communication and game-state management.
- Implemented REST-based service communication and API-key authentication.
- Used **Azure Cosmos DB** for persistent game state and **Azure Key Vault** for secret management.
- Added in-memory caching to reduce repeated remote secret lookups.
- Containerized services with Docker and deployed them using **Azure Container Apps**.
- Integrated GitHub Actions and OpenTelemetry for deployment and observability.

[Project](https://github.com/Dungeon-RPG-Discord-Game-Server)

---

## VisionCursor
### Vision-Based Touchless Human-Computer Interface

**Python · OpenCV · MediaPipe · PyAutoGUI**

A monocular-camera interface that translates hand gestures into mouse input.

- Extracted real-time hand landmarks using MediaPipe.
- Implemented geometric finger-state and gesture classification.
- Used thumb-index pinch distance for click detection.
- Separated computer-vision, gesture-processing, and OS-input components.

[Repository](https://github.com/vbn930/vision-cursor)

---

# 💼 Experience

### Teaching Assistant — Computer Networks I
**DigiPen Institute of Technology · Sep 2025 – Dec 2025**

- Assisted students with **C/C++ network programming** assignments covering TCP/IP, UDP, sockets, non-blocking I/O, and client-server architecture.
- Collaborated with the course instructor to design and develop networking programming assignments and projects.
- Helped debug networking, concurrency, packet-handling, and protocol-level issues.
- Explained networking and distributed-systems concepts during labs and individual troubleshooting sessions.

### Freelance Python Automation Developer
**South Korea · 2024**

Worked with multiple clients to build practical Python automation and data-collection systems.

**AMNotify KR**
- Built long-running Python/Selenium product-monitoring systems with authenticated proxy rotation, configurable polling, Discord alerts, logging, and persistent product records.

**BikeOnline Korea**
- Developed Python/Selenium crawlers for motorcycle-accessory catalogs, including make-model-year traversal, product metadata, options, descriptions, images, and structured Excel export.

**Other Clients**
- Developed additional data-collection and automation tools for health-product information, medical terminology, and user-activity tracking.

### Computer Operations Sergeant
**Republic of Korea Air Force · Nov 2021 – Aug 2023**

- Maintained communication/network equipment, servers, IT assets, and server-room infrastructure.
- Diagnosed hardware, connectivity, and system issues under operational security procedures.
- Performed scheduled antivirus definition updates and endpoint-security maintenance on **isolated internal-network systems**.

---

# 🎓 Education

### University of Stuttgart
**M.Sc. Computer Science · Incoming, Winter Semester 2026/27**

Interests: Robotics · Autonomous Systems · Computer Vision · AI · Simulation

### DigiPen Institute of Technology
**B.S. Computer Science in Real-Time Interactive Simulation · Apr 2026**

**Cum Laude · GPA: 3.52 / 4.00**

Dean's List: Fall 2024 · Spring 2025 · Fall 2025

### Keimyung University
**B.E. DigiPen Game Engineering · Aug 2026**

Dual-degree pathway · GPA: **3.6023 / 4.50**

---

# 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dohun_Lee-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dohun-lee-304971313/)
[![Email](https://img.shields.io/badge/Email-vbn9302%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:vbn9302@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-vbn930-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/vbn930)
