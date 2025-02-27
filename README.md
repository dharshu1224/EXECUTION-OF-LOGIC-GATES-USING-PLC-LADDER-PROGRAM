# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :S.Dharshini
 # REGISTER NUMBER :212224230061
 # DEPARTMENT:AI&DS 
 # YEAR :I

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:
AND GATE:

![WhatsApp Image 2025-02-27 at 22 37 27_8bca2d69](https://github.com/user-attachments/assets/89f3acf7-54b3-4993-9b94-7b86c49856a9)

OR GATE:

![WhatsApp Image 2025-02-27 at 22 38 26_a447f119](https://github.com/user-attachments/assets/90ed02e9-d4e4-42c5-8318-1583cc180d41)

NOT GATE:

![WhatsApp Image 2025-02-27 at 22 39 58_9fc04891](https://github.com/user-attachments/assets/1bb82f4d-6cd5-4e8e-81e0-38c6915fca84)

NAND GATE:

![WhatsApp Image 2025-02-27 at 22 40 47_7709952c](https://github.com/user-attachments/assets/e38171d0-a613-453e-9a69-2be0430ed33e)

NOR GATE:

![WhatsApp Image 2025-02-27 at 22 41 51_5e2809a5](https://github.com/user-attachments/assets/aa114252-8bd8-4bfc-b7f4-9139f75ee4f5)

XOR GATE:

![WhatsApp Image 2025-02-27 at 22 42 53_5167ab6c](https://github.com/user-attachments/assets/ed91b2c7-6a88-4594-97e0-c2242b3270d8)

 
# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 

AND GATE:

![AND1](https://github.com/user-attachments/assets/aebab7e5-2734-416a-acde-a34e6500a477)
![AND2](https://github.com/user-attachments/assets/4c6766b3-b214-4d4d-8be1-6c226fb04499)
![AND3](https://github.com/user-attachments/assets/2dbb606f-21b8-4a78-acb6-5a95fc1ec83f)
![AND4](https://github.com/user-attachments/assets/db749228-c299-44f1-ac24-31fdd361aa9b)

OR GATE:

![OR1](https://github.com/user-attachments/assets/1ab309f7-c5b9-4919-aa8b-886859f9c98e)
![OR2](https://github.com/user-attachments/assets/988b3acf-19e1-4799-8cd2-d5b7fbace4e7)
![OR3](https://github.com/user-attachments/assets/cf02cc95-c841-4bad-9ed2-4175dbb115f2)
![OR4](https://github.com/user-attachments/assets/5ab903dc-3e52-4835-8423-628fd17be8f0)

NAND GATE:

![NAND1](https://github.com/user-attachments/assets/e84e9473-4519-40fd-a925-760d7c33d966)
![NAND2](https://github.com/user-attachments/assets/51ffd1f4-9b03-4b67-9aaf-a74f1cb3a571)
![NAND3](https://github.com/user-attachments/assets/d21c2b39-32f3-4b17-b137-0862d9579e28)
![NAND4](https://github.com/user-attachments/assets/00286bd4-4694-4f1c-a323-8835061907d0)

NOR GATE:

![NOR1](https://github.com/user-attachments/assets/46eb31e3-7f87-4138-a075-701a975ab8f2)
![NOR2](https://github.com/user-attachments/assets/eda3cd16-e9eb-4c54-8cc3-ada836b217c4)
![NOR3](https://github.com/user-attachments/assets/05cc5bbb-79c6-4f3a-a503-3cf16bfd2fca)
![NOR4](https://github.com/user-attachments/assets/837d6052-a943-4ac1-af65-fda75345fed2)

XOR GATE:

![XOR1](https://github.com/user-attachments/assets/31037671-9378-4865-89fa-2a3413f67720)
![XOR2](https://github.com/user-attachments/assets/76698691-62fc-49b9-8c44-cb3dc03ab96b)
![XOR3](https://github.com/user-attachments/assets/ef2256b8-7630-458d-ad45-1f6326e66fba)
![XOR4](https://github.com/user-attachments/assets/eaa4a992-f0e6-4cfb-8a2b-209f6331c81a)





#Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
