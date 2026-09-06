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

PROGRAM:

module exe2(a,b,c,d,f1,w,x,y,z,f2);

input a,b,c,d,w,x,y,z;

output f1,f2;

assign f1=((~b&~d)| (~a&b&d)| (a&b&~c))

; assign f2=((~y&z)|(x&y)|(w&y)); 

endmodule




Developed by:vignesh s

RegisterNumber:212225040489

**RTL realization**


<img width="1620" height="853" alt="image" src="https://github.com/user-attachments/assets/bbcb1f45-17c6-4a8e-937c-52448b573b4f" />



**RTL**


<img width="1920" height="1022" alt="image" src="https://github.com/user-attachments/assets/bc4dc540-7b8f-481b-91ec-849a3a64cc87" />





**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

