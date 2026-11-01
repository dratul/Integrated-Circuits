# Integrated Circuits (BEC-501)

This repository contains AKTU-aligned study material, lecture references, lab work, and tutorial resources for Integrated Circuits.

- Course Code: BEC-501
- Credits: 4
- L-T-P: 3L:1T:0P
- Syllabus Source: [25_07_syllabus.pdf](./25_07_syllabus.pdf)
- YouTube Playlist: [Integrated Circuits Playlist](https://www.youtube.com/watch?v=ov1TF34Wnpw&list=PLKy7tXMLcgM3aUpBq_02YGHKkookFxZNO)

## Course Outcomes
At the end of this course students will demonstrate the ability to:

1. Explain complete internal analysis of Op-Amp 741-IC.
2. Examine and design Op-Amp based circuits and basic components of ICs such as various types of filters.
3. Implement the concept of Op-Amp to design Op-Amp based non-linear applications.
4. Analyse and design basic digital IC circuits using CMOS technology.
5. Describe the functioning of application specific ICs such as 555 timer, PWM and ramp generators.

## Syllabus

### Unit I: The 741 IC Op-Amp
The 741 IC Op-Amp: Introduction to integrated circuits, types of integrated circuits, device parameters (properties of Opamp), slew rate, relationship between frequency and slew rate, gain, frequency response of 741, a simplified equivalent model of opamp, inverting amplifier, non-inverting amplifier, and basic applications of Op-Amp.

### Unit II: Linear Applications of IC Op-Amps and Active Analog Filters
Linear applications of IC Op-Amps:
- Op-Amp based V-I and I-V converters
- Instrumentation amplifier
- Generalized impedance converter
- Simulation of inductors

Active analog filters:
- First order active filters
- Low pass and high pass filter design
- Practical low pass filter design
- Second order filters and implementation topologies
- Designing of second order lowpass and high pass Butterworth filter
- Introduction to band pass and band stop filters
- All pass active filters
- Sallen Key second order filter
- KHN filters
- Introduction to higher order filter design

### Unit III: Non-Linear Applications of IC Op-Amps
Non-linear applications of IC Op-Amps:
- Basic Log-Anti Log amplifiers using diode and BJT
- Temperature compensated Log-Anti Log amplifiers using diode
- Analog multiplier circuit design using log amplifier
- Analog divider circuit design using log amplifier
- Peak detectors
- Sample and hold circuits
- Op-amp as a comparator and zero crossing detector
- Schmitt triggers and hysteresis voltage/current
- Astable and monostable multivibrator
- Generation of square and triangular waveforms
- Frequency of generated triangular waveform

### Unit IV: Digital Integrated Circuit Design
Digital Integrated Circuit Design: an overview of digital integrated circuits, basic logic generation in ICs, CMOS logic gate circuit’s basic structure, CMOS realization of inverters, AND, OR, NAND and NOR gates.

Latches and Flip flops:
- The latch
- CMOS implementation of SR flip-flops
- Simpler CMOS implementation of the clocked SR flip-flop
- CMOS implementation of J-K flip-flops
- D flip-flop circuits

### Unit V: Integrated Circuit Timer and Applications
Integrated Circuit Timer: Introduction to 555 Timer IC, timer IC 555 pin and functional block diagram, internal architecture, operating modes of 555 Timer, monostable and astable multivibrator using the 555 IC, bistable multivibrator using IC 555.

Applications:
- Pulse Width Modulation (PWM) with 555
- Ramp/triangle wave generator

## Text Books
1. Microelectronic Circuits, Sedra and Smith, 7th Edition, Oxford, 2017.
2. Behzad Razavi: Design of Analog CMOS Integrated Circuits, TMH.

## Reference Books
1. Gayakwad: Op-Amps and Linear Integrated Circuits, 4th Edition, Prentice Hall of India, 2002.
2. Franco, Analog Circuit Design: Discrete & Integrated, TMH, 1st Edition.
3. Salivahnan, Electronics Devices and Circuits, TMH, 3rd Edition, 2015.
4. Millman and Halkias: Integrated Electronics, TMH, 2nd Edition, 2010.

## Repository Resources

### Notes and PDFs
- [25_07_syllabus.pdf](./25_07_syllabus.pdf)
- [106_Notes_equivalent_model_of_opamp.pdf](./106_Notes_equivalent_model_of_opamp.pdf)
- [Tutorial_Assignment_01.pdf](./Tutorial_Assignment_01.pdf)
- [log amplifier temperature compansated.pdf](./log%20amplifier%20temperature%20compansated.pdf)

### Lecture and tutorial links
- [YouTube Playlist](https://www.youtube.com/watch?v=ov1TF34Wnpw&list=PLKy7tXMLcgM3aUpBq_02YGHKkookFxZNO)
- [Equivalent model of op-amp notes](./106_Notes_equivalent_model_of_opamp.pdf)
- [Tutorial Assignment 01](./Tutorial_Assignment_01.pdf)

# Integrated Circuits Lab (BEC-551)

## Experiment List
1. Design the following using Op-Amp (through Virtual Lab):
   - Unity gain amplifier
   - Inverting amplifier with gain A
   - Non-inverting amplifier with gain A
2. Study and design Log and Antilog amplifiers.
3. Voltage-to-current and current-to-voltage converters.
4. Second order filters using operational amplifier for:
   - Low pass filter of cutoff frequency 1 kHz
   - High pass filter of frequency 12 kHz
5. Realization of band pass filter with unit gain of pass band from 1 kHz to 12 kHz.
6. Study and design voltage comparator and zero crossing detectors.
7. Function generator using operational amplifier (sine, triangular, and square wave).
8. Design and construct astable multivibrator using IC 555 and:
   - Plot output waveform
   - Measure frequency of oscillation
9. Design and construct monostable multivibrator using IC 555 and:
   - Plot output waveform
   - Measure time delay
10. Implement Schmitt Trigger circuit using IC 555.
11. Implement voltage-controlled oscillator using IC 566 and plot the waveform.
12. Study and design ramp generator using IC 566.

### Virtual Lab Links
1. [IIT Kharagpur Virtual Lab](http://vlabs.iitkgp.ernet.in/be/exp17/index.html)
2. [Monostable-Astable Oscillator Lab](https://he-coep.vlabs.ac.in/exp/monostable-astable-oscillator/)
3. [Tinkercad](https://www.tinkercad.com/joinclass/GJKQXTTE3)

### Lab Course Outcomes
At the end of this course students will demonstrate the ability to:

1. Design different non-linear applications of operational amplifiers such as log, antilog amplifiers and voltage comparators.
2. Explain and design different linear applications of operational amplifiers such as filters.
3. Demonstrate the function of waveform generators using op-amp.
4. Construct multivibrator and oscillator circuits using IC 555 and IC 566 and perform measurements of frequency and time.
5. Design and practically demonstrate the applications based on IC 555 and IC 566.

# Tutorials

Last date: 15th October

1. [Tutorial-01](https://bietjhsacin-my.sharepoint.com/:w:/g/personal/akd_bietjhs_ac_in/IQAiRDnH5VB-TYU-V8RzGu9DAWUyNfYJM_udHUK-n37-U9M)
2. [Tutorial-02](https://bietjhsacin-my.sharepoint.com/:w:/g/personal/akd_bietjhs_ac_in/IQATPwqqGNpWRILEf29HFGERAQNR9zQLEIvkjeP5DRpFbM4?e=y6Q9aq)
3. [Tutorial-03](https://bietjhsacin-my.sharepoint.com/:w:/g/personal/akd_bietjhs_ac_in/IQBM6e8J6QtoTbHQlMeQlDFjAQo_gPooE5ULIKcWu-WJgc0?e=2y2qWA)
4. [Tutorial-04](https://bietjhsacin-my.sharepoint.com/:w:/g/personal/akd_bietjhs_ac_in/IQBA3BaeY7N0QaaD2J1kNqvgASH9Dp8eeQ_C7fAVUmEqz0o)
5. [Tutorial-05](https://bietjhsacin-my.sharepoint.com/:w:/g/personal/akd_bietjhs_ac_in/IQB9GDseDhmcRb_90tB69EQCAWFRZUE_79HR-ZB3u9ja3hA)

