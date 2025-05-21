# Digital_Electronics_Internship

# Table of contents 

- [What is Digital Electronics](#what-is-digital-electronics)
- [Applications of Digital Electronics](#applications-of-digital-electronics)
- [Digital vs Analog Signals](#digital-vs-analog-signals)
- [Number Systems](#number-systems)
- [Conversion between Number Systems](#conversion-between-number-systems)
- [Basic Logic Gates](#basic-logic-gates)
- [Integrated Circuits-IC's](#integrated-circuits-ics)
  

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

**Truth Table**

|A|B| A & B|
|-----|----|------|
|0|0|0|
|0|1|0|
|1|0|0|
|1|1|1|

**Key Point:**

Output is true (1) only when both inputs are true (1).

**Symbol:**

![image](https://github.com/user-attachments/assets/cb7096d8-4fae-4a1e-a0ff-5204effddf5a)

# 2.OR Gate

An OR gate is a basic digital logic gate that implements logical disjunction. It gives a high (1) output if at least one of its inputs is high. In other words, the output is true when any input is true.

**Truth Table:**
|*A|	**B|	**Y (A OR B)*|
|-----|-------|---------------|
|0	|0	|0|
|0	|1	|1|
|1	|0	|1|
|1|	1|	1|

**Key Points**

If both inputs are 0, the output is 0.

If at least one input is 1, the output is 1.

*Symbol*

![image](https://github.com/user-attachments/assets/a93f89ba-5389-436e-aa8d-42604ea7bc62)

# 3.NOT Gate

A NOT gate, also known as an inverter, is a basic digital logic gate that outputs the opposite (inverse) of its input. It has only one input and one output.

**Function:**

If the input is 1 (true or HIGH), the output is 0 (false or LOW).

If the input is 0, the output is 1

The NOT gate is usually represented by a triangle pointing to the right with a small circle (called a "bubble") at the output.

**Truth Table:**
|*Input (A)* |	*Output (¬A)*|
|--------------|------------------|
|0	|1|
|1	|0|

This table shows that the NOT gate simply flips the input value.

**Symbol:**

![image](https://github.com/user-attachments/assets/4631b202-0aab-47cd-96d1-8cefdcc79094)

# 4.NAND GATE

Definition:

A NAND gate is a fundamental digital logic gate that outputs false (0) only when all its inputs are true (1); otherwise, it outputs true (1).

**Truth Table**
| Input A | Input B | Output (A NAND B) |
| ------- | ------- | ----------------- |
| 0       | 0       | 1                 |
| 0       | 1       | 1                 |
| 1       | 0       | 1                 |
| 1       | 1       | 0                 |


**Symbol:**

![image](https://github.com/user-attachments/assets/ab715794-ca3e-4cc3-b0e3-9ddf5699c003)


# 5.NOR GATE

It’s NOT-OR gate — the output is true only when all inputs are false.

It outputs *1* if all inputs are 0, else outputs 0.

**Truth Table** 

| Input A | Input B | Output (A NOR B) |
| ------- | ------- | ---------------- |
| 0       | 0       | 1                |
| 0       | 1       | 0                |
| 1       | 0       | 0                |
| 1       | 1       | 0                |


**Symbol:**

![image](https://github.com/user-attachments/assets/c6c825aa-818a-4dab-a85a-3b7d0fe7acd0)


# 6.XOR GATE

Outputs 1 if the inputs are different.
  
Outputs 0 if the inputs are the same.

**Truth Table** 

| Input A | Input B | Output (A XOR B) |
| ------- | ------- | ---------------- |
| 0       | 0       | 0                |
| 0       | 1       | 1                |
| 1       | 0       | 1                |
| 1       | 1       | 0                |


**Symbol:** 

![image](https://github.com/user-attachments/assets/f6bcbeed-6b5c-4962-90e2-d6790a4e9890)

# 7.XNOR GATE

It outputs 1 if the inputs are the same (both 0 or both 1)

It outputs 0 if the inputs are different.

**Truth Table**

| Input A | Input B | Output (A XNOR B) |
| ------- | ------- | ----------------- |
| 0       | 0       | 1                 |
| 0       | 1       | 0                 |
| 1       | 0       | 0                 |
| 1       | 1       | 1                 |


**Symbol** 

![image](https://github.com/user-attachments/assets/377c4950-ab15-4d06-9218-266d993dbec0)

# Integrated Circuits-IC's

**What is an Ic**

A tiny electronic device that combines multiple electronic components, such as transistors, resistors, and capacitors, onto a single semiconductor chip.

**Types of Logic Gates and Their ICs**

| Logic Gate | Symbol | Function                                             | Boolean Expression | Common ICs (TTL 74xx Series) |
| ---------- | ------ | ---------------------------------------------------- | ------------------ | ---------------------------- |
| AND        | ∧      | Output is HIGH only if all inputs are HIGH           | A · B              | 7408                         |
| OR         | ∨      | Output is HIGH if at least one input is HIGH         | A + B              | 7432                         |
| NOT        | ¬      | Inverts the input                                    | ¬A or A̅           | 7404                         |
| NAND       | ↑      | Output is LOW only if all inputs are HIGH (NOT-AND)  | ¬(A · B)           | 7400                         |
| NOR        | ↓      | Output is LOW if at least one input is HIGH (NOT-OR) | ¬(A + B)           | 7402                         |
| XOR        | ⊕      | Output is HIGH if inputs are different               | A ⊕ B              | 7486                         |
| XNOR       | =      | Output is HIGH if inputs are the same (NOT-XOR)      | ¬(A ⊕ B)           | 74266, 74LS266               |


**1.AND GATE - 7408 IC**

![image](https://github.com/user-attachments/assets/c844323d-756e-45f9-97b4-c84b2a2ddb1c)

![image](https://github.com/user-attachments/assets/3b2a3ff7-335f-460c-9153-dd8157a9ceb3)

**Tinkercad Circuit:AND GATE using IC 7408**

https://www.tinkercad.com/things/aWRce276Cfu-and-gate-ic-7408

![image](https://github.com/user-attachments/assets/676fa23b-e09c-44a8-9e3d-b3019c543881)

| **Pin Number** | **Pin Name** | **Function**                         |
| -------------- | ------------ | ------------------------------------ |
| 1              | A1           | Input to the 1st AND gate (A)        |
| 2              | B1           | Input to the 1st AND gate (B)        |
| 3              | Y1           | Output of the 1st AND gate (A AND B) |
| 4              | A2           | Input to the 2nd AND gate (A)        |
| 5              | B2           | Input to the 2nd AND gate (B)        |
| 6              | Y2           | Output of the 2nd AND gate (A AND B) |
| 8              | A3           | Input to the 3rd AND gate (A)        |
| 9              | B3           | Input to the 3rd AND gate (B)        |
| 10             | Y3           | Output of the 3rd AND gate (A AND B) |
| 11             | A4           | Input to the 4th AND gate (A)        |
| 12             | B4           | Input to the 4th AND gate (B)        |
| 13             | Y4           | Output of the 4th AND gate (A AND B) |
| 7              | Vcc          | Power supply pin (Typically +5V)     |
| 14             | GND          | Ground pin                           |


**Description**
 
The 7408 IC contains four 2-input AND gates. It’s used in:

•Logic Circuits for basic AND operations.

•Control Systems for conditions requiring multiple inputs.

•Timing & Synchronization in clocked circuits.

•Arithmetic for binary addition or multiplication.


**2.OR GATE - 7432 IC**

![image](https://github.com/user-attachments/assets/f51060d3-9527-4c46-b48a-29dbd0ffdb54)

![image](https://github.com/user-attachments/assets/9216fa49-fb7c-4795-a671-d44e4b6030a2)

**Tinkercad Circuit:OR GATE using IC 7432**

https://www.tinkercad.com/things/5ks4rsow4P2-or-gate-ic-7432

![image](https://github.com/user-attachments/assets/297c4b3c-72d4-49ff-9698-a26eb44bcf8e)

| Pin Number | Pin Name                  | Function                                 |
| ---------- | ------------------------- | ---------------------------------------- |
| **1**      | **Input A (1st OR Gate)** | First input for the first OR gate.       |
| **2**      | **Input B (1st OR Gate)** | Second input for the first OR gate.      |
| **3**      | **Output (1st OR Gate)**  | Output for the first OR gate.            |
| **4**      | **Ground (GND)**          | Connects to the ground.                  |
| **5**      | **Input A (2nd OR Gate)** | First input for the second OR gate.      |
| **6**      | **Input B (2nd OR Gate)** | Second input for the second OR gate.     |
| **7**      | **Output (2nd OR Gate)**  | Output for the second OR gate.           |
| **8**      | **Ground (GND)**          | Ground connection.                       |
| **9**      | **Input A (3rd OR Gate)** | First input for the third OR gate.       |
| **10**     | **Input B (3rd OR Gate)** | Second input for the third OR gate.      |
| **11**     | **Output (3rd OR Gate)**  | Output for the third OR gate.            |
| **12**     | **Vcc**                   | Connects to the positive supply voltage. |
| **13**     | **Input A (4th OR Gate)** | First input for the fourth OR gate.      |
| **14**     | **Input B (4th OR Gate)** | Second input for the fourth OR gate.     |

**Description**

•Adders: Perform binary addition.

•Control Systems: Trigger actions in alarms.

•Signal Combination: Combine signals for output.

•Memory: Store data in flip-flops.

**3.NOT GATE - 7404 IC**

![image](https://github.com/user-attachments/assets/2f9e41ef-60be-4513-a4cd-615608ae6ffb)

![image](https://github.com/user-attachments/assets/6dbca3b3-8d17-4b35-bdee-dd3accc3a4a9)

**Tickercad Circuit:NOT GATE using IC 7404**

https://www.tinkercad.com/things/hEjVv9kj5nc-not-gate-ic-7404

![image](https://github.com/user-attachments/assets/17635a7c-36e2-4942-94e5-fa36955a3171)

| **Pin Number** | **Pin Name** | **Function**                         |
| -------------- | ------------ | --------------------------------------- |
| **1**          | **A1**       | Input of the first inverter             |
| **2**          | **Y1**       | Output of the first inverter            |
| **3**          | **A2**       | Input of the second inverter            |
| **4**          | **Y2**       | Output of the second inverter           |
| **5**          | **A3**       | Input of the third inverter             |
| **6**          | **Y3**       | Output of the third inverter            |
| **7**          | **GND**      | Ground connection                       |
| **8**          | **Y4**       | Output of the fourth inverter           |
| **9**          | **A4**       | Input of the fourth inverter            |
| **10**         | **Y5**       | Output of the fifth inverter            |
| **11**         | **A5**       | Input of the fifth inverter             |
| **12**         | **Y6**       | Output of the sixth inverter            |
| **13**         | **A6**       | Input of the sixth inverter             |
| **14**         | **VCC**      | Positive supply voltage (typically +5V) |


**Description**

The 7404 Hex Inverter IC is used for:

•Signal Inversion: Inverts logic signals.

•Logic Gates: Builds NAND, NOR, etc.

•Oscillators: Generates clock signals.

•Pulse Shaping: Cleans noisy signals.

**4.NAND GATE - 7400 IC**

![image](https://github.com/user-attachments/assets/718150c0-662f-49d0-9585-b9147ef3e8f4)

![image](https://github.com/user-attachments/assets/b355ab93-7209-4eb4-8781-d53df7260473)

**Tinkercad Circuit: NAND GATE using IC 7400**

https://www.tinkercad.com/things/5fOCR436lhR-nand-gate-ic-7400

![image](https://github.com/user-attachments/assets/13040ba7-5f8d-442a-9cfc-370bca2ad5cd)

| **Pin Number** | **Pin Name** | **Function**                                                                             |
| -------------- | ------------ | ----------------------------------------------------------------------------------------------- |
| 1              | A1           | Input pin for the first input of the first NAND gate (G1).                                      |
| 2              | B1           | Input pin for the second input of the first NAND gate (G1).                                     |
| 3              | Output 1     | Output of the first NAND gate (G1).                                                             |
| 4              | GND          | Ground pin. Connect to the ground of the circuit.                                               |
| 5              | A2           | Input pin for the first input of the second NAND gate (G2).                                     |
| 6              | B2           | Input pin for the second input of the second NAND gate (G2).                                    |
| 7              | Output 2     | Output of the second NAND gate (G2).                                                            |
| 8              | VCC          | Power supply pin. Connect to +5V or appropriate voltage depending on the specific logic family. |
| 9              | A3           | Input pin for the first input of the third NAND gate (G3).                                      |
| 10             | B3           | Input pin for the second input of the third NAND gate (G3).                                     |
| 11             | Output 3     | Output of the third NAND gate (G3).                                                             |
| 12             | A4           | Input pin for the first input of the fourth NAND gate (G4).                                     |
| 13             | B4           | Input pin for the second input of the fourth NAND gate (G4).                                    |
| 14             | Output 4     | Output of the fourth NAND gate (G4).                                                            |

**Description**

The 7400 IC is used in:

•Logic Gates: Builds basic gates and complex circuits.

•Flip-Flops: Creates SR, D, and JK flip-flops for memory.

•Counters/Registers: Used in binary counters and shift registers.

•Sequential Logic: Designs state machines and timers.


**5.NOR GATE - 7402 IC**

![image](https://github.com/user-attachments/assets/37ef15d9-f545-4f6e-b5d3-26a114ebdef9)

![image](https://github.com/user-attachments/assets/f2776db2-f67a-45ff-8ae2-938033464c35)


**Tinkercad Circuit: NOR GATE using IC 7402**

https://www.tinkercad.com/things/bBbvIe2XoFh-nor-gate-ic-7402

![image](https://github.com/user-attachments/assets/e9d51b74-9d92-4bf5-a4e6-1c46b3affaa6)

| **Pin Number** | **Pin Name** | **Function**                                         |
| -------------- | ------------ | ----------------------------------------------------------- |
| 1              | A1           | Input pin for the first input of the first NOR gate (G1).   |
| 2              | B1           | Input pin for the second input of the first NOR gate (G1).  |
| 3              | Output 1     | Output of the first NOR gate (G1).                          |
| 4              | GND          | Ground pin. Connect to the ground of the circuit.           |
| 5              | A2           | Input pin for the first input of the second NOR gate (G2).  |
| 6              | B2           | Input pin for the second input of the second NOR gate (G2). |
| 7              | Output 2     | Output of the second NOR gate (G2).                         |
| 8              | VCC          | Power supply pin. Connect to +5V or appropriate voltage.    |
| 9              | A3           | Input pin for the first input of the third NOR gate (G3).   |
| 10             | B3           | Input pin for the second input of the third NOR gate (G3).  |
| 11             | Output 3     | Output of the third NOR gate (G3).                          |
| 12             | A4           | Input pin for the first input of the fourth NOR gate (G4).  |
| 13             | B4           | Input pin for the second input of the fourth NOR gate (G4). |
| 14             | Output 4     | Output of the fourth NOR gate (G4).                         |


**Description**

The 7402 IC is used for:

•Logic Circuits: Implements basic logic operations.

•Memory Circuits: Forms flip-flops and memory elements.

•Signal Inversion: Used for inverting signals in circuits.

•Control Systems: Applied in sequential logic and control systems.

**6.XOR GATE - 7486 IC**

![image](https://github.com/user-attachments/assets/1193bfdc-87aa-4b7f-8483-150f51bb11d2)

![image](https://github.com/user-attachments/assets/0a085c32-654d-47a8-b00f-4b02ecca7500)

**Tinkercad Circuit:XOR GATE using IC 7486**

https://www.tinkercad.com/things/6pBX3T16bJr-xor-gate-ic-7486

![image](https://github.com/user-attachments/assets/470b5fb1-0cb0-4cdd-8a6c-8336a374778f)

| **Pin Number** | **Pin Name** | **Function**                                         |
| -------------- | ------------ | ----------------------------------------------------------- |
| 1              | A1           | Input pin for the first input of the first XOR gate (G1).   |
| 2              | B1           | Input pin for the second input of the first XOR gate (G1).  |
| 3              | Output 1     | Output of the first XOR gate (G1).                          |
| 4              | GND          | Ground pin. Connect to the ground of the circuit.           |
| 5              | A2           | Input pin for the first input of the second XOR gate (G2).  |
| 6              | B2           | Input pin for the second input of the second XOR gate (G2). |
| 7              | Output 2     | Output of the second XOR gate (G2).                         |
| 8              | VCC          | Power supply pin. Connect to +5V or appropriate voltage.    |
| 9              | A3           | Input pin for the first input of the third XOR gate (G3).   |
| 10             | B3           | Input pin for the second input of the third XOR gate (G3).  |
| 11             | Output 3     | Output of the third XOR gate (G3).                          |
| 12             | A4           | Input pin for the first input of the fourth XOR gate (G4).  |
| 13             | B4           | Input pin for the second input of the fourth XOR gate (G4). |
| 14             | Output 4     | Output of the fourth XOR gate (G4).                         |


**Description**

The 7486 IC is used for:

•Binary Adders: In half and full adders.

•Error Detection: Parity generators and checkers.

•Data Comparison: In digital comparators.

•Digital Signal Processing: For signal manipulation.


**7.XNOR GATE - 74266 IC**

![image](https://github.com/user-attachments/assets/8113d208-7e1c-417f-9106-e9bafc9c4a64)

![image](https://github.com/user-attachments/assets/29861909-1d58-4f74-8010-ffad7ac8209b)

**Tinkercad Circuits:XNOR GATE using IC 74266**

https://www.tinkercad.com/things/1emzC4qRiU8-xnor-gate-ic-74266

![image](https://github.com/user-attachments/assets/9b43fe3e-ef56-4352-b303-e8ad24395d17)

| **Pin No.** | **Pin Name** | **Function**                  |
| ----------- | ------------ | -------------------------------- |
| 1           | Y1           | Output for Buffer 1 (open-drain) |
| 2           | Y2           | Output for Buffer 2 (open-drain) |
| 3           | Y3           | Output for Buffer 3 (open-drain) |
| 4           | Y4           | Output for Buffer 4 (open-drain) |
| 5           | Y5           | Output for Buffer 5 (open-drain) |
| 6           | Y6           | Output for Buffer 6 (open-drain) |
| 7           | GND          | Ground (0V) connection           |
| 8           | A1           | Input for Buffer 1 (logic input) |
| 9           | A2           | Input for Buffer 2 (logic input) |
| 10          | A3           | Input for Buffer 3 (logic input) |
| 11          | A4           | Input for Buffer 4 (logic input) |
| 12          | A5           | Input for Buffer 5 (logic input) |
| 13          | A6           | Input for Buffer 6 (logic input) |
| 14          | Vcc          | Power supply (positive voltage)  |

**Description**

•The LS 74266 is used for:

•Bus Systems (e.g., I²C)

•Signal Level Shifting

•Open-Drain Logic

•Interrupt Lines

•Multiple Device Control.


**Applications of IC's**

| **Logic Gate** | **Common IC Number**     | **Application Examples**                              |
| -------------- | ------------------------ | ----------------------------------------------------- |
| **AND**        | 7408 (Quad 2-input AND)  | Input validation circuits, digital comparators        |
| **OR**         | 7432 (Quad 2-input OR)   | Alarm systems, control systems, logic decision making |
| **NOT**        | 7404 (Hex Inverter)      | Signal inversion, waveform generation                 |
| **NAND**       | 7400 (Quad 2-input NAND) | Logic building blocks, memory circuits, timers        |
| **NOR**        | 7402 (Quad 2-input NOR)  | SR Latch, control circuits, pattern detection         |
| **XOR**        | 7486 (Quad 2-input XOR)  | Adders, parity checkers, digital comparators          |
| **XNOR**       | 74266 or 74LS266         | Equality checkers, digital logic comparators          |


**IMPLEMENTATION OF LOGIC GATES**

**AND USING NAND**

https://www.tinkercad.com/things/9honMKm8l6i-and-using-nand

![image](https://github.com/user-attachments/assets/46337248-f2af-4ede-8b5a-12fee2793b69)

**OR USING NAND**

https://www.tinkercad.com/things/4TEf68leyWs-or-using-nand

![image](https://github.com/user-attachments/assets/e79211b2-3ea4-4372-94da-d5d3fed9e2bd)





