# Roundrobin

<ins>_**Experiment name:**_</ins> Implementation of the Round Robin scheduling algorithm

<ins>_**Description:**_</ins>
The code starts by including the header files for input-output operations and the standard library. It employs the bits/stdc++.h header file for convenience and declares a namespace to avoid prefixing standard library functions. The code then declares several arrays and variables to store process-related information, including the remaining burst time (st[]), burst time (bt[]), waiting time (wt[]), and turnaround time (tat[]), as well as other counters and averages.Next, the user is prompted to enter the number of processes (n), burst times (bt[]), and time quantum (tq). The remaining burst time (st[]) is set to the burst time (bt[]) for each process.The code's core uses a while loop to implement the Round Robin scheduling algorithm.
This loop checks each process's remaining burst time. If it is zero, the count variable is updated to reflect completed processes. If it exceeds the time quantum, it is subtracted from the remaining time. If it is less than or equal to the time quantum, the burst time is reset to zero. In addition, the system queue time (sq) and turnaround time (tat[]) are updated during this process.

<ins>_**Input**_</ins>
The input required for the provided Round Robin scheduling code is as follows:

-Total Processes (n): The user is prompted to enter the total number of processes that should be scheduled. 
-Arrival time (at[]): The time at which the process enters the ready queue. 
-Burst time (bt[]): The time it takes for the process to complete its execution. 
-Time Quantum:The user specifies the time quantum, which is the maximum time each process can run in a single turn during Round Robin scheduling.

<ins>_**Output**_</ins>
The output of the provided Round Robin scheduling code will display the turnaround time and waiting time for each process  and the final result:
!
