### ENCODER 8TO3 DATAFLOW Modelling

## **AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

## **SOFTWARE REQUIRED:** Quartus prime

## **THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

## **Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

## **Procedure**

1. Open Quartus and go to File -> New Project Wizard to create a new project.

2. Then, Go to File -> New -> Verilog HDL File and type the program. Compile and run the program.

3. Then go to Tools -> NetList Viewers -> RTL Viewer and generate the RTL schematic and save the logic diagram.

4. Then go to File -> New -> University program VWF. Create nodes for inputs and outputs to generate the timing diagram.

5. Give different input combinations and go to Run Functional Simulation to generate the timing diagram.

## **PROGRAM**

![Screenshot (364)](https://github.com/user-attachments/assets/f2c118f2-6c51-4852-a8b4-2b861c7d0088)

## **LOGIC DIAGRAM**

![Screenshot (363)](https://github.com/user-attachments/assets/e3d83daa-db0a-4f95-8549-3ddd9a39bf40)

## **WAVEFORM**

![waveform](https://github.com/user-attachments/assets/ca4f56b0-5244-4129-b975-92388dde2171)

## **RESULTS**




