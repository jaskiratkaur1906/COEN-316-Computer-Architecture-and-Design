# COEN 316 – Computer Architecture & Design Labs

## Project Overview
This repository contains the lab work for **COEN 316: Computer Architecture & Design** at Concordia University.  
The labs focus on the design and implementation of CPU components using VHDL, simulation in ModelSim, and FPGA deployment on the Nexys A7 board.

The progression moves from designing individual components (ALU, Register File) to integrating them into a simple CPU, demonstrating the fundamentals of digital system design.

---

## Lab Summaries

### **Lab 1 – Arithmetic Logic Unit (ALU) Design**
- Designed a 32-bit ALU in VHDL capable of performing arithmetic and logical operations.
- Simulated the design in ModelSim to verify correctness.
- Prepared the ALU for integration into a CPU in later labs.

### **Lab 2 – 32-bit Register File**
- Implemented a **32-register, 32-bit register file** in VHDL.
- Supported independent read ports and a synchronous write port with control signals.
- Verified functionality using `.do` simulation scripts in ModelSim.
- Deployed design to the Nexys A7 FPGA using Vivado.

### **Lab 3 – CPU Integration**
- Integrated the ALU and Register File into a basic CPU architecture.
- Implemented control logic to execute a subset of CPU instructions.
- Simulated the integrated CPU and tested it on FPGA hardware.

### **Lab 4 – Memory & I/O Integration**
- Expanded the CPU design to interact with memory and I/O devices.
- Implemented memory-mapped I/O for reading/writing data.
- Simulated and tested the extended system on FPGA.

---

## Goals & Key Learnings

| Lab | Goals | Key Learnings |
|-----|-------|--------------|
| **Lab 1** | Learn ALU design and simulation | VHDL coding, ModelSim simulation |
| **Lab 2** | Implement a register file for CPU use | Memory-mapped I/O, synchronous logic design |
| **Lab 3** | Integrate CPU components | Control unit design, multi-module integration |
| **Lab 4** | Implement memory and I/O interaction | Address decoding, FPGA testing |

---

## Setup Instructions

### Prerequisites
- **Xilinx Vivado** (for synthesis & FPGA programming)
- **ModelSim** (for simulation)
- **Nexys A7 FPGA board**

---

## How to Run

### FPGA-based Labs
1. Open the VHDL project in Vivado.
2. Run simulations in ModelSim.
3. Synthesize and implement the design.
4. Generate bitstream and program the FPGA.

---

## License
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.
