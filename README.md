# OS-Practicals

Operating Systems Practicals

This repository contains a collection of Operating Systems laboratory programs implemented in C/C++. The experiments cover core OS concepts such as system calls, process creation, synchronization, CPU scheduling, memory allocation, and deadlock avoidance.


List of Programs

01_system_calls.c
Demonstrates basic file operations using system calls (open, read, write, close).

02_fork_process_creation.c
Creates parent and child processes using fork().

03_orphan_zombie.c
Shows orphan and zombie process behavior.

04_exec_system_call.c
Demonstrates program replacement using the exec family of system calls.

05_process_synchronization.c
Process synchronization using semaphores or producer–consumer logic.

06_cpu_scheduling.cpp
Implements CPU scheduling algorithms such as FCFS, SJF, Priority, or Round Robin.

07_first_fit.c
Memory allocation using the First Fit strategy.

07_best_fit.c
Memory allocation using the Best Fit strategy.

07_worst_fit.c
Memory allocation using the Worst Fit strategy.

08_bankers_algorithm.c
Implements the Banker's Algorithm for deadlock avoidance.

Topics Covered

    1.System calls

    2.Process creation

    3.Orphan and zombie processes

    4.Exec system call

    5.Semaphores and synchronization

    6.CPU scheduling algorithms

    7.Memory allocation methods

    8.Deadlock avoidance

How to Run

  Compile C programs:

    gcc filename.c -o output
    ./output


  Compile C++ programs:

    g++ filename.cpp -o output
    ./output

Note

This repository is designed for OS lab submissions, viva preparation, and academic learning.
