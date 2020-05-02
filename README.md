# fixed-Microchip-CE018-code-example
This is a fixed Microchip's "CE018 - Using the Fast Fourier Transform (FFT) for Frequency Detection" code example that works with modern XC16 compilers and MPLAB X IDE.

For now it works as expected ONLY with twiddle factors in program memory.

It compiles and runs ok but with one (stupid) warning at compile time. Output results are as they should be:

peakFrequency = 1014

peakFrequencyBin = 26

having FFT_BLOCK_LENGTH	= 256, LOG2_BLOCK_LENGTH = 8

## How to compile and run

clone this project folder, open it with MPLAB X, if it does not compile already, right-click on the project name -> properties -> Conf:[default] -> XC16-> xc16-ld -> in "Additional options:" put the string: "--library "dsp""