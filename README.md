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
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: pramisha
 RegisterNumber:24004263
module exe2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
```

**Output:**
![Screenshot 2024-11-13 081458](https://github.com/user-attachments/assets/27c040e0-4ec9-4665-bd18-a74b3a023a06)
**Timing diagram**

![Screenshot 2024-11-13 081802](https://github.com/user-attachments/assets/eaaf4d85-4c5a-48cf-8fcc-157eb94273ac)

**Result:**

Thus the basic  logic gate are statisfied andthe truth tables are verified.

