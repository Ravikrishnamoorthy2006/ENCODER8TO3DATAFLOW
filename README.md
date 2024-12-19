### ENCODER 8TO3 DATAFLOW Modelling

Name : D.Ravikrishnamoorthy

Reg no : 24008789

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**

/* write all the steps invloved */

**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 
```
module encoder(din,a,b,c);
input[0:7]din;
output a;
output b;
output c;
assign a=din[4]|din[5]|din[6]|din[7];
assign a=din[4]|din[3]|din[6]|din[7];
assign a=din[2]|din[4]|din[6]|din[7];
endmodule


Developed by: D.Ravikrishnamoorthy
RegisterNumber: 24008789
```
*/

**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**

![Screenshot 2024-11-21 111114](https://github.com/user-attachments/assets/5c8ac223-83d1-4ccc-83cf-c1913082bf16)


**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**


![Screenshot 2024-12-19 105403](https://github.com/user-attachments/assets/abcb3608-0610-4034-bc27-0c4d01150f81)


**RESULTS**

Thus, the Encoder 8 To 3 is implemented in Dataflow Modelling using verilog and validating their functionality using their functional tables







