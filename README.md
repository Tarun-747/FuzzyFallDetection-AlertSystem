# Fuzzy Logic-Based Fall Detection and Alert System

This project involves designing and deploying a Fuzzy logic-based Android/iOS application for real-time fall detection, danger level estimation, and alert system. The app monitors the phone's accelerometer data to detect falls, measures sound levels, estimates danger levels using fuzzy logic, and sends alerts with GPS location for high danger levels.

## Features

1. **Real-Time Fall Detection**:
   - Monitors accelerometer data to detect falls when the app is ON.

2. **Sound Level Measurement**:
   - Automatically switches ON the microphone and measures the sound level upon detecting a fall.

3. **Fuzzy Logic-Based Danger Level Estimation**:
   - Uses fuzzy logic to estimate the level of danger (Low, Medium, High) based on sound and accelerometer levels.

4. **Automated Alerts**:
   - Sends an alert to another phone via TCP/IP or UDP network if the danger level is High.
   - Transmits the recorded sound and GPS location of the first phone.

5. **Buzzer Activation**:
   - Plays a buzzer sound on the first phone if the danger levels are Medium or High.
   - The sound level of the buzzer is proportional to the danger level.
