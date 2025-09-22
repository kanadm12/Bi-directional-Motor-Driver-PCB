# Bi-directional Motor Driver & Mixed Signal Board Project  

## 📘 Project Overview
This repository contains my **end-to-end mixed-signal PCB design project**, developed as part of my advanced PCB design work.  
The project demonstrates my ability to design **complex multi-layer mixed-signal boards** that integrate microcontrollers, high-speed interfaces, precision ADC/DACs, audio systems, and high-power motor drivers.  

I personally handled every stage of the design flow — from **requirement analysis, component selection, schematic design, stack-up planning, to final PCB layout optimization**.  

---

## 🧩 My Work Process

### 1. **Component Selection**
- Researched and selected each component based on datasheet analysis and design requirements.  
- Key components chosen by me:
  - **STM32F407** (main controller)  
  - **STM32F103** (programmer/debugger)  
  - **Ethernet PHY (10/100 Mb/s)**  
  - **24-bit ADC & I2S DAC**  
  - **MEMS microphone**  
  - **CH340C USB to UART converter**  
  - **36W bi-directional brushed DC motor drivers**  
  - Power supply, ferrite beads, ESD diodes, and protection circuits  

---

### 2. **Schematic Design**
- Designed **all schematic blocks** based on datasheet reference designs and application notes.  
- Created **power budgeting diagrams** and block diagrams before schematic capture.  
- Implemented high-speed and mixed-signal interfaces:  
  - **USB 2.0, UART/USART, CAN, I2C, I2S, MII/RMII**  
- Applied EMI/EMC best practices at the schematic level.  

---

### 3. **Stack-up & Placement**
- Designed **4-layer, 6-layer, 8-layer, and 12-layer stack-ups**, choosing the optimal configuration per requirement.  
- Performed **field solver simulation** to validate impedance control.  
- Created **rigid-flex PCB stack-ups** and explored different board shapes.  
- Planned component placement across analog, digital, power, and motor driver sections.  

---

### 4. **Layout Planning & Execution**
- Executed **layout planning** for inter-block and intra-block connections.  
- Routed more than **10,000 interconnects** with differential pairs and controlled impedance lines.  
- Separated analog, digital, and power domains for signal integrity.  
- Optimized layout for EMI/EMC compliance.  
- Performed **Power Distribution Network (PDN) analysis** and resolved power ripple/noise issues.  

---

## 🔑 Major Blocks Designed
- **Ethernet PHY (10/100 Mb/s)**  
- **I2S DAC for headphones and speakers**  
- **MEMS microphone module**  
- **24-bit ADC for precision signal acquisition**  
- **36W bi-directional brushed DC motor drivers**  
- **UART to USB TTL converter (CH340C)**  
- **STM32F103 debugger/programmer**  
- **STM32F407 main controller**  
- **Complete power supply and protection circuits**  

---

## 📚 Additional Tasks Completed
- Block diagrams and power budgeting (pre-schematic design)  
- Stack-up selection and layer planning  
- Grounding techniques: signal, earth, and chassis grounding  
- Pin mapping using **STM32CubeMX**  
- Selection and application of ferrite beads, ESD diodes, and magnetic components  
- Placement planning (even simulated with simple tools like MS Paint)  

---

## 🎯 Skills Demonstrated
- Datasheet analysis & component selection  
- Schematic capture of complex mixed-signal circuits  
- High-speed interface design (USB, Ethernet, I2S, CAN, UART, I2C)  
- PCB stack-up design (4L/6L/8L/12L)  
- Rigid-flex PCB design  
- EMI/EMC-conscious design decisions  
- Layout optimization with thousands of nets  
- PDN analysis & issue resolution  

---

## ✅ Outcome
Through this project, I successfully designed and documented a **complete mixed-signal board** that combines microcontrollers, networking, audio, precision ADC/DAC, and high-power drivers.  

This work demonstrates my **end-to-end capability in PCB design**, from **concept to manufacturable design**, using industry-relevant practices and tools.

---

## 📌 Author
**Kanad Mukherjee**  
Electronics & Telecommunication Engineer | PCB & Embedded Systems Designer  

