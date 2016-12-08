# Recursive Fork

## Use

This program creates processes and their respective threads.
It handles the problem of synchronization

## Overview

This program creates 3 processes recursively (each process is created inside the other).  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The order of the processes is 1 2 3  
Each process creates 3 threads in a loop  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The order of the threads in each process is 1 2 3

## Output

This version of the program gives the following output:

Spawning process 1 pid 9496  
I am thread pid 9496.1  
I am thread pid 9496.2  
I am thread pid 9496.3  
Spawning process 2 pid 9500  
I am thread pid 9500.1  
I am thread pid 9500.2  
I am thread pid 9500.3  
Spawning process 3 pid 9504  
I am thread pid 9504.1  
I am thread pid 9504.2  
I am thread pid 9504.3  


