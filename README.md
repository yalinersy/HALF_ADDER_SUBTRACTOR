### NAME : SRI YALINE R
### REG NO : 24006194
# EXPERIMENT 3 : IMPLEMENTATION OF HALF ADDER AND HALF SUBTRACTOR


# AIM

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

# EQUIPMENTS REQIURED

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

# HALF ADDER

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

# HALF SUBTRACTOR

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF SUBTRACTOR

# TRUTH TABLE
![WhatsApp Image 2024-11-09 at 18 16 37_73c525a4](https://github.com/user-attachments/assets/5f328484-aca9-4050-83f1-bab3ee57e368)

# PROCEDURE

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# PROGRAM
![WhatsApp Image 2024-11-09 at 18 16 37_0a5f6f7e](https://github.com/user-attachments/assets/a17693e7-69c8-42ae-b6c4-d8e1e54f9b36)

# RTL OUTPUT
![WhatsApp Image 2024-11-09 at 18 16 36_83699907](https://github.com/user-attachments/assets/c34dc1bd-d250-42c3-ab87-0fb25bc35755)

# OUTPUT WAVEFORM
![WhatsApp Image 2024-11-09 at 18 16 37_9e7e459a](https://github.com/user-attachments/assets/51ade2af-bc04-49a2-96de-eea699e4f117)

# RESULT
 Studing and verifing a half adder and half subtractor circuit nad verify its truth table in
 Quartus using Verilog programming.
