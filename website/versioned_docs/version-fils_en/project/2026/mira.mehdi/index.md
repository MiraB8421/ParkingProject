Smart Dual-Barrier Parking System with NFC and Coin Detection

Description
This Project presents a smart parking barrier system using the STM32 NUCLEO-U545RE microcontroller designed to simulate a realistic automated parking management system. The system includes three stations: an entry barrier station, a payment station, and an exit barrier station.

Motivation
I chose this project to show how embedded systems can be presented in real life application. Moreover, it shows how improving security and reducing manual supervision in parking systems.

Architecture
 This system is connected to STM32 board:
 •	STM32 NUCLEO-U545RE – main controller 
•	Two NFC reader (PN532) – reads authorization card 
•	 Two Servo motor – opens and closes the barrier 
•	LCD display (16×2) – shows status messages 
•	Green LED – indicates access granted 
•	Red LED – indicates access denied 
•	Buzzer – activates when access is denied 
•	Breadboard and jumper wires – connect components
•	Ultrasonic distance sensor – detects vehicle entry into parking area
•	IR Sensor – Coin detection 


what are the main components (architecture components, not hardware components)
how they connect with each other
Log
Week 5 - 11 May
Week 12 - 18 May
Week 19 - 25 May
Hardware
Detail in a few words the hardware used.

Schematics
Place your KiCAD or similar schematics here in SVG format.

Bill of Materials
Device	Usage	Price
Raspberry Pi Pico W	The microcontroller	35 RON
Software
Library	Description	Usage
st7789	Display driver for ST7789	Used for the display for the Pico Explorer Base
embedded-graphics	2D graphics library	Used for drawing to the display
