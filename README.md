# SmartKargo
![Java](https://img.shields.io/badge/java-11%2B-orange)
![Prolog](https://img.shields.io/badge/prolog-2p32-red)
![Gradle](https://img.shields.io/badge/build-gradle-green)
![Architecture](https://img.shields.io/badge/architecture-microservices-blue)
![Status](https://img.shields.io/badge/status-completed-success)

---

## 📖 About The Project

**SmartKargo** is a distributed software system designed to manage a robotic agent (DDR - Differential Drive Robot) tasked with handling logistic operations in a cargo warehouse environment.


The system utilizes an **Actor-Based Architecture** (using the custom QAk infrastructure) to ensure non-blocking, asynchronous communication between components. It integrates high-level reasoning (via **Prolog**) with low-level actuation.
It is built upon a **Microservices Architecture**, where each component (Service, Controller, Robot Adapter) functions as an independent, loosely coupled service. This design ensures modularity, scalability, and ease of deployment across different computational nodes

### 🎯 Key Features
*   **Planning Strategy:** Prolog-based logic for task handling.
*   **Distributed System:** Components (GUI, Controller, Robot) can run on different contexts.
*   **Clean Architecture:** Separation between business logic and technology details (Hexagonal Architecture approach).
*   **Microservices Architecture:** The system is decomposed into distinct services communicating asynchronously.
*   **Autonomous Navigation:** The robot (DDR) autonomously handles transport requests, pathfinding, and obstacle avoidance.
*   **Distributed Deployment:** Services can be deployed on separate machines, communicating via TCP/IP, MQTT, or CoAP.
*   **Smart Monitoring:** A Web GUI microservice for real-time tracking of the robot's status and warehouse storage.

---

## 📂 Project Structure & Sprints

The project follows an incremental **Agile/Scrum** development process divided into Sprints. Each Sprint includes Requirements Analysis, Problem Analysis, Design, and Testing.

| Phase | Description | Documentation | Status |
| :--- | :--- | :---: | :---: |
| **Sprint 0** | Requirements Analysis & Architecture Definition | [📂 View Sprint 0](./Sprint0) | ✅ Completed |
| **Sprint 1** | Core Logic & Microservices Setup | [📂 View Sprint 1](./Sprint1) | ✅ Completed |
| **Sprint 2** | Robot Physical Adapter & Interaction | [📂 View Sprint 2](./Sprint2) | ✅ Completed |
| **Sprint 3** | GUI, Optimization & Final Deployment | [📂 View Sprint 3](./Sprint3) | ✅ Completed |


---

## 🛠️ Technology Stack

*   **Language:** Kotlin (Primary), Java.
*   **Logic/AI:** Prolog (tuProlog / 2p32).
*   **Build System:** Gradle.
*   **Infrastructure:** QAk (QActors) - Custom Unibo Actor Framework.
*   **Hardware Target:** Raspberry Pi (with varying DDR implementations).
*   **Communication:** TCP/IP, MQTT, CoAP.

---

## Team
Membri del team di sviluppo :
| <img src="./commons/resources/Profileimg/vale.jpg" width="150"/> | <img src="./commons/resources/Profileimg/Angela.jpg" width="150"/> | <img src="./commons/resources/Profileimg/Siria.jpeg" width="150"/> |
|-----------------------|-----------------------|-----------------------|
| [Bacchelli Valentina](https://github.com/VBacchelli)       | [Russo Angela](https://github.com/gioliee)        | [Savignano Siria](https://github.com/sirius-22)       |
