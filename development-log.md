# Development Log
This development log documents all the progress, challenges, and steps I take towards developing the ESP32-C6 smartwatch.

## November 22 - Initial Setup
### Objective
Set up the watch development environment and develop the foundation for future projects and functions on the smartwatch.
### Hardware
- Waveshare ESP32-C6 Touch AMOLED 2.06-inch development board
- ESP32-C6 RISC-V 32-bit microcontroller
### Development Environment
- Arduino IDE
- ESP32 Arduino Core
- Arduino GFX Library
- C++
### What I Did
- Installed Arduino IDE
- Set up board & port (ESP32C6 Dev Board & COM port, found from device manager)
- Downloaded Waveshare example code including HelloWorld.ino & the libraries folder
- Uploaded HelloWorld.ino & libraries into Arduino IDE (added libraries folder to Arduino folder, opened HelloWorld.ino)
- Compiled manufacturer's HelloWorld.ino code and successfully uploaded to watch dev board
### What I learned
- How to set up development environment for this project
- setup() and loop(), and the structure of the provided HelloWorld.ino code (e.g the Arduino_GFX and bus)
