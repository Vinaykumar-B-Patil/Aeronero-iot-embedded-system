# Aeronero Air-to-Water System – Embedded IoT Platform

## Overview
Embedded firmware and hardware platform developed for real-time sensor acquisition,
calibration, and cloud telemetry in an air-to-water generation system.

This system integrates multiple sensors, performs real-time data processing,
and transmits structured telemetry to a cloud dashboard via Wi-Fi.

## System Architecture
- STM32 Microcontroller
- Multi-sensor acquisition pipeline
- Real-time calibration engine
- JSON-based telemetry formatting
- Wi-Fi cloud transmission

## Key Features
- Real-time acquisition from 8+ sensors
- Digital calibration algorithms
- Structured telemetry packets (JSON)
- Reliable Wi-Fi cloud connectivity
- Robust fault detection and recovery

## Sensors Integrated
- TDS
- pH
- Ultrasonic level sensor
- Air quality sensor
- Temperature sensor
- Humidity sensor
- Water flow sensor

## Technologies Used
- Embedded C, STM32 HAL/LL
- UART, SPI, I2C
- JSON telemetry formatting
- Wi-Fi communication
- Sensor calibration algorithms

## Highlights
- Achieved 3–5% measurement accuracy improvement through calibration
- Reduced sensor noise by 30% via digital filtering
- Enabled real-time cloud monitoring

## Future Improvements
- OTA firmware update
- Edge ML based anomaly detection
- MQTT protocol integration
