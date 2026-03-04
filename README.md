# 🐕 In-House High-Performance Quadruped Robot

## 📌 Project Overview

This project focuses on the design and development of a **high-performance quadruped robotic dog**, built entirely in-house with a strong emphasis on modularity, efficiency, and scalability.

The system is built around custom motor control electronics using the **STM32G431CBU6** microcontroller, implementing advanced **Field Oriented Control (FOC)** and real-time **CAN FD communication** between joints.

Our goal is to design and develop every critical subsystem internally — including actuator electronics, firmware architecture, communication stack, and mechanical integration.

---

## 🎯 Objectives

- Develop high-efficiency FOC-based motor control
- Design modular smart actuators
- Implement deterministic real-time CAN FD communication
- Build scalable firmware architecture for multi-joint control
- Optimize for performance, responsiveness, and energy efficiency
- Maintain complete in-house system ownership and understanding

---

## 🧠 System Architecture

### 🔹 Control Electronics
- Microcontroller: STM32G431CBU6
- Advanced timer-based PWM generation
- Inline / low-side current sensing
- High-speed ADC sampling
- CAN FD communication interface

### 🔹 Motor Control
- Field Oriented Control (FOC)
- High switching frequency PWM
- Real-time current control loop
- Velocity and position control loops
- Optimized for low latency and high torque response

### 🔹 Communication
- CAN FD based multi-node architecture
- Deterministic joint-level communication
- Scalable bus structure for 12+ actuators
- Distributed-ready control design

### 🔹 Mechanical Design
- Modular actuator units
- Custom motor driver PCB
- Compact, serviceable architecture
- Strength-to-weight optimized structure

---

## 📂 Repository Structure
/firmware
/motor_control
/can_fd
/drivers
/middleware

/hardware
/pcb_design
/schematics
/bom

/mechanical
/cad_files
/actuator_design

/docs
/progress_reports
/architecture_notes


---

## 🚀 Current Progress

- ✅ Custom motor driver PCB designed
- ✅ STM32G431 bring-up completed
- ✅ PWM generation validated
- ✅ ADC sampling verified
- ✅ Initial FOC implementation tested
- 🔄 CAN FD communication framework in progress
- 🔄 Multi-joint synchronization under development
- 🔄 Actuator mechanical refinement ongoing

---

## 🔜 Next Steps

- Complete closed-loop position control
- Optimize FOC loop timing and stability
- Finalize CAN FD protocol structure
- Integrate multiple actuators
- Begin quadruped gait testing
- Implement high-level motion control layer

---

## 🛠️ Development Tools

- STM32CubeIDE
- STM32 HAL / LL Drivers
- Custom FOC algorithms
- Oscilloscope and logic analyzer for validation
- CAN FD debugging tools

---

## 📈 Long-Term Vision

- Fully autonomous quadruped platform
- Advanced locomotion algorithms
- Real-time state estimation
- AI-assisted gait optimization
- Expandable research and development platform

---

## 🤝 Contribution

This is currently an in-house development project.  
Documentation and structured releases will be improved progressively.

---

## 📜 License

License information will be added soon.
