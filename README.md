# VSMmonitor
# VSMmonitor

## Motivation
The Vital Sign Monitoring System is designed to address the critical need for accurate and reliable monitoring of vital signs, including temperature, ECG, body impedance, and pulse rate. The motivation behind this project is to provide medical professionals and caregivers with a powerful tool to quickly and accurately assess a patient's vital signs, enabling timely medical intervention and care.

## Project Overview
The Vital Sign Monitoring System consists of two separate devices connected via Bluetooth Low Energy (BLE). The hardware board, equipped with a range of sensors and a microcontroller, measures vital signs, while a mobile or PC application collects and displays this information in a user-friendly interface.

## Key Components
### Microcontroller
- Silicon Labs EFR32BG13P732F512GM48-D
  - Arm Cortex M-4
  - 512 kB Flash
  - 64 Kb RAM
  - BLE and Bluetooth 5 support

### Sensors
- ECG Sensor: Analog Devices AD8232
  - Low supply current
  - Lead-off detection
- Temperature Sensor: Melexis Technologies MLX90614ESF-AAA
  - Infrared sensing
  - High accuracy
- Body Impedance Sensor: Analog Devices AD5941BCPZ
  - 16-Bit ADC
  - Voltage/Current/Impedance measurement capability

### Additional Components
- Power Management IC (BQ25570)
- Boost Converter (TLV61220)
- Custom Inverted F Antenna
- LCD Screen (LS013B7DH03)
- Load Switch (SN74LVC1G66DBVR)
- On-board 8MB Flash (MX25R8035FM1IL0)

## Features
- Real-time monitoring of temperature, ECG, body impedance, and pulse rate.
- Energy-efficient design with solar power harvesting and USB charging.
- High precision sensors for accurate measurements.
- Bluetooth Low Energy (BLE) for wireless data transmission.
- User interface for data visualization and storage.
- Compact form factor for portability.

## Acknowledgments
Special thanks to Kevin Tom for their contributions to this project. Inspiration from Kevin Tom.



