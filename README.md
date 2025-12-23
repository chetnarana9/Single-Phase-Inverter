# Single-Phase-Inverter
An Inverter converts DC power to AC power with variable voltage and frequency for powering the standard appliances.

Key Features:
1. Basic ON/OFF control of inverter.
2. Stable DC to AC conversion using SPWM with MOSFET and IGBTs.

Components Used: Arduino UNO, MOSFET IRF540, Transformer(9-0-9/220 V), Diode 1N4148, Resistor, Capacitor (0.68µF,400 V)

Working Principle: 

The Arduino produces SPWM signals with a varying duty cycle to emulate a sine wave. These signals switch MOSFETs to create alternating current in the transformer primary, stepping up the voltage. The output capacitor smooths the waveform to obtain near-sinusoidal AC.
