# Class-D-Audio-Amplifier
Class-D Audio Amplifier – Design & Simulation

A complete Class-D audio amplifier design project covering PWM generation, power stage design and output filtering. 

------------------------------

Project Overview

Class-D amplifiers achieve high efficiency by converting audio signals into high-frequency PWM signals and using switching power devices.  
This project demonstrates a half-bridge Class-D amplifier, designed from first principles and validated through simulation.

-----------------------

System Architecture ->

Audio Input->

Comparator + Triangle Wave (PWM)->

MOSFET Half-Bridge->
   
LC Low-Pass Filter->
   
Amplified Audio Output->

------------------------------

Design Highlights

- PWM-based audio modulation  
- High-frequency switching (100 kHz)  
- MOSFET half-bridge power stage  
- LC reconstruction filter  
- PCB-ready design considerations  

--------------------------

Key Components
Component | Description 

| Comparator / Op-Amp | Generates PWM by comparing audio & carrier |
| Triangle Wave Generator | High-frequency PWM carrier |
| NMOS + PMOS | Half-bridge switching stage |
| Inductor (33 µH) | Output smoothing |
| Capacitor (2.7 µF) | Switching noise removal |
| ±12 V Supply | Symmetrical power rails |

------------------------------
