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
![Screenshot 2024-10-16 062030](https://github.com/user-attachments/assets/e9dcc15b-74e6-4600-8190-9d907dc42424)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming. // Verilog model:Circuit with boolean expressions 
```
module ex02 (E,F,A,B,C,D);
input A, B, C, D; output E,F;
assign E = A || (B && C) || ((!B) && D);
assign F=((!B) && C) || ( B && (!C) && (!D));
endmodule
```

Developed by: SARANYA V

RegisterNumber: 212223040188

**RTL realization**

![Screenshot 2024-10-16 062253](https://github.com/user-attachments/assets/a9c535f6-8795-46a2-8abe-5a329b034de2)

**Output:**

**RTL**

**Timing Diagram**

![Screenshot 2024-10-16 062442](https://github.com/user-attachments/assets/ddc7c5e4-2da6-42d3-8191-eda14ae32a42)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

