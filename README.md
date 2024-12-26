# JKFLIPFLOP-USING-IF-ELSE

**AIM:** 

To implement  JK flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**JK Flip-Flop**

JK flip-flop is the modified version of SR flip-flop. It operates with only positive clock transitions or negative clock transitions. The circuit diagram of JK flip-flop is shown in the following figure.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/a649c30b-232b-4558-b188-fd6c09845180)


This circuit has two inputs J & K and two outputs Qtt & Qtt’. The operation of JK flip-flop is similar to SR flip-flop. Here, we considered the inputs of SR flip-flop as S = J Qtt’ and R = KQtt in order to utilize the modified SR flip-flop for 4 combinations of inputs. The following table shows the state table of JK flip-flop.

![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/c4360742-e8a8-4937-b089-c46c0433f9a3)

 
Here, Qtt & Qt+1t+1 are present state & next state respectively. So, JK flip-flop can be used for one of these four functions such as Hold, Reset, Set & Complement of present state based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of JK flip-flop. Present Inputs Present State Next State
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/6c275261-a6d5-4c37-a3a7-1e88ca11c4cd)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. Three variable K-Map for next state, Qt+1t+1 is shown in the following figure.
 
![image](https://github.com/naavaneetha/JKFLIPFLOP-USING-IF-ELSE/assets/154305477/5174f41b-0ce0-4329-a372-6d1943ea6673)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=JQ(t)′+K′Q(t)Q(t+1)=JQ(t)′+K′Q(t)

**Procedure**

1. Go to Quartus software.

2. Set new environment.

3. Type the code to implement SR flipflop using Verilog and validate their functionality using
their functional tables.

4. Run the program.

5. Give inputs in the waveform table.

6. Run the program.

**PROGRAM**

![Screenshot 2024-12-26 090545](https://github.com/user-attachments/assets/31389206-513a-42d5-99d2-857330f5f777)

Developed by: SUBIKSHA K RegisterNumber: 24001100

**RTL LOGIC FOR FLIPFLOPS**

![Screenshot 2024-12-26 090617](https://github.com/user-attachments/assets/536d5e72-c66b-4afe-b2cf-f51ea3285500)


**TIMING DIGRAMS FOR FLIP FLOPS**

![Screenshot 2024-12-26 090646](https://github.com/user-attachments/assets/b74c5774-4d94-420b-9835-bb15eb01a870)


**RESULTS**

Implementing JK flipflop using Verilog and validating their functionality using their functional tables
is executed and the output is verified successfully.
