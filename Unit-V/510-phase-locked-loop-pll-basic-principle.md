# 510 - Phase locked loop (PLL): basic principle

## Navigation
- Previous: [509 - Ramp/triangle wave generator](./509-ramp-triangle-wave-generator.md)
- Next: [511 - Block diagram and working of PLL](./511-block-diagram-and-working-of-pll.md)
- Related topics: [509 - Ramp/triangle wave generator](509-ramp-triangle-wave-generator.md), [511 - Block diagram and working of PLL](511-block-diagram-and-working-of-pll.md), [501 - Introduction to 555 timer IC](501-introduction-to-555-timer-ic.md), [512 - Ex-OR gates and multipliers as phase detectors](512-ex-or-gates-and-multipliers-as-phase-detectors.md)

## Unit
Unit-V

## Overview
A PLL continuously compares the phase of a generated signal with a reference and adjusts itself until both match. Once locked, the PLL tracks changes in the reference, keeping the output aligned. This makes PLLs essential for frequency synthesis, clock generation, demodulation, and communication systems.

Phase-locked loop is one of the most commonly used circuit in both
telecommunication and measurement engineering. Depending on the operation
principle of loop components we distinguish
* Analog
* Digital
* Hybrid

A PLL is a feedback system that locks the phase of a VCO to an input reference.
It consists of:
- Phase Detector
- Loop Filter
- Voltage-Controlled Oscillator

### Applications
- Clock recovery
- Frequency synthesis
- FM demodulation


## Notes
### Concept
A phase-locked loop synchronizes the output signal with a reference signal by comparing phase and frequency. PLLs are essential in communication, signal recovery, frequency synthesis, and clock generation.

### Working principle
- Compare the reference and feedback phases using a phase detector.
- Use the loop filter to stabilize the control signal.
- Explain how PLLs lock frequency and phase in communication systems.

### Important points
- Phase detector output is proportional to phase error
- Low-pass loop filter reduces noise and sets stability
- VCO frequency locks to the reference signal when the loop is stable.

### Applications
- FM demodulation
- Clock recovery
- Frequency synthesis

### Key equations
- Phase error: φe = φref - φout
- Loop equation: Vcont ∝ phase error
- VCO frequency: fVCO = f0 + Kv * Vcontrol
- Lock condition: reference and feedback phases become equal

### Exam focus
- Explain the basic working principle using a circuit diagram or block diagram.
- List the important parameters and their significance.
- Solve numerical problems involving gain, frequency response, timing, or component values.
- Connect the concept to an engineering application in analog or digital electronics.
