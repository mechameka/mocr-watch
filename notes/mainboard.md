# MOCR Watch - Mainboard Schematic Notes

## Li-Po Charger Circuit
Design based from Xiao ESP32-C3, TP4056 Circuit

TP4056 Circuit:
https://dlnmh9ip6v2uc.cloudfront.net/datasheets/Prototyping/TP4056.pdf
- Connected to 2 status LEDs on status pins for Charge and Standby
-  PROG pin pulled down to GND with 1.2KOhm, set to Constant Charge Current Setting
- TEMP pin pulled to GND
- Connected to DW01A Battery Protection + FS8205A
https://www.digikey.com/en/products/detail/evvo/FS8205A/26220994


Voltage Switching Protection Circuit
- Replacement SOT23301SA1SHB MOSFET, SOT-23
    - 20V P-Channel, Continuous Drain Current 3.0A
- Replacement MSK4005 Zener Diode
    - 
https://www.best-microcontroller-projects.com/tp4056-page2.html

