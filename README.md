# Telemetry-IEEE-KiCad
Design a telemetry system using BMP280, DHT11, MPU6050, NEO-6M sensors
# Telemetry System Design using KiCad

## Project Overview
This project presents the schematic design of a telemetry system that collects
environmental, motion, and location data using multiple sensors.

## Components Used
- Arduino UNO
- BMP280 – Pressure and Temperature Sensor
- DHT11 – Temperature and Humidity Sensor
- MPU6050 – Accelerometer
- NEO-6M – GPS Module

## Communication Interfaces
- I²C: BMP280, MPU6050
- Digital GPIO: DHT11
- UART (D0, D1): NEO-6M GPS

## System Architecture
Sensors are interfaced with the Arduino UNO, which acts as the central controller.
The collected telemetry data is transmitted via serial communication to an
external system for logging and analysis.

## Design Tool
- KiCad (Schematic Design)

## Author
Prajeet Varma Mudunuri

