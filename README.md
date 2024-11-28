# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

![image](https://github.com/user-attachments/assets/8f59e91d-a7f0-4e2c-bdc1-69e4d35c7c07)


**procedure**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram.

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. */
###Developed by:RAHA PRIYA DHARSHINI M  ###RegisterNumber:24901069
![fulladder prog](https://github.com/user-attachments/assets/50959c07-1a16-4b23-87af-c85188d73fe3)

![fullsub prog](https://github.com/user-attachments/assets/b9421de3-0ac6-478a-b1d8-255ac1c7b644)



**RTL Schematic**
![fulladder rtl](https://github.com/user-attachments/assets/3b19b5b3-adaf-41f0-84e1-ec825065a161)

![fullsub rtl](https://github.com/user-attachments/assets/9cb49a23-e5ee-4db9-b8ee-d463d463e18d)

**Output Timing Waveform**
![fulladder waveform](https://github.com/user-attachments/assets/dba39828-7f99-4168-becf-c85ec48d1c70)

![fullsub waveform](https://github.com/user-attachments/assets/f7e0e24d-1f2c-46ea-a93c-d3ca741996cc)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



