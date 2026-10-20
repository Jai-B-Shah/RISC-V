# RISC-V Workshop Reference Material

This repository holds reference documentation collected during a workshop on RISC-V processors. It is study material rather than an original design or independent project: block diagrams, a chip pinout/signal reference, and a demonstration-board circuit sketch for a RISC-V system-on-chip (the "Raven" RISC-V SoC), used to understand how a RISC-V core is laid out at the chip and board level — core logic, SRAM, SPI/UART peripherals, GPIO banking, analog I/O (ADC/DAC/comparator), and the supporting board-level circuitry (power regulation, clock sources, USB-to-serial programming interface).

## Skills & Tools Demonstrated

- Exposure to RISC-V processor architecture and instruction-set fundamentals
- Reading and interpreting chip-level block diagrams and pinout references
- Understanding of SoC peripheral integration: SRAM, SPI, UART, GPIO, ADC/DAC, and analog comparators
- Familiarity with board-level circuit design concepts: voltage regulation, clock distribution, and USB-based programming interfaces

## What This Repository Contains

- A block diagram of a RISC-V (RV32I) SoC core and its on-chip peripherals
- A demonstration board block diagram showing how the chip connects to power, clock, USB programming, and a Raspberry Pi-compatible GPIO header
- A preliminary circuit board sketch showing the chip, flash memory, USB-serial interface, and supporting components

## Repository Structure

- `Reference_Material/` — workshop reference diagrams and circuit sketches (PNG, PDF, and PostScript formats)

## Author

**Jai B Shah**
Reference material compiled from a Workshop on RISC-V VEGA Processors.
