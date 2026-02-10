Smart Milk Quality Assurance System
🎯 Objective

To develop a low-cost IoT and Machine Learning based system for real-time milk quality monitoring and early detection of spoilage or adulteration.

📘 Introduction

Milk is highly perishable, and traditional quality testing methods are slow and manual. This project provides an automated solution using sensors and machine learning to ensure milk safety during storage and transportation.

📡 System Overview

The system measures pH, temperature, and TDS values of milk using sensors connected to a NodeMCU microcontroller. Based on these parameters, a machine learning model classifies the milk quality.

🛠️ Hardware Used

NodeMCU (ESP8266 / ESP32)

pH Sensor

Temperature Sensor (DS18B20)

TDS Sensor

OLED Display (128×64)

Buck Converter (LM2596)

🧠 Machine Learning

Algorithm: K-Nearest Neighbors (KNN)

Output: Fresh / Moderate / Spoiled

🧵 Working Flow

Sensors collect milk quality data

NodeMCU processes the values

ML model analyzes the data

Quality result is displayed

📦 Applications

Dairy farms

Milk transportation

Quality control units

Small milk vendors

✅ Conclusion

This project demonstrates a reliable and cost-effective approach to milk quality assurance by combining IoT sensors with machine learning, reducing manual testing and improving food safety.
