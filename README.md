# Digital_Electronics_Internship

# Table of contents 

- [What is Digital Electronics](#what-is-digital-electronics)
- [Applications of Digital Electronics](#applications-of-digital-electronics)
- [Digital vs Analog Signals](#digital-vs-analog-signals)
- [Number Systems](#number-systems)
- [Conversion between Number Systems](#conversion-between-number-systems)
- [Basic Logic Gates](#basic-logic-gates)
- [Integrated Circuits-IC's](#integrated-circuits-ics)
  

# What is Digital Electronics

Digital electronics is a branch of electronics that deals with systems and devices that use digital signals, which are discrete representations of data, 
typically using binary code (0s and 1s).

Some key elements in digital electronics include:

Logic Gates, Binary System, Combinational Circuits, Digital electronics is fundamental to modern technology, including computing, communication, and control system.

# Applications of Digital Electronics

1.Computing and Microprocessors

2.Communication Systems

3.Control Systems

4.Home Appliances.

5.Smart Refrigerators

6.Automotive 

# Digital vs Analog signals

| **Analog** | **Digital**|
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

| **System**      | **Base** | **Digits**                   | **Used In**                                                                 | **Example**                                  |
| --------------- | -------- | ---------------------------- | --------------------------------------------------------------------------- | -------------------------------------------- |
| **Binary**      | 2        | 0, 1                         | All digital systems; the most fundamental system.                           | 1011 (binary) = 11 (decimal)                 |
| **Decimal**     | 10       | 0, 1, 2, 3, 4, 5, 6, 7, 8, 9 | Human-readable format; not commonly used internally in digital electronics. | 27 (decimal) = 11011 (binary)                |
| **Hexadecimal** | 16       | 0–9, A–F (A=10, F=15)        | Compact representation of binary values (4 bits = 1 hex digit).             | 2F (hex) = 0010 1111 (binary) = 47 (decimal) |

# Conversion between number systems 

| **Conversion Type**       | **Explanation**                                                             | **Example**                                                                                                      |
| ------------------------- | --------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Binary → Decimal**      | Convert binary to decimal by summing the powers of 2.                       | $1011$ (binary) = $1 \times 2^3 + 0 \times 2^2 + 1 \times 2^1 + 1 \times 2^0 = 8 + 0 + 2 + 1 =$ **11 (decimal)** |
| **Decimal → Binary**      | Divide decimal by 2, recording the remainders.                              | $27$ (decimal) = **11011 (binary)**                                                                              |
| **Binary → Octal**        | Group binary in sets of 3 (from right) and convert each set to octal.       | $101101$ (binary) = $101 \, 101$ = **55 (octal)**                                                                |
| **Octal → Binary**        | Convert each octal digit to its 3-bit binary equivalent.                    | $5$ (octal) = **101 (binary)**                                                                                   |
| **Binary → Hexadecimal**  | Group binary in sets of 4 (from right) and convert each set to hexadecimal. | $101101$ (binary) = $1011 \, 0101$ = **2D (hexadecimal)**                                                        |
| **Hexadecimal → Binary**  | Convert each hex digit to its 4-bit binary equivalent.                      | $2F$ (hex) = $0010 \, 1111$ = **00101111 (binary)**                                                              |
| **Decimal → Octal**       | Divide decimal by 8 and record the remainders.                              | $27$ (decimal) = **33 (octal)**                                                                                  |
| **Octal → Decimal**       | Multiply each octal digit by 8 raised to its position power and sum them.   | $33$ (octal) = $3 \times 8^1 + 3 \times 8^0 = 24 + 3 =$ **27 (decimal)**                                         |
| **Decimal → Hexadecimal** | Divide decimal by 16 and record the remainders.                             | $47$ (decimal) = **2F (hexadecimal)**                                                                            |
| **Hexadecimal → Decimal** | Multiply each hex digit by 16 raised to its position power and sum them.    | $2F$ (hex) = $2 \times 16^1 + 15 \times 16^0 = 32 + 15 =$ **47 (decimal)**                                       |
| **Octal → Hexadecimal**   | Convert octal to binary, then binary to hexadecimal.                        | $55$ (octal) = $101 \, 101$ (binary) = **2D (hexadecimal)**                                                      |
| **Hexadecimal → Octal**   | Convert hexadecimal to binary, then binary to octal.                        | $2F$ (hex) = $0010 \, 1111$ (binary) = **55 (octal)**                                                            |

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

<img src="https://github.com/user-attachments/assets/056f91e0-ddcf-4a94-bca3-4c89963965b4" width="300" />

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

**Symbol**

<img src="https://github.com/user-attachments/assets/bad49c2d-e96d-4de8-9839-4d7954054b33" width="300" />

# 3.NOT Gate

A NOT gate, also known as an inverter, is a basic digital logic gate that outputs the opposite (inverse) of its input. It has only one input and one output.

**Function:**

If the input is 1 (true or HIGH), the output is 0 (false or LOW).

If the input is 0, the output is 1

The NOT gate is usually represented by a triangle pointing to the right with a small circle (called a "bubble") at the output.

**Truth Table:**
|**Input (A)** |	*Output (¬A)*|
|--------------|------------------|
|0	|1|
|1	|0|

This table shows that the NOT gate simply flips the input value.

**Symbol:**

<img src="https://github.com/user-attachments/assets/b1b4a9d2-90b9-47dd-b9af-9307ee2643d9" width="300" />

# 4.NAND GATE

**Definition:**

A NAND gate is a fundamental digital logic gate that outputs false (0) only when all its inputs are true (1); otherwise, it outputs true (1).

**Truth Table**
| Input A | Input B | Output (A NAND B) |
| ------- | ------- | ----------------- |
| 0       | 0       | 1                 |
| 0       | 1       | 1                 |
| 1       | 0       | 1                 |
| 1       | 1       | 0                 |


**Symbol:**

<img src="https://github.com/user-attachments/assets/8aaa79e8-12b8-4b9f-b6b9-79da1172183f" width="300" />

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

<img src="https://github.com/user-attachments/assets/9805dcb4-97d2-48ba-912e-6cc9f5932daa" width="300" />

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

<img src="https://github.com/user-attachments/assets/8e657000-92e7-4d27-b17d-69acf030fd99" width="300" />

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

<img src="https://github.com/user-attachments/assets/66024712-e907-4684-8b96-588ce7f86d1b" width="300" />


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


**1.AND GATE - 7408 IC**

<img src="https://github.com/user-attachments/assets/fefbe148-7b5f-4121-b694-ee580744b6bb" width="350">

![image](https://github.com/user-attachments/assets/335f63ee-4dbb-4444-8be7-bbbd344dc09a)

<img src="https://github.com/user-attachments/assets/0f08012c-269a-46eb-a2dc-8af2bcc650f3" width="400" />

**Tinkercad Circuit:AND GATE using IC 7408**

[TinkerCAD](https://www.tinkercad.com/things/aWRce276Cfu-and-gate-ic-7408)


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
 
The 7408 IC contains four 2-input AND gates. It’s used in: Logic Circuits for basic AND operations. Control Systems for conditions requiring multiple inputs. Timing & Synchronization in clocked circuits.
Arithmetic for binary addition or multiplication.


**2.OR GATE - 7432 IC**

<img src="https://github.com/user-attachments/assets/9216fa49-fb7c-4795-a671-d44e4b6030a2" width="350" />

![image](https://github.com/user-attachments/assets/f51060d3-9527-4c46-b48a-29dbd0ffdb54)

<img src="https://github.com/user-attachments/assets/99de0dd5-2850-4146-b5bc-e2f982a891ea" width="400" />

**Tinkercad Circuit:OR GATE using IC 7432**

[TinkerCAD](https://www.tinkercad.com/things/2Oc23z71esd-or-gate-ic-7432)


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

An OR gate IC is a digital electronic component that performs the logical OR operation. The OR gate is one of the basic building blocks in digital logic circuits. It has two or more input signals and produces a single output signal. The output of an OR gate is high (logic 1) if at least one of its inputs is high. If all inputs are low (logic 0), the output is also low.

**3.NOT GATE - 7404 IC**

<img src="https://github.com/user-attachments/assets/6dbca3b3-8d17-4b35-bdee-dd3accc3a4a9" width="350" />

![image](https://github.com/user-attachments/assets/64917dd8-a04a-475d-9a0b-0eb7c535321d)

<img src="https://github.com/user-attachments/assets/b4cf7dde-995f-42ef-be34-bc5426a92b0c" width="400" />

**Tickercad Circuit:NOT GATE using IC 7404**

[TinkerCAD](https://www.tinkercad.com/things/jr1CT429oD6-not-gate-ic-7404)


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

A NOT gate IC is a digital logic device that implements the inverter function. It is one of the basic building blocks of digital circuits. The NOT gate has only one input and one output, and its operation is based on logical negation. The NOT gate performs the function of inverting the input signal. If the input is logic 1 (high), the output will be logic 0 (low), and if the input is logic 0 (low), the output will be logic 1 (high). 

**4.NAND GATE - 7400 IC**

<img src="https://github.com/user-attachments/assets/b355ab93-7209-4eb4-8781-d53df7260473" width="350" />

![image](https://github.com/user-attachments/assets/718150c0-662f-49d0-9585-b9147ef3e8f4)

<img src="https://github.com/user-attachments/assets/f2a7e74a-39ba-4267-9f70-9efcc173b14e" width="400" />

**Tinkercad Circuit: NAND GATE using IC 7400**

[TinkerCAD](https://www.tinkercad.com/things/iREb6SH4aop-nand-gate-ic-7400)


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

A NAND gate IC is an integrated circuit that implements the NAND (Not AND) logic function, which is a fundamental building block in digital electronics. The NAND gate performs the opposite operation of an AND gate; it produces a low output only when all of its inputs are high, and outputs a high signal in all other cases. In theory, the NAND gate takes multiple input signals and outputs the inverse of their logical AND operation.
For two inputs, the NAND gate’s output is high if at least one input is low, and only goes low when both inputs are high. 

**5.NOR GATE - 7402 IC**

<img src="https://github.com/user-attachments/assets/6b2eac61-21c1-4f70-b073-137ba249e327" width="350" />

![image](https://github.com/user-attachments/assets/735fa2be-d893-4d45-8135-007433b85917)

<img src="https://github.com/user-attachments/assets/fb5b42e7-2067-46cb-867a-9d5b1e11372e" width="400" />

**Tinkercad Circuit: NOR GATE using IC 7402**

[TinkerCAD](https://www.tinkercad.com/things/eK8OsWxEUWg-nor-gate-ic-7402)


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

A NOR gate IC is a digital logic integrated circuit that performs the NOR (Not OR) operation. The NOR gate is a combination of an OR gate followed by a NOT gate, meaning it inverts the result of the OR operation. It is one of the fundamental logic gates used in digital electronics.
In theory, the NOR gate produces a high output only when all of its inputs are low. If any of the inputs is high, the output becomes low. This behavior makes the NOR gate a universal gate, meaning that any other logic gate can be constructed using only NOR gates.

**6.XOR GATE - 7486 IC**

<img src="https://github.com/user-attachments/assets/0a085c32-654d-47a8-b00f-4b02ecca7500" width="350" />

![image](https://github.com/user-attachments/assets/1193bfdc-87aa-4b7f-8483-150f51bb11d2)

<img src="https://github.com/user-attachments/assets/470b5fb1-0cb0-4cdd-8a6c-8336a374778f" width="400" />

**Tinkercad Circuit:XOR GATE using IC 7486**

[TinkerCAD](https://www.tinkercad.com/things/6pBX3T16bJr-xor-gate-ic-7486)


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

The XOR gate, or Exclusive OR gate, is a fundamental digital logic gate that outputs a high signal only when the inputs are unequal. It performs the logical operation of exclusive disjunction, meaning it gives a true (logic 1) output only when the number of true inputs is odd.
In its simplest form with two inputs, the XOR gate outputs a logic 1 only if one of the inputs is 1 and the other is 0. If both inputs are the same—either both 0 or both 1—the output is 0. 

**7.XNOR GATE - 74266 IC**

<img src="https://github.com/user-attachments/assets/ca46a46e-b20b-46ac-b327-ea11ee43efa6" width="350" />

![image](https://github.com/user-attachments/assets/29861909-1d58-4f74-8010-ffad7ac8209b)

<img src="https://github.com/user-attachments/assets/9b43fe3e-ef56-4352-b303-e8ad24395d17" width="400" />


**Tinkercad Circuits:XNOR GATE using IC 74266**

[Tinkercad](https://www.tinkercad.com/things/1emzC4qRiU8-xnor-gate-ic-74266)

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

An XNOR gate (Exclusive-NOR gate) is a digital logic gate that produces a high output (logic 1) when its inputs are equal. It is the complement of the XOR (Exclusive-OR) gate.
The XNOR gate performs the logical equality operation. It compares two input signals and returns a true (high) output if both inputs are the same—either both 0 or both 1. If the inputs are different, the output is false (low).


**IMPLEMENTATION OF LOGIC GATES**

**AND USING NAND**

[TinkerCAD](https://www.tinkercad.com/things/9honMKm8l6i-and-using-nand)

<img src="https://github.com/user-attachments/assets/3863da6d-3a32-4063-836a-fa7b55a5ed04" width="400" />

**OR USING NAND**

[TinkerCAD](https://www.tinkercad.com/things/4TEf68leyWs-or-using-nand)

<img src="https://github.com/user-attachments/assets/9ed481ee-4f38-400e-a90f-90a6d32eccc7" width="400" />

**NOT USING NAND**

[TinkerCAD](https://www.tinkercad.com/things/alJbUbqD9En-not-using-nand)

<img src="https://github.com/user-attachments/assets/40335afb-22d3-4933-abe1-1e2673c45491" width="400" />

**AND USING NOR**

[TinkerCAD](https://www.tinkercad.com/things/640aOLXYdO9-and-using-nor-)

<img src="https://github.com/user-attachments/assets/34abe037-bae7-4abd-9ea2-5a2002261ccf" width="400" />

**NOT USING NOR**

[TinkerCAD](https://www.tinkercad.com/things/acczd58xnGi-not-using-nor)

<img src="https://github.com/user-attachments/assets/abcacfbf-febe-417c-b0ad-34a15865e7ef" width="400" />

**OR USING NOR**

[TinkerCAD](https://www.tinkercad.com/things/4VRQSxWR4VX-or-using-nor)

<img src="https://github.com/user-attachments/assets/71d5b9c5-d02f-4287-a7a6-14c92cbf801a" width="400" />




