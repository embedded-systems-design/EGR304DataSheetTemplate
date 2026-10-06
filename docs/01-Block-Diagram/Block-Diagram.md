---
title: Individal Block Diagram
tags:
- tag1
- tag2
---

## Overview
This block diagram shows the main power, sensing, processing, and communication functions of the pressure-sensing PCB. The board receives 9 V power through a barrel jack, which is reduced to 5 V by a voltage regulator to provide power for the circuit. The pressure sensor produces an analog signal that is conditioned by an op amp before being sent to the PIC18F57Q43 microcontroller for processing. The microcontroller also controls an LED using a PWM-capable output to provide a visual indication of circuit operation.

The PIC communicates with the rest of the team system through Connector 1 using UART transmit and receive signals. The connector also provides a common ground connection between boards. This allows the pressure measurement collected by this PCB to be transferred to the other subsystems in the team device.


## Example Block Diagram 
Showing an example of how to import a screenshot of the block diagram created outside of git and brought into a page.

![ Indivial Block diagram ]<img width="1850" height="1892" alt="image" src="https://github.com/user-attachments/assets/961efd1d-a171-4aa2-92d4-f100a3049dc8" />

