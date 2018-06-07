# Embedded_Logic_and_Design
## This repository contains all labs done as a part of the Embedded Logic and Design course. 
### Instructor : Dr. Sumit Darak

### Lab 1
1. Design and implement a half-adder (using data ow approach) on the Zedboard.
2. Using the half-adders designed in step 1, implement a full-adder.
3. Implement a 4-bit adder/subtractor (adds/subtracts two 4-bit inputs) using the full-adders designed in step

### Lab 2
1. Generate the Boolean expression for the following problem statements.
2. Implement them by data flow and behavioral model.
3. Compare the RTL schematic and resource utilization for both modelling
schemes.
4. Verify the design on Zedboard.

### Lab 3
Design and implement a counter on Zedboard. The counter should continuously count from 0 to 31. The output of the counter can be displayed on the LEDs of Zedboard at a rate of 1, 2, 4 or 8 seconds. The speed is to be decided by the user (use switches for this task). The counter should be able to clear itself whenever the clear button is pressed.

### Lab 4
Design a counter that counts from 00000000 to 11111111. Convert this 8-bit binary number to a BCD number. Display the count from 0 to 255 on the seven segment display. Note that the frequency divider will generate a clock of 1Hz.
(Hint: Use time multiplexing to display different digits at different decimal position.)

### Lab 5
1) Design and implement a BCD adder which adds two numbers A and B ranging from 0 to 9. Display A on the rightmost digit of the 7 segment display and B on the leftmost digit. Output of the BCD adder should be displayed on the middle two digits of 7-segment display. 
2) Design an 8-bit SIPO shift register. Shift the binary data into the shift register using 2 push buttons. One push button passes 0 and another passes 1. Display the content of shift register on the seven segment display in the BCD format. 

### Lab 6
1) Design and code an FSM to detect an overlapping sequence of '11011' as
    a) Moore machine.
    b) Mealy machine.
2) Design and code an FSM to detect a non-overlapping sequence of '10101' as
    a) Moore machine.
    b) Mealy machine.

### Lab 8
Write a Verilog code which connects a keypad and external 7 segment display to the Basys 3 board via PMOD ports. Instead of using switches in Ques. 1, use the key press on the keypad to enter the value of 𝑥[𝑛] that ranges from 0 to 9. Display the output 𝑦[𝑛] to an external 7-segement display.

### Lab 9.1
This lab guides you through the process of extending the processing system you created in the previous lab by adding two GPIO (General Purpose Input/Output) IPs. 

### Lab 9.2
This lab guides you through the process of using Vivado to create a simple ARM Cortex-A9 based processor design targeting the ZedBoard or Zybo board. Where the instructions refer to both boards, choose the board you are using. You will use Vivado to create the hardware system and SDK (Software Development Kit) to create an example application to verify the hardware functionality. 

### Lab 11 
Design and implement an interrupt based design on Zedboard, which displays different numbers on the SSD according to the push button being pressed.
