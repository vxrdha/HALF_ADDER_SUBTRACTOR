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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:AMSAVARADHAN M

RegisterNumber:25011322

**RTL Schematic**
HALF ADDER
<img width="1136" height="690" alt="394116096-0163d5e3-fda4-46e5-b48d-c4f5023a0b6a" src="https://github.com/user-attachments/assets/5bb0940d-72da-4404-99d5-b27d4c1d6f7f" />

HALF SUBTRACTOR
<img width="1206" height="671" alt="394117308-69257a8c-0afa-44a0-a4d3-3973d8438069" src="https://github.com/user-attachments/assets/8dbabcfb-185d-4c1a-92e7-dd3736ad38be" />


**Output/TIMING Waveform**
HALF ADDER
<img width="1921" height="1201" alt="394116606-0597ca12-88b3-4231-878a-e3a4da2af7ff" src="https://github.com/user-attachments/assets/a087c976-d547-4c35-8b9f-f1526856b029" />

HALF SUBTRACTOR
<img width="1921" height="1199" alt="394117564-5d6b55fe-2e1d-43a7-a3a5-51dd04b9b713" src="https://github.com/user-attachments/assets/06e93671-5a1f-4c02-945c-5c948dfa3236" />


**Result:**
Thus the Half Adder and Half Subtractor are studied and the truth tables are verified
