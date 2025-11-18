This project implements a 32-bit Carry Lookahead Adder (CLA) using full custom VLSI design flow.
**INCLUDED ONLY SCHEMATIC FILES.
The adder is constructed hierarchically using:

1-bit Generate & Propagate (G/P) logic
4-bit CLA block
Final 32-bit CLA (made of Eight 4-bit CLAs)

**The design includes:
Transistor-level schematic of all blocks (G/P block, CLA block, full adder block)
Symbol creation for hierarchical design
Complete layout for each module using Siemens L-Edit
DRC clean layouts
LVS matched schematic ↔ layout
HSPICE simulation for functional verification
This demonstrates a practical full-custom digital design flow used in ASIC physical design.

**Objectives:
Implement a high-speed 32-bit CLA architecture
Minimize propagation delay using hierarchical carry-lookahead logic
Translate schematic to a DRC-clean and LVS-clean layout
Verify electrical behavior through HSPICE transient simulations

**Software & Tools Used:
*Siemens S-Edit
Schematic capture
Symbol creation
Transistor-level design

*Siemens L-Edit
Layout creation
DRC (Design Rule Check)
LVS (Layout vs Schematic)

*HSPICE
Simulation of schematic
Delay and waveform analysis

**Technology Used:
250 nm / 180 nm CMOS design rules (depending on setup)
NMOS/PMOS transistors sized based on reference inverter ratios
