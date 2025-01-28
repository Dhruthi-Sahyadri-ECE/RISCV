<details>
  
<summary> Task 3 </summary>

## 15 Unique RISC-V Instructiona and their 32-bit encodings
  
## RISC-V instructions and their Encodings

addi sp, sp, -16
Type: I-Type 
Binary Encoding: 11111111 00000001 000 00010 0010011

sd ra, 8(sp)
Type: S-Type 
Binary Encoding: 00000001 00001 00101 010 01000 0100011

li a5, 100 
Type: I-Type 
Binary Encoding: 00000110 01000000 000 01010 0010011

addiw a5, a5, -1
Type: I-Type 
Binary Encoding: 11111111 01111000 000 01010 0011011

bnez a5, <main+0xc>
Type: B-Type 
Binary Encoding: 11111110 01111001 001 00000 1100011

lui a2, 0x1
Type: U-Type 
Binary Encoding: 00000000 00000001 00010 0110111

addi a2, a2, 954
Type: I-Type 
Binary Encoding: 00111011 10100110 000 00010 0010011

li a1, 100 
Type: I-Type 
Binary Encoding: 00000110 01000000 000 00011 0010011

lui a0, 0x21
Type: U-Type 
Binary Encoding: 00000010 00010000 00000 0110111

addi a0, a0, 400
Type: I-Type 
Binary Encoding: 00011001 00000101 000 00000 0010011

jal ra, <printf>
Type: J-Type 
Binary Encoding: 00000000 00000000 000 00001 1101111

li a0, 0 
Type: I-Type 
Binary Encoding: 00000000 00000000 000 00000 0010011

ld ra, 8(sp)
Type: I-Type 
Binary Encoding: 00000000 10000001 010 00001 0000011

addi sp, sp, 16
Type: I-Type 
Binary Encoding: 00010000 00000001 000 00010 0010011

ret 
Type: I-Type 
Binary Encoding: 00000000 00000000 000 00000 1100111







<details>

<summary> TASK 5

## OVERVIEW OF SMART PLANT CARE VSD QUADRON MINI BOARD

The Smart Plant Care system operates through a network of interconnected components that work together to provide real-time monitoring and automated watering solutions. The user can remotely monitor the plant’s environment and adjust the soil moisture threshold via a WiFi-connected interface. When the soil moisture level falls below the set threshold, the system automatically activates a water pump to deliver the necessary amount of water to the plant. This process helps in conserving water and ensuring that the plant remains healthy.

## COMPONENTS REQUIRED
CH32V003F4U6 Microcontroller: Acts as the central processing unit, managing sensor data and system operations.
ESP-01S ESP8266 WiFi Module: Facilitates wireless communication, allowing remote data monitoring and control.
Soil Moisture Sensor Module: Detects the moisture content in the soil.
DHT11 Humidity and Temperature Sensor: Measures ambient temperature and humidity.
Water Pump: Provides irrigation to the plant when needed.
Relay Module: Helps to control high-power pump with low-power signals.
Switch: Manages the on/off states of the water pump.

## TABLE FOR PIN CONFIGURATION
For Soil Moisture senosor
VCC - 3.3V
GND - GND
SIG - PA2

FOR RELAY MODULE
VCC - 3.3V
GND - GND
IN - PC0

FOR ESP 01S 8266 WIFI MODULE
VCC - 3.3V
CH_EN - 3.3V
GND - GND
UORXD - PD5
UOTXD - PD6







