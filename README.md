
# Experiment--09-Implementation-of Shift-registers-using-verilog-
### AIM: To implement PISO , PIPO,PISO  using verilog and validating their functionality using their functional tables
### HARDWARE REQUIRED:  – PC, Cyclone II , USB flasher
### SOFTWARE REQUIRED:   Quartus prime
### THEORY 
Shift registers are basically of 4 types. These are:

Serial In Serial Out shift register
Serial In parallel Out shift register
Parallel In Serial Out shift register
Parallel In parallel Out shift register
Serial-In Serial-Out Shift Register (SISO) –
The shift register, which allows serial input (one bit after the other through a single data line) and produces a serial output is known as Serial-In Serial-Out shift register. Since there is only one output, the data leaves the shift register one bit at a time in a serial pattern, thus the name Serial-In Serial-Out Shift Register.

The logic circuit given below shows a serial-in serial-out shift register. The circuit consists of four D flip-flops which are connected in a serial manner. All these flip-flops are synchronous with each other since the same clock signal is applied to each flip flop.

![image](https://user-images.githubusercontent.com/36288975/172337366-540cc45e-11fe-4cce-9503-560dc704bc7d.png)
FIGURE -01 
erial-In Parallel-Out shift Register (SIPO) –
The shift register, which allows serial input (one bit after the other through a single data line) and produces a parallel output is known as Serial-In Parallel-Out shift register.

The logic circuit given below shows a serial-in-parallel-out shift register. The circuit consists of four D flip-flops which are connected. The clear (CLR) signal is connected in addition to the clock signal to all the 4 flip flops in order to RESET them. The output of the first flip flop is connected to the input of the next flip flop and so on. All these flip-flops are synchronous with each other since the same clock signal is applied to each flip flop.

![image](https://user-images.githubusercontent.com/36288975/172337438-03416c7e-7c9d-4939-ba34-c355b9fc79c5.png)
FIGURE-02
The above circuit is an example of shift right register, taking the serial data input from the left side of the flip flop and producing a parallel output. They are used in communication lines where demultiplexing of a data line into several parallel lines is required because the main use of the SIPO register is to convert serial data into parallel data.
Parallel-In Serial-Out Shift Register (PISO) –
The shift register, which allows parallel input (data is given separately to each flip flop and in a simultaneous manner) and produces a serial output is known as Parallel-In Serial-Out shift register.

The logic circuit given below shows a parallel-in-serial-out shift register. The circuit consists of four D flip-flops which are connected. The clock input is directly connected to all the flip flops but the input data is connected individually to each flip flop through a multiplexer at the input of every flip flop. The output of the previous flip flop and parallel data input are connected to the input of the MUX and the output of MUX is connected to the next flip flop. All these flip-flops are synchronous with each other since the same clock signal is applied to each flip flop.
![image](https://user-images.githubusercontent.com/36288975/172337544-1632407f-1743-4b17-b480-00663d01e59f.png)
FIGURE-03
A Parallel in Serial out (PISO) shift register us used to convert parallel data to serial data.

Parallel-In Parallel-Out Shift Register (PIPO) –
The shift register, which allows parallel input (data is given separately to each flip flop and in a simultaneous manner) and also produces a parallel output is known as Parallel-In parallel-Out shift register.

The logic circuit given below shows a parallel-in-parallel-out shift register. The circuit consists of four D flip-flops which are connected. The clear (CLR) signal and clock signals are connected to all the 4 flip flops. In this type of register, there are no interconnections between the individual flip-flops since no serial shifting of the data is required. Data is given as input separately for each flip flop and in the same way, output also collected individually from each flip flop![image](https://user-images.githubusercontent.com/36288975/172337661-babb1f90-6286-4d14-8cbd-26a380ee085e.png)
FIGURE-04
A Parallel in Parallel out (PIPO) shift register is used as a temporary storage device and like SISO Shift register it acts as a delay element.

### Procedure
/* write all the steps invloved */



### PROGRAM 
/*
Program for  Implementation-of Shift-registers-using-verilog-
Developed by: DEVASANJAY N
RegisterNumber: 23013004 
*/

SERIAL INPUT PARALLEL OUTPUT:
![SIPO CODE](https://github.com/DEVASANJAY002/Exercise-09-Shift-registers-using-verilog-/assets/152069249/db2286c2-41ac-4d3f-a9c0-58b750e64335)


PARALLEL INPUT SERIAL OUTPUT:
![PISO CODE](https://github.com/DEVASANJAY002/Exercise-09-Shift-registers-using-verilog-/assets/152069249/3b52a210-8d24-4a2f-b0ad-be678fdb9dc2)
 


PARALLEL INPUT PARALLEL OUTPUT:
![PIPO CODE](https://github.com/DEVASANJAY002/Exercise-09-Shift-registers-using-verilog-/assets/152069249/4e27b7be-62ed-4929-a0f7-ddf902e9b0f3)

 ### RTL LOGIC REGISTERS:
 
SERIAL INPUT PARALLEL OUTPUT:
![SIPO RTL](https://github.com/DEVASANJAY002/Exercise-09-Shift-registers-using-verilog-/assets/152069249/778e9af6-45aa-4d31-915e-3a2b5cd9dedd)

### PARALLEL INPUT SERIAL OUTPUT:
![PISO RTL](https://github.com/DEVASANJAY002/Exercise-09-Shift-registers-using-verilog-/assets/152069249/2acbbaa7-ded5-40e4-9849-54eff4096666)

### PARALLEL INPUT PARALLEL OUTPUT:
![PIPO RTL](https://github.com/DEVASANJAY002/Exercise-09-Shift-registers-using-verilog-/assets/152069249/aa222755-86b2-4172-99f9-a21b687532fa)

### TIMING DIGRAMS FOR SHIFT REGISTERS
### SERIAL INPUT PARALLEL OUTPUT:
![SIPO TIME](https://github.com/DEVASANJAY002/Exercise-09-Shift-registers-using-verilog-/assets/152069249/cab51862-9d80-4518-8c3b-1d034c0b0571)

### PARALLEL INPUT SERIAL OUTPUT:
![PISO TIME](https://github.com/DEVASANJAY002/Exercise-09-Shift-registers-using-verilog-/assets/152069249/8afa5e39-6a85-4376-aa45-ad67203e4f8d)


### PARALLEL INPUT PARALLEL OUTPUT:
![PIPO TIME](https://github.com/DEVASANJAY002/Exercise-09-Shift-registers-using-verilog-/assets/152069249/1e35d1ee-78d0-4c5b-a062-90f7f6ea40cf)



### RESULTS 
Implementation of PISO , PIPO, PISO using verilog program is done and its functionality is validated
using their functional tables.
