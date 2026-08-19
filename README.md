# 100 MHz FM Transmitter

## Overview

This repository contains the design and simulation files for a **100 MHz FM transmitter**, including the transmitter circuit, PCB design, manufacturing files, and a dedicated 100 MHz antenna design.

The project covers the workflow from **circuit simulation and PCB design to antenna modeling**.

For detailed technical specifications, design methodology, calculations, and simulation results, refer to the **[FM Radio Transmitter.pdf](FM%20Radio%20Transmitter.pdf)** included in this repository.

---

## Repository Structure

The repository is organized into the following sections:

- **Antenna/** — Contains the 100 MHz antenna model.
- **Transmitter/** — Contains the LTspice transmitter circuit and KiCad PCB design files.
- **FM Radio Transmitter.pdf** — Contains the detailed technical documentation and simulation results.
- **README.md** — Provides an overview and guide to the repository.

---

## Antenna

The `Antenna/` folder contains the antenna model designed specifically for operation at **100 MHz**.

### File

`FM Antenna.maa`

The `.maa` file can be opened using **MMANA-GAL** to inspect and simulate the antenna design.

**Software:** MMANA-GAL

---

## Transmitter

The `Transmitter/` folder contains the transmitter circuit and PCB design files.

### LTspice Circuit

The `Circuit .asc` file contains the transmitter schematic and can be opened using **LTspice** to inspect the circuit and reproduce the simulation.

**Software:** LTspice

### KiCad Files

The `KiCad/` folder contains the schematic, PCB layout, and manufacturing files.

- `RF Transmitter.kicad_sch` — KiCad schematic
- `RF Transmitter.kicad_pcb` — PCB layout
- `Gerber.zip` — Gerber files prepared for PCB fabrication

**Software:** KiCad

---

## Documentation

The `FM Radio Transmitter.pdf` contains the detailed technical documentation of the project, including the design, calculations, circuit analysis, simulation results, and antenna analysis.

For complete technical details, refer to the **[FM Radio Transmitter.pdf](FM%20Radio%20Transmitter.pdf)**.

---

## Software Used

| Software | Purpose |
|---|---|
| **LTspice** | Transmitter circuit design and simulation |
| **KiCad** | Schematic and PCB design |
| **MMANA-GAL** | 100 MHz antenna modeling and simulation |

---

## How to Explore the Repository

- To inspect the **transmitter circuit**, open the `.asc` file using LTspice.
- To inspect the **PCB schematic**, open the `.kicad_sch` file using KiCad.
- To inspect the **PCB layout**, open the `.kicad_pcb` file using KiCad.
- To fabricate the PCB, use the **Gerber.zip** manufacturing files.
- To inspect the **100 MHz antenna**, open the `.maa` file using MMANA-GAL.
- For detailed technical specifications, calculations, and simulation results, refer to the **FM Radio Transmitter PDF**.
