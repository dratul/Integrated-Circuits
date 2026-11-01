# 510 - Phase locked loop (PLL): basic principle

- Previous: [509 - Ramp/triangle wave generator](./509-ramp-triangle-wave-generator.md)

## Definition 
A PLL continuously compares the phase of a generated signal with a reference and adjusts itself until both match. Once locked, the PLL tracks changes in the reference, keeping the output aligned. This makes PLLs essential for signal recovery, frequency synthesis, clock generation, Clock recovery, demodulation, and communication systems. Phase-locked loop is one of the most commonly used circuit in both telecommunication and measurement engineering. Depending on the operation
principle of loop components we distinguish Analog, Digital, Hybrid pll। 
A PLL is a feedback system that locks the phase of a VCO to an input reference. It consists of:
- Phase Detector
- Loop Filter
- Voltage-Controlled Oscillator

### Key equations
- calculate Phase error: φe = φref - φout
- Loop equation: Vcont ∝ phase error
- VCO frequency: fVCO = f0 + Kv * Vcontrol
- Lock condition: reference and feedback phases become equal

### Exam focus
- What is PLL. List the important parameters and their significance. What are its main applications.Connect the concept to an engineering application in analog or digital electronics.

  - Next: [511 - Block diagram and working of PLL](./511-block-diagram-and-working-of-pll.md)
 
  - - Related topics: [509 - Ramp/triangle wave generator](509-ramp-triangle-wave-generator.md), [511 - Block diagram and working of PLL](511-block-diagram-and-working-of-pll.md), [501 - Introduction to 555 timer IC](501-introduction-to-555-timer-ic.md), [512 - Ex-OR gates and multipliers as phase detectors](512-ex-or-gates-and-multipliers-as-phase-detectors.md)
