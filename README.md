# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**
![384848212-1662b15f-b920-4b95-af98-337730977f06](https://github.com/user-attachments/assets/2aee78c4-9da4-42c2-9bad-25628176d221)

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
module exp2(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule

Developed by: RegisterNumber:*/24900824


**RTL realization**

**Output:**
![384849226-ff3af9ed-2093-4859-b7f4-5c02028f702c](https://github.com/user-attachments/assets/51dad019-d3c7-49f5-8399-d4071cfe07a6)

**RTL**
![384848097-d568f6c1-e9db-481a-a632-b61696036c4f](https://github.com/user-attachments/assets/38a70706-2553-49ce-a904-587f31670939)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

