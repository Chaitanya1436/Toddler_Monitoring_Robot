# Baby Monitoring Robot Project

## Overview
This project involves creating a robot that follows a baby, detects crying, and sends notifications to parents. It uses an ESP32 for sensor control and notifications, and an ESP32-CAM for video streaming.

## Components Used
- **Arduino UNO**: Main controller
- **ESP32-CAM**: Video streaming
- **Ultrasonic Sensors**: For distance measurement
- **Sound Sensor**: To detect crying
- **Moisture Sensor**: To detect spills
- **L298N Motor Driver**: For motor control
- **Motors**: For movement

## Wiring Diagram
- [Block Diagram](docs/Block_Diagram.png)

## Code
- **ESP32_Code.ino**: Main ESP32 code
- **ESP32_CAM_Code.ino**: ESP32-CAM code

## Setup Instructions
1. Connect the components as per the wiring diagram.
2. Upload the `ESP32_Code.ino` to the ESP32.
3. Upload the `ESP32_CAM_Code.ino` to the ESP32-CAM.
4. Configure the WiFi credentials and Telegram bot in the code.
5. Start the ESP32-CAM and access the video stream via the provided URL.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements
- NewPing Library
- UniversalTelegramBot Library
- ESP32 Camera Library
