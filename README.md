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

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
 ```
module form(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
endmodule
```
```
module Form2(x,y,z,w,f2);
input x,y,z,w;
output f2;
assign f2=((x&~y&z)|(~x&~y&z)|(~w&x&y)|(w&~x&y)|(w&x&y));
endmodule
```



Developed by:Thilak raj .P

RegisterNumber:24900585


**RTL**
![Screenshot 2024-11-04 093124](https://github.com/user-attachments/assets/04c9dc43-35e4-4d7a-96c0-79892c9788a5)
![Screenshot 2024-11-05 132512](https://github.com/user-attachments/assets/f5b17f41-de89-4f98-80bc-fda5c448c529)

**Output:**
![Screenshot 2024-11-04 094418](https://github.com/user-attachments/assets/60521c61-cbc2-4305-b622-fd88f3a31842)

![Screenshot 2024-11-05 132326](https://github.com/user-attachments/assets/22ed7e5f-071d-4678-80f6-c64c5b766730)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

