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
| Component        | Quantity | Notes                  | Price (₹) | Price (USD) |
| ---------------- | -------- | ---------------------- | --------- | ----------- |
| Microcontroller  | 1        | ESP32 or Arduino       | ₹280.00   | $3.15       |
| DHT22 Sensor     | 2        | Temperature & Humidity | ₹219.00   | $2.46 (x2)  |
| BMP280 Sensor    | 1        | Pressure & Altitude    | ₹128.00   | $1.44       |
| Power Supply     | 1        | 5V USB or Battery      | ₹309.00   | $3.47       |
| Resistors        | 2        | 7.4kΩ pull-up          | ₹0.00*    | $0.00*      |
| Raindrops sensor | 2        | Raindrops              | ₹163.00   | $1.83 (x2)  |
| PCB/Breadboard   | 1        | For assembly           | ₹279.00   | $3.13       |
| Prototype board  | 1        | Prototyping            | ₹199.00   | $2.24       |

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
