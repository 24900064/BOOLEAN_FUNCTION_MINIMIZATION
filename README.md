# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/

module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule




**RTL realization**

**Output:**

**RTL**
![WhatsApp Image 2024-12-25 at 09 23 28_352617f2](https://github.com/user-attachments/assets/f95a02f6-bcd6-4637-be84-5c461fbab91b)

**Timing Diagram**
![WhatsApp Image 2024-12-25 at 09 23 28_283533f2](https://github.com/user-attachments/assets/5badc2ea-3840-4095-b3e7-05a74b34c95a)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

