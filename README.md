
# Smart Parking Spot Detection System (IoT)

An IoT-based smart parking system that detects parking slot occupancy using ESP32, ultrasonic sensors, and IR sensors. The system provides real-time parking status and uploads data to the ThingSpeak cloud platform.

## Features
- Detects parking slot occupancy using ultrasonic sensor
- Tracks vehicle entry and exit using dual IR sensors
- Real-time monitoring through ThingSpeak IoT dashboard
- LED indicators showing parking availability
- WiFi-based communication using ESP32

## Hardware Used
- ESP32 Microcontroller
- Ultrasonic Sensor (HC-SR04)
- IR Sensors
- LEDs
- Breadboard and jumper wires

## Software Used
- Arduino IDE
- ThingSpeak IoT Cloud
- ESP32 WiFi Libraries

## Working
The ultrasonic sensor measures the distance between the sensor and the parking surface. When a vehicle occupies the slot, the distance decreases and the system marks the slot as occupied. IR sensors detect vehicle entry and exit events. The ESP32 processes this data and sends real-time updates to the ThingSpeak cloud.

## Results
The system achieved around **90% detection accuracy** during prototype testing after multiple calibration experiments.

## Future Improvements
- Mobile app for parking availability
- Multi-slot parking system
- Automatic gate control using servo motors
