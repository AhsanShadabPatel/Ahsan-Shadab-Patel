# Hi, I'm Ahsan 👋

**Embedded Systems & VLSI Engineer | Firmware, Hardware-Software Integration, and Digital Systems Design**

I design and build **embedded systems, digital hardware, and firmware** that tightly integrate hardware and software — from CNC machines and handheld game consoles to **SRAM memory arrays** and **fault-tolerant oxygen concentrators**.

My work focuses on **performance, reliability, and system-level integration**, with hands-on experience across microcontrollers, PCB design, and VLSI.

---

## 🔧 Technical skills

- **Languages:** C, Python, Verilog, VHDL, Embedded C.
- **MCUs & Platforms:** STM32, ARM Cortex, Arduino, Raspberry Pi. 
- **Tools & EDA:** STM32CubeIDE, Cadence Virtuoso, Silvaco, MATLAB, Simulink, AutoCAD  
- **Hardware Design:** PCB design, FPGA, VLSI physical design, schematic capture, IC layout, SRAM design  
- **Protocols:** USART, SPI, I2C, CAN, REST/SOAP APIs  
- **Embedded Concepts:** Firmware development, DMA, ADC, DAC, timers, GPIO, real-time systems  
- **Practices:** Debugging, hardware testing, system integration, CI/CD, version control  

---

## 🕹 Handheld game console (STM32F407VG)

**Tech:** STM32F407VG, C, USART, ADC, DAC, DMA  

- **What it is:** A handheld game console that runs **Snake** and **Tetris** using an STM32 microcontroller with a serial-terminal UI.  
- **Highlights:**
  - Real-time UI using **ANSI escape sequences** over USART
  - **Joystick input** via ADC with GPIO buttons
  - **Audio output** using DAC + TIM6 + DMA for smooth playback
  - Modular firmware architecture with unified menu and built-in debug hooks

👉 **Repo:** `https://github.com/AhsanShadabPatel/Handheld-Gaming-Console`

---

## 💾 16×16 SRAM memory design (Cadence Virtuoso)

**Tech:** Cadence Virtuoso, VLSI, schematic design  

- **What it is:** A **16×16 SRAM cell array** designed and simulated from bit-cell to full-array level.  
- **Highlights:**
  - **6T SRAM bit cells** with read/write capability
  - Row decoder, column multiplexer, and sense amplifiers
  - Timing analysis and **corner-case verification** via transient simulations

👉 **Repo:** `(https://github.com/AhsanShadabPatel/16-16-SRAM-Array)`

---

## 🫁 Portable oxygen concentrator with fault detection

**Tech:** Arduino, RF, Embedded C  

- **What it is:** A **battery-operated portable oxygen concentrator prototype** with integrated **fault detection** and real-time monitoring. *(Patent pending)*  
- **Highlights:**
  - Real-time fault detection using sensor feedback and RF communication
  - Pressure swing adsorption control with oxygen concentration monitoring
  - Reliability-focused design with system data analysis for rapid fault response

👉 **Repo:** `https://github.com/AhsanShadabPatel/Portable-Oxygen-Concentrator-Fault-Detection`  

> Note: Some implementation details may be abstracted/redacted due to IP/patent considerations.

---

## ⚙️ 3-axis metal cutting CNC machine

**Tech:** Arduino, G-code, stepper motors, CAM  

- **What it is:** A **3-axis CNC machine** for precision metal cutting, milling, and engraving.  
- **Highlights:**
  - Arduino-based G-code interpreter for motion control
  - Stepper motor + driver integration for accurate X, Y, Z positioning
  - Custom mechanical structure integrated with electronics and firmware

👉 **Repo:** `https://github.com/AhsanShadabPatel/3-Axis-Metal-Cutting-CNC-Machine`

---

## 💼 Professional experience

- **Software Engineer – Coforge**  
  - Integrated enterprise systems using **REST/SOAP APIs**, handling 1,000+ daily transactions  
  - Improved backend performance through query tuning and DB optimization  
  - Managed CI/CD deployments with a 99%+ success rate across environments  

- **Graduate Teaching Assistant – University of Texas at Arlington**  
  - Mentored engineers in **PCB design, embedded systems debugging, and HDL simulation**  
  - Guided teams through full project lifecycle: design → implementation → testing → documentation  
  - Supported hardware–software integration and enforced lab safety protocols  

- **Engineering Intern – Pro Imaginations**  
  - Automated CNC machine movements with Arduino, sensors, and wireless transceivers, cutting manual intervention by **70%**  
  - Designed embedded solutions using IC testing data to optimize product performance  
  - Prototyped components using 3D printing and Solidworks to speed up development

---

## 📫 Contact

- **Email:** ahsanshadabpatel@gmail.com  
- **LinkedIn:** [linkedin.com/in/ahsan-patel](https://linkedin.com/in/ahsan-patel)  
- **Location:** Irving, TX  

Open to roles in **embedded systems, firmware, and VLSI/hardware design**. If your work touches hardware–software co-design, I’d be interested in talking.
