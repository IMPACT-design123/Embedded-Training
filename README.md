# Embedded Systems Training 🚀

A hands-on embedded systems training repository focused on ESP32 programming, wireless communication, IoT monitoring, CAN bus communication, and real-time operating systems.

This repository documents my practical learning journey through hardware interfacing, communication protocols, sensor integration, cloud connectivity, and multitasking using FreeRTOS.

## 🛠️ Technologies & Tools

- **Microcontroller:** ESP32
- **Programming Language:** C/C++ (Arduino framework)
- **Communication Protocols:** SPI, UART, CAN
- **Wireless Communication:** LoRa
- **IoT Platform:** Adafruit IO, Blynk IoT
- **Real-Time Operating System:** FreeRTOS
- **Sensors:** DHT11 temperature and humidity sensor
- **Hardware Modules:** MCP2515 CAN controller, buzzer, RGB LEDs
- **Development Environment:** Arduino IDE

## 📂 Projects

### 1. ESP32 LoRa Wireless Communication Using SPI

**File:** `ESP32 LoRa Wireless Communication using SPI.c`

- Established wireless communication between two ESP32-based LoRa modules.
- Used SPI for communication between the ESP32 and LoRa modules.
- Implemented sender and receiver programs.
- Verified message transmission and reception using the Arduino IDE Serial Monitor.

**Key concepts:** SPI, LoRa, wireless communication, serial debugging.

### 2. ESP32 CAN Bus Communication Using MCP2515

**File:** `ESP32 CAN Bus Communication using MCP2515.c`

- Implemented CAN bus communication using ESP32 and MCP2515 CAN controller modules.
- Configured CAN communication at 500 kbps with an 8 MHz MCP2515 oscillator setting.
- Developed transmitter and receiver programs.
- Used the Serial Monitor to send and observe CAN messages.

**Key concepts:** CAN protocol, SPI interfacing, MCP2515, embedded communication.

### 3. ESP32 Temperature and Humidity Monitoring with Adafruit IO

**File:** `ESP32 DHT11 Monitoring with Adafruit IO and Buzzer Control.c`

- Interfaced a DHT11 sensor with the ESP32 to obtain temperature and humidity readings.
- Connected sensor data to the Adafruit IO cloud platform.
- Used temperature-based alerts with a buzzer.
- Included cloud-based buzzer control through an Adafruit IO dashboard.

**Key concepts:** Sensor interfacing, IoT, cloud dashboards, GPIO, alert systems.

### 4. ESP32 FreeRTOS Multitasking with Three Tasks and Two Queues

**File:** `ESP32 FreeRTOS Multitasking with Three Tasks and Two Queues.c`

- Implemented multitasking using FreeRTOS on the ESP32.
- Organized sensor reading, data processing, and alert handling into separate tasks.
- Used two queues to exchange data between tasks.
- Implemented temperature threshold-based alert handling using a DHT11 sensor and buzzer.

**Key concepts:** RTOS, tasks, queues, inter-task communication, real-time embedded programming.

## 📁 Additional Projects

| Project | File |
|---|---|
| ESP32 UART2 Serial Communication Using Loopback | `ESP32 UART2 Serial Communication Using Loopback.c` |
| ESP32-Based RGB LED Control Using Blynk IoT | `ESP32-Based RGB LED Control Using Blynk IoT.c` |
| ESP32 Temperature Alert Using Simulated Temperature | `ESP32 Temperature Alert System Using Simulated Temperature.c` |
| Smart Temperature Alert System Using ESP32 | `Smart Temperature Alert System Using ESP32.c` |

## ⚙️ Getting Started

### Prerequisites

- ESP32 development board
- Arduino IDE
- Appropriate USB driver for your ESP32 board
- Required sensors and modules for the selected project
- A USB data cable
- Internet connectivity for cloud-based projects

### Setup Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/IMPACT-design123/Embedded-Training.git
   ```

2. Open the cloned repository folder.

3. Open the source file for the project you want to run in Arduino IDE.

4. Install the required Arduino libraries for that project.

5. Connect the ESP32 and the relevant hardware according to the pin configuration in the source code.

6. Select your ESP32 board and the correct serial port.

7. Upload the program and open the Serial Monitor at the baud rate specified in the code.

8. For IoT projects, configure your Wi-Fi credentials and platform credentials before uploading.

**Note:** Hardware connections, libraries, credentials, and configuration settings differ between projects. Review the individual source file before running it.

## 🎯 Learning Outcomes

Through these projects, I am developing practical skills in:

- Embedded C/C++ programming
- ESP32 hardware interfacing
- SPI, UART, CAN, and LoRa communication
- Sensor data acquisition and monitoring
- IoT cloud integration
- FreeRTOS multitasking and queue-based communication
- Hardware debugging and serial monitoring

## 👨‍💻 About This Repository

This repository serves as a record of my hands-on embedded systems training and practical implementation of microcontroller-based projects.

I aim to strengthen my understanding of embedded software development, communication protocols, real-time systems, and connected devices through continuous experimentation and learning.

## 📌 Repository

GitHub: [IMPACT-design123/Embedded-Training](https://github.com/IMPACT-design123/Embedded-Training)

---

*Built while learning, testing, debugging, and exploring embedded systems.*
