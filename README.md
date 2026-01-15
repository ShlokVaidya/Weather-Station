# Weather Station

## Overview
A comprehensive weather monitoring system that measures temperature, humidity, pressure, and other atmospheric conditions.

## Features
- Real-time temperature and humidity monitoring
- Atmospheric pressure measurement
- Data logging and storage
- User-friendly interface

## Hardware Requirements

### Bill of Materials (BOM)
*Assuming Rs89 = $1, Also note 2components have a minimum order quantity of 2, hence a gap of $3.28 in total cost calculations*
| Component            | Quantity | Notes                                    | Price   | Purchase Link                                                                                                                                                                |
| -------------------- | -------- | ---------------------------------------- | ------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Microcontroller**  | 1        | ESP8266 / ESP32 / Arduino (ESP8266 used) | ₹280.00 | [https://www.amazon.in/Robocraze-ESP8266-Nodemcu-Internet-Development/dp/B0829Z1W6Y/](https://www.amazon.in/Robocraze-ESP8266-Nodemcu-Internet-Development/dp/B0829Z1W6Y/)   |
| **DHT22 Sensor**     | 1        | Temperature & Humidity                   | ₹219.00 | [https://www.amazon.in/Robocraze-Digital-Temperature-Humidity-Sensor/dp/B0D6R8RMVV/](https://www.amazon.in/Robocraze-Digital-Temperature-Humidity-Sensor/dp/B0D6R8RMVV/)     |
| **BMP280 Sensor**    | 2 (min)  | Pressure & Altitude                      | ₹128.00 | [https://www.amazon.in/Robodo-Pressure-Precision-Arduino-Replace/dp/B07DDJ3MFX/](https://www.amazon.in/Robodo-Pressure-Precision-Arduino-Replace/dp/B07DDJ3MFX/)             |
| **Power Supply**     | 1        | 5V USB / 5V 600 mAh Battery              | ₹309.00 | [https://www.amazon.in/gp/product/B0CYQ6H8FW/](https://www.amazon.in/gp/product/B0CYQ6H8FW/)                                                                                 |
| **Resistors**        | 2        | 7.5 kΩ pull-up resistors                 | —       | [https://www.amazon.in/7-5K-ohm-Watt-Resistor-Tolerance/dp/B0DQJG1MHL/](https://www.amazon.in/7-5K-ohm-Watt-Resistor-Tolerance/dp/B0DQJG1MHL/)                               |
| **Raindrop Sensor**  | 2 (min)  | Rain detection                           | ₹163.00 | [https://www.amazon.in/Robodo-Electronics-Raindrops-Detection-Humidity/dp/B00NEINLWO/](https://www.amazon.in/Robodo-Electronics-Raindrops-Detection-Humidity/dp/B00NEINLWO/) |
| **PCB / Breadboard** | 1        | Circuit assembly & testing               | ₹279.00 | [https://www.amazon.in/ePro-Labs-KIT-0010-Breadboard-Pieces/dp/B01BLJGS7M/](https://www.amazon.in/ePro-Labs-KIT-0010-Breadboard-Pieces/dp/B01BLJGS7M/)                       |
| **Prototype Board**  | 1        | Final prototyping                        | ₹248.00 | (Local vendor / optional)                                                                                                                                                    


Total Cost: ₹1577.00 | $17.72
Due to Min Order Qty, Actual Cost: ₹1868 | $21 with a buffer of $3 for conversion fees.

Also note:
Any extra/excess grant will be duely returned.

## BOM
![Bill of Material](./images/image.png)
## Schematic
![Weather Station Schematic](./images/circuit_image.png)

## Installation
1. Assemble hardware according to schematic
2. Flash firmware to microcontroller
3. Connect to power supply
4. Monitor via serial interface or web dashboard

## Usage
```bash
# Serial monitoring example
screen /dev/ttyUSB0 115200
```

## License
See LICENSE file for details.
