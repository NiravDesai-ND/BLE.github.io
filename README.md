# BLE.github.io
# BLE Read and Write Example - Electrify Energy

This is a web-based interface for interacting with BLE (Bluetooth Low Energy) devices, specifically designed for Electrify Energy Private Limited. The application allows users to connect to BLE devices, send specific commands, and read the responses from the device. 

The commands and responses are related to various device parameters like serial number, PCB number, firmware version, SIM ICCID, SIM IMEI, and more. It also supports actions like memory erase and relay control.

## Features

- **Scan for BLE Devices**: Scan and connect to nearby Bluetooth devices that support a custom service.
- **Send Commands**: Send predefined commands to the connected device for retrieving or modifying specific information.
- **Display Responses**: The application displays the responses from the BLE device in real-time on the UI.

### Supported Commands

- **Serial Number**: Retrieves the serial number of the connected device.
- **Read PCB Number**: Retrieves the PCB number of the device.
- **Memory Erase**: Initiates a memory erase operation on the device.
- **Relay Connect**: Connects the relay on the device.
- **Relay Disconnect**: Disconnects the relay on the device.
- **Firmware Version**: Retrieves the firmware version of the device.
- **SIM ICCID**: Retrieves the ICCID (Integrated Circuit Card Identifier) of the SIM.
- **SIM IMEI**: Retrieves the IMEI (International Mobile Equipment Identity) of the SIM.

## Technologies Used

- **HTML**: For structuring the web page.
- **CSS**: For styling and responsiveness.
- **JavaScript**: For Bluetooth operations and event handling using the Web Bluetooth API.

## Prerequisites

To use this application, your browser must support the Web Bluetooth API. At the time of writing, this is supported in most Chromium-based browsers (e.g., Google Chrome).

- **Google Chrome (latest version)** is recommended.
- Your device must have Bluetooth capabilities.

## How to Use

1. **Clone the Repository**:
   To get started, clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/ble-read-write-example.git
