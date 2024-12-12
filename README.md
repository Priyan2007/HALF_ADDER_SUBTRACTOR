**NAME:PRIYAN**
**REG NO:24000051**

# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**
<img width="479" alt="Screenshot 2024-12-12 at 10 22 46 AM" src="https://github.com/user-attachments/assets/73fefdd6-edb1-40db-90e6-30373fc85f3b" />


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
<img width="490" alt="Screenshot 2024-12-12 at 10 24 26 AM" src="https://github.com/user-attachments/assets/aeead4b6-0fcc-45e2-b2e0-2fb4e24242fe" />


/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.


**RTL Schematic**
<img width="531" alt="Screenshot 2024-12-12 at 10 23 47 AM" src="https://github.com/user-attachments/assets/63c11d2c-3d95-4294-9c35-b947a9fb9fc4" />


**Output/TIMING Waveform** 
<img width="1710" alt="Screenshot 2024-12-12 at 10 30 06 AM" src="https://github.com/user-attachments/assets/0f6c6693-6cc4-4a43-b94d-4b2ebe50059b" />


**Result:**
Thus, we designed a half adder and half subtractor circuit and verified its truth table in Quartus using Verilog programming
