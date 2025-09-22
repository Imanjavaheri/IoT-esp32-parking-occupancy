# IoT-esp32-parking-occupancy
Wokwi and Power Consumption – Challenge 1

This project explores the design and energy analysis of an IoT parking occupancy detection node built and simulated in Wokwi using an ESP32 microcontroller and an HC-SR04 ultrasonic distance sensor.

It includes both the hardware simulation and the data analysis of the node’s power consumption in different operating modes.

**Project Overview**

**Parking Occupancy Node**

Hardware Simulation: The ESP32 is paired with the HC-SR04 sensor to detect whether a parking bay is occupied.

Logic: If the measured distance is less than 50 cm, the space is marked “Occupied”; otherwise, it is “Free”.

Communication: Messages (“Free” or “Occupied”) are broadcast using the esp_now Wi-Fi protocol.

Power Management: The node cycles between active measurement and deep sleep to minimize power usage
