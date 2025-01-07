# Active-Noise-Cancellation

This project implements ANC using the Least Mean Squares (LMS) algorithm on an ESP32 microcontroller with two MAX4466 microphones, a MAX98357A DAC, and a speaker.

Active Noise Cancellation (ANC) is a technique used to reduce unwanted sound by introducing a secondary sound wave of equal amplitude but opposite phase, effectively canceling the noise through destructive interference.

The LMS algorithm adjusts filter coefficients to minimize the error signal between the desired and actual output, making it ideal for real-time applications like ANC.

Used Arduino IDE for programming and uploading the code to the ESP32.
