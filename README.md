<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Logic Design</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  Flip Flops
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.researchgate.net/profile/Eleni-Tsalera-2" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, June 2021
</p>

---

# Project Overview

This repository contains the documentation and circuit simulations for **Workshop 3** of the **Digital Design** course at the **University of West Attica**. The project focuses on the **operation and implementation of sequential logic circuits**, specifically latches and flip-flops.

---

## Table of Contents

| Section | Folder/File | Description |
|------:|-------------|-------------|
| 1 | `assign/` | Assignment material for the Flip-Flops workshop |
| 1.1 | `assign/ASSIGNMENT 3.pdf` | Assignment description in English |
| 1.2 | `assign/ΕΡΓΑΣΙΑ 3.pdf` | Assignment description in Greek |
| 2 | `docs/` | Documentation covering flip-flops theory and memory states |
| 2.1 | `docs/Flip-Flops.pdf` | English documentation for flip-flops |
| 2.2 | `docs/Κατάσταση-Μνήμης.pdf` | Greek documentation for flip-flops and memory states |
| 3 | `multisim/` | Multisim flip-flop and counter simulation files |
| 3.1 | `multisim/D-Flip-Flop.ms14` | D Flip-Flop circuit simulation |
| 3.2 | `multisim/RS-Flip-Flop.ms14` | RS Flip-Flop circuit simulation |
| 3.3 | `multisim/counter.ms14` | Counter circuit simulation |
| 3.4 | `multisim/pentagon-with-NAND.ms14` | Pentagon sequence generator using NAND gates |
| 4 | `README.md` | Repository overview and usage instructions |

---

## Project Overview

The objective of this workshop is to explore the **fundamental behavior of sequential circuits** through theoretical analysis and software simulation.

### Key Topics Covered

- **Latches:** NAND and NOR gate implementations  
- **Flip-Flops:** RS, D, JK, T, and Master-Slave configurations  
- **Operational Features:** Excitation tables, asynchronous inputs, and clock triggering  

---

## Technical Specifications

### Simulation Tools
- NI Multisim for circuit design, simulation, and testing  

### Components Used
- **Logic Gates:** AND, OR, NOR, NAND, XOR, XNOR, NOT  
- **Hardware Elements:** VCC sources (5V), ground, cables, switches  
- **Monitoring Tools:** Logic lamps and oscilloscopes for signal visualization  

---

## Exercises and Results

### 1. NAND Gate Latch (Exercise 5.2.1)

Analyzes the truth table of a **basic cross-coupled NAND gate latch**.

| S | R | Q | NOT_Q | Result Description |
|---|---|---|-------|------------------|
| 0 | 0 | 0 | 1 | Theoretical State |
| 1 | 0 | 1 | 1 | Invalid / Prohibited |
| 0 | 1 | 0 | 1 | Reset State |
| 1 | 1 | 1 | 0 | Set State |

---

### 2. RS Flip-Flop (Exercise 5.2.2)

Analysis of a **clocked RS Flip-Flop** implementation.

| S | R | Q | NOT_Q |
|---|---|---|-------|
| 0 | 0 | 1 | 0 |
| 1 | 0 | ? | ? |
| 0 | 1 | 1 | 1 |
| 1 | 1 | 0 | 1 |

> **Note:** Detailed simulation captures for each input combination (S=0/R=0, S=1/R=0, etc.) are included in the documentation.

---

## Conclusion

Workshop 3 emphasizes the behavior and design of **sequential circuits**, building a foundation for memory elements in digital systems and demonstrating how **flip-flops** can store and manipulate binary information reliably.

---

# Installation & Setup Guide

This repository contains **Workshop 3 – Flip-Flops** simulations and documentation for the **Digital Design** course at the **University of West Attica**. The focus is on **sequential circuits**, including latches, flip-flops, and counters.

All simulations are implemented using **NI Multisim**.

---

## Prerequisites

### Required Software
- **NI Multisim 14** or later  
  Required to open and run `.ms14` simulation files.

Download:  
https://www.ni.com/en-us/shop/electronic-test-instrumentation/application-software-for-electronic-test-and-instrumentation-category/what-is-multisim.html

---

### Optional Software
- **PDF Viewer** to open documentation files (`Flip-Flops.pdf`, `Κατάσταση-Μνήμης.pdf`)  
- **Git** for cloning the repository

---

## Installation Steps

### 1. Clone the Repository

Clone using Git:

```bash
git clone https://github.com/Logic-Design-aka-Uniwa/Flip-Flops.git
```

Or download the project as a ZIP file and extract it manually.

### 2. Navigate to Project Directory
```bash
cd Flip-Flops
```
Ensure the following folder structure exists:
```bash
assign/
docs/
multisim/
README.md
```

--- 

## Multisim Simulation Files
The repository includes simulation files for the main arithmetic circuits:

| File | Description |
|------|-------------|
| `multisim/D-Flip-Flop.ms14` | D Flip-Flop simulation |
| `multisim/RS-Flip-Flop.ms14` |	RS Flip-Flop simulation |
| `multisim/counter.ms14` |	Counter circuit simulation | 
| `multisim/pentagon-with-NAND.ms14` |	Pentagon sequence generator using NAND gates |

These circuits cover sequential behavior, memory storage, and clocked operation.

### 3. Open a Simulation in Multisim
1. Launch **NI Multisim**.
2. Select **File** → **Open**.
3. Navigate to the repository folder.
4. Open the `multisim/` directory.
5. Select a `.ms14` file.
6. Wait for the circuit to load.
7. Run the simulation using the Run button.

---

## Open the Documentation
1. Navigate to the `docs/` folder.
2. Open the preferred documentation:

| Language | File |
|----------|------|
| English | `docs/Flip-Flops.pdf` |
| Greek | `docs/Κατάσταση-Μνήμης.pdf` |

The documentation includes:
- Circuit theory and memory states
- Flip-flop operation tables (RS, D, JK, T, Master-Slave)
- Excitation and truth tables
- Multisim implementation and screenshots