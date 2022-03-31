## possible sources to look through to create project


1. [Finite Impulse Response Filter](https://www.fpga4student.com/2017/01/a-low-pass-fir-filter-in-vhdl.html)


2. [Prof.K Lu Pong Lab GitHub](https://github.com/kevinwlu/dsd/tree/master/Nexys-A7/Lab-6)

The adc_if module converts the serial data from both channels of the ADC into 12-bit parallel format.

When the CS line of the ADC is taken low, it begins a conversion and serially outputs a 16-bit quantity on the next 16 falling edges of the ADC serial clock.
The data consists of 4 leading zeros followed by the 12-bit converted value.
These 16 bits are loaded into a 12-bit shift register from the least significant end.
The top 4 zeros fall off the most significant end of the shift register leaving the 12-bit data in place after 16 clock cycles.
When CS goes high, this data is synchronously loaded into the two 12-bit parallel outputs of the module.
