# McGill Rocket Team 2020 - Iridium COTS with Teensy 3.5

Contains the code for using Teensy 3.5 with RockBLOCK MK2/Iridium and Adafruit Ultimate GPS V3. 

Raymond Yang wrote most of the code, link: https://github.com/yanghaoqin/Iridium-RockBLOCK

# Hardware
- Teensy 3.5
- RockBLOCK MK2
- Adafruit Ultimate GPS (V3)

# Dependencies

The code requires the following libraries:
- *_IridiumSBD_* Arduino Library
- *_TinyGPS++_* Arduino Library

#Setup

The code uses the Serial1 for the GPS and Serial3 for the RockBLOCK on the Teensy 3.5 and USB Serial for displaying information. Connect:
- GPS RX/TX to Teensy pins 0/1
- RockBLOCK RX/TX to Teensy pins 7/8
