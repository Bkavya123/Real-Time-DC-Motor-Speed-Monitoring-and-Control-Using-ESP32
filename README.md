# IoT-Based DC Motor Speed Control Using ESP32 Web Server

## Project Overview

This project demonstrates an IoT-based DC motor speed control system using an ESP32 microcontroller and an L298N motor driver. The ESP32 hosts a web server that provides a user-friendly slider interface accessible through any web browser. Users can remotely adjust the motor speed in real time using a smartphone, tablet, or computer connected to the same Wi-Fi network.

The slider value is converted into a PWM (Pulse Width Modulation) signal, which controls the speed of the DC motor through the L298N motor driver.

---

## Features

- Wireless motor speed control
- Web-based user interface
- Real-time PWM speed adjustment
- ESP32 web server implementation
- Mobile and desktop browser compatibility
- No additional mobile application required

---

## Hardware Components

| Component | Quantity |
|------------|------------|
| ESP32 Development Board | 1 |
| L298N Motor Driver Module | 1 |
| DC Motor | 1 |
| 9V/12V Power Supply | 1 |
| Breadboard | 1 |
| Jumper Wires | As Required |

---

## Circuit Connections

### ESP32 to L298N

| ESP32 Pin | L298N Pin |
|------------|------------|
| GPIO 27 | ENA |
| GPIO 26 | IN1 |
| GPIO 25 | IN2 |
| GND | GND |

### Motor Connections

| DC Motor | L298N |
|------------|------------|
| Terminal 1 | OUT1 |
| Terminal 2 | OUT2 |

### Power Supply

| Supply | L298N |
|------------|------------|
| +9V / +12V | 12V |
| GND | GND |

**Note:** Connect the ESP32 GND and L298N GND together.

---

## Software Requirements

- Arduino IDE
- ESP32 Board Package
- Wi-Fi Network
- Web Browser (Chrome, Edge, Firefox)

---

## Working Principle

1. ESP32 connects to the local Wi-Fi network.
2. A web page is hosted on the ESP32.
3. Users access the webpage through the ESP32 IP address.
4. A slider on the webpage sends speed values to ESP32.
5. ESP32 generates PWM signals based on slider input.
6. L298N motor driver adjusts the motor speed accordingly.

---

## Project Workflow

```text
User Browser
      │
      ▼
ESP32 Web Server
      │
      ▼
PWM Signal Generation
      │
      ▼
L298N Motor Driver
      │
      ▼
DC Motor Speed Control
```

---

## Web Interface

The web page contains:

- Speed control slider
- Real-time speed adjustment
- Responsive design for mobile and desktop devices

---

## Applications

- Smart Home Automation
- Industrial Automation
- Conveyor Belt Systems
- Robotic Vehicles
- Remote Machine Control
- IoT-Based Motor Monitoring

---

## Advantages

- Wireless operation
- Simple user interface
- Low-cost implementation
- Real-time control
- Easy integration with IoT systems

---

## Future Enhancements

- Motor speed feedback monitoring
- Mobile application integration
- Cloud connectivity
- Voice-controlled operation
- Multiple motor control

---

## Technologies Used

- ESP32
- Embedded C/C++
- PWM Control
- Web Server Technology
- IoT
- L298N Motor Driver

---

## Results

Successfully developed a web-based DC motor speed control system using ESP32. The motor speed can be adjusted remotely through a web browser using a slider interface, providing efficient and real-time wireless motor control.

---

## Author

**BONALA KAVYA**

Electronics and Communication Engineering (ECE)

Embedded Systems | IoT | Arduino | ESP32
