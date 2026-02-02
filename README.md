# iot-train-safety-gsm-gps
IoT train safety project using GSM, GPS, and sensors to detect hazards and send live SMS alerts with location.
# IoT Train Safety Monitoring System using GSM & GPS

This project is an IoT-based railway safety monitoring system developed using Embedded C on Arduino.

## Objective

To prevent railway accidents by detecting:
- Track cracks
- Obstacles on track
- Fire inside train

The system automatically stops the train and sends an emergency SMS with live GPS location.

## Technologies Used

- Embedded C (Arduino)
- GSM Module for SMS alerts
- GPS Module for live location tracking
- Ultrasonic Sensor for obstacle detection
- IR Sensors for track crack detection
- Fire Sensor
- Buzzer alert system
- Motor control using digital pins

## Working

When any abnormal condition is detected:
1. Train is stopped immediately
2. Buzzer is activated
3. GPS location is captured
4. SMS is sent with Google Maps link to emergency contact

## Code Files

- Main Arduino program
- GPS integration using TinyGPS library
- Sensor interfacing and motor control logic

## Outcome

This system provides real-time safety monitoring and accident prevention in railway systems using IoT.

