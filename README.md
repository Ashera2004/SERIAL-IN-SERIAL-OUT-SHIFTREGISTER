# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

1. Create a new Verilog project in Quartus:

   • Open Quartus Prime software.
   • Create a new project and file (Verilog HDL).
2. Write Verilog Code for the SISO Shift Register:

  • Define the module, inputs, and outputs.
  • Use D flip-flops (or the built-in D flip-flop) to implement the register functionality.
  • Use the clock signal to synchronize the shifting.


**PROGRAM**

![siso_code](https://github.com/user-attachments/assets/ff9245f4-9d0b-407e-a17f-34ee59595344)



Developed by: A S SIDDARTH  

Register Number: 212224040316



**RTL LOGIC FOR SISO Shift Register**


![siso_rtl](https://github.com/user-attachments/assets/3d5aefee-fafb-4bb1-a972-d6ca01ef82d7)


**TIMING DIGRAMS FOR SISO Shift Register**


![siso_waveform](https://github.com/user-attachments/assets/1e5bfd73-7745-4265-bdde-2a49b816d92a)


**RESULTS**

The Serial-In Serial-Out Shift Register has been successfully implemented and simulated in Quartus Prime using Verilog. The functionality of the register has been verified by applying a test input sequence and observing the output through simulation. The behavior of the register matches the expected results based on the truth table, confirming its correct operation.


