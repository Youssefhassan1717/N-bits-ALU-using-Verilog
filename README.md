# N-bits-ALU-using-Verilog
This is a Verilog code for an Arithmetic Logic Unit (ALU) module that performs arithmetic and logical operations on two input operands (Op1 and Op2). The ALU module has four outputs: Result, zFlag, oFlag, and cFlag, which represent the result of the operation, the zero flag, the overflow flag, and the carry flag, respectively.

The ALU module includes two submodules: adder and subtractor, which are used to perform the addition and subtraction operations, respectively. The ALU module also includes a case statement that selects the appropriate operation based on the value of the OpCode input.

The testbench module (test) instantiates the ALU module and applies test inputs to it. The simulation is monitored using $monitor statements that display the ALU's output signals. The test inputs used in this code test the ALU's ability to perform addition with a carry input.
