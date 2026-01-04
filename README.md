# Water Level Indicator System Using NOT Gate

## Overview
This mini project demonstrates a **simple water level indicator and controller** using a NOT gate. The system is designed to prevent **water tank overflow and dry running of the pump** by indicating water levels and controlling the pump automatically using basic digital logic.

## Objective
- To design a basic water level indicator using logic gates  
- To understand the practical use of a NOT gate in control applications  
- To prevent overflow and dry-run conditions in water tanks  

## Working Principle
The circuit uses a **NOT gate (IC 7404)** to invert the input from water level sensors.  
- When the **low-level sensor does not detect water**, the NOT gate output becomes HIGH, turning the pump ON.  
- When the **high-level sensor detects water**, the output disables the pump, stopping further filling.

A transistor and relay are used to drive the pump, while LEDs indicate the water level status.

## Components Used
- IC 7404 (NOT Gate)
- BC547 Transistor
- Resistors (10kΩ, 220Ω)
- LED
- Breadboard
- Jumper Wires
- 9V Battery
- 7805 Voltage Regulator

## Results
- Successfully indicated low and high water levels  
- Automatic pump control achieved  
- Simple and reliable operation with minimal components  

## What I Learned
- Practical application of logic gates  
- Digital electronics basics  
- Sensor interfacing  
- Simple control circuit design  

## Applications
- Water tank level monitoring  
- Automatic pump control systems  
- Basic home automation projects  

## Authors
Dinesh Kumar  
ECE Students
