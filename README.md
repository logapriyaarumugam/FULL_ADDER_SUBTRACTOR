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

**Procedure**

Write the detailed procedure here

**Program:**
![WhatsApp Image 2025-12-14 at 10 25 28 PM](https://github.com/user-attachments/assets/20b98c42-f638-4fbc-b6bf-8c80eef9b3ab)
![WhatsApp Image 2025-12-14 at 10 20 47 PM](https://github.com/user-attachments/assets/85927bbf-f77c-4dca-812e-8cab1ae93d4e)




/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
Developed by: LOGAPRIYA A
RegisterNumber:25011409
*/

**RTL Schematic**
![WhatsApp Image 2025-12-14 at 10 25 27 PM](https://github.com/user-attachments/assets/a5d224ca-437c-4a95-9a65-b05269c8786e)
![WhatsApp Image 2025-12-14 at 10 20 47 PM (1)](https://github.com/user-attachments/assets/265c4162-ec15-4649-b44b-9eb4d5c0c60a)


**Output Timing Waveform**
![WhatsApp Image 2025-12-14 at 10 25 28 PM (1)](https://github.com/user-attachments/assets/02828899-98db-45cf-8d7f-5964d752ef73)
![WhatsApp Image 2025-12-14 at 10 20 47 PM (2)](https://github.com/user-attachments/assets/efdec4cb-9fb2-4c5b-825e-6f904a63ab1c)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



