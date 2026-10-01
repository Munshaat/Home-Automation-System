# Home Automation System

A sensor-based **Home Automation System** developed as part of the **EEE 4604 – Measurement and Instrumentation Lab** at the Islamic University of Technology (IUT).

The project integrates multiple sensors and control mechanisms to automate common household functions, including lighting activation, temperature-based motor control, smoke detection, water-level monitoring, and automatic water dispensing.

## Project Overview

The system demonstrates the practical application of **sensor interfacing, measurement, circuit design, and automation** by integrating several sensing and control functions into a single home automation system.

The project was designed and tested to demonstrate how sensor inputs can be processed to trigger appropriate automated responses.

## Key Features

* LDR-based system activation
* Temperature monitoring and motor activation
* Smoke detection and alert
* Ultrasonic water-level monitoring
* IR-based automatic water dispensing
* Sensor interfacing and signal processing
* Automated control of household functions
* Hardware troubleshooting and integration

## Automated Functions

### 1. LDR-Based System Activation

An **LDR (Light Dependent Resistor)** is used to detect changes in ambient light conditions.

The sensor input is used to activate the corresponding system functionality based on the detected light level.

### 2. Temperature Monitoring and Motor Activation

A temperature sensor monitors the surrounding temperature.

When the temperature reaches the defined condition, the system activates the motor automatically, demonstrating temperature-dependent control.

### 3. Smoke Detection and Alert System

A smoke sensor is used to detect the presence of smoke.

When smoke is detected, the system activates an alert mechanism to provide a warning condition.

### 4. Water-Level Monitoring

An **ultrasonic sensor** is used to monitor the water level.

The sensor measures the distance to the water surface and allows the system to determine the corresponding water-level condition.

### 5. Automatic Water Dispensing

An **IR sensor** is used to detect the presence of an object or user near the dispensing point.

Based on the sensor input, the system automatically controls water dispensing.

## System Concept

```text
                 ┌───────────────────┐
                 │   Sensor Inputs   │
                 └─────────┬─────────┘
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
        LDR          Temperature        Smoke Sensor
          │             Sensor              │
          │                │                │
          └────────────────┼────────────────┘
                           │
                           ▼
                  Control / Processing
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
     Motor Control    Alert System    Water Control
          │                                 │
          │                                 │
          ▼                                 ▼
       Motor                         Water Dispensing

             Ultrasonic Sensor
                    │
                    ▼
             Water-Level Data

               IR Sensor
                    │
                    ▼
          Automatic Dispensing
```

## Sensors and Functions

| Sensor             | Function                                    |
| ------------------ | ------------------------------------------- |
| LDR                | Light-dependent system activation           |
| Temperature Sensor | Temperature monitoring and motor activation |
| Smoke Sensor       | Smoke detection and alert                   |
| Ultrasonic Sensor  | Water-level measurement                     |
| IR Sensor          | Automatic water dispensing                  |

## Technical Implementation

The project focused on integrating multiple sensor-based subsystems into a coordinated automation system.

The main implementation tasks included:

* Interfacing different sensors with the control circuitry.
* Processing sensor outputs.
* Establishing threshold-based control conditions.
* Driving motors and alert devices based on sensor inputs.
* Integrating multiple automated functions into one system.
* Testing and troubleshooting individual subsystems.
* Verifying the overall system operation.

## Challenges

During implementation, the team worked through practical challenges involving:

* Sensor calibration
* Hardware integration
* Interfacing different sensing elements
* Troubleshooting unexpected circuit behavior
* Coordinating multiple subsystems

These challenges provided practical experience in debugging and hardware-level problem solving.

## Skills Demonstrated

* Sensor Interfacing
* Measurement & Instrumentation
* Circuit Design
* Automation
* Hardware Troubleshooting
* Embedded System Concepts
* Motor Control
* Team Collaboration
* System Integration

## Project Highlights

* Developed a multi-function home automation system.
* Integrated **five different sensing/automation functions**.
* Implemented both environmental monitoring and automated control.
* Worked with multiple sensor technologies in a single system.
* Troubleshot sensor and hardware integration issues.
* Applied measurement and instrumentation concepts to a practical automation application.

## Academic Information

**Course:** EEE 4604 – Measurement and Instrumentation Lab
**Department:** Electrical and Electronic Engineering
**Institution:** Islamic University of Technology (IUT)


```
