# d_flip_flop


AIM:

To implement D flipflop using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

D Flip-Flop

D flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, D latch operates with enable signal. That means, the output of D flip-flop is insensitive to the changes in the input, D except for active transition of the clock signal. The circuit diagram of D flip-flop is shown in the following figure.


****<img width="742" height="355" alt="image" src="https://github.com/user-attachments/assets/c41ab649-f6e9-4cb6-9c43-6d7c80516788" />


This circuit has single input D and two outputs Qtt & Qtt’. The operation of D flip-flop is similar to D Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of D flip-flop.


<img width="457" height="168" alt="image" src="https://github.com/user-attachments/assets/11d45395-3a6b-495f-9c54-5fc1b332f9d0" />


Therefore, D flip-flop always Hold the information, which is available on data input, D of earlier positive transition of clock signal. From the above state table, we can directly write the next state equation as Qt+1t+1 = D


<img width="467" height="241" alt="image" src="https://github.com/user-attachments/assets/d3d0adc7-9a6b-4b1f-82ee-2274565a3d5a" />


Next state of D flip-flop is always equal to data input, D for every positive transition of the clock signal. Hence, D flip-flops can be used in registers, shift registers and some of the counters.

Procedure

/* write all the steps invloved */

PROGRAM

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber: */

RTL LOGIC FOR FLIPFLOPS

TIMING DIGRAMS FOR FLIP FLOPS

RESULTS
