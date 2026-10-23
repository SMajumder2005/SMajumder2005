# Souhardya Majumder | Digital VLSI, RTL Design & Hardware Engineering

**B.Tech, Electronics & Communication Engineering | NIT Durgapur (2022–2026) | CGPA 8.41/10**

Hi, I'm Souhardya. I'm an ECE graduate from NIT Durgapur interested in digital hardware design, RTL development, functional verification and FPGA-based systems. My work so far spans Verilog-based design, processor architecture, AMBA bus protocols, FPGA development and the RTL-to-GDS-II flow, through internships at **C-DOT** and **Maven Silicon**, training at **NIELIT**, and self-paced projects.

I'm looking for entry-level opportunities in **Digital VLSI, RTL Design, Design Verification and FPGA / semiconductor hardware engineering**.

📧 souhardya2005aps@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/souhardya-majumder-431231251/) · 📍 New Delhi, India

---

## 🎯 Technical Focus

- **Digital RTL Design:** combinational and sequential logic, FSMs, datapaths and control logic
- **Design Verification:** RTL simulation, Verilog testbenches, functional verification, hardware debugging
- **FPGA Development:** FPGA-based digital systems, timestamp acquisition, host interfacing (AXI DMA)
- **Computer Architecture:** processor datapaths, instruction fetch/decode, ALU, register files
- **SoC Interconnects:** AMBA APB/AHB protocols and bus-bridge design
- **Digital VLSI:** CMOS fundamentals and the RTL-to-GDS-II design flow

## 🛠️ Skills

| Area | Skills & Tools |
|---|---|
| HDL | Verilog, SystemVerilog |
| Programming | Python, C, C++ |
| Digital Design | RTL design, FSMs, datapath and control logic |
| Verification | RTL simulation, Verilog testbenches, functional verification, hardware debugging |
| Protocols | AMBA APB / AHB |
| FPGA | Xilinx Vivado |
| VLSI Flow & EDA | Cadence Virtuoso, Yosys, OpenROAD, OpenSTA, Magic |
| Other Tools | MATLAB, Simulink, Linux |

*Currently deepening SystemVerilog, verification methodology and the digital implementation flow.*

---

## 🚀 Projects

| # | Project | Context | Repository |
|---|---|---|---|
| 1 | FPGA-based Time-to-Digital Converter for Single-Photon OTDR | C-DOT (Govt. of India) Internship, Delhi · May–Jul 2025 | [OTDR-TDC-RTL](https://github.com/SMajumder2005/OTDR-TDC-RTL) |
| 2 | APB–AHB Bridge using Verilog | Maven Silicon Internship · May–Jun 2024 | _To be added_ |
| 3 | RISC-V Processor in Verilog | Self-paced course project | [RISC-V-Verilog](https://github.com/SMajumder2005/RISC-V-Verilog) |
| 4 | AI-inspired Traffic Signal Controller (Verilog HDL & FSM) | ElevanceSkills online project | _To be added_ ([project page](https://www.elevanceskills.com/projects/ai-based-traffic-signal-controller-using-vlsi)) |

### 1. FPGA-Based Time-to-Digital Converter for Single-Photon OTDR
**C-DOT (Govt. of India) Internship, Delhi | May–July 2025** · FPGA Design · RTL Development · Digital Measurement

Designed and implemented a Time-to-Digital Converter (TDC) on FPGA for photon-level detection of optical backscattered signals in an OTDR-like system.

- Developed signal-processing logic to compute distances from timestamp data
- Interfaced the FPGA with a host PC using AXI DMA for real-time timestamp acquisition and analysis
- Worked on detection accuracy and resolution of photon events for fibre characterisation
- Performed functional verification of FPGA modules through simulation and hardware testing
- Gained experience in RTL verification, timing-analysis concepts and hardware debugging

🔗 **Repository:** [OTDR-TDC-RTL](https://github.com/SMajumder2005/OTDR-TDC-RTL)

---

### 2. APB–AHB Bridge Using Verilog
**Maven Silicon Internship | May–June 2024** · RTL Design · AMBA Protocols · Functional Verification

Designed and implemented an AMBA-compliant APB–AHB bridge enabling communication between the high-performance AHB bus and the low-power APB peripheral bus.

- Developed control logic for address decoding, handshaking and data transfer between the two protocols
- Verified correct data transfer using Verilog testbenches
- Gained hands-on exposure to the VLSI design and verification flow: RTL design, simulation and debugging

🔗 **Repository:** _To be added once the source is ready to share._

---

### 3. RISC-V Processor in Verilog
**Self-paced course project** · Digital Design · Processor Architecture · RTL Simulation

A modular RISC-V processor core in Verilog HDL covering fetch, decode, execute and write-back, built to understand pipelining and control-logic concepts.

**Repository contents:**

| Module | Purpose |
|---|---|
| `instruction_fetch_unit.v` | Program counter and branch/jump flow |
| `INSTRUCTION_MEMORY.v` | Predefined instruction sequence |
| `control_unit.v` | Instruction decoding and control-signal generation |
| `register_file.v` | Register bank and access logic |
| `imm_gen.v` | Immediate extraction |
| `alu.v` | Arithmetic, logic, shift and comparison operations |
| `data_memory.v` | Load/store data storage |
| `data_path.v` | Connects register file, ALU, data memory and branch logic |
| `top_riscv.v` | Top-level integration |
| `top_tb.v` | Testbench (clock and reset generation) |

**Instructions exercised in the source:** R-type (ADD, SUB, SLL, XOR, SRL, SRA, OR, AND), I-type (ADDI, SLLI, SLTI, SRLI, ORI, ANDI), load/store, branches (BEQ, BNE, BGE), LUI and JAL.

**To simulate (Xilinx Vivado):** add the `.v` files as design sources, add `top_tb.v` as the simulation source, set `top_tb` as the top module and run behavioural simulation.

🔗 **Repository:** [RISC-V-Verilog](https://github.com/SMajumder2005/RISC-V-Verilog)

---

### 4. AI-inspired Traffic Signal Controller using Verilog HDL and FSM
**ElevanceSkills online project** · Digital Design · Finite State Machines · RTL Simulation

Designed an AI-inspired traffic signal controller in Verilog HDL using Finite State Machines, with state-transition and signal-timing logic verified through RTL simulation using Verilog testbenches.

🔗 **Project page:** [ElevanceSkills](https://www.elevanceskills.com/projects/ai-based-traffic-signal-controller-using-vlsi)
🔗 **Repository:** _To be added once the source is uploaded._

---

## 🎓 Education

**National Institute of Technology Durgapur** — B.Tech, Electronics & Communication Engineering (2022–2026)

- CGPA: **8.41 / 10**
- GATE 2026 (ECE): **Score 625 · Percentile 98.35 · AIR 1577**
- PGEE 2026: **Rank 13**

**Relevant coursework:** Digital Electronics, Digital System Design, Computer Architecture, Microprocessors & Microcontrollers, VLSI Design Fundamentals, Analog IC Design, CMOS Fundamentals

## 🏢 Internships & Training

- **NIELIT Noida:** VLSI Design Flow (RTL to GDS-II) · Apr–May 2026
- **C-DOT (Govt. of India), Delhi:** FPGA-based TDC for Single-Photon OTDR · Jun–Jul 2025
- **Maven Silicon:** APB–AHB bridge in Verilog · May–Jun 2024
- **NIELIT Calicut:** VLSI for Beginners · Dec 2023; MATLAB & Simulink · Jan 2024
- **Udemy:** CMOS Digital VLSI for Beginners · Oct 2023
- **IIT Guwahati & TIDF:** AI & ML Training Program · Jun 2023

## 🔬 What I'm Working Towards

- SystemVerilog-based design verification, constrained-random testing and functional coverage
- Universal Verification Methodology (UVM)
- Synthesis, timing constraints and static timing analysis
- Well-documented projects with reproducible simulation steps and results

These are learning goals, not a claim of equal proficiency in every area.

---

## 🤝 Connect

- **GitHub:** [SMajumder2005](https://github.com/SMajumder2005)
- **LinkedIn:** [Souhardya Majumder](https://www.linkedin.com/in/souhardya-majumder-431231251/)
- **Email:** souhardya2005aps@gmail.com

I welcome opportunities to learn and contribute to digital hardware design, verification and semiconductor engineering.
