# Single-Phase-Inverter
An Inverter converts DC power to AC power with variable voltage and frequency for powering the standard appliances.

Key Features:
1. Basic ON/OFF control of inverter.
2. Stable DC to AC conversion using SPWM with MOSFET and IGBTs.

Components Used: Arduino UNO, MOSFET IRF540, Transformer(9-0-9/220 V), Diode 1N4148, Resistor, Capacitor (0.68µF,400 V)

Working Principle: 

The Arduino produces SPWM signals with a varying duty cycle to emulate a sine wave. These signals switch MOSFETs to create alternating current in the transformer primary, stepping up the voltage. The output capacitor smooths the waveform to obtain near-sinusoidal AC.

Outcomes:
1. Achieved near-sinusoidal AC output from a 12 V DC source using Arduino-based SPWM control.
2. Successfully implemented MOSFET switching and transformer voltage step-up for inverter operation.
3. Improved output waveform quality using filtering, reducing harmonic distortion.

Learnings:
1. Gained hands-on understanding of SPWM generation and its role in harmonic reduction.
2. Learned practical aspects of MOSFET gate driving, switching losses, and timing control.
3. Developed insight into DC–AC power conversion, transformer operation, and output filtering.

