# blink
project for testing how to use github with arduino blink project
Project Title: Intelligent Lamp Control Using Arduino UNO

Overview:

This project demonstrates the implementation of a fundamental yet essential concept in embedded systems: controlling an electrical output device—in this case, an LED lamp—using a microcontroller platform. Leveraging the capabilities of the Arduino UNO, we establish a reliable digital control mechanism, enabling precise switching operations for the lamp based on pre-defined logic.

Objective:

To design and program a microcontroller-based system that can autonomously control the on/off state of a lamp (represented by an LED), using digital I/O interfacing and basic embedded logic.

Components Used:

Arduino UNO R3 (ATmega328P-based microcontroller board)

5mm LED (as a representation of a lamp)

220Ω resistor (for current limiting)

Breadboard and jumper wires

USB cable for programming and power supply

System Architecture & Operation:

The Arduino board acts as the central processing unit. The LED is interfaced with one of the digital output pins (e.g., pin 13), and a series resistor is connected to ensure current regulation and prevent damage to the LED.

In the firmware, the digital pin is configured as an output using the pinMode() function. The main control loop utilizes the digitalWrite() function to toggle the LED state, either manually or based on predefined time intervals or external input triggers.
