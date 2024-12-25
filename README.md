# BOOLEAN_FUNCTION_MINIMIZATION

NAME : PRAGATHEESHRAAJ D

REG.NO : 24900064

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

i)

module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii)

module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule



**RTL realization**

**Output:**

**RTL**
![WhatsApp Image 2024-12-25 at 09 23 28_fc74c22a](https://github.com/user-attachments/assets/1386ee49-1687-4c93-97d4-e0898fd5bb76)

**Timing Diagram**
![WhatsApp Image 2024-12-25 at 09 23 28_7e0b5b5b](https://github.com/user-attachments/assets/7e95c5d3-62f9-49ef-abf6-47fcd673fa0c)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

