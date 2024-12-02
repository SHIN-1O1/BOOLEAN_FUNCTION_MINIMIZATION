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

---
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
---

Developed by: A.Sherwin infano

ref no: 24010314

**RTL**
![image](https://github.com/user-attachments/assets/4f098a84-9727-43df-a7aa-1cf07ab95112)

**Timing Diagram**
![image](https://github.com/user-attachments/assets/29fa900d-abce-4442-aaef-0a0603a3141f)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

