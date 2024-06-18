# Smart-Street-Lighting-System
This project employs Arduino, IR sensors, and LEDs to create an automatic street lighting system. It adjusts brightness based on day/night conditions and vehicle presence. Additionally, it integrates with ThingSpeak for remote monitoring and analysis of power consumption.

Components:

Arduino Board: Acts as the central control unit for the system, facilitating sensor interfacing and LED control.
IR Sensor: Detects the presence of vehicles to adjust lighting brightness accordingly.
LDR (Light Dependent Resistor): Determines day/night conditions to control street light operation.
LEDs: Emit light at variable brightness levels based on sensor inputs.
Wi-Fi Module (e.g., ESP8266): Enables connectivity to the ThingSpeak cloud platform for data transmission.
Power Supply: Provides electrical power to the system components.
Breadboard and Jumper Wires: Facilitate electrical connections between components.

Functionality:

Day/Night Detection: The LDR senses ambient light levels to distinguish between day and night. When it's daytime, the street lights remain off.
Vehicle Detection: The IR sensor detects the presence of vehicles passing by. If a vehicle is detected at night, the LEDs illuminate at full brightness (100%). If no vehicle is present, the LEDs operate at reduced brightness (50%).
IoT Monitoring: The system sends real-time data to the ThingSpeak cloud platform for remote monitoring and analysis. This includes information about LED brightness levels and estimated power consumption.
Power Usage Analysis: Utilizing ThingSpeak's analytics capabilities, users can track power consumption trends over time and optimize lighting operation for energy efficiency.

Implementation:

The Arduino board interfaces with the IR sensor, LDR, and LEDs, adjusting lighting intensity based on sensor inputs.
Wi-Fi connectivity is established using the ESP8266 module, enabling communication with the ThingSpeak platform.
Data regarding LED brightness and power consumption is transmitted to ThingSpeak at regular intervals for monitoring and analysis
