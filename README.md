# Custom CPU Architecture in Logisim

This repository contains the design and simulation of **two custom computer architectures** built using **Logisim**.
The project focuses on understanding how a processor works internally — from basic data paths to microprogrammed control units.

The CPUs were designed as part of an academic project to explore **instruction execution, control logic, and CPU organization** at a low level.

---

## Project Overview

### Computer-1 (Hardwired Control CPU)

Computer-1 is a basic CPU built by integrating core digital components:

* Arithmetic Logic Unit (ALU)
* Registers
* Control Unit
* Memory

The architecture simulates the full **fetch–decode–execute cycle** using logic gates, multiplexers, and flip-flops.
This design helped in understanding how instructions move through the processor and how control signals are generated.

---

### Computer-2 (Microprogrammed Control CPU)

Computer-2 is an advanced version that uses a **microprogrammed control unit**.
Instead of hardwired control, instruction execution is driven by **microcode** stored in control memory.

Key additions include:

* Control Memory
* Control Address Register
* Sequencer
* Microinstruction Decoder

This architecture supports more modular and scalable instruction execution.

---

## Instruction Set

Both CPUs support a small, custom assembly-like instruction set, including:

* `LDA` – Load Accumulator
* `STA` – Store Accumulator
* `JMP` – Jump

Control signal patterns were carefully designed and implemented using **microinstructions** (for Computer-2).

---

## Files in this Repository

* `.circ` files — Logisim circuit files for Computer-1 and Computer-2
* Microcode/control logic files used for instruction execution
* Supporting design files and documentation

(Open the `.circ` files directly in Logisim to view and simulate the CPUs.)

---

## Tools Used

* **Logisim / Logisim Evolution**
* Digital logic components (gates, multiplexers, flip-flops)
* Microprogrammed control concepts

---

## Results & Evaluation

* **Computer-1**: Awarded **A grade**
* **Computer-2**: Received **commendation** for architectural advancement and depth of control logic

---

## How to Run

1. Install **Logisim** or **Logisim Evolution**.
2. Clone or download this repository.
3. Open the `.circ` files in Logisim.
4. Load instructions into memory and simulate the CPU step-by-step.

---

## Learning Outcomes

* Hands-on understanding of CPU datapaths and control units
* Practical exposure to microprogrammed control logic
* Experience designing instruction sets and execution logic
* Deeper insight into how real processors work internally

---

## License

This project is for educational purposes.
You may reuse or modify it for learning or academic use.
