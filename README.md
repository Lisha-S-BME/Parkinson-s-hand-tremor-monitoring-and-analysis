# Real-Time Hand Tremor Monitoring System for Parkinson’s Disease

## 🧠 Overview
This project is a wearable biomedical monitoring system designed to detect and classify hand tremors in Parkinson’s disease patients using sensor-based signal acquisition and real-time analysis. The system combines Arduino-based hardware with MATLAB-based signal processing to provide continuous monitoring and severity classification.

## 🎯 Problem Statement
Parkinson’s disease causes involuntary hand tremors that worsen over time. Continuous monitoring in real-life conditions is difficult outside clinical environments.

This project aims to:
- Detect tremor activity in real time
- Classify tremor severity levels
- Provide immediate alerts to users and caregivers
- Enable basic remote monitoring using Bluetooth communication

## 👥 Target Users
- Parkinson’s disease patients  
- Caregivers and family members  
- Healthcare professionals  

## 💡 Solution
A sensor-based wearable system that:
- Captures wrist motion using MPU6050 sensor
- Uses threshold-based logic to classify tremor levels
- Displays real-time status on LCD
- Provides LED and buzzer alerts for severity indication
- Sends data to mobile devices via Bluetooth
- Uses MATLAB for signal simulation and frequency analysis

## 🔧 Hardware Used
- Arduino Nano  
- MPU6050 Accelerometer + Gyroscope  
- Flex Sensor  
- I2C LCD Display  
- LEDs (Green, Yellow, Red)  
- Buzzer  
- HC-05 Bluetooth Module  
- Breadboard and connecting wires  

## 💻 Software Used
- Arduino IDE  
- MATLAB  
- Embedded C Programming  

## ⚙️ Working Logic
- MPU6050 captures acceleration values from wrist movement  
- Tremor classification is based on thresholds:
  - Normal: 1.0 – 1.9  
  - Mild Tremor: 2.0 – 2.9  
  - High Tremor: ≥ 3.0  
- Output is displayed on LCD and indicated using LEDs and buzzer  
- Data is transmitted via Bluetooth for remote viewing  
- MATLAB simulates tremor signals (~5 Hz frequency validation)

## 📊 Features
- Real-time tremor detection  
- Severity classification system  
- Multi-level alert system (LCD, LED, buzzer)  
- Wireless Bluetooth communication  
- MATLAB-based signal validation  
- Wearable prototype design  

## 🎥 Demonstrations

- 📌 PowerPoint Presentation:  
  https://drive.google.com/file/d/1YkOlkfav6zBrzKj8MsykQ9FQaOXegsAm/view?usp=drivesdk  

- 📌 Hardware Demo Video:  
  https://drive.google.com/file/d/1gkI12efmiTqExFKt-m-5Q4VM4rDWTyUG/view?usp=drivesdk  

- 📌 MATLAB Simulation Video:  
  https://drive.google.com/file/d/1Arebi8exJOZqhskv1juYYupq5dq5sZfE/view?usp=drivesdk  

## 📈 Impact
- Helps in early monitoring of Parkinson’s disease tremors  
- Reduces dependency on continuous hospital monitoring  
- Assists caregivers in real-time patient observation  
- Demonstrates integration of biomedical engineering, embedded systems, and signal processing  

## 🚀 Future Improvements
- Machine learning-based tremor classification  
- Mobile application integration  
- Cloud-based patient monitoring dashboard  
- Improved sensor fusion accuracy
