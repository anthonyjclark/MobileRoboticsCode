# Mobile Robotics Code

Code for CS 181R---Mobile Robotics---at Pomona College.

## Directory Structure

```text
.
├── Examples
│  ├── Encoders
│  ├── MotorControl
│  ├── ProportionalControl
│  ├── WSHeartbeat
│  └── WSHeartbeatRefactored
├── Simulation
│  └── positionControl.py
├── Web
│  └── index.html
├── include
│  ├── display.h
│  ├── forwardkinematics.h
│  ├── intervaltimer.h
│  ├── motorcontrol.h
│  ├── positioncontrol.h
│  └── wscommunicator.h
└── README.md
```

The Arduino-based motor code is split into the `Examples` and `include` directories. The `include` directory contains headers files for use in all complete programs.

## Life of an Arduino Sketch

1. Creating an `.ino` file.
2. (Optionally) include custom header and source files.
3. (Optionally) include official or 3rd party libraries.
4. Build (compile) the sketch.
5. Upload (flash) the sketch.
6. The board resets and the bootloader jumps to the sketch.

## Dependencies

You will need to install

- [Arduino](https://www.arduino.cc/en/software)
- The [Espressif Systems ESP32 board manager](https://github.com/espressif/arduino-esp32)
- Libraries
  - [WebSocket Server and Client for Arduino](https://github.com/Links2004/arduinoWebSockets)
  - [ESP32Encoder](https://github.com/madhephaestus/ESP32Encoder/)
  - [QMC5883L Compass Arduino Library](https://github.com/mprograms/QMC5883LCompass)
  - [SparkFun Qwiic Time-of-Flight Sensor VL53L5CX Arduino Library](https://github.com/sparkfun/SparkFun_VL53L5CX_Arduino_Library)
  - [U8g2: Library for monochrome displays](https://github.com/olikraus/u8g2)
