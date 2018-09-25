# Image Pattern Matching

Finds patterns in an "image" (a grid of ascii characters) and reports the number of matches each pattern has on the images and where they occur. The result is printed in the console and saved in output.txt files. This program is merely an abstraction and simplification of the real life problem.

Version 1 - Child processes are clones of their parents:

Create child processes equal to the number of image files 
Each child will check to see if the pattern files match with their image 
Results are written to files named after the PID of each process 

Version 2 - Child processes report their results via a pipe

Child processes send their report via an unnamed pipe
