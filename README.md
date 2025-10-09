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

module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule

   

**RTL**

<img width="837" height="515" alt="Screenshot 2025-10-07 085249" src="https://github.com/user-attachments/assets/8378aff8-1581-42e4-b14d-efac77092dfc" />

![21](https://github.com/user-attachments/assets/58e4e4c8-08bd-4b2c-8c6e-11f826a857a4)

**Timinrng diadram**

<img width="1917" height="534" alt="Screenshot 2025-10-07 091550" src="https://github.com/user-attachments/assets/e156f3f4-ba69-4fec-bdb0-870403114df6" />

![22](https://github.com/user-attachments/assets/da88bc68-caed-409b-92fd-6bb7fc748feb)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

