# Speech Recognition System 

A simple **Speech Recognition System** built using an **Arduino Uno** and an **HC-05 Bluetooth module**. The system receives voice commands from a smartphone, where speech is recognized by a mobile application and transmitted to the Arduino via Bluetooth. Based on the received command, the Arduino performs the corresponding action, such as controlling an output device.

## Features

* Speech recognition using a smartphone application
* Wireless Bluetooth communication with HC-05
* Real-time command execution
* Controls LEDs, relays, and other output devices
* Easy-to-understand Arduino implementation
* Beginner-friendly embedded systems project

## Hardware Requirements

* Arduino Uno/Nano
* HC-05 Bluetooth Module
* LED or Relay Module
* Breadboard
* Jumper Wires
* Android smartphone with a speech recognition Bluetooth application

## Circuit Connections

### HC-05 → Arduino

| HC-05 Pin | Arduino Pin             |
| --------- | ----------------------- |
| VCC       | 5V                      |
| GND       | GND                     |
| TXD       | D10 (SoftwareSerial RX) |
| RXD       | D11 (SoftwareSerial TX) |

## How It Works

1. Upload the Arduino sketch to the board.
2. Pair the HC-05 Bluetooth module with your smartphone.
3. Open a Bluetooth voice-control application.
4. Speak a predefined voice command such as **"ON"** or **"OFF"**.
5. The mobile application converts the spoken command into Bluetooth serial data.
6. The Arduino receives the command and controls the connected output device.

##  Compatible Applications

* Arduino Voice Control
* Bluetooth Voice Control
* BT Voice Control
* AMR Voice

##  Applications

* Speech-controlled devices
* Home automation systems
* Smart lighting
* Assistive technology
* Robotics
* Educational embedded systems projects

##  Future Enhancements

* Support multiple voice commands
* Offline speech recognition
* Custom Android application
* ESP32 Wi-Fi integration
* Google Assistant or Alexa integration
* Feedback through LCD or OLED display
