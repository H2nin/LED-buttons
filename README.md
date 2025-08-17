# LED-buttons
a simple Arduino project where push buttons are used as inputs and LEDs as outputs to demonstrate the basic input → processing → output concept.

## Overview
This project demonstrates the basic concept of **inputs** and **outputs** using an Arduino Uno.  
- **Inputs:** Push buttons  
- **Outputs:** LEDs  

When a button is pressed, the corresponding LED turns ON.  
Each button controls one LED.  

## Components
- Arduino Uno  
- 3 Push Buttons (inputs)  
- 3 LEDs (outputs)  
- Resistors (for LEDs and buttons)  
- Breadboard and jumper wires  

## How It Works
1. Each push button is connected to a digital input pin on the Arduino.  
2. Each LED is connected to a digital output pin on the Arduino.  
3. When a button is pressed, the Arduino detects the signal and turns ON the LED linked to that button.  
4. When the button is released, the LED turns OFF.  

## Purpose
This task shows the concept of **processing (Arduino)**:
- **Inputs → Processing → Outputs**  
- The Arduino reads input signals (buttons), processes them, and activates the outputs (LEDs). 
