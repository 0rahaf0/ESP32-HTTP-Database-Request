# ESP32 HTTP Database Request

This project demonstrates how to use an ESP32 to make HTTP requests to retrieve data from a database and control LEDs based on the received data.

## Project Overview

- **Objective**: Retrieve directional commands (forward, backward, left, right) from a database using HTTP requests and control corresponding LEDs.
- **Components**:
  - ESP32 Development Board
  - 4 LEDs (Forward, Backward, Right, Left)
  - Jumper wires
  - Breadboard

## Hardware Setup

- **Connections**:
  - Forward LED: GPIO 32
  - Backward LED: GPIO 33
  - Right LED: GPIO 25
  - Left LED: GPIO 26

## Software Requirements

- **Libraries**:
  - `WiFi.h` - for WiFi connectivity
  - `HTTPClient.h` - for making HTTP requests

## Code Explanation

The `main.ino` file contains the code to connect the ESP32 to a WiFi network and make HTTP GET requests to specified URLs. The data retrieved from these URLs is used to control LEDs based on the received commands.

- **WiFi Connection**:
  The ESP32 connects to a predefined WiFi network.

- **HTTP Requests**:
  The code makes HTTP GET requests to URLs (representing the database endpoints) and retrieves data, which is then used to control the LEDs.

<img width="949" alt="web" src="https://github.com/user-attachments/assets/7a0efc8c-93b2-44d8-95c6-7da28046be2f">
