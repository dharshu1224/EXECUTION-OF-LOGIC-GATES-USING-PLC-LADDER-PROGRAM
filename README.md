# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :S.DHARSHINI
 # REGISTER NUMBER :212224230061
 # DEPARTMENT :AI&DS
 # YEAR :1ST YEAR

 
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

![WhatsApp Image 2025-03-02 at 17 47 46_d3026009](https://github.com/user-attachments/assets/b5da078c-1d13-4fa1-a454-62462d30984e)

NAND GATE:

![WhatsApp Image 2025-03-02 at 17 48 33_3073e4d2](https://github.com/user-attachments/assets/b35135ac-92a6-4cd7-97cc-f7b29a183731)

OR GATE:

![WhatsApp Image 2025-03-02 at 17 49 19_fa478a6a](https://github.com/user-attachments/assets/955d82bf-fcf0-4f49-a111-3c14d79de98f)

NOT GATE:

![WhatsApp Image 2025-03-02 at 17 49 53_56d01770](https://github.com/user-attachments/assets/8d11c9a6-7496-4d5b-a232-0230d9286436)

NOR GATE:

![WhatsApp Image 2025-03-02 at 17 50 35_f604556c](https://github.com/user-attachments/assets/2ac1e10a-9721-4d17-9c11-1d001e476e62)

XOR GATE:

![WhatsApp Image 2025-03-02 at 17 53 50_0d90104a](https://github.com/user-attachments/assets/80b9c215-0e86-42bd-9560-7f6138d25936)

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

![ANDMINE1](https://github.com/user-attachments/assets/68bb933d-0a33-4493-bad9-e09cf2c47861)

![ANDMINE2](https://github.com/user-attachments/assets/8016e89b-efdd-4b2f-b604-465dca975aa2)

![ANDMINE3](https://github.com/user-attachments/assets/08a0bde6-d35d-4ce5-9d8b-742b1ec616cf)

![ANDMINE4](https://github.com/user-attachments/assets/959ae604-3607-4b3e-8948-995fc4675d04)

NAND GATE:

![NANDMINE1](https://github.com/user-attachments/assets/79e17504-150f-4066-85f0-147273abb424)

![NANDMINE2](https://github.com/user-attachments/assets/d34fa50d-29b1-4ea3-ba3e-c4965636d790)

![NANDMINE3](https://github.com/user-attachments/assets/0910f245-7b67-47b8-b843-4b8a91cdff80)

![NANDMINE4](https://github.com/user-attachments/assets/d6a84ff3-dfed-4a10-81ac-5abb2ca5546f)

OR GATE:

![ORMINE1](https://github.com/user-attachments/assets/8b6d570e-634e-4bee-a561-9986c41e88dd)

![ORMINE2](https://github.com/user-attachments/assets/b37f3f65-e297-4bf2-b11c-37a09e0acec4)

![ORMINE3](https://github.com/user-attachments/assets/d7c30e98-899e-4e8b-ac38-e2625ceefab5)

![ORMINE4](https://github.com/user-attachments/assets/6be8992c-1f8b-427d-9c32-9655443fb4f7)

NOT GATE:

![NOTMINE1](https://github.com/user-attachments/assets/b7a50844-e0e3-4615-96cd-149ede70be31)

![NOTMINE2](https://github.com/user-attachments/assets/760f7e71-1f6e-42e0-b275-7a90380665f1)

NOR GATE:

![NORMINE1](https://github.com/user-attachments/assets/0c203e60-8c25-45d6-95ec-b2683c161f70)

![NORMINE2](https://github.com/user-attachments/assets/90351b62-897c-48dd-b562-1135c0b429f1)

![NORMINE3](https://github.com/user-attachments/assets/0f538ebb-2543-4078-82e9-923a1be810f5)

![NORMINE4](https://github.com/user-attachments/assets/ca0b13c3-25a8-436b-92af-258819efe996)

XOR GATE:

![XORMINE1](https://github.com/user-attachments/assets/84fa376b-c5b3-4e65-981f-ccb5d93025f5)

![XORMINE2](https://github.com/user-attachments/assets/752542e8-931f-4fc8-89c7-cd2a4cc9b90a)

![XORMINE3](https://github.com/user-attachments/assets/d03ee229-6875-42c3-a244-e1aad889464c)

![XORMINE4](https://github.com/user-attachments/assets/60858e83-339a-4c9c-a9dd-5bd9bdf9ff98)



#Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
