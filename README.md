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

**Full adder**

 Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 
 


<img width="846" height="249" alt="Screenshot 2025-11-15 205313" src="https://github.com/user-attachments/assets/856ff655-a9b2-478b-bcc1-4d6337731db0" />

**Full subtractor**

 Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. 

<img width="686" height="263" alt="Screenshot 2025-11-15 212521" src="https://github.com/user-attachments/assets/ca7de544-e9ac-46b0-9552-d2ef413c0375" />



 Developed By:JUHI JAHAN T S Register no:25011334




**RTL Schematic**

**Full adder**
<img width="983" height="580" alt="Screenshot 2025-11-15 205157" src="https://github.com/user-attachments/assets/c8aaa8b5-bbac-41eb-a638-4f326c599d7f" />

**Full subtractor**
<img width="1520" height="632" alt="Screenshot 2025-11-15 210712" src="https://github.com/user-attachments/assets/d9859291-9274-4af3-9ad2-a5eb58d81240" />



**Output Timing Waveform**

**Full adder**
<img width="1837" height="315" alt="Screenshot 2025-11-15 212406" src="https://github.com/user-attachments/assets/23cce9f4-c2d8-445c-9e6e-73083386a6c7" />

**Full subtractor**
![WhatsApp Image 2025-11-15 at 21 36 36_14b9905a](https://github.com/user-attachments/assets/bc7ca4e2-ff51-465c-8d3f-62f0e36b22d6)




**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



