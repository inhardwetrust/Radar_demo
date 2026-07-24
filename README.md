![Experimental radar system](img/00_header.png)

# Experimental Radar System

A Zynq-based experimental radar platform combining RF hardware, FPGA data acquisition, embedded firmware, high-speed data streaming, host-side processing, visualization, and field testing.

---

## 1. What This System Is

Lorem ipsum dolor sit amet, consectetur adipiscing elit. This section should briefly explain what kind of radar system this is, what subsystems it includes, and what the current prototype can already do.

Suggested topics to cover later:

- radar type and operating principle;
- overall hardware platform;
- antenna and RF chain;
- Zynq-based digital processing;
- host software and visualization;
- current prototype status.

---

## 2. What Problem It Solves

Lorem ipsum dolor sit amet, consectetur adipiscing elit. This section should explain the engineering goal of the project, the intended use case, and why a custom hardware and software architecture was required.

Suggested topics to cover later:

- target detection and range measurement;
- continuous acquisition during antenna rotation;
- synchronization of radar data with azimuth angle;
- high-throughput transfer to the host computer;
- real-time visualization and offline analysis;
- support for field testing and rapid experimentation.

---

## 3. My Contribution

Lorem ipsum dolor sit amet, consectetur adipiscing elit. This section should clearly separate personal engineering work from third-party hardware, existing IP cores, libraries, and other external components.

My responsibilities included:

- system architecture;
- RF subsystem integration;
- electronics and hardware bring-up;
- FPGA / PL logic development;
- Zynq PS firmware;
- DMA-based data acquisition;
- USB data streaming and custom communication protocol;
- motor and antenna-angle integration;
- Python host software;
- A-scope and B-scope visualization;
- data storage and processing pipelines;
- debugging, performance optimization, and field testing.

---

## 4. System Architecture

Lorem ipsum dolor sit amet, consectetur adipiscing elit. This section should present the full signal and control path from the antenna to the host software.

### Signal path

```text
Antenna
   ↓
Circulator / RF front end
   ↓
Receiver and ADC
   ↓
FPGA / Zynq PL
   ↓
DMA
   ↓
Zynq PS
   ↓
USB bulk streaming
   ↓
Python host software
   ↓
Capture / Storage / A-scope / B-scope / Processing
```

### Control path

```text
Python host software
   ↓
USB command interface
   ↓
Zynq PS firmware
   ↓
FPGA control / UART
   ↓
Motor drive / antenna angle / TX amplifier gating
```

---

## 5. Key Technical Characteristics

Lorem ipsum dolor sit amet, consectetur adipiscing elit. This section should summarize the most important measurable properties of the system.

| Parameter | Current value |
|---|---:|
| Processing platform | Xilinx Zynq |
| Acquisition architecture | FPGA / PL → DMA → PS |
| Host interface | USB bulk |
| Host software | Python |
| Visualization | A-scope, B-scope |
| Antenna operation | Motorized rotation |
| Angle synchronization | Integrated with acquisition pipeline |
| Data mode | Continuous streaming and single capture |
| Signal processing | Range-profile processing and visualization |
| Development status | Working experimental prototype |

---

## Project Media

Additional screenshots, hardware photographs, field-test images, and demonstration videos will be added as the project documentation is expanded.
