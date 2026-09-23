# My Projects

A collection of my software, embedded systems, AI, robotics, web development, and C++ projects.

My projects cover several areas: **C++ development, embedded systems, ESP32, robotics, AI agents, motion tracking, web development, APIs, and algorithmic programming.**

---

## Embedded Systems, Robotics & Hardware

### 1. HS-1 — Kinematic Motion Tracking Suit

[GitHub Repository](https://github.com/Perry1231/HS-1)

HS-1 is a distributed wearable motion-tracking system designed to capture human body movement in real time.

**Technologies:**

* C++
* Python
* ESP32-C3
* BNO055 IMU
* I2C
* UART
* PlatformIO
* Sensor Fusion
* 3D visualization
* Robotics

**Main features:**

* Multiple ESP32-C3 sensor nodes.
* BNO055 orientation sensors.
* Distributed motion data collection.
* Real-time orientation tracking.
* Euler angle processing.
* Communication between sensor nodes and the central system.

The project combines embedded electronics, sensor integration, firmware development and motion tracking.

---

### 2. MoSy — Motion Sync Edge AI

[GitHub Repository](https://github.com/Perry1231/MoSy)

MoSy is an Edge AI motion-control framework designed to connect the HS-1 motion-tracking suit with a quadrupedal robot.

**Technologies:**

* Python
* ONNX Runtime
* ESP32-C3
* BNO055
* UART
* I2C
* PCA9685
* Servo motors
* Edge AI

**System architecture:**

```text
HS-1 Suit
    |
    v
ESP32-C3 + BNO055
    |
    v
UART Telemetry
    |
    v
MoSy Edge AI
    |
    v
ONNX Model
    |
    v
Servo Mapping
    |
    v
PCA9685
    |
    v
Robot Actuators
```

The system is designed around a 50 Hz control loop and local Edge AI inference.

---

### 3. AbsoluteLocation — ESP32-C3 + BNO055

[GitHub Repository](https://github.com/Perry1231/AbsoluteLocation)

Embedded C++ project for obtaining absolute spatial orientation using an ESP32-C3 and BNO055 IMU.

**Technologies:**

* C++
* ESP32-C3
* BNO055
* I2C
* PlatformIO
* Wi-Fi
* HTML
* CSS
* JavaScript

**Features:**

* Real-time Yaw, Pitch and Roll measurements.
* BNO055 hardware sensor fusion.
* Serial terminal HUD.
* Wi-Fi Access Point.
* Local HTTP server.
* Real-time browser visualization.
* Interactive 3D orientation visualization.

The project demonstrates integration between embedded firmware, sensors, networking and web visualization.

---

## Artificial Intelligence

### 4. AlbertAgent — GAIA AI Agent

[GitHub Repository](https://github.com/Perry1231/AlbertAgent)

AlbertAgent is an AI agent designed to solve tasks from the GAIA Benchmark.

**Technologies:**

* Python
* smolagents
* Groq API
* OpenAI-compatible API
* GPT-OSS-120B
* Hugging Face
* Tool Calling
* GAIA Benchmark

**Features:**

* Multi-step AI reasoning.
* External tool usage.
* Web research.
* Python execution.
* API integrations.
* GAIA benchmark evaluation.
* Automatic generation of `submission.jsonl`.

**Architecture:**

```text
GAIA Task
    |
    v
ToolCallingAgent
    |
    v
GPT-OSS-120B
    |
    +------> External Tools
    |              |
    |              v
    |         Tool Results
    |              |
    +<-------------+
    |
    v
Final Answer
    |
    v
submission.jsonl
```

The project focuses on AI agents, tool calling, automated research and benchmark evaluation.

---

### 5. Dispersy
[GitHub Repository](https://github.com/Perry1231/Dispersy)
AI-powered multi-agent development environment designed to coordinate specialized AI agents for software development.

Dispersy uses a central coordinator to analyze user requests, break complex tasks into smaller problems, delegate them to specialized agents, and combine their results into a final solution.

The platform is designed around collaborative AI agents that can independently handle different parts of the development process, such as planning, coding, debugging, testing, research, documentation, and code review.

The goal is to create a flexible AI development workspace where multiple specialized agents can work together instead of relying on a single model for the entire task.

---
## Web Development

### 6. PortfolioWebsite

[GitHub Repository](https://github.com/Perry1231/PortfolioWebsite)

[Live Website](https://portfolio-website-sigma-three-21.vercel.app/)

Personal portfolio website designed to present projects, skills and experience.

**Technologies:**

* HTML5
* CSS3
* JavaScript
* React
* Responsive Web Design

**Features:**

* Responsive interface.
* Personal introduction.
* Skills section.
* Project showcase.
* Contact section.
* Modern navigation.

---

### 6. MarketPulse

[GitHub Repository](https://github.com/Perry1231/MarketPulse)

A project focused on financial and market data.

The repository is currently an experimental project for exploring application architecture and data-related development.

---

## C++ Projects

### 7. Adventure-Game

[GitHub Repository](https://github.com/Perry1231/Adventure-Game)

A C++17 terminal RPG demonstrating object-oriented programming and a larger multi-file project architecture.

**Features:**

* Character generation.
* Character statistics.
* Weapons.
* Armor.
* Inventory management.
* Potions.
* Equipment system.
* Item durability.
* Random events.
* NPCs.
* Traders.
* Combat.
* Story events.

**Technologies:**

* C++17
* Object-Oriented Programming
* Dynamic memory
* Multi-file architecture
* GitHub Actions

The project can be compiled using GCC/MinGW, MSVC or Clang and includes an automated GitHub Actions build workflow.

---

### 8. LeetCode Solutions in C++

[GitHub Repository](https://github.com/Perry1231/LeetCode-Solutions-In-C-)

A collection of solutions to algorithmic programming problems written in C++.

**Focus:**

* Algorithms.
* Data structures.
* Problem solving.
* Competitive programming.
* C++ programming.

---

## GitHub & Developer Tools

### 9. My GitHub Stats

[GitHub Repository](https://github.com/Perry1231/My-GitHub-Stats)

A customized GitHub profile and statistics project.

Includes:

* GitHub statistics.
* Most-used programming languages.
* Developer badges.
* LeetCode integration.
* LinkedIn integration.
* Custom profile presentation.

---

### 10. GitHub Profile

[GitHub Repository](https://github.com/Perry1231/Perry1231)

The repository containing my GitHub profile README and developer presentation.

It presents my main areas of interest:

* Embedded Systems.
* C++.
* Electronics.
* ESP32.
* Robotics.
* Artificial Intelligence.
* Web Development.
* Algorithms.

---

## Learning & Open Source

### 11. First Contributions

[GitHub Repository](https://github.com/Perry1231/FirstContributions)

Repository related to learning and practicing GitHub open-source contribution workflows.

**Topics:**

* Git.
* GitHub.
* Pull Requests.
* Branches.
* Open-source contribution workflow.

---

### 12. First Contributions

[GitHub Repository](https://github.com/Perry1231/first-contributions)

Another repository related to the First Contributions workflow and Git/GitHub practice.

The project represents practice with collaborative development and open-source contribution workflows.

---

### 13. Content Ops Starter

[GitHub Repository](https://github.com/Perry1231/content-ops-starter)

A starter project related to content operations, development workflows and experimentation with project structure and automation.

---

## Project Collection

### 14. AllProjects

[GitHub Repository](https://github.com/Perry1231/AllProjects)

A central repository intended to collect and present my projects in one place.

The repository serves as a portfolio and index for my development work.

---

# Technologies & Skills Demonstrated

## Programming

* C++
* Python
* JavaScript
* HTML
* CSS
* Object-Oriented Programming
* Algorithms
* Data Structures
* REST APIs

## Embedded Systems

* ESP32
* ESP32-C3
* Arduino
* PlatformIO
* I2C
* UART
* PWM
* Sensor integration
* IMU sensors
* Embedded C++

## Robotics

* Motion tracking
* Kinematics
* Sensor fusion
* Servo control
* PCA9685
* Robot control
* 3D visualization

## Artificial Intelligence

* AI Agents
* Tool Calling
* LLM APIs
* Groq
* smolagents
* ONNX
* Edge AI
* Benchmark evaluation
* GAIA Benchmark

## Web Development

* HTML5
* CSS3
* JavaScript
* React
* Responsive Web Design
* REST APIs
* Web interfaces

## Algorithms

* LeetCode
* Data Structures
* Problem Solving
* C++ Algorithms
* Competitive Programming

---

# Project Structure

| Category                | Projects                                              |
| ----------------------- | ----------------------------------------------------- |
| Embedded Systems        | HS-1, AbsoluteLocation                                |
| Robotics                | HS-1, MoSy                                            |
| Artificial Intelligence | AlbertAgent, MoSy                                     |
| C++                     | Adventure-Game, TaskBook, LeetCode, Classes & Objects |
| Web Development         | PortfolioWebsite, MarketPulse                         |
| Algorithms              | LeetCode Solutions                                    |
| Learning                | First Contributions, Classes & Objects                |
| GitHub Tools            | My-GitHub-Stats, GitHub Profile                       |
| Project Collection      | AllProjects                                           |
| Experimental            | Content Ops Starter                                   |

---

# Development Direction

My projects are focused on combining several engineering disciplines:

```text
Electronics
     |
     v
Embedded Systems
     |
     v
ESP32 / Sensors
     |
     v
Motion Tracking
     |
     v
Robotics
     |
     +----------------+
     |                |
     v                v
Artificial        C++ / Algorithms
Intelligence
     |                |
     +-------+--------+
             |
             v
       Complete Systems
       Hardware + AI
       + Software
```

The overall goal is to develop complete engineering systems that combine **electronics, embedded systems, C++, artificial intelligence, robotics and software development**.

---

# Links

GitHub: https://github.com/Perry1231

LinkedIn: https://www.linkedin.com/in/vladyslav-vytrykush-4b1a29380/

Portfolio: https://portfolio-website-sigma-three-21.vercel.app/

---
