# Eltochpribor RRG Driver for LabVIEW.
LabVIEW instrument driver for Eltochpribor RRG mass flow controler.

Tested on RRG-20.

## Requirements
LabVIEW 2015 and higher.

## Features
1. Read/configure flow rate setpoint, valve mode, baudrate and Modbus address.
2. Read measured flow rate.
3. Zero measured flow rate.
4. Automatic reconnection to device.

## Dependencies
[Modbus Client Library](https://github.com/plasmapper/modbus-client-labview)

## Extra
[GCF Calculator Library](https://github.com/plasmapper/gcf-calculator-labview) can be used to calculate actual flow rate when using gas/mixture other than calibrated.

## Examples
### Eltochpribor RRG.vi
Example VI that demonstrates all library features.

## Software and Documentation
[RRG-12](https://eltochpribor.ru/upload/zip/%D0%A0%D0%A0%D0%93-12.rar)  
[RRG-20](https://drive.google.com/file/d/1ov4l3L0pDe8frplhclJo1kfsVCZQ7Hfq/view?usp=sharing)  