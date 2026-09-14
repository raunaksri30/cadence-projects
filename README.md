This repository documents the implementation and verification of fundamental CMOS digital circuits designed using **Cadence Virtuoso** with **GPDK 90nm** and **GPDK 45nm** process technologies. Each design follows the complete custom IC design flow from schematic capture to post-layout verification.

## Design Flow

For every circuit, the following stages have been completed:

- Schematic Design
- Functional Simulation
- Physical Layout Design
- Design Rule Check (DRC)
- Layout Versus Schematic (LVS)
- Parasitic Extraction (Extracted View)
- Post-Layout Simulation

## Implemented Digital Circuits

### Basic Logic Gates
- CMOS Inverter (NOT Gate)
- NAND Gate
- NOR Gate
- AND Gate
- OR Gate
- XOR Gate
- XNOR Gate

### Multiplexers
- 2:1 Multiplexer
- 4:1 Multiplexer

### Encoders & Decoders
- 2:4 Decoder
- Priority Encoder

### Sequential Circuits
- SR Flip-Flop
- D Flip-Flop
- JK Flip-Flop
- T Flip-Flop

## Technology Stack

- **EDA Tool:** Cadence Virtuoso
- **Simulator:** Spectre
- **Technology Nodes:** GPDK 90nm, GPDK 45nm

## Verification Summary

Each circuit includes:

- ✔ Schematic Implementation
- ✔ Functional Verification
- ✔ Layout Design
- ✔ DRC Clean Layout
- ✔ LVS Matched Design
- ✔ Extracted View (Parasitic RC Extraction)
- ✔ Post-Layout Simulation

## Ongoing Work

### Advanced Peripheral Bus (APB) Protocol

Current work focuses on the transistor-level implementation of the **AMBA APB Protocol**, including hierarchical module development, simulation, physical layout, DRC/LVS verification, parasitic extraction, and post-layout validation.

---

**Design Methodology:** Custom CMOS VLSI Design  
**Technology:** 90nm & 45nm CMOS  
**Verification Flow:** Schematic → Simulation → Layout → DRC → LVS → Extraction → Post-Layout Simulation
