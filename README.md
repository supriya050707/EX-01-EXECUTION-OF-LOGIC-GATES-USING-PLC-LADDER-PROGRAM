# EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME : Supriy S J
 # REGISTER NUMBER : 212224110051
 # DEPARTMENT :B.E-CSE(IOT)
 # YEAR :3rd YEAR
 # DATE : 26/10/2026

 
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
AND Gate:

<img width="327" height="250" alt="image" src="https://github.com/user-attachments/assets/f3531a5a-dde9-4f63-b277-cdf7279df454" />

OR Gate:

<img width="324" height="254" alt="image" src="https://github.com/user-attachments/assets/ac2f9e01-59d7-4b7b-97ae-c3b045d01bfc" />

NOT Gate:

<img width="214" height="159" alt="image" src="https://github.com/user-attachments/assets/4337f75d-2b1b-4b14-96d0-4bfa3350aca7" />

 NAND Gate:

<img width="333" height="250" alt="image" src="https://github.com/user-attachments/assets/46a1cddd-75c8-4647-bced-df644a80f502" />

NOR Gate:

<img width="330" height="249" alt="image" src="https://github.com/user-attachments/assets/c364e75d-c0bc-4eff-859e-f5315c1e9ffd" />

XOR Gate:

<img width="326" height="248" alt="image" src="https://github.com/user-attachments/assets/83f8ec71-06ff-46e0-9d58-2df3a90a6a61" />

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
<img width="1505" height="572" alt="Screenshot 2026-10-26 102518" src="https://github.com/user-attachments/assets/f99224cf-76b3-4943-85b4-4da0d9fc7198" />

<img width="1485" height="670" alt="image" src="https://github.com/user-attachments/assets/1320f587-47d9-4dff-971f-50ea04344f2d" />

<img width="1482" height="992" alt="image" src="https://github.com/user-attachments/assets/1793f3dd-bc15-448b-a472-df4820a891d0" />

<img width="1487" height="987" alt="image" src="https://github.com/user-attachments/assets/b21d752a-9a02-40bc-bc7d-89769060fe3f" />



<img width="957" height="752" alt="image" src="https://github.com/user-attachments/assets/73456d32-b72c-4a75-b25b-8cd7519cf7d3" />

<img width="862" height="595" alt="image" src="https://github.com/user-attachments/assets/98d506c4-5cbc-411d-9872-3801445ecc5f" />


# Results:

The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
