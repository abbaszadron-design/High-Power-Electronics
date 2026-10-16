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


<img width="755" height="652" alt="image" src="https://github.com/user-attachments/assets/04d0bc54-50cb-4020-8d57-d240afb86304" />
Figure #1: Simulink Model of Square Wave Voltage source feeding an RL Load



<img width="1326" height="787" alt="image" src="https://github.com/user-attachments/assets/68276cd9-01fa-43a0-8ecf-f743c5104bc2" />
Figure #2: Simulink RL Square Wave (RL Load Current) and (Source Voltage) Waveforms 



<img width="1262" height="468" alt="image" src="https://github.com/user-attachments/assets/98efbf90-15d8-4c8d-970b-fe5e424aaaf9" />
Figure #3: Hand-Drawn Equivalent Circuit for the Highly Inductive Load



<img width="1507" height="805" alt="image" src="https://github.com/user-attachments/assets/6db4fdfc-4c5b-4865-8778-dfc2e1a44aea" />
Figure #4: Simulink Model for the HIL case



<img width="1606" height="957" alt="image" src="https://github.com/user-attachments/assets/ce4229a6-0f93-4ee2-bd31-5764f53358ad" />
Figure #5: Simulated Waveforms showing Voltage and Current 



<img width="1277" height="937" alt="image" src="https://github.com/user-attachments/assets/d90c0bb7-948b-4d0e-b705-405b949bbe54" />
Figure #6: The Simulink model along with The Equivalent Circuit for Capacitive Filter Case

