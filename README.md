# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2= xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: SARANYA V , RegisterNumber: 212223040188

F1
```
module exp21(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|( ~a & b & d )|(a & b & ~c));
endmodule
```

F2
```
module exp22(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

**RTL realization**

F1
![Screenshot 2024-11-20 111053](https://github.com/user-attachments/assets/29808b0f-0b4d-4fd9-b388-42f899db98af)

F2
![Screenshot 2024-11-20 114357](https://github.com/user-attachments/assets/372405e1-e08e-4834-9416-9edfdc5d4c26)


**Timing Diagram**

F1
![image](https://github.com/user-attachments/assets/5ebba3c8-3b11-4d09-ad4a-9afeb66c8200)

F2
![Screenshot 2024-11-20 114913](https://github.com/user-attachments/assets/232cb1b0-c34d-42d4-a426-c61bffa598d4)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

