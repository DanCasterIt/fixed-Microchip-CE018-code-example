# fixed-Microchip-CE018-code-example
This is a fixed the Microchip's "CE018 - Using the Fast Fourier Transform (FFT) for Frequency Detection" code example that works with modern XC16 compilers and MPLAB X IDE.

It compiles and runs ok but with few warnings at compile time. Output results are as they should be:

peakFrequency = 1014

peakFrequencyBin = 26

## How to compile and run

clone this project folder, open it with MPLAB X, if it does not compile already, right-click on the project name -> properties -> Conf:[default] -> XC16-> xc16-ld -> in "Additional options:" put the string: "--library "dsp""