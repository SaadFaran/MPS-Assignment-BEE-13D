This is the accumulator logic circuit designed by Muhammad Saad Faran Malik on Logisim. 
The accumulator is to be connected with the ALU (as shown in the main circuit of the microprocessor). 
The circuitry was then converted into the form of an IC to minimize the space occupied by it, and the final accumulator is also shown as an IC that is connected with the ALU in the main circuit of the 4-bit microprocessor.

 - Switch represents output from the ALU and the pin reporesents the output from the accumulator register.
 - I connected the output of the ALU (rep. by switch here) to one input of each MUX, and the output of the accumulator register to the other input of each MUX.
 - With the help of control signal, each MUX selects between the accumulator output and the ALU output, the selected output is then fed back into the data input of the accumulator to update its value.
 - I then connected the output of the accumulator (rep. by pin here) as one of the inputs to the ALU for subsequent operations. For example, if I wanted to perform an addition operation, I would connect the output of the accumulator to one input of the ALU and the other operand to the other input of the ALU. The ALU would then compute the sum and output the result, which could be stored back into the accumulator.

<img width="664" alt="accumulator circuit" src="https://user-images.githubusercontent.com/127740712/230774740-89e42ad4-9116-43bb-b8b9-944abe8f3a1a.png">

 - The output of the accumulator register is connected to one input of each MUX, as well as to the input of the ALU. This way, the output of the accumulator can be either passed through the mux to the output, or it can be combined with the output of the ALU to perform arithmetic or logic operations.

 - Here is that representation:
![image](https://user-images.githubusercontent.com/127740712/230777915-4f0af204-1cfa-4b92-94da-3542ae477bd0.png)


 - Here is how my accumalator ICs look like in the main circuit of 4-bit microprocessor. The diagram is just a portion of the entire main circuit so as to show my combinational circuit portion:
 - ![image](https://user-images.githubusercontent.com/127740712/230779717-71bf92ce-a78a-4302-b61f-cea8fe7ff735.png)
 - The wire from the left are coming from the main circuit as well as the ALU.
