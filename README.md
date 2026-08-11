# ⚡ SD Card Audio Player PCB

Custom-designed ESP32-based audio playback system capable of playing stored audio tracks from an SD card through user-controlled button inputs.

---

## 📐 Overview

This project involved the complete development of an embedded audio playback system, including circuit design, microcontroller programming, PCB development, assembly, and hardware testing.

An ESP32 was programmed in C++ using the Arduino IDE to process physical button inputs and control SD-card-based audio playback. The supporting electrical circuit was initially developed and tested before being transferred into a custom PCB designed in KiCad.

The final PCB was manufactured, manually soldered, assembled, and tested as a complete embedded system.

### Key Objectives

- Design a functional SD-card-based audio playback circuit
- Program an ESP32 to control system behaviour
- Process user inputs through physical push buttons
- Implement audio playback control using Arduino/C++
- Develop the circuit schematic in KiCad
- Design and route a custom PCB
- Assemble and solder the manufactured PCB
- Test and debug the completed embedded system

---

## 🛠️ Software & Tools

- KiCad
- Arduino IDE
- C++
- ESP32
- Soldering equipment
- Digital multimeter
- Breadboard and prototyping equipment

---

## 💻 ESP32 Programming

The ESP32 served as the primary controller for the system.

Custom firmware was written in C++ using the Arduino IDE to:

- Read physical push-button inputs
- Execute user-triggered playback commands
- Interface with the audio playback hardware
- Control playback of tracks stored on the SD card
- Coordinate the behaviour of the overall system
- Support testing and debugging of the completed hardware

---

## 🔌 System Design

The system was designed around an ESP32 microcontroller that processed user inputs and controlled audio playback from an SD card.

The project progressed through several stages:

1. Circuit design and component selection
2. Breadboard prototyping and electrical testing
3. ESP32 firmware development
4. Button input integration
5. SD-card audio playback integration
6. Schematic development in KiCad
7. PCB component placement and trace routing
8. PCB manufacturing
9. Manual soldering and assembly
10. Hardware and software debugging
11. Final system testing

---

## 🖥️ PCB Design

After validating the circuit, the electrical design was transferred into KiCad.

The PCB development process included:

- Creating the electrical schematic
- Assigning component footprints
- Positioning components
- Routing signal and power traces
- Managing electrical connections
- Performing design-rule checks
- Preparing manufacturing files

The custom PCB provided a cleaner, more compact, and more permanent implementation than the original prototype.

---

## 🔧 PCB Assembly

After fabrication, the PCB was manually assembled and soldered.

Assembly and validation included:

- Installing electrical components
- Soldering board connections
- Inspecting solder joints
- Checking continuity
- Connecting external components
- Uploading and testing ESP32 firmware
- Debugging button inputs and audio playback

---

## 🧠 Engineering Skills Demonstrated

- Embedded systems development
- ESP32 programming
- C++ / Arduino
- Circuit design
- PCB schematic capture
- PCB layout and routing
- KiCad
- Electronic prototyping
- Soldering
- Hardware/software integration
- Electrical testing
- System debugging
- Design iteration

---

## ✅ Project Outcome

The project progressed from an initial circuit concept to a custom-designed and physically assembled embedded system.

The final system combined custom ESP32 firmware, user-input processing, SD-card-based audio playback, and a purpose-built PCB. Developing the project required integrating embedded programming, circuit design, PCB development, soldering, and hardware debugging into a complete electronics development workflow.
