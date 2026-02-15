# Hi, my name is Adriel Motter

**Computer Science & Mathematics Student | Software Engineer | Game Developer**  

---

## About Me

I am a Computer Science and Mathematics student at the University of Central Florida with a strong foundation in data structures, algorithms, and systems-level programming. I am particularly interested in native programming (C/C++), performance-oriented design, and building clean, modular systems from first principles.


---

# Featured Programming Projects

---

## 🔹 ADSR-Echo (C++)

**Repository:** [ADSREchoVST](https://github.com/crabnebuelar/ADSREchoVST)

(View the .README in the repository for more information.)
### Overview

ADSR Echo is a cross-platform JUCE audio plugin (VST3/AU) built in C++ that serves as a modular hub for reverb and time-based effects in digital audio production. This was developed as a group project, with my contributions involving development of the routing and architecture of the audio processing.

The project explores a flexible, modular DSP architecture that allows users to construct custom signal chains using both series and parallel routing, similar to modern DAWs and modular effect racks. The goal is to improve workflow efficiency when working with multiple reverb and spatial effects.

The current implementation is fully functional at the DSP level, with a temporary UI that will evolve as development continues.


### My Contributions
- Designed and implemented the core modular DSP architecture  
- Built support for dynamic module creation/removal and parallel chain routing  
- Implemented plugin parameter/state management (APVTS)  
- Ensured real-time audio thread safety (no allocations on the real-time audio thread, atomic GUI → DSP communication)

### Files of Interest
- `PluginProcessor.*`
- `Modular Classes/ModuleSlot.*`
- `Modular Classes/Effect Modules/*`


---

## 🔹 Quantum Sensor Optimization Simulator – (C#/Python)

**Repository:** [Quickstart-Sensor-Optimization-Sim](https://github.com/crabnebuelar/Quickstart-Sensor-Optimization-Sim)

(View the .README in the repository for more information.)

**Tech:** Unity, Qiskit  

This project is a Unity-based simulation demonstrating how quantum optimization algorithms can be applied to a sensor placement problem. Users place sensors in a virtual facility, define coverage, and run an optimization routine that selects an optimal subset using a QUBO formulation solved with QAOA (via Qiskit).

The Unity application handles visualization and interaction, while optimization is executed by an external Python process and returned via JSON.

### Technical Higlights:
- Implemented QUBO formulation for sensor selection  
- Built QAOA-based optimization pipeline using Qiskit  
- Designed Unity ↔ Python integration (process execution + JSON serialization)  
- Implemented ray-based visibility checks and adjustable sensor coverage in Unity  

### Files of Interest
- `Assets/StreamingAssets/sensor_optimizer.py`
- `Assets/Scripts/SensorManager.cs`
- `Assets/Scripts/Sensor.cs`

---

## 🔹 Cretastrophe – Dynamic Physics Puzzle Platformer (C#)

**Repository:** [Cretastrophe](https://github.com/crabnebuelar/Cretastrophe)

(View the .README in the repository for more information.)

**Role:** Team Lead (4 Developers)  
**Award:** Best In Show – Fall 2024 (UCF AI in Game Programming Showcase)

Cretastrophe is a 2D puzzle-platformer centered around drawing and erasing chalk platforms in real time. Players dynamically create physics-enabled geometry to navigate levels, requiring the engine to handle continuously changing collision surfaces and unstable physics interactions.

As team lead, I directed overall system design and implemented the core gameplay architecture.

### Technical Highlights
- Designed and implemented a custom 2D player controller using raycasting-based collision detection  
- Built the real-time chalk drawing and erasing system  
- Implemented runtime geometry splitting with physics reassignment for gravity-affected chalk  
- Ensured stable movement and collision handling on dynamically changing surfaces  
- Designed core puzzle mechanics built on player-generated physics objects  

### Files of Interest
- `Assets/Scripts/PlayerControl/`
- `Assets/Scripts/DrawErase/`

---

# Technical Skills

### Languages
C++, C#, Python, C, Java, JavaScript, SQL

### Frameworks & Tools
Unity, React, Node.js, Express, Git, MongoDB, VS Code, Visual Studio  

