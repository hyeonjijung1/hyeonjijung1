#                                                                                       Hi there, I'm Hyeonji 👋

I design and build hardware from schematic capture to fully validated systems, bridging **analog, digital, and embedded domains**.  
My work includes **RF telemetry modules**, **RISC-V CPU cores**, **FPGA-based audio systems**, and **custom PCBs** tested and verified in the lab.  

Aside from engineering, I mentor **550+ Frosh Week leaders** to create an inclusive, welcoming experience for first-year students.

---

## 📂 Featured Projects

### **LoRa Telemetry Module**  
*(Repo: coming soon)*

> STM32WL-based LoRa transceiver for real-time solar car telemetry. Bidirectional data link between car and chase vehicle with Raspberry Pi gateway.

| Block Diagram | 3D PCB Render | Assembled Board | Field Test Setup |
|---------------|---------------|-----------------|------------------|
| ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) |

**Tech Stack:** `STM32WL` · `LoRa` · `Raspberry Pi` · `PCB design & RF testing`

---

### **SDR Controller Hardware**  
*(Repo: [controller-hardware-sdr](https://github.com/hyeonjijung1/controller-hardware-sdr))*

> ATmega324PB microcontroller + Si5351A frequency generation, UART CAT protocol, Python-based test automation, system integration and validation.

| 3D PCB Render | Block Diagram | Schematic | Assembled Hardware |
|---------------|--------------|-----------|--------------------|
| ![3D Render](https://github.com/hyeonjijung1/controller-hardware-sdr/blob/main/images/3D%20PCB%20render.png) | ![Block Diagram](https://github.com/hyeonjijung1/controller-hardware-sdr/blob/main/images/block_diagram_sdr.png) | ![Schematic](https://github.com/hyeonjijung1/controller-hardware-sdr/blob/main/images/original_schematic.png) | ![Assembled](https://github.com/hyeonjijung1/controller-hardware-sdr/blob/main/images/assembled_pcb.png) |

**Tech Stack:** `ATmega324PB` · `Si5351A` · `UART CAT` · `Python / Shell` (test automation) · `PCB layout & hardware debugging`

**Example: Python CAT Command Test**
```python
import serial

# Connect to SDR controller over UART
ser = serial.Serial("COM3", 9600, timeout=1)

# Send CAT command to enable TX
ser.write(b"TX;")
response = ser.readline().decode().strip()

print(f"Response: {response}")
ser.close()
```
Automated verification of UART CAT commands for SDR hardware bring-up.

---

### **RISC-V 5-Stage CPU Core**  
*(Repo: [riscv-pipeline-cpu](https://github.com/hyeonjijung1/riscv-pipeline-cpu))*

> Pipeline with hazard detection, forwarding, and branch handling. Verified in ModelSim with instruction/memory testbenches.

| Block Diagram | Waveform Simulation | FPGA Test Setup | Coming Soon |
|---------------|---------------------|-----------------|-------------|
| ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) |

**Tech Stack:** `Verilog` · `RISC-V Assembly` · `ModelSim` · `Quartus Prime`

---

### **FPGA Hearing Loss Simulator**  
*(Repo: [fpga-piano-audio-system](https://github.com/hyeonjijung1/fpga-piano-audio-system))*

> Real-time audio processing with volume, noise, and speech simulation + VGA UI. Designed for DE1-SoC with Verilog.

| VGA UI Output | DE1-SoC Hardware | Block Diagram | Coming Soon |
|---------------|------------------|---------------|-------------|
| ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) |

**Tech Stack:** `Verilog` · `Audio DSP` · `VGA` · `DE1-SoC FPGA`

---

### **Linear Voltage Regulator PCB**  
*(Repo: [linear-voltage-regulator-pcb](https://github.com/hyeonjijung1/linear-voltage-regulator-pcb))*

> Analog regulator from schematic capture to lab validation. Includes LTspice analysis, soldered PCB, oscilloscope verification.

| Schematic | 3D PCB Render | Assembled Board | Lab Validation |
|-----------|---------------|-----------------|----------------|
| ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) | ![Coming Soon](https://via.placeholder.com/300x200?text=Coming+Soon) |

**Tech Stack:** `Analog PCB` · `LTspice` · `Oscilloscope` · `Multimeter`

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

## 👥 Leadership & Outreach

- **Frosh Leadership Training Coordinator** — Designed & delivered leadership modules for **550+ engineering students**  
- **VP Competitions, SEA** — Created case competition on sustainable cold storage for Indigenous communities in Canada  
- **Strategy & Operations Lead, Global Spark** — Scaled Hack the Globe to ~2,000 participants across 5 countries

---

## 📫 Let's Connect
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Hyeonji%20Jung-blue?logo=linkedin)](https://www.linkedin.com/in/hyeonjijung)  
[![Email](https://img.shields.io/badge/Email-hyeonjijung1%40gmail.com-red?logo=gmail)](mailto:hyeonjijung1@gmail.com)

---

"Engineering ideas into tested, working hardware."
