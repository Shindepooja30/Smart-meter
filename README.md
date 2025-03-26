
# Energy Monitoring System



## Traditional Approach & Existing Solution
Problems:

Lack of Real-Time Monitoring: Traditional energy meters do not provide real-time consumption data, leading to inefficient energy use.

High Energy Bills: Consumers often receive bills at the end of the month without insights into their daily usage, making it difficult to manage and optimize consumption.

Manual Meter Reading: Traditional energy meters require manual readings, which are time-consuming and prone to human errors.

Energy Theft and Loss: Unauthorized electricity consumption (power theft) leads to losses for power companies and increased tariffs for consumers.

Environmental Concerns: Lack of efficient energy management contributes to excessive energy consumption, increasing carbon emissions.

Existing Solutions:

Smart Meters: Some areas have implemented smart meters that provide digital readings and remote monitoring, but they are expensive and not widely adopted.

IoT-Based Solutions: Some IoT-enabled energy monitors exist, but they often lack real-time tracking, advanced analytics, or user-friendly dashboards.
## Our Solution

An Advanced IoT-Based Energy Monitoring System
Our project aims to develop a cost-effective, real-time energy monitoring system that tracks and optimizes energy usage using IoT and web technologies.

Key Features:
1. Real-Time Energy Consumption Monitoring via IoT-based smart sensors.
2. Web Dashboard for Visualization (Next.js frontend) to analyze energy trends.
3. MQTT Protocol for Data Transmission between energy meters and the server.
4. User Alerts & Notifications for high energy usage.
5. Data Logging & Historical Analysis to identify wastage patterns.
6. Remote Access for users to monitor their energy consumption from anywhere.


## Benefits to society
1. Energy Efficiency: Helps users optimize energy usage, reducing waste.
2. Cost Savings: Identifies unnecessary power consumption, lowering electricity bills.
3. Awareness & Accountability: Users become more conscious of their consumption patterns.
4. Grid Optimization: Reduces the strain on power grids, improving energy distribution.
5. Prevention of Energy Theft: Tracks anomalies in energy consumption.
6. Sustainability & Environment: Promotes responsible energy usage, reducing carbon footprint.
## Hardware Solution & Components
Components Used :
 1. ACS712 Current Sensor :
Measures AC/DC current using the Hall Effect principle.
Compact and easy to interface with ESP32.
Provides real-time current measurement for monitoring power consumption.

2. ZMPT101B Voltage Sensor :
Measures AC voltage (110V/230V) using an isolation transformer.
Outputs a proportional analog signal for processing.
Works well with ESP32 ADC (Analog-to-Digital Converter).

3. Microcontroller: ArduinoUno & ESP32 (NodeMCU)
ESP32 acts as the brain of the system, performing the following tasks:
Reads current and voltage sensor data.
Calculates power consumption (Wattage) and energy usage (kWh).
Sends data to the cloud/web dashboard via MQTT protocol over WiFi.

4. Electrical Appliances - Bulb

Code:
https://github.com/Shindepooja30/Smart-meter/blob/main/Code%20hardware

Demo Video: 
https://github.com/Shindepooja30/Smart-meter/blob/main/hardware%20video.mp4


## Software Technologies 
Technologies Used :
https://github.com/Shindepooja30/Smart-meter/blob/main/software%20textstack.jpg

Demo Video :
https://github.com/Shindepooja30/Smart-meter/blob/main/software%20video.mp4
## Conclusion
This project aims to bridge the gap between traditional energy meters and modern smart energy management. By integrating IoT, web technologies, and data analytics, our Energy Monitoring System provides a real-time, cost-effective, and scalable solution to improve energy efficiency and sustainability.
