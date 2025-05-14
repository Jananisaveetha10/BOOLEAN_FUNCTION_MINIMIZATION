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

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
module exp_2a (a,b,c,d,f1);
input (a,b,c,d);
output (f1);
assign f1=((~a&b&d)|(a&b&~c)|(~b& ~d));
endmodule
```
```
module exp_2b(w,x,y,z,f2);
input(w,x,y,z);
output f2;
assign f2=((x&y)|(~w&y)|(~y&z));
endmodule
```



**Output:**
![Screenshot 2025-05-14 215440](https://github.com/user-attachments/assets/3efa9bd8-ab46-4913-be7b-06697f69d29e)

![Screenshot 2025-05-14 215255](https://github.com/user-attachments/assets/9b73d0bb-5ff9-4924-a33b-7ee4e216bf7d)





**Timing Diagram**
![Screenshot 2025-05-14 215557](https://github.com/user-attachments/assets/faeec3b4-0a49-4c7f-a2f2-2dc1d357e73d)
![Screenshot 2025-05-14 215725](https://github.com/user-attachments/assets/5d3ca894-b2c3-4629-8138-5da88885128f)


Name:JANANI S
Register number:212224040127





**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

