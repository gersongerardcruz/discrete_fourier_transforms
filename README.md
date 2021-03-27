# Discrete Fourier Transform
Signals, Spectra, and Signal Processing Project. This algorithm calculates the discrete fourier transform for a signal file based on a chosen frequency and displays it either in a Real-Imaginary form or a Magnitude-Phase form.

A Fourier Transform (FT) is a progress that decomposes a signal into its corresponding individual frequences. For instance, whenever we pluck a guitar, each string produces sound based on different frequencies. 
Through the fourier transform, these frequencies can be approximated. So for instance, an 800 Hz frequency can be a mix of 100 Hz, 200 Hz, and 400 Hz individual signals and the FT decomposes that signal to determine its constituent frequencies.

For this project, the Fourier Transform is to be taken a discrete points in time hence the term Discrete Fourier Transform (DFT). 

## Project Specifications

The user of the program will be asked the following:
1. Sampling rate of the signal
2. Starting Frequency in Hertz
3. Ending Frequency in Hertz
4. Number of Steps to take going from start to end
5. Form of the DFT (Magnitude-Phase, Real-Imaginary, or Both)

For instance, let us take a signal to be sampled at a rate of 200 Hz with a starting frequency of 0 and an ending frequency of 9 with 9 steps to be taken. 

This means that we must take 9 steps in going from 0 to 9 giving us a step size of (9-0)/9 = 1. This means that for every iteration, we increase our step size by 1 and this will ensure that it takes nine steps to get to 9 (excluding the first step).

Hence in this example, we will have ten different sampled outputs:
* A 0 Hz signal sampled at 200 Hertz
* A 1 Hz signal sampled at 200 Hertz
* A 2 Hz signal sampled at 200 Hertz
* .........
* A 9 Hz signal sampled at 200 Hertz. 

Giving us a total of 10 outputs. 

## Inputs 
There are five different inputs in this project:
1. testsignal1.txt
2. testsignal2.txt
3. testsignal3.txt
4. testsignal4.txt
5. testsignal5.txt

## Outputs
Those five inputs result into a set of two outputs per input as follows:
1. r1.txt and m1.txt (outputs of testsignal1.txt)
2. r2.txt and m2.txt (outputs of testsignal2.txt)
3. r3.txt and m3.txt (outputs of testsignal3.txt)
4. r4.txt and m4.txt (outputs of testsignal4.txt)
5. r5.txt and m5.txt (outputs of testsignal5.txt)

## Reference User Inputs
These are the inputs used in getting the sample outputs from the sample inputs
1. testsignal1: Sampling Rate (SR): 200, Start (S): 0, End (E): 9, Steps (St): 9
2. testsignal2: SR:100, S:1, E:100, St:99
3. testsignal3: SR:500, S:80, E:180, St:10
4. testsignal4: SR:500, S:80, E:180, St:10
5. testsignal5: SR:100, S:1.75, E:15.45, St:20

Each function used has been given documented within the .cpp file. Enjoy!



