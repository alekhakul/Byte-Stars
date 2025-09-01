# Byte Stars - ECE 319H Final Project

This repository contains the source code for the "Byte Stars" project, developed as part of ECE 319H at the University of Texas at Austin.

## Description

Byte Stars is a 2D battle game created by Alex Lekhakul and Abhishek Shrestha for their ECE 319H final project, with themes very loosely based on the mobile game, Brawl Stars. Players can select from 4 playable ECE professors (Prof. Lucas Holt, Prof. Ramesh Yeraballi, Prof. Evan Speight, and Prof. Jonathan Valvano) to defeat progressively stronger waves of bug enemies. Each playable character has 4 unique moves, each with corresponding animations and voice lines.

---

## Hardware & Software

* **Microcontroller:** TI LP-MSPM0G3507
* **IDE:** Texas Instruments Code Composer Studio (CCS)
* **Key Components:**
  - Adafruit 1.8" Color TFT LCD Display with MicroSD Card Breakout - ST7735R
  - Sparkfun Thumb Joystick
  - Audio Jack / Speaker
  - 4 Buttons
  - 4 LEDs
  - MicroSD Card

---

## Attributions & Acknowledgements

A significant portion of the low-level driver code for interfacing with the hardware was provided by **Professor Jonathan Valvano**. His foundational work was instrumental in the development of this project.

The drivers and libraries provided include, but are not limited to:
- ADC (Analog-to-Digital Converter)
- Joystick Interface
- LCD Screen Control
- System Tick and Timers

All other application-level logic and project-specific code were written by **Alex Lekhakul** and **Abhishek Shrestha**. As part of the project, the students also edited Professor Valvano's provided files.

Project roles and responsibilities were roughly divided as such:

**Alex Lekhakul:**
- Audio System
- SD card through SPI on the LCD
- Images
- Sprites
- Combat Move Animations
- Combat Move Logic
- PCB Design

**Abhishek Shrestha:**
- Enemy Logic
- Joystick Implementation
- Playable Character Logic
- Movement Animation

Both students soldered their own PCBs and presented the project to their peers, being voted top 2 in their section to advance to finals and receiving the **Most Creative** award in the Spring 2025 ECE 319H cohort of 350+ students.

Special thanks go to **Professor Jonathan Valvano**, **Professor Ramesh Yerraballi**, **Professor Lucas Holt**, and **Professor Evan Speight** for providing their voice lines and likenesses to the game.

---

## How to Build

To build and run this project:

1.  Clone this repository.
2.  Open Code Composer Studio.
3.  Import the project (`File` > `Import` > `CCS Projects`).
4.  Build the project and flash it to the target microcontroller.
