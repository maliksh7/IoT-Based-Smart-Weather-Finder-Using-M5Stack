# IoT-Based Smart Weather Finder Using M5Stack

### Author: Muhammad Saad Hassan  
**Course**: IoT  
**Date**: 14/06/2023  

## Overview
This project introduces an **IoT-Based Smart Weather Finder** using the **M5Stack development kit**, **ENV III sensor**, **GPS sensor**, and **RGB LED sensor**. The system collects, analyzes, and visualizes real-time weather data, while the GPS sensor provides precise geolocation data for tagging weather information. The system is also capable of predicting rain probabilities.

By leveraging the capabilities of **M5Stack**, sensors, and IoT technologies like **Blocky** and **Micropython (UIFlow)**, this project aims to create a comprehensive and efficient weather monitoring solution.

## Components and Accessories

### M5Stack
The **M5Stack** serves as the core platform for the weather monitoring system, providing connectivity and control over the connected sensors and modules.

### Environmental (ENV III) Sensor
The **ENV III sensor** measures essential environmental parameters such as:
- **Temperature**
- **Humidity**
- **Pressure**
- **Air Quality**

### GPS Sensor
The **GPS sensor** captures precise latitude and longitude coordinates, allowing the system to tag weather data with geolocation information, enhancing weather tracking accuracy.

### RGB LED Sensor
The **RGB LED sensor** visualizes weather conditions through color codes:
- **Green:** Favorable weather
- **Yellow:** Cautionary weather conditions
- **Red:** Severe weather alerts

### Button Controls
Buttons on the M5Stack are used for various actions, such as switching between weather data views, triggering data logging, or adjusting settings.

### SD Card Support
An **SD card** is used to:
- Read and write activity and error logs.
- Store sensor data in **JSON** format for easy retrieval and analysis.

### Cloud Handling with EZData
The system uses **EZData Database**, a cloud-based service, to store and manage sensor data, GPS coordinates, and weather alerts.

### Wi-Fi Connectivity
Wi-Fi integration allows the system to:
- Fetch dynamic data from APIs.
- Connect to online web services for weather updates.
  
### Mobile Device Integration
Users can configure and monitor the weather station via a connected mobile device, receiving real-time updates and alerts on weather changes.

### IMU Sensors
Integrated **IMU sensors** enhance the system's capabilities, allowing for additional data, such as device orientation, to be captured for specific use cases.

### Speaker
An onboard speaker provides audio alerts and notifications, enhancing user interaction with real-time sound cues for critical weather conditions.

## System UI Components

### M5Stack UI
The user interface for **M5Stack** is designed to provide an intuitive and visually appealing experience, featuring:
- Title bars for easy identification of displayed data.
- Interactive shapes, images, and labels for smooth navigation.
- Dynamic labels, updated in real-time via API data.
  
### Mobile UI
The mobile UI mirrors the M5Stack experience but is optimized for smaller screens, allowing:
- Convenient access to weather information.
- Configuration options and alerts.
- Easy navigation through a responsive design.
