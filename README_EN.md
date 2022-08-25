# LabVIEW Instrument Driver for Eltochpribor RRG Series Mass Flow Controllers
Tested on Eltochpribor RRG-20.

## Requirements
LabVIEW 2015 and higher.

[Modbus Client Library](https://github.com/plasmapper/modbus-client-labview) ([VIPM package](https://www.vipm.io/package/plasmapper_lib_pl_modbus_client/))

## Installation
[VIPM package](https://www.vipm.io/package/plasmapper_lib_pl_eltochpribor_rrg/)

## Features
1. Read/configure flow rate setpoint, valve mode, baudrate and Modbus address.
2. Read measured flow rate.
3. Zero measured flow rate.
4. Automatic reconnection to device.

## Extra
[GCF Calculator Library](https://github.com/plasmapper/gcf-calculator-labview) can be used to calculate actual flow rate when using gas/mixture other than calibrated.

## Examples
### Eltochpribor RRG.vi
Example VI that demonstrates all library features.

## Software and Documentation
[RRG-12](https://eltochpribor.ru/upload/zip/%D0%A0%D0%A0%D0%93-12.rar)  
[RRG-20](https://drive.google.com/file/d/1ov4l3L0pDe8frplhclJo1kfsVCZQ7Hfq/view?usp=sharing)  
