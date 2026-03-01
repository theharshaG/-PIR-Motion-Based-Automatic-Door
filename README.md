# -PIR-Motion-Based-Automatic-Door

## Project Overview
This project demonstrates an **automatic door system**
using a **PIR motion sensor** and a **servo motor** with ESP32.

The door opens automatically when motion is detected
and closes when no motion is present.

## Components Required
- ESP32
- PIR Motion Sensor
- Servo Motor (SG90 / MG90)
- Jumper Wires
- Breadboard

## Connections
### PIR Sensor
PIR Pin --->ESP32 Pin
VCC ---->5V / 3.3V
GND---->GND 
OUT---->GPIO 12

### Servo Motor
Servo Wire ---->ESP32 Pin
Red---->5V 
Brown/Black---->GND
Yellow/Orange---->GPIO 21

Use external 5V supply if servo draws high current.

## Concepts Used
- PIR motion detection
- Servo motor control
- Digital input reading
- Conditional logic

## How to Run
1. Install **ESP32Servo library**
2. Connect PIR sensor and servo correctly
3. Upload the code to ESP32
4. Open Serial Monitor (9600 baud)

## 📟 Sample Output
Motion detected → Door OPEN
No motion → Door CLOSED

## Learning Outcome
- Learn how PIR sensors work
- Control servo motor using ESP32
- Build basic automation systems

## Author
Harsha G
