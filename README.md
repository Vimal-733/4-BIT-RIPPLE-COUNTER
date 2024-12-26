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
Step 1: Open Quartus II in your laptop.

Step 2: Write code to implement SR flipflop using Verilog and validating their functionality using their functional tables.

Step 3: Run compilation to check for errors.

Step 4: Open waveform output and load input values.

Step 5: Run simulation to get the output.

Step 6: Open in RTL viewers to get RTL diagram output.

**PROGRAM**

/* Program for 4 Bit Ripple Counter and verify its truth table in quartus using Verilog programming.

 Developed by:A.VIMAL
 RegisterNumber:24005922
*/

**RTL LOGIC FOR 4 Bit Ripple Counter**
![WhatsApp Image 2024-12-26 at 21 32 18_319a430d](https://github.com/user-attachments/assets/01b7da40-0ed3-45b2-897d-ef0a7a70e3a7)

**TIMING DIGRAMS FOR 4 Bit Ripple Counter**
![WhatsApp Image 2024-12-26 at 21 32 43_01d61d36](https://github.com/user-attachments/assets/ee863c2f-4602-4747-b893-2f55a1606e6e)

**RESULTS**
The observation of the simulation results and confirm the successful execution of the program.
