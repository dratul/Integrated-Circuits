# 221 - Practice problem 2 on active filters

## Navigation
- Previous: [220 - Practice problem 1 on active filters](./220-practice-problem-1-on-active-filters.md)
- Next: [222 - Second-order low pass filters](./222-second-order-low-pass-filters.md)
- Related topics: [220 - Practice problem 1 on active filters](220-practice-problem-1-on-active-filters.md), [222 - Second-order low pass filters](222-second-order-low-pass-filters.md), [201 - Op-Amp based V-I converters or transconductance amplifier or voltage dependent current source](201-op-amp-based-v-i-converters-or-transconductance-amplifier-or-voltage-dependent-current-source.md), [223 - Second-order high pass filters](223-second-order-high-pass-filters.md)

## Unit
Unit-II

## Overview
This topic focuses on practice problem 2 on active filters in integrated circuits. It is an important concept in analog circuit analysis and design because it connects device behavior with practical amplifier and signal-processing applications.

Students should understand the basic operating principle, the role of the circuit in the wider system, and the key parameters that affect performance such as gain, bandwidth, stability, linearity, and efficiency.

In practical engineering work, this topic helps explain how circuit blocks are designed, analyzed, and used for real applications in operational amplifiers, filters, oscillators, and digital logic.

Key points to remember include the physical meaning of the concept, the mathematical relationships involved, and the relationship between theory and circuit behavior in real ICs.

## Link
https://bietjhsacin-my.sharepoint.com/:b:/g/personal/akd_bietjhs_ac_in/Ee09T3VqtDFMvnQklE0aTHEBuDFtuQhIQ7d0bes43FN3xA?e=DQiYJE

## Notes
### Concept
This topic covers frequency-selective networks that pass or reject signals based on frequency. Filters are fundamental in analog signal conditioning, noise reduction, and signal shaping in communication and instrumentation systems.

### Working principle
- Classify the filter as first-order, second-order, passive, or active.
- Use frequency response to identify cutoff, passband, stopband, and Q-factor behavior.
- Relate filter topology to the required application such as noise removal or signal conditioning.

### Important points
- Cutoff frequency = 1/(2πRC) for first-order RC filters
- Filter order determines roll-off rate and selectivity
- Active filters provide gain and better drive capability compared with passive filters.

### Applications
- Noise suppression
- Audio processing
- Signal conditioning for ADCs

### Related circuits
- First-order RC low-pass filter
- First-order RC high-pass filter
- Second-order active low-pass filter
- Sallen-Key filter
- Multiple feedback filter

### Key equations
- First-order cutoff: fc = 1 / (2πRC)
- Second-order Q factor: Q = 1 / (3 - K) or as defined by topology
- Transfer function: H(s) = Vout / Vin
- Bandwidth and passband relation: BW = fH - fL

### Exam focus
- Explain the basic working principle using a circuit diagram or block diagram.
- List the important parameters and their significance.
- Solve numerical problems involving gain, frequency response, timing, or component values.
- Connect the concept to an engineering application in analog or digital electronics.
