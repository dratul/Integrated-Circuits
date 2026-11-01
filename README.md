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

### Unit-I: The 741 IC Op-Amp
101 [The 741 IC Op-Amp: introduction, types of integrated circuits](./Unit-I/101-the-741-ic-op-amp-introduction-types-of-integrated-circuits.md) ([YouTube](https://youtu.be/ov1TF34Wnpw?si=jFG_f3cXeFSfkkDS))  
102 [General operational amplifier stages](./Unit-I/102-general-operational-amplifier-stages.md) ([YouTube](https://youtu.be/_7Zcg41SqLo?si=YQCb0viWVLhfc6fd))  
103 [Bias circuit](./Unit-I/103-bias-circuit.md)  
104 [Input stage and second stage](./Unit-I/104-input-stage-and-second-stage.md)  
105 [Output stage](./Unit-I/105-output-stage.md)  
106 [Short-circuit protection circuitry](./Unit-I/106-short-circuit-protection-circuitry.md)  
107 [DC analysis of input stage](./Unit-I/107-dc-analysis-of-input-stage.md) ([YouTube](https://youtu.be/qDoCvZoLmiE?list=PLKy7tXMLcgM3aUpBq_02YGHKkookFxZNO))  
108 [DC analysis of input stage notes](./Unit-I/108-dc-analysis-of-input-stage-notes.md)  
109 [Equivalent model of op-amp](./Unit-I/109-equivalent-model-of-op-amp.md)  
110 [Op-amp device parameters](./Unit-I/110-op-amp-device-parameters.md) ([YouTube](https://youtu.be/r6zfYXGk3PY?si=JYgyD3nHCOpKnkgI))  
111 [Voltage gain, differential gain, common mode gain, CMRR](./Unit-I/111-voltage-gain-differential-gain-common-mode-gain-cmrr.md) ([YouTube](https://youtu.be/EMY-IriwEM0))  
112 [Input bias current, input offset current, power supply rejection ratio, frequency response of 741](./Unit-I/112-input-bias-current-input-offset-current-power-supply-rejection-ratio-frequency-response-of-741.md)  
113 [Slew rate and relationship between input signal frequency and slew rate](./Unit-I/113-slew-rate-and-relationship-between-input-signal-frequency-and-slew-rate.md)  
114 [Relationship between output capacitance and slew rate](./Unit-I/114-relationship-between-output-capacitance-and-slew-rate.md)  
115 [Inverting amplifier](./Unit-I/115-inverting-amplifier.md)  
116 [Non-inverting amplifier](./Unit-I/116-non-inverting-amplifier.md)  
117 [Basic applications of Op-Amp](./Unit-I/117-basic-applications-of-op-amp.md)  

### Unit-II: Linear Applications of IC Op-Amps and Active Analog Filters
201 [Op-Amp based V-I converters or transconductance amplifier or voltage dependent current source](./Unit-II/201-op-amp-based-v-i-converters-or-transconductance-amplifier-or-voltage-dependent-current-source.md) ([YouTube](https://www.youtube.com/live/CtBofs9Z5WM?si=3opBHx_PDd-Zr0XT))  
202 [Numerical practice problem 1](./Unit-II/202-numerical-practice-problem-1.md) ([YouTube](https://www.youtube.com/live/5vIqPVD52qw?si=NhYbqeH6cT_AwtGK))  
203 [Op-Amp based I-V converters](./Unit-II/203-op-amp-based-i-v-converters.md) ([YouTube](https://www.youtube.com/live/PVHRGN-kW9Q?si=dUXbbql4J5vX8LZ1))  
204 [Difference amplifier](./Unit-II/204-difference-amplifier.md)  
205 [Instrumentation amplifier Part-01](./Unit-II/205-instrumentation-amplifier-part-01.md) ([YouTube](https://youtu.be/lcykQsh8KCk?si=IV_kC5dFcHtiLwSS))  
206 [Instrumentation amplifier Part-02](./Unit-II/206-instrumentation-amplifier-part-02.md) ([YouTube](https://www.youtube.com/live/m43aEDeCoU0?si=0solVW4tUso9oC03))  
207 [Instrumentation amplifier practice problem](./Unit-II/207-instrumentation-amplifier-practice-problem.md) ([YouTube](https://www.youtube.com/live/gyGvx3tu0Hc?si=VeUJHiREJgP-0Efl))  
208 [Negative resistance](./Unit-II/208-negative-resistance.md) ([YouTube](https://youtu.be/LO-BRHI8RPs?si=7QDfRfj0n_lghpCc))  
209 [Ideal current and voltage sources using negative resistance](./Unit-II/209-ideal-current-and-voltage-sources-using-negative-resistance.md)  
210 [Generalized impedance converter](./Unit-II/210-generalized-impedance-converter.md) ([YouTube](https://www.youtube.com/live/OyGvj18pmAc?si=cOmcEb1LUp6vfqBO))  
211 [Simulation of inductors](./Unit-II/211-simulation-of-inductors.md) ([YouTube](https://youtu.be/OyGvj18pmAc?list=PLKy7tXMLcgM3aUpBq_02YGHKkookFxZNO&t=2877))  
212 [Passive first-order low pass filter](./Unit-II/212-passive-first-order-low-pass-filter.md)  
213 [Passive first-order high pass filter](./Unit-II/213-passive-first-order-high-pass-filter.md)  
214 [Band pass and band stop filters (passive)](./Unit-II/214-band-pass-and-band-stop-filters-passive.md)  
215 [All-pass filter (passive)](./Unit-II/215-all-pass-filter-passive.md)  
216 [Higher-order passive filters](./Unit-II/216-higher-order-passive-filters.md)  
217 [Active first-order low pass and high pass filters](./Unit-II/217-active-first-order-low-pass-and-high-pass-filters.md)  
218 [Active band pass and band stop filters](./Unit-II/218-active-band-pass-and-band-stop-filters.md)  
219 [All-pass active filter](./Unit-II/219-all-pass-active-filter.md)  
220 [Practice problem 1 on active filters](./Unit-II/220-practice-problem-1-on-active-filters.md) ([Reference](https://bietjhsacin-my.sharepoint.com/:b:/g/personal/akd_bietjhs_ac_in/EZrLt6GFutpIqZh6FOC-zsEBJu-FEodXtamjTAEEh7HoNA?e=Eecrqn))  
221 [Practice problem 2 on active filters](./Unit-II/221-practice-problem-2-on-active-filters.md) ([Reference](https://bietjhsacin-my.sharepoint.com/:b:/g/personal/akd_bietjhs_ac_in/Ee09T3VqtDFMvnQklE0aTHEBuDFtuQhIQ7d0bes43FN3xA?e=DQiYJE))  
222 [Second-order low pass filters](./Unit-II/222-second-order-low-pass-filters.md)  
223 [Second-order high pass filters](./Unit-II/223-second-order-high-pass-filters.md)  
224 [Second-order band pass filters](./Unit-II/224-second-order-band-pass-filters.md)  
225 [Second-order band stop filters](./Unit-II/225-second-order-band-stop-filters.md)  
226 [All-pass second-order active filters](./Unit-II/226-all-pass-second-order-active-filters.md)  
227 [Biquad filters](./Unit-II/227-biquad-filters.md) ([YouTube](https://youtu.be/HXt5m6Q_nYg?t=1518))  
228 [Sallen-Key second-order filter](./Unit-II/228-sallen-key-second-order-filter.md)  
229 [KHN filters Part-01](./Unit-II/229-khn-filters-part-01.md) ([YouTube](https://www.youtube.com/live/HXt5m6Q_nYg?si=ah0aM--zSNbR9L3d))  
230 [KHN filters Part-02](./Unit-II/230-khn-filters-part-02.md) ([YouTube](https://www.youtube.com/live/ZoRuUx8ouAo?si=pfQ8V4ddrzBe1t-g))  
231 [Introduction to design of higher-order filters](./Unit-II/231-introduction-to-design-of-higher-order-filters.md)  

### Unit-III: Frequency Compensation & Non-Linear Applications of IC Op-Amps
301 [Frequency compensation](./Unit-III/301-frequency-compensation.md)  
302 [Compensation of two-stage op-amps](./Unit-III/302-compensation-of-two-stage-op-amps.md)  
303 [Slewing in two-stage op-amp](./Unit-III/303-slewing-in-two-stage-op-amp.md)  
304 [Nonlinearity of differential circuits](./Unit-III/304-nonlinearity-of-differential-circuits.md)  
305 [Effect of negative feedback on nonlinearity](./Unit-III/305-effect-of-negative-feedback-on-nonlinearity.md)  
306 [Basic log-anti log amplifiers using diode and BJT](./Unit-III/306-basic-log-anti-log-amplifiers-using-diode-and-bjt.md)  
307 [Temperature-compensated log-anti log amplifiers using diode](./Unit-III/307-temperature-compensated-log-anti-log-amplifiers-using-diode.md)  
308 [Analog multiplier circuit design using log amplifier](./Unit-III/308-analog-multiplier-circuit-design-using-log-amplifier.md)  
309 [Analog divider circuit design using log amplifier](./Unit-III/309-analog-divider-circuit-design-using-log-amplifier.md)  
310 [Peak detectors](./Unit-III/310-peak-detectors.md)  
311 [Sample and hold circuits](./Unit-III/311-sample-and-hold-circuits.md)  
312 [Op-amp as a comparator and zero crossing detector](./Unit-III/312-op-amp-as-a-comparator-and-zero-crossing-detector.md)  
313 [Schmitt trigger](./Unit-III/313-schmitt-trigger.md) ([YouTube](https://youtube.com/live/F_qzAaZkRIg))  
314 [Astable multivibrator](./Unit-III/314-astable-multivibrator.md) ([YouTube](https://www.youtube.com/live/bVItmFjMpxw?si=3AH-mo6Nmh2-Xj2d))  
315 [Monostable multivibrator](./Unit-III/315-monostable-multivibrator.md) ([YouTube](https://www.youtube.com/live/RBR8xrr-cPU?si=iGvbSzeqgY3wc7-i))  
316 [Generation of square waveforms](./Unit-III/316-generation-of-square-waveforms.md)  
317 [Generation of triangular waveforms](./Unit-III/317-generation-of-triangular-waveforms.md)  
318 [Frequency of generated triangular waveform](./Unit-III/318-frequency-of-generated-triangular-waveform.md)  
319 [Analog multipliers and their applications](./Unit-III/319-analog-multipliers-and-their-applications.md) ([YouTube](https://youtu.be/papMcmgUnaM?si=HY366qA_F3KxTrtp))  

### Unit-IV: Digital Integrated Circuit Design
401 [Overview of digital integrated circuits](./Unit-IV/401-overview-of-digital-integrated-circuits.md)  
402 [Basic logic generation in ICs](./Unit-IV/402-basic-logic-generation-in-ics.md)  
403 [CMOS logic gate circuit basic structure](./Unit-IV/403-cmos-logic-gate-circuit-basic-structure.md)  
404 [CMOS realization of inverters](./Unit-IV/404-cmos-realization-of-inverters.md)  
405 [CMOS realization of AND gates](./Unit-IV/405-cmos-realization-of-and-gates.md)  
406 [CMOS realization of OR gates](./Unit-IV/406-cmos-realization-of-or-gates.md)  
407 [CMOS realization of NAND gates](./Unit-IV/407-cmos-realization-of-nand-gates.md)  
408 [CMOS realization of NOR gates](./Unit-IV/408-cmos-realization-of-nor-gates.md)  
409 [Latches and flip-flops](./Unit-IV/409-latches-and-flip-flops.md)  
410 [The latch](./Unit-IV/410-the-latch.md)  
411 [CMOS implementation of SR flip-flops](./Unit-IV/411-cmos-implementation-of-sr-flip-flops.md)  
412 [Simpler CMOS implementation of the clocked SR flip-flop](./Unit-IV/412-simpler-cmos-implementation-of-the-clocked-sr-flip-flop.md)  
413 [CMOS implementation of J-K flip-flops](./Unit-IV/413-cmos-implementation-of-j-k-flip-flops.md)  
414 [D flip-flop circuits](./Unit-IV/414-d-flip-flop-circuits.md)  
415 [Pass transistor logic](./Unit-IV/415-pass-transistor-logic.md)  

### Unit-V: Integrated Circuit Timer and Applications
501 [Introduction to 555 timer IC](./Unit-V/501-introduction-to-555-timer-ic.md)  
502 [Timer IC 555 pin and functional block diagram](./Unit-V/502-timer-ic-555-pin-and-functional-block-diagram.md)  
503 [Internal architecture of 555 timer](./Unit-V/503-internal-architecture-of-555-timer.md)  
504 [Operating modes of 555 timer](./Unit-V/504-operating-modes-of-555-timer.md)  
505 [Monostable multivibrator using 555 IC](./Unit-V/505-monostable-multivibrator-using-555-ic.md)  
506 [Astable multivibrator using 555 IC](./Unit-V/506-astable-multivibrator-using-555-ic.md)  
507 [Bistable multivibrator using 555 IC](./Unit-V/507-bistable-multivibrator-using-555-ic.md)  
508 [Pulse width modulation (PWM) with 555](./Unit-V/508-pulse-width-modulation-pwm-with-555.md)  
509 [Ramp/triangle wave generator](./Unit-V/509-ramp-triangle-wave-generator.md)  
510 [Phase locked loop (PLL): basic principle](./Unit-V/510-phase-locked-loop-pll-basic-principle.md)  
511 [Block diagram and working of PLL](./Unit-V/511-block-diagram-and-working-of-pll.md)  
512 [Ex-OR gates and multipliers as phase detectors](./Unit-V/512-ex-or-gates-and-multipliers-as-phase-detectors.md)  
513 [Applications of PLL](./Unit-V/513-applications-of-pll.md)  

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

# Tutorials/ Assignments 

Last date: 15th October
Submission guidelines: To be submitted in Hardcopy
Write any five questions from each unit tutorials
1. [Tutorial-01](https://bietjhsacin-my.sharepoint.com/:w:/g/personal/akd_bietjhs_ac_in/IQAiRDnH5VB-TYU-V8RzGu9DAWUyNfYJM_udHUK-n37-U9M)
2. [Tutorial-02](https://bietjhsacin-my.sharepoint.com/:w:/g/personal/akd_bietjhs_ac_in/IQATPwqqGNpWRILEf29HFGERAQNR9zQLEIvkjeP5DRpFbM4?e=y6Q9aq)
3. [Tutorial-03](https://bietjhsacin-my.sharepoint.com/:w:/g/personal/akd_bietjhs_ac_in/IQBM6e8J6QtoTbHQlMeQlDFjAQo_gPooE5ULIKcWu-WJgc0?e=2y2qWA)
4. [Tutorial-04](https://bietjhsacin-my.sharepoint.com/:w:/g/personal/akd_bietjhs_ac_in/IQBA3BaeY7N0QaaD2J1kNqvgASH9Dp8eeQ_C7fAVUmEqz0o)
5. [Tutorial-05](https://bietjhsacin-my.sharepoint.com/:w:/g/personal/akd_bietjhs_ac_in/IQB9GDseDhmcRb_90tB69EQCAWFRZUE_79HR-ZB3u9ja3hA)

