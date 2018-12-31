# PiezoBuzzer
Author: Jacob H. Adamczyk
Timestamp: 31 December 2018 02:32:37 EST
Python for Raspberry Pi Piezoelectric Buzzer

Version: Python 3.4.2
Raspberry Pi 3B+
Standard Piezoelectric Buzzer

Directly wire buzzer to GPIO pins and ground or use breadboard. 
Store the GPIO pin value (running 'pinout' without quotes in the RPi terminal may be of help).

The python program in this repository allows the buzzer to play at different frequencies from standard modulation.
Notes are selected from known frequencies.
The user may create their own tunes from the given notes (and rest), having different note lengths.
It is possible to extend this code to multiple buzzers through multiple GPIOs and have chords played.
