# GoGo Board 6
The main portal for the GoGo Board version 6

<img src="/gogo6_overview.png" width="600" height="485">


## [Latest Firmware](https://gogo-board-project.gitbook.io/gogo6-demo/getting-started/firmware-updates)
* [Firmware Update Tool](https://github.com/MomePP/gogo-updater-electron/releases/latest)
  * Firmware 15.x or older must use the legacy updater - [GoGo Updater v0.5.0](https://github.com/MomePP/gogo-updater-electron/releases/tag/version-0.5.0)
* [Latest ESP firmware (main CPU)](https://github.com/LILCMU/GoGoBoard-ESP32/releases/latest)
* [Latest STM firmware (communication CPU)](https://github.com/LILCMU/GoGoBoard-STM32/releases/latest)
* [Latest Arduino firmware (arduino core CPU)](https://github.com/LILCMU/GoGoBoard-Arduino-Core/releases/latest)

## Feature Highlights
* Screen with UI to observe and control without coding. Allow users to play around with the functionalities before drilling into programming. 
* Runs Logo. Supports Logo programming language developed at MIT. Suitable for learning about powerful ideas in robotics and coding. Offers a drag-and-drop visual programming environment.
* Low threshold, high ceiling. Easy to get started (both for students and teachers) but is powerful enough to fulfill the most demanding tasks (e.g. via the Arduino-core)
* Well designed abstraction of modern robotics and IoT functionalities. Allow learners to focus on their ideas more than the technical details.
* Wifi connectivity allows wireless access from iPads and other network-connected platforms.

## Hardware Specifications
* __Triple CPU__
  * ESP32 Wi-Fi & Bluetooth MCU - Runs the user program and manages most underlying components
  * STM32 - Handles USB communications and control DC Motors
  * STM32 - Arduino-core. Allows Arduino programming and can interact with the ESP32 CPU.
* __2" Color screen and navigation controls__ - Display sensor values and control output ports without needing a computer. 
* __4x Analog sensor inputs__ - Compatible with analog Grove sensors. 12-bit resolution (Software capped to 10-bit). RGB LEDs on each port displays red, yellow, and green for easy observation.
* __4x Bi-directional DC motor ports__ - SMT connector, supplies maximum 0.5 Amps @5V per port (based-on a LB1836M driver). Suitable for small motors and LEDs. LEDs on each port show on/off states and direction.
* __4x Servo motor ports__ - Compatible with most hobby 5V servos
* __2x Expansion ports__ - Uses I2C for communication
* __3x Special ports__ - Connects to the Arduino-core CPU. Can be easily programmed via an auxilary USB port. Shipped with support for ultrasonic, digital temperature and RH sensors and Neo Pixel LEDs. 
* __Built-in Sensors__ - Gyro/Accelerometers, Gesture sensors, Lux meter, color sensor, loudness sensor.
* IR transciver
* Built-in beeper
* On/off power switch
* USB-C for power and communication
* Raspberry Pi GPIO connector
* RGB LEDs on the underside.

