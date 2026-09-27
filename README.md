# ESP8266 Wi-Fi Web-Controlled Robot

## Project Overview

This project is a Wi-Fi web-controlled mobile robot based on the ESP8266 NodeMCU.

The robot can be controlled through a web interface using a mobile phone or laptop. The user first connects their device to the ESP8266 Wi-Fi network. After connecting, a web page is provided through which the robot can be controlled.

The ESP8266 NodeMCU acts as the central processing and decision-making unit of the robot. It receives commands from the web interface and controls the robot's components accordingly.

The ESP8266 is programmed using the Arduino programming environment.

## Features

- Wi-Fi-based wireless control
- Web-based control interface
- Control using a mobile phone or laptop
- ESP8266 NodeMCU as the main controller
- Arduino programming
- Motor control

## Hardware

- ESP8266 NodeMCU
- L298N Motor Driver
- DC Motors
- Robot chassis
- Battery
- Wheels

## Software

- Arduino IDE
- C/C++ (Arduino)
- HTML
- ESP8266 Wi-Fi libraries

## How It Works

1. The ESP8266 creates a Wi-Fi network.
2. A mobile phone or laptop connects to the ESP8266.
3. The user accesses the robot's web interface.
4. Control commands are sent through the web interface.
5. The ESP8266 receives and processes the commands.
6. The ESP8266 sends the appropriate signals to the motor driver.
7. The motors move the robot according to the received commands.

## Project Structure

ESP8266-WiFi-Controlled-Robot/
│
├── README.md
├── robot.ino
├── images/
└── report/

