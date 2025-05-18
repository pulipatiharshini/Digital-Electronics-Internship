# Digital_electronics

# Table of contents 

- [What is Digital Electronics](#what-is-digital-electronics)
- [Applications of Digital Electronics](#applications-of-digital-electronics)
- [Digital vs Analog Signals](#digital-vs-analog-signals)
- [Number Systems](#number-systems)
- [Conversion between Number Systems](#conversion-between-number-systems)
- [Basic Logic Gates](#basic-logic-gates)
  

# Task 1

# What is Digital Electronics

Digital electronics is a branch of electronics that deals with systems and devices that use digital signals, which are discrete representations of data, 
typically using binary code (0s and 1s).

Some key elements in digital electronics include:

Logic Gates: Basic building blocks of digital circuits (AND, OR, NOT, XOR, etc.).

Binary System: Using binary numbers (0 and 1) to represent data.

Combinational Circuits: Circuits where the output depends only on the current inputs (e.g., adders, multiplexers).

Digital electronics is fundamental to modern technology, including computing, communication, and control systems. It's used in everything from computers and mobile phones to appliances and automobiles.

# Applications of Digital Electronics

Computing and Microprocessors

Communication Systems

Control Systems

Home Appliances

Smart Refrigerators

Automotive 

# Digital vs Analog signals

| **Analog** | **Digital** 
|------------|------------|
|A continuous wave that represents data|A discrete signal that represents data in binary form (0s and 1s)|
|Requires less bandwid from transmission| Request more bandwidth due to discrete data encoding|
|Less expensive to produce and transmit| More expensive due to advanced technology and processing requirements|
|Less flexible. order to modify or enhance| Highly flexible. easy to modify,compress, or enhance|
|Analog signal use more power| Digital signal useless power|
|Analog signal easily affected by the noise| Digital signal are stable and less prone to noise|
|Components like resistors,Capacitors, Inductors,Diodes are used in analog circuits.| Components like transistors, logic gates,and microcontrollers are used in digital circuits.|


# Logic Levels

In digital electronics, logic levels represent the two states, typically 0 and 1, of a digital signal, often corresponding to a voltage level. These levels are crucial for how digital circuits interpret and process information.

Binary Representation:

Logic levels are used to represent binary data, where 0 and 1 are the fundamental states. 
Voltage Levels:

In many digital systems, a low voltage represents a 0 (logic low), and a high voltage represents a 1 (logic high). 


# Number systems

In digital electronics, number systems are crucial for representing and manipulating data within electronic circuits. The most important number systems are binary (base 2), octal (base 8), and hexadecimal (base 16), with decimal (base 10) being used for human understanding. Binary is fundamental because digital systems primarily operate using two states (0 and 1)

# Binary (Base 2), Decimal (Base 10), Hexadecimal (Base 16).

1. Binary (Base 2)
Digits: 0, 1

Used in: All digital systems; the most fundamental system.

Example: 1011 (binary) = 11 (decimal)

2. Decimal (Base 10)
Digits: 0 to 9

Used in: Human-readable format; not commonly used internally in digital electronics.

Example: 27 (decimal) = 11011 (binary)

3. Hexadecimal (Base 16)
Digits: 0–9 and A–F (where A=10 to F=15)

Used in: Compact representation of binary values (4 bits = 1 hex digit).

Example: 2F (hex) = 0010 1111 (binary) = 47 (decimal)

# Conversion between number systems 

**1. Binary → Decimal**
Binary: 1011₂

= (1×2³) + (0×2²) + (1×2¹) + (1×2⁰) = 8 + 0 + 2 + 1 = 11₁₀

**2. Decimal → Binary**
Decimal: 13₁₀

13 ÷ 2 = 6 remainder 1 6 ÷ 2 = 3 remainder 0 3 ÷ 2 = 1 remainder 1 1 ÷ 2 = 0 remainder 1

Read remainders bottom to top → 1101₂

**3. Binary → Octal**
Binary: 110110₂

Group in 3 bits → 110 | 110 110₂ = 6₈ 110₂ = 6₈

Result → 66₈

**4. Octal → Binary**
Octal: 57₈

5₈ → 101₂ 7₈ → 111₂

Result → 101111₂

**5. Binary → Hexadecimal**
Binary: 10101110₂

Group in 4 bits → 1010 | 1110 1010₂ = A₁₆ 1110₂ = E₁₆

Result → AE₁₆

**6. Hexadecimal → Binary**
Hex: 3F₁₆

3₁₆ → 0011₂ F₁₆ → 1111₂

Result → 00111111₂

**7. Decimal → Octal**
Decimal: 125₁₀

125 ÷ 8 = 15 remainder 5 15 ÷ 8 = 1 remainder 7 1 ÷ 8 = 0 remainder 1

Read remainders bottom to top → 175₈

**8. Octal → Decimal**
Octal: 745₈

= (7×8²) + (4×8¹) + (5×8⁰) = (7×64) + (4×8) + (5×1) = 448 + 32 + 5 = 485₁₀

**9. Decimal → Hexadecimal**
Decimal: 254₁₀

254 ÷ 16 = 15 remainder 14 (E) 15 ÷ 16 = 0 remainder 15 (F)

Read remainders bottom to top → FE₁₆

**10. Hexadecimal → Decimal**
Hex: 2A₁₆

= (2×16¹) + (A×16⁰) = (2×16) + (10×1) = 32 + 10 = 42₁₀

**11. Octal → Hexadecimal**
Octal: 745₈

Step 1: Octal → Binary 7 → 111 4 → 100 5 → 101 Binary = 111100101₂

Step 2: Binary → Hex Group 4 bits: 0011 | 1100 | 101 (pad left 0 → 0101) 0011 → 3 1100 → C 0101 → 5

Result → 3C5₁₆

**12. Hexadecimal → Octal**
Hex: 2F₁₆

Step 1: Hex → Binary 2 → 0010 F → 1111 Binary = 00101111₂

Step 2: Binary → Octal Group 3 bits: 000 | 101 | 111 000 → 0 101 → 5 111 → 7

Result → 057₈

# Task 2

# BASIC LOGIC GATES

# 1.AND Gate

An AND gate is a basic digital logic gate that outputs 1 (true) only when all its inputs are 1. Otherwise, it outputs 0 (false).

Represented as: A AND B = A ⋅ B or A ∧ B

*Truth Table*

|A|B| A & B|
|-----|----|------|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|

*Key Point:*

Output is true (1) only when both inputs are true (1).

*Symbol:*

![image](https://github.com/user-attachments/assets/06b17f4e-446d-4716-8b54-1b54191bb661)

# 2.OR Gate

An OR gate is a basic digital logic gate that implements logical disjunction. It gives a high (1) output if at least one of its inputs is high. In other words, the output is true when any input is true.

*Truth Table:*
|*A|	**B|	**Y (A OR B)*|
|-----|-------|---------------|
|0	|0	|0|
|0	|1	|1|
|1	|0	|1|
|1|	1|	1|

*Key Points*:

If both inputs are 0, the output is 0.

If at least one input is 1, the output is 1.

*Symbol*

![image](https://github.com/user-attachments/assets/9a5865c7-a982-4b78-a88f-4b383f66c838)

# 3.NOT Gate

A NOT gate, also known as an inverter, is a basic digital logic gate that outputs the opposite (inverse) of its input. It has only one input and one output.

*Function:*

If the input is 1 (true or HIGH), the output is 0 (false or LOW).

If the input is 0, the output is 1

The NOT gate is usually represented by a triangle pointing to the right with a small circle (called a "bubble") at the output.

*Truth Table:*
|*Input (A)* |	*Output (¬A)*|
|--------------|------------------|
|0	|1|
|1	|0|

This table shows that the NOT gate simply flips the input value.

*Symbol:*

![image](https://github.com/user-attachments/assets/b7ef0b26-2648-4ccd-8ba9-3d6c8bcec104)


# 4.NAND GATE

A NAND gate is a fundamental digital logic gate that outputs false (0) only when all its inputs are true (1); otherwise, it outputs true (1).

Definition:


### Truth Table (2-input NAND gate):

| Input A | Input B | Output (A NAND B) |
| ------- | ------- | ----------------- |
| 0       | 0       | 1                 |
| 0       | 1       | 1                 |
| 1       | 0       | 1                 |
| 1       | 1       | 0                 |


### Symbol:

![image](https://github.com/user-attachments/assets/e778b15d-9fa1-41a3-a75c-50fd50839e8c)


# 5.NOR GATE

* It’s NOT-OR gate — the output is true only when all inputs are false.
* It outputs *1* if all inputs are 0, else outputs 0.

### Truth Table (2-input NOR gate):

| Input A | Input B | Output (A NOR B) |
| ------- | ------- | ---------------- |
| 0       | 0       | 1                |
| 0       | 1       | 0                |
| 1       | 0       | 0                |
| 1       | 1       | 0                |


# Symbol:

![image](https://github.com/user-attachments/assets/3c3e88e0-6c59-4be3-8378-14e478461cdd)


# 6.XOR GATE

* Outputs 1 if the inputs are different.
  
* Outputs 0 if the inputs are the same.

---

### Truth Table (2-input XOR gate):

| Input A | Input B | Output (A XOR B) |
| ------- | ------- | ---------------- |
| 0       | 0       | 0                |
| 0       | 1       | 1                |
| 1       | 0       | 1                |
| 1       | 1       | 0                |


### Symbol: 

![image](https://github.com/user-attachments/assets/8ab12f1d-e963-4a60-9e25-0e380cea3308)


# 7.XNOR GATE

* It outputs 1 if the inputs are the same (both 0 or both 1).
* 
* It outputs 0 if the inputs are different.

---

### Truth Table (2-input XNOR gate):

| Input A | Input B | Output (A XNOR B) |
| ------- | ------- | ----------------- |
| 0       | 0       | 1                 |
| 0       | 1       | 0                 |
| 1       | 0       | 0                 |
| 1       | 1       | 1                 |


### Symbol: 

![image](https://github.com/user-attachments/assets/6c954d16-0ade-459d-b01d-2447943fb80b)
