Hybrid Scheduling Algorithm: Shortest Job First (SJF) and Round Robin (RR)

This project implements a hybrid CPU scheduling algorithm combining Shortest Job First (SJF) and Round Robin (RR) to strike a balance between fairness and efficiency by considering the burst time of processes.

Features

Hybrid Scheduling: Combines the advantages of SJF and RR scheduling algorithms.

Fairness and Efficiency: Ensures fair process scheduling while optimizing for efficiency.

Dynamic Burst Time Consideration: Dynamically considers the burst time of processes for scheduling decisions.

Requirements
C++ Compiler (supporting C++11 or higher)

Standard Template Library (STL)

Installation

Clone the Repository

git clone https://github.com/Dilip-code584/Hybrid-Of-SJF-and-RR.git

Compile the Source Code

g++ filename.cpp


Run the Executable

./hybrid_scheduler

or just use

./a.out

Usage

Input Process Details

The program will prompt you to enter the number of processes, followed by the burst time and arrival time for each process.

Hybrid Scheduling Execution

The hybrid scheduler will execute the processes based on the combined SJF and RR algorithm, and display the order of execution along with relevant metrics such as waiting time, turnaround time, etc.

Explanation
Hybrid Scheduling Algorithm

This algorithm combines the SJF and RR scheduling techniques to achieve both fairness and efficiency:

Shortest Job First (SJF): Prioritizes processes with the shortest burst time, minimizing the average waiting time.

Round Robin (RR): Ensures fairness by assigning a fixed time quantum to each process, allowing all processes to execute in a cyclic order.

Burst Time Consideration

The scheduler dynamically considers the burst time of processes, ensuring that processes with shorter burst times are given higher priority while maintaining fairness through the RR approach.
