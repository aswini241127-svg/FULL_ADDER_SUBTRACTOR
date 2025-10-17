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
![WhatsApp Image 2025-10-09 at 18 29 47_0ae40d1c](https://github.com/user-attachments/assets/0fde5564-ae59-44f9-bc0e-628908aacb04)


**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:25018420
*/

**RTL Schematic**
![WhatsApp Image 2025-10-09 at 18 29 47_fb6567d8](https://github.com/user-attachments/assets/2ce89b42-d789-47b6-bd2c-b56e9309c8fc)

![WhatsApp Image 2025-10-09 at 18 29 47_67cb357e](https://github.com/user-attachments/assets/2abd30ef-d066-444c-945a-0f950a18f3b5)



**Output Timing Waveform**

![WhatsApp Image 2025-10-09 at 18 29 47_4a058aab](https://github.com/user-attachments/assets/424e50c6-1ee2-4fb7-b5e5-7fbf74012aee)


![WhatsApp Image 2025-10-09 at 18 29 48_5689332c](https://github.com/user-attachments/assets/adfdf879-f2c1-4a39-9aab-a78839bfd7d2)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



