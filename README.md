# Project-Alfred_TRD

# Building Alfred: The Humanoid Receptionist Robot

## Introduction

This repository contains the technical requirements document and implementation plan for building Alfred, a humanoid robot designed to greet and interact with visitors at the Innovation Lab. The project aims to enhance visitor engagement while providing an innovative and futuristic experience.

## Technical Requirements

### 3D Printing Requirements

**Hardware:**
- 3D Printer Models: Creality Ender 3, Anycubic i3 Mega, or Prusa i3 MK3.
- Time to Build Models: Approximately 200 hours of printing time, depending on the complexity and size of the parts.
- Filaments: PLA or ABS filaments. PLA is preferred for ease of use and lower printing temperatures.
- Compatible Models: Reachy and Poppy models are compatible with most FDM 3D printers. The parts will be scaled according to the required dimensions for Alfred.

**Cost of Hardware:**
- 3D Printer: INR 20,000 to INR 50,000 depending on the model.
- Filaments: INR 1,500 per kg for PLA.
- Total Estimated Cost: INR 25,000 to INR 60,000.

### Electronics

**Components:**
- Microcontroller: Raspberry Pi 4 (INR 4,000) or Arduino Mega 2560 (INR 1,500).
- Sensors:
  - Cameras: Logitech C920 (INR 8,000) or Raspberry Pi Camera Module (INR 2,000).
  - Microphones: USB Microphone (INR 1,500) or MEMS microphones for integration (INR 500).
  - Ultrasonic Sensors: HC-SR04 (INR 100 each).
- Motors:
  - Servos: MG996R (INR 300 each) or Dynamixel AX-12A (INR 6,000 each).
  - Stepper Motors: NEMA 17 (INR 1,200 each).
- Power Supply: 12V 10A power supply (INR 2,000).
- Additional Components: Breadboards, jumper wires, resistors, capacitors (INR 2,000).

**Assembly Process:**
- 3D Printing: Print all necessary parts using the specified filaments.
- Microcontroller Setup: Install the operating system and necessary software libraries.
- Sensor Integration: Connect cameras and microphones to the microcontroller.
- Motor Assembly: Attach motors to the 3D-printed parts and connect to the power supply and microcontroller.
- Final Assembly: Combine all parts to form the complete humanoid robot.

**Cost of Components:**
- Microcontroller and Accessories: INR 6,000
- Sensors: INR 12,000
- Motors: INR 25,000
- Power Supply and Additional Components: INR 4,000
- Total Estimated Cost: INR 47,000

### Supported Movement Capabilities by the Humanoid

- Head Movements: Pan and tilt using servo motors.
- Arm Movements: Shoulder and elbow movements for waving and gesturing.
- Hand Gestures: Basic open/close actions.
- Tracking Movements: Utilizing cameras and sensors to follow guests.
- Audio-based Cues: Nodding in response to speech recognition.

### Cost-Efficient Ways to Build and Test the Humanoid

- Simulation Software: Use Gazebo or V-REP for testing the humanoid in a virtual environment before physical assembly.
- Modular Design: Develop and test individual modules (e.g., head, arm) separately to identify issues early.
- Reuse Components: Utilize components from previous projects or educational kits to reduce costs.

## 12-Week Implementation Plan

### Phase 1: Planning and Design (Weeks 1-2)

- Define project scope and objectives.
- Assign roles and responsibilities to engineers.
- Finalize design specifications for Alfred.

### Phase 2: 3D Printing and Parts Preparation (Weeks 3-4)

- Set up 3D printers and begin printing all parts.
- Conduct quality checks on printed parts.

### Phase 3: Electronics Integration (Weeks 5-6)

- Set up microcontroller and integrate cameras, microphones, and basic electronic components.

### Phase 4: Software Development (Weeks 7-9)

- Develop control software, vision processing algorithms, speech recognition, and text-to-speech capabilities.

### Phase 5: System Integration and Testing (Weeks 10-11)

- Perform full system integration and conduct comprehensive testing of the entire humanoid robot.

### Phase 6: Deployment and Training (Week 12)

- Deploy Alfred in the Innovation Lab and train staff on operating and troubleshooting procedures.

## Summary of Engineering Resources

- Total Duration: 12 weeks
- Total Engineers: 4 engineers
  - 3D Printing and Parts Preparation: 2 engineers
  - Electronics Integration: 4 engineers
  - Software Development: 2 software engineers
  - System Integration and Testing: 4 engineers
  - Deployment and Training: 2 engineers

This README.md provides an overview of the technical requirements and implementation plan for Building Alfred: The Humanoid Receptionist Robot.
