# Sensing Subsystem README

## Overview
This README provides an overview of the sensing subsystem designed, its components, functionalities, and usage.

## Components
The sensing subsystem consists of the following main components:
-3 TSAL6200 Infrared Emitting Diodes
-3 BPV10NF Photodiodes
-3 BS170 MOSFETs
-3 4.7u Capacitors
-3 0.1u Capacitors
-3 2k Ohm Resistors
-3 10k Ohm Resistors
-6 100 Ohm Resistors

## Functionalities
Infrared Emitting Diodes (TSAL6200): 
These diodes emit infrared light. In the sensing subsystem, they would be used to emit infrared light beams towards the maze walls or obstacles.

Photodiodes (BPV10NF): 
These photodiodes detect the intensity of light falling on them. In the sensing subsystem, they would receive the reflected infrared light from the maze walls or obstacles. The intensity of the received light would vary depending on the distance between the sensor and the wall or obstacle.

MOSFETs (BS170): 
These MOSFETs act as switches to control the operation of the infrared emitting diodes. They would be used to turn the diodes on or off based on signals from the microcontroller.

Capacitors (4.7u and 0.1u): 
These capacitors are used for filtering and stabilizing the power supply to the components. They help reduce noise and ensure a stable voltage supply.

Resistors (2k Ohm, 10k Ohm, and 100 Ohm):
The 2k Ohm resistors used as pull-down resistors in the circuit.
The 10k Ohm resistors may be used for voltage division.
The 100 Ohm resistors may be used for current limiting.
