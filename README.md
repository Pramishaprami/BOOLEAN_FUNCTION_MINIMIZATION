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
module exe_2(f_and,f_or,f_not,f_nor,f_nand,f_xor,f_xnor,a,b);
input a,b;
output f_and,f_or,f_not,f_nor,f_nand,f_xor,f_xnor;
and(f_and,a,b);
or(f_or,a,b);
not(f_not,a);
nand(f_nand,a,b);
nor(f_nor,a,b);
xor(f_xor,a,b);
xnor(f_xnor,a,b);
endmodule
```

**Output:**
![logi2](https://github.com/user-attachments/assets/5a67e2c6-fac7-4c84-882b-68a13ba84e0e)

**Timing Diagram**
![Screenshot 2024-10-23 025854](https://github.com/user-attachments/assets/d5dae295-3964-452d-a8b1-88281bc188df)

**Result:**

Thus the basic  logic gate are statisfied andthe truth tables are verified.

