**HALF ADDER AND HALF SUBTRACTOR**

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**
To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**EQUIPMENTS REQUIRED:**
Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**HALF ADDER:**
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

**Figure - 1 Half Adder**

![alt text](<half adder.png>)

**HALF SUBTRACTOR:**
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.

Diff = A’B+AB’ =A ⊕ B Borrow = A’B

**Figure - 2 Half Subtractor**

![alt text](<half subtractor.png>)

**Truthtable**

**PROCEDURE:**
1. Type the program in Quartus software.

2. Compile and run the program.

3. Generate the RTL schematic and save the logic diagram.

4. Create nodes for inputs and outputs to generate the timing diagram.

5. For different input combinations generate the timing diagram.

**PROGRAM:**

**HALF ADDER**

![alt text](<half adder program.png>)

**HALF SUBTRACTOR**

![alt text](<half subtractor program.png>)


Developed by: Sandya S      Register Number : 25017264

**RTL SCHEMATIC**

**HALF ADDER**

![alt text](<half adder diag.png>)

**HALF SUBTRACTOR**

![alt text](<half subtractor diag.png>)

**OUTPUT:**

**RTL**

HALF ADDER

![alt text](<half adder wave.png>)

HALF SUBTRACTOR

![alt text](<half subtractor wave.png>)


**RESULT:**
Thus the a half adder and half subtractor circuit is designed and its truth table is verified in Quartus using Verilog programming .





......




......




......




.......



....


....




.....





......



......



.....



......




......



.....




.......





......





.......





......




......





......





......





......




......




......


.....

