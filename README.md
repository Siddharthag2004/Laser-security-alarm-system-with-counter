# Laser Security Alarm System with Counter

## Project Title

**Laser Security Alarm System with Counter**: A reliable security system utilizing laser technology and a counter for intrusion detection and monitoring.

## Project Description

The **Laser Security Alarm System with Counter** is designed to provide enhanced security by creating an invisible perimeter using a laser beam. When an object or person interrupts the beam, an alarm is triggered, and the event is logged by incrementing a counter displayed on an LCD. This project uses an Arduino microcontroller, IR sensors, LDR, and various other components to form a customizable and scalable security solution.

### Key Features:
- **Intrusion Detection**: Detects any interruptions in the laser beam and triggers an alarm via a buzzer.
- **Visitor Counter**: Tracks the number of intruders or people entering the secured area using IR sensors and displays the count on an LCD.
- **Customizable**: The system can be adjusted for different security zones by varying the number of lasers and sensors.
- **Applications**: Suitable for homes, offices, warehouses, museums, and sensitive data centres.

## Table of Contents

- [Project Title](#project-title)
- [Project Description](#project-description)
- [Installation](#installation)
- [How to Use the Project](#how-to-use-the-project)
- [Components Required](#components-required)
- [Working Principle](#working-principle)
- [Credits](#credits)
- [License](#license)
- [References](#References)

##  Installation

### Hardware Setup
1. **Components Procurement**: Ensure all components listed in the  [Components Required](#components-required) section are available.
2. **Circuit Assembly**: Assemble the circuit according to the provided diagram. Pay special attention to the positioning of the laser source, LDR, and IR sensors.
### Software Setup

1. **Writing the Arduino Code**:
   - Open the Arduino IDE on your computer.
   - Copy and paste the provided Arduino code into the IDE.
2. **Uploading the Code:**:
   - Connect your Arduino Uno board to your computer using a USB cable.
   - Select the correct board and port from the Arduino IDE under Tools.
   - Click on the "Upload" button to transfer the code to your Arduino board.

## How to Use the Project

1. **Powering the System**:
   - Connect your Arduino Uno to a power source using a USB cable or a 9V battery. Ensure the circuit is properly assembled as per the circuit diagram.
2. **Initial Setup**:
   - Position the laser pointer so that its beam directly hits the LDR (Light Dependent Resistor). This creates an invisible boundary that the system will monitor.
3. **Activating the System**:
   - Once powered on, the LCD will display "NOBODY," indicating no intrusions have been detected.
4. **Intrusion Detection**:
   - When someone crosses the laser beam, the alarm will sound, and the LCD will display the current count of intrusions. The LED will light up, indicating that the laser beam was interrupted.
5. **Monitoring the Counter**:
   - The LCD will continuously update, showing the number of people or objects that have crossed the beam. This count helps monitor activity in the secured area.
6. **Resetting the System**:
   - To reset the system, simply reset the Arduino board using the reset button or disconnect and reconnect the power source.
7. **Understanding the Alerts**:
   - The system will emit a sound via the buzzer whenever the laser beam is interrupted, allowing you to quickly identify potential intrusions.
## Important Tips: 
- Ensure the laser beam is always aligned with the LDR for accurate detection.
- Keep the system in a location where the laser and LDR won't be accidentally moved or misaligned.
By following these steps, you can effectively use the Laser Security Alarm System with Counter to monitor and secure any space!

## Components Required

- Breadboard
- BC547 Transistor
- Arduino Uno and cable
- 16x1 LCD Display
- Light Emitting Diode (LED)
- 100K ohm Resistor
- 5V Buzzer
- Light Dependent Resistor (LDR)
- 5mW Laser light source
- IR Sensors
- Switch and Jumper Wires

## Working Principle

The Laser Security Alarm System with Counter works by using a laser beam directed at a Light Dependent Resistor (LDR). Under normal conditions, the LDR receives the laser light, and its resistance remains low. When an object interrupts the beam, the LDR’s resistance increases, and this change is detected by the Arduino microcontroller.

Upon detection, the Arduino triggers an alarm using a buzzer and lights up an LED, indicating a breach. At the same time, the system increments and displays the count of intrusions on the LCD screen. Once the object clears, the system resets, ready for the next interruption. This process ensures continuous monitoring and counting of intrusions in real-time.

## License 

This project is licensed under the MIT License.

## References
- [BC547 Transistor](https://www.theengineeringprojects.com/2017/06/introduction-to-bc547.html)
- [Laser Light Source](https://makerbazar.in/products/kids-toys-laser-light)
- [LDR Specifications](https://techdelivers.com/LDR-5mm-Photocell)
