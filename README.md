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
Developed by:SHALINI.I RegisterNumber:25015951


**RTL realization Output**
i)
<img width="514" height="268" alt="Screenshot 2025-11-25 223257" src="https://github.com/user-attachments/assets/01622d1c-a9f9-4dff-80ec-ee62ae69d5af" />
ii)
<img width="514" height="268" alt="Screenshot 2025-11-25 223257" src="https://github.com/user-attachments/assets/e50b058c-ba29-42d9-b7bd-f0ea05489356" />

**RTL Timing Diagram**
i)
<img width="518" height="274" alt="Screenshot 2025-11-25 223559" src="https://github.com/user-attachments/assets/668409c5-93c8-4adc-b348-8979466b4aab" />
ii)

<img width="949" height="486" alt="Screenshot 2025-11-25 223753" src="https://github.com/user-attachments/assets/41a64dcd-fb07-448f-984f-58618bd75cd4" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

