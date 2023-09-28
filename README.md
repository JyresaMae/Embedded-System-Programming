# Embedded System Programming Activities

### Binary Counter and Seven-segment Display

#### Materials:
***
* Microchip Studio (Previously ATMEL Studio)
* Arduino Uno Kit
* LEDs
* Resistors
* Push Buttons

A. Seven-segment Display Background
  The objective of this laboratory activity is to design and implement a seven-segment display using
  Arduino Uno microcontroller and assembly program, as shown in Figure 1. Each of the seven
  segments is labeled “a” through “g”. The numbers “0” through “F” light up the segments shown in
  Figure 2. For example, the number 0 lights up all but the middle segment, segment g.

  ![7 segment display](https://github.com/JyresaMae/Embedded-System-Programming/assets/112668033/d61a8176-8f98-4a17-bbf0-46bc78ef7dfa)
  
  You will build a seven-segment display using LEDs and resistors, shown in Figure 3. The
  circuit has four input bits, using push buttons (e.g., PB 0 , PB 1 , PB 2 , and PB 3 ) (representing a
  hexadecimal number between 0 and F), and produces seven output bits, S a:g , that drive the seven
  segments to display the number. A segment of the display turns on when it is LOW or 0. Such an
  output is called a low-asserted output or active low output. Another version of this is a segment of the
  display turns on when it is HIGH or 1. Such an output is called a high-asserted output or active high output. As for this laboratory activity, we will be implementing the low-asserted output or active low output.

  To design your seven-segment display using Arduino Uno microcontroller, you will first write the truth table specifying the output values for each input combination. We have started the truth table for you in Table 1. For example, when the input is PB 3:0 = 0000, all of the segments except g should be on. Because the outputs are active low, they must be S g:a = 1000000. Complete the truth 
  table for the 7-segment display decoder circuit. You will need to turn in your completed truth table.

Video Simuation:

https://github.com/JyresaMae/Embedded-System-Programming/assets/112668033/a1f7672d-541a-438e-8cf7-f07adc4108ad



https://github.com/JyresaMae/Embedded-System-Programming/assets/112668033/9bd01be4-e923-4ebd-9f65-452fd41ba86f

### AVR in Programming

#### Activity 1: LED Flashing
Write a program to flash the LEDs driven by PORTD on your Arduino Uno with the following
pattern below:
* Turn on all LEDs for 200 ms and turn them off for 200 ms.
*. Repeat Step 1 three more times.
* Turn on one LED at a time, from left to right, with each LED turned on for 200 ms.
* Repeat Step 3 three more times.
* Turn on one LED at a time, from right to left, with each LED turned on for 200 ms.
* Repeat Step 5 three more times.
* Turn LEDs driven by pins PD7 and PD0 on and off four times. The on and off times are both 200
ms.
* Turn LEDs driven by pins PD6 and PD1 on and off four times. The on and off times are both 200
ms.
* Turn LEDs driven by pins PD5 and PD2 on and off four times. The on and off times are both 200
ms.
* Turn LEDs driven by pins PD4 and PD3 on and off four times. The on and off times are both 200
ms.
* Turn LEDs driven by pins PD3 and PD4 on and off four times. The on and off times are both 200
ms.
* Turn LEDs driven by pins PD2 and PD5 on and off four times. The on and off times are both 200
ms.
* Turn LEDs driven by pins PD1 and PD6 on and off four times. The on and off times are both 200
ms.


https://github.com/JyresaMae/Embedded-System-Programming/assets/112668033/93d7ef9b-10e3-4bc2-8dff-c4d99ab374b9


#### Activity 2: Fibonacci Sequence
Write a C program to display the Fibonacci numbers on the LEDs. Pause for 3s between values.
Stop when the value would exceed 255. Use a recursive function to calculate the nth Fibonacci number.
Define the function in a separate file or in your own library.


https://github.com/JyresaMae/Embedded-System-Programming/assets/112668033/714c3888-1149-4a7e-b718-beda365988ac

