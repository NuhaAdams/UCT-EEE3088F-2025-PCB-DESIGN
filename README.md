# UCT-EEE3088F-2025-PCB-DESIGN
EEE3088F-MicroMouse Power Subsystem-Group55
# Overall Project
This repository contains the design files, documentation, and supporting resources for the Power Subsystem of the EEE3088F Micro-Mouse course project.
The project involved designing a power board for a micro-mouse maze-solving robot, while the sensing board, processor and motherboard were given.
# The Power Board
The power subsystem is responsible for:
Bidirectional control of 4 motors via H-Bridge drivers (DRV8833PWR).
5V and 3.3V regulated outputs using MC33063AD and TPS62200DBV regulators respectively.
Battery monitoring via INA219 current sensor on the I2C bus.
Battery charging from a USB-C 9V input, with two selectable charging modes (200mA and ~600mA).
High-side switching for two external 5V loads.
System ON/OFF control ensuring <30µA in the OFF state.
The PCB design meets strict budget and dimension constraints, fully interfacing with the Micro-Mouse motherboard.
# How this GitHub repo works
This GitHub repository serves as a central hub for all files related to the power subsystem design of the EEE3088F micro-mouse project.
Each folder in the repository is organized by function. Each of these folders contain the relevant documents that are associated with the design of the power subsystem.
