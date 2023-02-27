# CS50
A program that recovers JPEGs from a forensic image. 
Program accept exactly one command-line argument, the name of a forensic image from which to recover JPEGs.
If program is not executed with exactly one command-line argument, it remind the user of correct usage.
If the forensic image cannot be opened for reading, program inform the user as much, and main should return 1.
The files generate should each be named ###.jpg, where ### is a three-digit decimal number, starting with 000 for the first image and counting up.
