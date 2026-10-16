# HW4 - Rectifier and Harmonic Analysis

## Deliverables
- Fourier series for a square-wave voltage source
- RL load response to a nonsinusoidal source
- Harmonic current analysis
- Single-phase full-wave diode rectifier
- Highly inductive load
- Infinite-inductance approximation
- Capacitor filtering

## Simulations

MATLAB and Simulink

Cases studied:

- Square-wave source feeding an RL load
- Rectifier with a highly inductive load
- Infinite-inductance load using a constant current source
- Capacitor-filtered rectifier with a resistive load

## Main Parameters

- Grid voltage: 120 Vrms
- Frequency: 60 Hz
- Load resistance: 10 ohms
- Diode forward voltage: 0.7 V
- Diode resistance: 0.25 ohms
- Line inductance: 5 uH per line
- Calculated load inductance: about 124 mH
- Calculated filter capacitance: about 13.6 mF

## Tools

- MATLAB
- Simulink
- Simscape Electrical / Specialized Power Systems


<p align="center">
  <img width="755" height="652" alt="image" src="https://github.com/user-attachments/assets/04d0bc54-50cb-4020-8d57-d240afb86304" />
</p>

<p align="center">
  <b>Figure 1: Simulink Model of a Square-Wave Voltage Source Feeding an RL Load</b>
</p>

<p>&nbsp;</p>
<p>&nbsp;</p>

<p align="center">
  <img width="1326" height="787" alt="image" src="https://github.com/user-attachments/assets/68276cd9-01fa-43a0-8ecf-f743c5104bc2" />
</p>

<p align="center">
  <b>Figure 2: Simulated RL Load Current and Square-Wave Source Voltage</b>
</p>

<p>&nbsp;</p>
<p>&nbsp;</p>

<p align="center">
  <img width="1262" height="468" alt="image" src="https://github.com/user-attachments/assets/98efbf90-15d8-4c8d-970b-fe5e424aaaf9" />
</p>

<p align="center">
  <b>Figure 3: Hand-Drawn Equivalent Circuit for the Highly Inductive Load</b>
</p>

<p>&nbsp;</p>
<p>&nbsp;</p>

<p align="center">
  <img width="1507" height="805" alt="image" src="https://github.com/user-attachments/assets/6db4fdfc-4c5b-4865-8778-dfc2e1a44aea" />
</p>

<p align="center">
  <b>Figure 4: Simulink Model for the Highly Inductive Load Case</b>
</p>

<p>&nbsp;</p>
<p>&nbsp;</p>

<p align="center">
  <img width="1606" height="957" alt="image" src="https://github.com/user-attachments/assets/ce4229a6-0f93-4ee2-bd31-5764f53358ad" />
</p>

<p align="center">
  <b>Figure 5: Simulated Voltage and Current Waveforms for the Highly Inductive Load Case</b>
</p>

<p>&nbsp;</p>
<p>&nbsp;</p>

<p align="center">
  <img width="1277" height="937" alt="image" src="https://github.com/user-attachments/assets/d90c0bb7-948b-4d0e-b705-405b949bbe54" />
</p>

<p align="center">
  <b>Figure 6: Simulink Model and Equivalent Circuit for the Capacitive Filter Case</b>
</p>

