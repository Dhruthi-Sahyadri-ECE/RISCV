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

## OVERVIEW OF Implementation of 2-bit Comparator using VSDSquadron Mini Board


This project aims to design and implement a 1-bit comparator using the VSD Squadron Mini Board. A 1-bit comparator is a digital circuit that compares two 1-bit binary numbers (A and B) and determines whether:

A > B (Greater than)
A = B (Equal to)
A < B (Less than)
The project involves designing the comparator logic using C programming in Visual Studio Code, setting up the hardware connections on a breadboard, and verifying the functionality through LEDs connected to the output.

## COMPONENTS REQUIRED
VSDSquadron Mini Board 
Breadboard and Jumper Wires 
LEDs 
Resistors 
Push button
## TABLE FOR PIN CONFIGURATION
LED  	VSD SQUADRON BOARD
LED1 -	PIN4 (PC4)
LED2 -	PIN5 (PC5)
LED3 -	PIN6 (PC6)
PUSH BUTTON 1 - PIN2 (PD2)
PUSH BUTTON 2 - PIN1 (PD1)

