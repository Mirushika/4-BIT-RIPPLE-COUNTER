# 4-BIT-RIPPLE-COUNTER

**AIM:**

To implement  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**4 Bit Ripple Counter**

A binary ripple counter consists of a series connection of complementing flip-flops (T or JK type), with the output of each flip-flop connected to the Clock Pulse input of the next higher-order flip-flop. The flip-flop holding the least significant bit receives the incoming count pulses. The diagram of a 4-bit binary ripple counter is shown in Fig. below.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/cb4b74d4-31ab-4359-95d0-d22e67daba13)

In timing diagram Q0 is changing as soon as the negative edge of clock pulse is encountered, Q1 is changing when negative edge of Q0 is encountered(because Q0 is like clock pulse for second flip flop) and so on.

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/a573a7d6-014e-4e54-93e6-e2ac9530960b)

![image](https://github.com/naavaneetha/4-BIT-RIPPLE-COUNTER/assets/154305477/85e1958a-2fc1-49bb-9a9f-d58ccbf3663c)

**Procedure**

1.Type the program in Quartus software.

2.Compile and run the program.

3.Generate the RTL schematic and save the logic diagram.

4.Create nodes for inputs and outputs to generate the timing diagram.

5.For different input combinations generate the timing diagram

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by: Mirushika .T     RegisterNumber: 24901203
*/


![Screenshot 2024-12-11 211230](https://github.com/user-attachments/assets/80ae69f1-e104-466c-a10c-a25d9d37d77e)


![Screenshot 2024-12-11 185711](https://github.com/user-attachments/assets/ec4639df-6958-48b2-a6c9-3f8d48831801)



**RTL LOGIC FOR 4 Bit Ripple Counter**


![Screenshot 2024-12-11 185731](https://github.com/user-attachments/assets/24f1c416-c24d-4239-afb3-f1f688113aa2)



**TIMING DIGRAMS FOR 4 Bit Ripple Counter**


![Screenshot 2024-12-11 211343](https://github.com/user-attachments/assets/0d0709ce-6157-4a42-a27c-83e3b8689734)


**RESULTS**

The implemented  4 Bit Ripple Counter using verilog and validating their functionality using their functional tables is verified.

