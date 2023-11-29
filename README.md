# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: KEERTHANA S
RegisterNumber: 23010209  
*/


### Output:

## HALF ADDER

## CODE:

![image](https://github.com/keerthanasivakumar02/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150827397/9fc67b25-a283-4a77-a11b-8c8525c7e154)

## RTL DIAGRAM:

![image](https://github.com/keerthanasivakumar02/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150827397/d789619a-2a4e-4141-8821-6984e17b421d)

 
### TRUTH TABLE :
![image](https://github.com/keerthanasivakumar02/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150827397/40382d95-b67f-4dfc-82aa-4501422cd60c)

## TIMING DIAGRAM:

![image](https://github.com/keerthanasivakumar02/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150827397/540dc199-d0a8-48f7-8269-9563fe90210b)

## FULL ADDER

## CODE:

![image](https://github.com/keerthanasivakumar02/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150827397/e2c07bc5-74b4-4443-98c9-38904e5c1f81)

## RTL DIAGRAM:

![image](https://github.com/keerthanasivakumar02/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150827397/2cf00254-62d3-46cc-89ca-ea218701c68d)

## TRUTH TABLE :

![image](https://github.com/keerthanasivakumar02/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150827397/98cbc07f-ca53-4e8e-ae50-6877dc351d8d)

## TIMING DIAGRAM:

![image](https://github.com/keerthanasivakumar02/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/150827397/9c8f00d2-dd7f-46e9-9af5-86f43ecb9ebf)





### Result:
