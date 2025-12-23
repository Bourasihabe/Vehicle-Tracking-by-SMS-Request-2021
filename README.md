# Vehicle-Tracking-by-SMS-Request-2021
Vehicle Tracking using GPS, triggered by SMS Request - Aug 2021

## Project Overview
This project is an embedded vehicle tracking system designed to provide real-time location information upon user request. The system allows users to remotely query the vehicle’s position via SMS and receive an automatic response containing the current geographic coordinates.

In addition to SMS-based tracking, the system uploads real-time location data to a cloud IoT platform, enabling continuous monitoring and historical analysis.

---

## System Architecture

### Hardware Components
- Arduino Nano
- GPS module NEO-6M
- GSM module SIM800L
- Power supply unit

### Software & Platforms
- Embedded firmware (Arduino)
- AT-command-based GSM communication
- ThingSpeak IoT platform

---

## Working Principle

### Location Acquisition
1. The GPS module continuously receives satellite signals.
2. The Arduino processes NMEA data to extract latitude and longitude.

### SMS-Based Tracking
1. A user sends an SMS request to the GSM module.
2. Upon receiving the request:
   - The system retrieves the current GPS coordinates.
   - A reply SMS is sent containing the vehicle’s real-time location.

### Cloud Data Logging
1. GPS coordinates are periodically uploaded to ThingSpeak via GSM.
2. Location data can be visualized remotely on dashboards or maps.

---

## Key Features
- Real-time vehicle location tracking
- SMS-triggered location requests
- Automatic SMS response with GPS coordinates
- Cloud-based location logging
- Reliable operation using GSM communication

---
