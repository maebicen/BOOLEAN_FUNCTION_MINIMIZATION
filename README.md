# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

```
module logic_gates(a, b, c1, c2, c3, c4, c5, c6, c7);
    input a, b;
    output c1, c2, c3, c4, c5, c6, c7;
    assign c1 = ~a;
    assign c2 = a & b;
    assign c3 = a | b;
    assign c4 = ~(a & b);
    assign c5 = ~(a | b);
    assign c6 = a ^ b;
    assign c7 = ~(a ^ b);
endmodule

```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Maebicen Kirubakar C

RegisterNumber: 24001839


**RTL**

![image](https://github.com/user-attachments/assets/e4c9eff5-d57f-4d1d-8f75-7d231f6781c3)


**Timing Diagram**

![image](https://github.com/user-attachments/assets/cb8959bf-a0a7-4546-a4f6-642e56ea30bd)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


