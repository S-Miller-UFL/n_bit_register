This is just a register where you can specify its width.

it contains 4 inputs:

1. in_input,
2. in_enable,
3. in_clk,
4. in_nres,

it contains 1 output:
1. out_output

when in_clk is on a rising edge, if in_enable is logical high (1), then the register
captures the value at in_input and is also outputted.

if in_nres is logical low (0), the register is set to 0. it is an asynchronous reset.
