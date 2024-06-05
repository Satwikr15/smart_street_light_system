# Smart Street Light System

This repository contains the implementation of a Smart Street Light System. The system is designed to automatically control the brightness of street lights based on the intensity of sunlight using an LDR (Light Dependent Resistor) sensor and other electronic components.

## Project Overview

The Smart Street Light System is an energy-efficient solution that reduces electricity consumption by adjusting the brightness of the street lights according to the surrounding light intensity. The primary components of this system include an LDR sensor to detect ambient light levels and a microcontroller to process the sensor data and control the light output.

## Features

- **Automatic Brightness Control**: The street lights adjust their brightness based on the intensity of sunlight, ensuring optimal lighting levels during different times of the day and night.
- **Energy Efficiency**: By reducing the brightness during periods of sufficient natural light, the system helps in saving energy and reducing electricity costs.
- **Scalability**: The system can be easily scaled to control multiple street lights in a network.
- **Remote Monitoring**: Integration with ThingSpeak allows for real-time monitoring and visualization of the system's status and performance.

## Components

- **LDR Sensor**: Detects the ambient light intensity.
- **Microcontroller (NodeMCU ESP8266)**: Processes the sensor data and controls the street light brightness.
- **LED Street Light**: The light source controlled by the system.
- **Additional Electronic Components**: Resistors and other components required for circuit design.

## How It Works

1. **LDR Sensor**: Measures the surrounding light intensity and sends the data to the microcontroller.
2. **Microcontroller (NodeMCU ESP8266)**: Analyzes the data and determines the required brightness level for the street light.
3. **LED Control**: Adjusts the brightness of the LED street light based on the processed data.
4. **ThingSpeak Integration**: The NodeMCU ESP8266 sends data to ThingSpeak for remote monitoring and visualization.

## Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/SmartStreetLightSystem.git
