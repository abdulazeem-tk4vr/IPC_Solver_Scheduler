# IPC Solver Scheduler

## Overview

This project focuses on efficiently computing the sum of "N" integers using multithreading, shared memory, and pthreads in the C programming language. Additionally, it includes implementations of two process scheduling algorithms: Round Robin and Pre-emptive Priority Scheduling. The project also analyzes the efficiency of these algorithms by comparing the turnaround time and waiting time of the processes.

## Features

- **Multithreaded Integer Sum Calculation:** The program leverages multithreading to efficiently compute the sum of "N" integers. By distributing the workload across multiple threads, it improves the overall performance of the calculation.
- **Shared Memory and Pthreads:** The results of the integer sum computation are transferred to a shared memory location, ensuring seamless communication and data sharing among threads. Pthreads (POSIX threads) are used for thread management and synchronization.
- **Round Robin Scheduling:** The project includes an implementation of the Round Robin scheduling algorithm. It schedules and executes processes in a circular order, allowing each process to run for a fixed time slice before moving to the next process.
- **Pre-emptive Priority Scheduling:** Another scheduling algorithm implemented in this project is Pre-emptive Priority Scheduling. It assigns priorities to each process and allows higher-priority processes to preempt lower-priority processes, ensuring efficient utilization of system resources.
- **Efficiency Analysis:** The project analyzes the efficiency of the implemented process scheduling algorithms by comparing the turnaround time and waiting time of the processes. These metrics provide insights into the effectiveness of the scheduling algorithms in terms of process execution and resource allocation.

## Installation

To compile and run the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/IPC_Solver_Scheduler.git
    ```
2. Navigate to the project directory:
    ```bash
    cd IPC_Solver_Scheduler
    ```
3. Compile the code:
    ```bash
    gcc -o ipc_solver_scheduler ipc_solver_scheduler.c -lpthread
    ```

## Usage

To run the program, use the following command:
```bash
./ipc_solver_scheduler
