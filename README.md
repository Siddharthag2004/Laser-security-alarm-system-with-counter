# Laser Security Alarm System with Counter

## Project Title

**Laser Security Alarm System with Counter**: A reliable security system utilizing laser technology and a counter for intrusion detection and monitoring.

## Project Description

The **Laser Security Alarm System with Counter** is designed to provide enhanced security by creating an invisible perimeter using a laser beam. When an object or person interrupts the beam, an alarm is triggered, and the event is logged by incrementing a counter displayed on an LCD. This project uses an Arduino microcontroller, IR sensors, LDR, and various other components to form a customizable and scalable security solution.

### Key Features:
- **Intrusion Detection**: Detects any interruptions in the laser beam and triggers an alarm via a buzzer.
- **Visitor Counter**: Tracks the number of intruders or people entering the secured area using IR sensors and displays the count on an LCD.
- **Customizable**: The system can be adjusted for different security zones by varying the number of lasers and sensors.
- **Applications**: Suitable for homes, offices, warehouses, museums, and sensitive data centers.

## Table of Contents

- [Project Title](#project-title)
- [Project Description](#project-description)
- [How to Install and Run the Project](#how-to-install-and-run-the-project)
- [How to Use the Project](#how-to-use-the-project)
- [Components Required](#components-required)
- [Working Principle](#working-principle)
- [Credits](#credits)
- [License](#license)
- [Additional Sections](#additional-sections)

## How to Install and Run the Project

### Prerequisites

- **Arduino Uno**
- **Breadboard**
- **Laser Light Source (5mW)**
- **IR Sensors**
- **Light Dependent Resistor (LDR)**
- **BC547 Transistor**
- **16x1 LCD Display**
- **LEDs**
- **Buzzer**
- **Switches**
- **Jumper Wires**
- **100K ohm Resistor**

### Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/laser-security-alarm.git
2. **Set Up the Circuit: Follow the circuit diagram provided in the /diagrams folder**:
File -> Open -> Navigate to laser_security_alarm.ino
Tools -> Board -> Arduino Uno
Tools -> Port -> Select the appropriate port
Sketch -> Upload
Arduino IDE -> Tools -> Manage Libraries -> Search for "LiquidCrystal" -> Install
