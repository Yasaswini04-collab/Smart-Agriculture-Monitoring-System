# Smart-Agriculture-Monitoring-System
IoT-based Smart Agriculture Monitoring System using ESP32, DHT22, and Soil moisture sensor.

# Title of the Project
Design and Implementation of an IoT-Based Smart Agriculture Monitoring System

# Problem Statement
Traditional irrigation systems often rely on manual observation or fixed schedules, which can lead to over-irrigation or under-irrigation. This results in water wastage, crop stress, and reduced agricultural productivity.

# Objective of the Project
- To Monitor soil moisture, temperature, and humidity
- To Reduce water wastage
- To Design a low-cost IoT solution

# Scope of the Project
-Suitable for small and medium farms
-Extendable to automation and cloud monitoring

# System Overview
The system uses sensors deployed in the field to collect environmental and soil data. An ESP32 microcontroller processes this data and applies intelligent decision logic at the edge level. Based on the conditions, alerts related to irrigation are generated.

# Tools Used
- ESP32
- DHT22
- Soil Moisture Sensor
- Arduino IDE
- DHT Library
- Wokwi Simulator

# Working Principle
- Sensors collect real-time data
- ESP32 processes data locally (edge computing)
- Alerts are generated based on predefined thresholds

# Data Flow Explanation
1.  Soil moisture sensor sends analog signal to ESP32 ADC pin
2.  DHT22 sends digital temperature and humidity data
3.  ESP32 processes raw data and converts it into meaningful values
4.  Decision logic evaluates conditions
5.  Alert or normal status is generated

# Advantages
- Low cost and easy to deploy
- Scalable and upgradable
- Real-time monitoring

# Conclusion
The project demonstrates a practical IoT-based smart agriculture monitoring system.
