# Three_Phase_Voltage_Simulation
Labview three phase voltage simulation
# Three-Phase Voltage Simulation Using LabVIEW

## 1. Project Overview

This project involves the simulation of a three-phase alternating current (AC) voltage system using LabVIEW.

The simulation generates and displays three sinusoidal voltage waveforms with equal frequencies and a phase displacement of 120 degrees.

The project demonstrates the fundamental principles of three-phase AC systems through graphical simulation.

## 2. Project Objectives

- Simulate a balanced three-phase voltage system.
- Generate three sinusoidal voltage waveforms.
- Demonstrate the 120° phase displacement between phases.
- Visualize the relationship between the three phases.
- Develop practical experience with LabVIEW programming and electrical engineering concepts.

## 3. Theoretical Background

A balanced three-phase voltage system consists of three sinusoidal voltages with equal magnitudes and frequencies, displaced from one another by 120 electrical degrees.

The three phase voltages are mathematically represented as:

**Phase R:**

$$V_R(t) = V_m\sin(\omega t)$$

**Phase Y:**

$$V_Y(t) = V_m\sin(\omega t - 120^\circ)$$

**Phase B:**

$$V_B(t) = V_m\sin(\omega t - 240^\circ)$$

Where:

- $V_m$ = Maximum voltage.
- $\omega$ = Angular frequency in radians per second.
- $t$ = Time in seconds.
- $120^\circ$ = Phase displacement between successive phases.

The angular frequency is given by:

$$\omega = 2\pi f$$

For this simulation, the operating frequency is 50 Hz.

Therefore:

$$\omega = 2\pi(50) = 100\pi\text{ rad/s}$$

The resulting three waveforms have equal frequencies and are separated by 120°.

## 4. Simulation Specifications
Software - LabVIEW 
System - Three-phase AC 
Frequency - 50 Hz 
Number of phases - 3 
Phase displacement - 120°
Waveform - Sinusoidal 
Visualization - Waveform Graph

## 5. Simulation Features

- Generation of three sinusoidal voltage waveforms.
- Operating frequency of 50 Hz.
- 120° phase displacement between successive phases.
- Different waveform colours for easy identification.
- Simultaneous visualization of all three phases.
- Continuous waveform display during simulation.

## 6. Current Limitations

- Phase-sequence reversal is not yet implemented.
- Adjustable voltage magnitude is not currently available.

## 7. Engineering Significance

Three-phase electrical systems are widely used in power generation, transmission, distribution and industrial electrical machinery.

They provide an effective method of transmitting electrical power and are essential in the operation of three-phase motors and other industrial equipment.

This project provides a practical introduction to the behaviour of three-phase AC voltage systems and their graphical representation.

## 8. Future Improvements

- Implement phase-sequence reversal.
- Add adjustable voltage magnitude.
- Add adjustable frequency.
- Calculate instantaneous line and phase voltage relationships.
- Explore integration with Arduino hardware.

## 9. Software and Tools

- LabVIEW
- Waveform Graph
- Sine Wave Generation Functions
- Mathematical and signal-processing functions

## 10. Author

SIISI BOTWE

Electrical Engineering Student  
University of Mines and Technology (UMaT)

---

*Developed as part of my practical learning journey in Electrical Engineering and LabVIEW programming.*
