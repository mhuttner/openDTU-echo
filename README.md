# openDTU Echo

PCB for openDTU onBattery

This PCB can be easily ordered from JLCPCB with assembly, but the ESP32-S3 and the Ebyte E49-900M20S module need to be soldered by hand.

## Features

![PCB](./images/3d.png)

- ESP32-S3
- CMT2300A Chip in an Ebyte E49-900M20S module, NRF Chip is **not** supported
- Three ADUM1201 isolators with Ports for Victron VE.Direct Charge controllers / Smart Shunt
- SN65HVD230 CAN transceiver connected to RJ45 connector (Pin 4 and 5)
- ISL3178EIBZ RS485 transceiver connected to RJ45 connector (Pin 1 and 2)
- 3.3V Switching regulator based on the TPS54202DDC
- I2C Header for an OLED display

## Schematic

![Schematic](./images/schematic.png)

## PCB

![PCB](./images/PCB.png)
