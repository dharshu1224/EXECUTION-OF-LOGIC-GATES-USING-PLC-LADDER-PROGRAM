# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :Dharhini.S
 # REGISTER NUMBER :212224230061
 # DEPARTMENT :AI&DS
 # YEAR :1st year

 
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
![image](https://github.com/user-attachments/assets/ec75207e-b0e9-4a03-9696-fb80cc1e08f8)

![image](https://github.com/user-attachments/assets/cce2f88d-bbe1-4c1c-bfbe-5528844a2006)

![image](https://github.com/user-attachments/assets/fd650bb3-6863-44c8-b558-e299491e738c)

![image](https://github.com/user-attachments/assets/8cec4b9c-778c-4750-ba2c-80755d33557d)

![image](https://github.com/user-attachments/assets/1c90cde8-6778-48be-bc0f-75a7d3a61773)

![image](https://github.com/user-attachments/assets/5b849a86-f7a1-47db-9c0f-363d3e4717f5)

 
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
![image](https://github.com/user-attachments/assets/3223cace-1e02-42a4-9ee8-e543609be70b)

![image](https://github.com/user-attachments/assets/6381b2e4-0920-4a6d-a28f-fa729c440c17)

![image](https://github.com/user-attachments/assets/c3671625-d88f-487b-9ed3-72308e25d3ae)

![image](https://github.com/user-attachments/assets/953be489-8449-400f-bafa-7978db75adef)

![image](https://github.com/user-attachments/assets/72993799-6562-47fa-947a-5d50bdb68416)

![image](https://github.com/user-attachments/assets/0a837c22-c0ea-49a9-86cc-aaefaf2fb34d)

![image](https://github.com/user-attachments/assets/a1c70bf4-a402-4824-b57d-1c7095eca611)

![image](https://github.com/user-attachments/assets/e2783063-3d87-432c-8177-4f3e64f77c7b)

![image](https://github.com/user-attachments/assets/5fe8ba73-09dc-4074-a465-25af120f7165)

![image](https://github.com/user-attachments/assets/dd530a37-e3ad-4107-859c-f6e96f0f72be)

![image](https://github.com/user-attachments/assets/027ffb88-07c2-45f3-ad6c-faf8ca03f177)

![image](https://github.com/user-attachments/assets/f072459f-5b9c-46e2-a553-f5569e8ca2c8)

![image](https://github.com/user-attachments/assets/ac8cb8a8-69f6-4f74-8ef0-812c6a5ec3ec)

![image](https://github.com/user-attachments/assets/54bff62d-8c78-4663-9630-b0597f64c86d)

![image](https://github.com/user-attachments/assets/c1c71ebf-74ee-4491-bd45-0f1b73031d46)

![image](https://github.com/user-attachments/assets/95c7fda5-7ae4-4faa-9844-1671bbb31248)

![image](https://github.com/user-attachments/assets/fd8cbfcd-7f2f-4143-b1cc-61357c70ca8a)

![image](https://github.com/user-attachments/assets/d5c3a367-78a9-4953-b4ee-b1cb8b8dee4b)

![image](https://github.com/user-attachments/assets/210f9289-44d7-4f78-8699-461be3875043)







#Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
