# <h1 align="center">Hi there, I'm Diana 👋</h1>

<p align="center">
  <!-- CPU -->
  <a href="https://github.com/hyeonjijung1/riscv-pipeline-cpu">
    <img src="https://img.shields.io/badge/GitHub-riscv--pipeline--cpu-black?style=flat&logo=github" alt="RISC-V Pipeline CPU Repo">
  </a>
  <!-- SDR -->
  <a href="https://github.com/hyeonjijung1/controller-hardware-sdr">
    <img src="https://img.shields.io/badge/GitHub-controller--hardware--sdr-black?style=flat&logo=github" alt="SDR Controller Hardware Repo">
  </a>
  <!-- FPGA Piano -->
  <a href="https://github.com/hyeonjijung1/fpga-piano-audio-system">
    <img src="https://img.shields.io/badge/GitHub-fpga--piano--audio--system-black?style=flat&logo=github" alt="FPGA Piano Audio System Repo">
  </a>
  <!-- LoRa -->
  <a href="https://github.com/hyeonjijung1/BlueSky-LoRa-Radio">
    <img src="https://img.shields.io/badge/GitHub-BlueSky--LoRa--Radio-black?style=flat&logo=github" alt="BlueSky LoRa Radio Repo">
  </a>
</p>

I design and build hardware from schematic capture to fully validated systems, bridging **analog, digital, and embedded domains**.  
My work includes **RF telemetry modules**, **RISC-V CPU cores**, **FPGA-based audio systems**, and **custom PCBs** tested and verified in the lab.  

Aside from engineering, I train **550+ Frosh Week leaders** to create an inclusive, welcoming experience for first-year engineering students.

---

## 📂 Featured Projects

### RISC-V 5-Stage Pipelined CPU Core  
[![Repo](https://img.shields.io/badge/GitHub-riscv--pipeline--cpu-black?style=flat&logo=github)](https://github.com/hyeonjijung1/riscv-pipeline-cpu)

> **Fully synthesizable Verilog CPU** implementing the RV32I ISA with **hazard detection**, **data forwarding**, and **branch handling**.  
> Verified with **ModelSim/GTKWave** and custom instruction & memory testbenches.

| **Block Diagram** | **Instruction Decode (ID)** | **Forwarding (EX)** | **Load/Store (MEM)** |
|---|---|---|---|
| ![Block Diagram](https://github.com/hyeonjijung1/riscv-pipeline-cpu/blob/main/docs/bd.png) |![ID Stage](https://github.com/hyeonjijung1/riscv-pipeline-cpu/blob/main/docs/id_stage.png) | ![EX Waveform](https://github.com/hyeonjijung1/riscv-pipeline-cpu/blob/main/docs/ex_stage.png) | ![MEM Waveform](https://github.com/hyeonjijung1/riscv-pipeline-cpu/blob/main/docs/mem_stage.png) |

<sub>**Figure:** Pipeline architecture (left) and waveform verification of execution and memory stages (middle, right).</sub>

**Tech Stack:** `Verilog` · `Tcl Scripting` · `RISC-V Assembly` · `Pipeline Design` · `Hazard Detection` · `Data Forwarding` · `ModelSim` · `GTKWave` · `Quartus Prime`

---

### **SDR Controller Hardware**  
[![GitHub Repo](https://img.shields.io/badge/Repo-controller--hardware--sdr-181717?logo=github)](https://github.com/hyeonjijung1/controller-hardware-sdr)  

> **ATmega324PB** + **Si5351A** for frequency generation, UART CAT protocol, and Python-based hardware validation.  
> Designed for SDR TX/RX switching, LO control, and integration with mixer & amplifier subsystems.  

| 3D PCB Render | Block Diagram | Schematic | Assembled Hardware |
|---|---|---|---|
| ![3D Render](https://github.com/hyeonjijung1/controller-hardware-sdr/blob/main/images/3D%20PCB%20render.png) | ![Block Diagram](https://github.com/hyeonjijung1/controller-hardware-sdr/blob/main/images/block_diagram_sdr.png) | ![Schematic](https://github.com/hyeonjijung1/controller-hardware-sdr/blob/main/images/original_schematic.png) | ![Assembled](https://github.com/hyeonjijung1/controller-hardware-sdr/blob/main/images/assembled_pcb.png) |

**Performance:** ±1 kHz LO stability · 90° I/Q accuracy · Instant TX/RX switching


---

### **FPGA Nios® V Hearing Loss & Aid Simulator**  
[![GitHub Repo](https://img.shields.io/badge/Repo-fpga--niosv--hearing--simulator-181717?logo=github)](https://github.com/hyeonjijung1/fpga-niosv-hearing-simulator)  

> **Real-time DSP** simulating hearing loss & aid — live mic / stored audio, VGA UI, PS/2 controls.  
> Built on **DE1-SoC FPGA** with **Intel Nios® V soft processor**.  

| VGA UI Start Screen | Hearing Aid Screen | Block Diagram | Waveform Verification |
|---|---|---|---|
| ![UI Screenshot](https://github.com/hyeonjijung1/fpga-niosv-hearing-simulator/blob/main/images/UI-background.jpg) | ![DE1-SoC Board](https://github.com/hyeonjijung1/fpga-niosv-hearing-simulator/blob/main/images/aid-screen.png) | ![Final Block Diagram](https://github.com/hyeonjijung1/fpga-niosv-hearing-simulator/blob/main/images/final-bd.png) | ![Loss Waveforms](https://github.com/hyeonjijung1/fpga-niosv-hearing-simulator/blob/main/images/oscilloscope_latency_demo.png) |

**Performance:** 8 ms latency · 100 MHz (< 1 ns slack) · 12% LUT / 5% BRAM

---


### **LoRa Telemetry Module**  
[![GitHub Repo](https://img.shields.io/badge/Repo-BlueSky--LoRa--Radio-181717?logo=github)](https://github.com/hyeonjijung1/BlueSky-LoRa-Radio)

> **Led a 4-member team** designing a **high-reliability STM32WL LoRa telemetry system** for the Blue Sky Solar Racing car.  
> Developed **full system architecture**, **4-layer** RF PCB design for chase & solar car modules, and a Raspberry Pi gateway for real-time bidirectional data.

| Block Diagram | 3D Chase Car PCB | 3D Solar Car PCB | Top Layer – Chase Car PCB |
|---|---|---|---|
| ![Block Diagram](https://github.com/hyeonjijung1/BlueSky-LoRa-Radio/blob/main/docs/block-diagram-LoRa.png) | ![3D Chase Car PCB](https://github.com/hyeonjijung1/BlueSky-LoRa-Radio/blob/main/docs/3d-LoRa-chase-car.png) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Top Layer Chase Car PCB](https://github.com/hyeonjijung1/BlueSky-LoRa-Radio/blob/main/docs/TOP-plane.png) |

**Tech Stack:** `STM32WL` · `LoRa` · `Raspberry Pi` · `4-layer PCB Design` · `System Architecture` · `Embedded C`

---

### **FPGA Piano Audio System**  
[![GitHub Repo](https://img.shields.io/badge/Repo-fpga--piano--audio--system-181717?logo=github)](https://github.com/hyeonjijung1/fpga-piano-audio-system)  

**VGA-rendered piano** + **PS/2 keyboard input** + **real-time PWM audio** — all in synthesizable **Verilog**.  
Automated from **Quartus compile → ModelSim simulation** with Tcl & Bash.  

| VGA UI | Block Diagram | Demo Video | Waveform |
|---|---|---|---|
| ![VGA UI](https://github.com/hyeonjijung1/fpga-piano-audio-system/blob/main/docs/demo_photo.png) | ![Block Diagram](https://github.com/hyeonjijung1/fpga-piano-audio-system/blob/main/docs/block_diagram_piano.png) | [![Watch the demo](https://img.shields.io/badge/🎥%20Watch%20Demo-red?style=for-the-badge)](https://drive.google.com/file/d/1-k1kQWv2bcY4y-GO6ZJZvzP8-Z2Uc33Q/view?resourcekey) | ![Waveform Simulation](https://github.com/hyeonjijung1/fpga-piano-audio-system/blob/main/docs/waveform_epwave.png) |

*Figure: VGA-rendered piano system with PS/2 keyboard input, real-time audio output, and simulation waveform validation.*

**Performance:** 100 MHz timing closure · < 10 % LUT · < 5 % BRAM  
**Tech:** Verilog · VGA · PWM · PS/2 · Audio Codec · Tcl/Bash Automation


---

### **Linear Voltage Regulator PCB**  
[![GitHub Repo](https://img.shields.io/badge/Repo-linear--voltage--regulator--pcb-181717?logo=github)](https://github.com/hyeonjijung1/linear-voltage-regulator-pcb)  

> **Discrete analog regulator** from schematic capture to full lab validation — LTspice simulation, soldered PCB, and oscilloscope verification.  

| Schematic | LTspice Simulation | Assembled Board | Oscilloscope Validation |
|-----------|--------------------|-----------------|-------------------------|
| ![Schematic](https://github.com/hyeonjijung1/linear-voltage-regulator-pcb/blob/main/images/schematic.png) | ![LTspice](https://github.com/hyeonjijung1/linear-voltage-regulator-pcb/blob/main/images/figure-5.png) | ![Assembled Board](https://github.com/hyeonjijung1/linear-voltage-regulator-pcb/blob/main/images/pcb-final.jpg) | ![Oscilloscope](https://github.com/hyeonjijung1/linear-voltage-regulator-pcb/blob/main/images/osc-1.png) |

**Performance:** Stable DC output · Accurate simulation-to-lab correlation · Low-noise regulation

---

### **1st Place – Smart Energy Grid PCB for Yakutsk**  
[![GitHub Repo](https://img.shields.io/badge/Repo-sea--smart--grid--yakutsk--pcb-181717?logo=github)](https://github.com/hyeonjijung1/sea-smart-grid-yakutsk-pcb)  

> **Microcontroller-based smart grid PCB** for one of the coldest inhabited cities on Earth (Yakutsk, Russia).  
> Optimized for renewable integration, local resilience, and efficient power distribution in extreme −40 °C climates.  

| Poster |3D PCB Render |
|---|---|
| ![Poster](https://github.com/hyeonjijung1/sea-smart-grid-yakutsk-pcb/blob/main/docs/poster.png) | ![3D PCB](https://github.com/hyeonjijung1/sea-smart-grid-yakutsk-pcb/blob/main/images/header-3d.png) |

**Performance:** Industrial-grade reliability · Real-time grid monitoring · Automated load management

---

## 🔧 Tech Stack

**Hardware Design:**  
`Verilog / SystemVerilog` · `RISC-V Assembly` · `Quartus Prime` · `ModelSim` · `Icarus Verilog` · `EDA Playground`  

**Embedded & Firmware:**  
`Embedded C` · `C / C++` · `Python / Shell` · `Linux` · `Git`  

**Electronics & Tools:**  
`Altium Designer` · `LTspice` · `MATLAB / Simulink` · `UART / SPI / I²C`  
`PCB Design & Soldering` · `Oscilloscope & Multimeter` · `Arduino`

---

## 📊 GitHub Stats

<!-- Skills & Activity Summary -->
- **5+** custom PCBs designed (RF, analog, digital)
- **3+** FPGA/ASIC projects (RISC-V CPU, audio DSP, VGA UI)
- LoRa telemetry system for solar racing team (STM32WL)
- Analog & mixed-signal circuit design with full lab validation

---

<!-- Most Used Languages -->
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=hyeonjijung1&layout=compact&theme=radical)


---

## Leadership & Outreach

- **Frosh Leadership Training Coordinator** — Designed & delivered leadership modules for **550+ engineering students**  
- **VP Competitions, SEA** — Created case competition on sustainable cold storage for Indigenous communities in Canada  
- **Strategy & Operations Lead, Global Spark** — Scaled Hack the Globe to ~2,000 participants across 5 countries

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hyeonji%20Jung-blue?logo=linkedin)](https://www.linkedin.com/in/dianajung-uoft/)  
[![Email](https://img.shields.io/badge/Email-dianajunguoftece%40gmail.com-red?logo=gmail)](mailto:dianajunguoftece@gmail.com)



---

>"Engineering ideas into tested, working hardware."

