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

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by:S Tozer Theophilus RegisterNumber:25016814
*/















Full Adder






<img width="1920" height="1080" alt="Screenshot 2025-11-24 175250" src="https://github.com/user-attachments/assets/93c4df3e-6469-4898-b055-70fdf61b99cb" />








Full Subtractor







<img width="1920" height="1080" alt="Screenshot 2025-11-24 180558" src="https://github.com/user-attachments/assets/e7742dd5-93e3-470b-8ff9-69cbe8e3f289" />










**RTL Schematic**

Full Adder



<img width="1920" height="1080" alt="Screenshot 2025-11-24 175227" src="https://github.com/user-attachments/assets/837d60bd-e2ca-429d-99cf-c3270f374612" />







Full Subtractor






<img width="1920" height="1080" alt="Screenshot 2025-11-24 175952" src="https://github.com/user-attachments/assets/c5ddf5f8-3bff-4a75-a142-c2c789600406" />










**Output Timing Waveform**
Full Adder








<img width="1920" height="1080" alt="Screenshot 2025-11-24 175501" src="https://github.com/user-attachments/assets/c325cef1-ee4a-47b5-a5f7-d50fef858353" />






Full Subtractor









<img width="1920" height="1080" alt="Screenshot 2025-11-24 180225" src="https://github.com/user-attachments/assets/e3a0770e-3cd6-482f-bd3e-21ef2502851c" />












**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



