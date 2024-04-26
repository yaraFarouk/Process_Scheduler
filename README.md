# Process_Scheduler
# Process Scheduler Simulation

## Introduction
Process scheduling involves allocating resources to different processes efficiently. This project simulates the operation of a process scheduler in a multiprocessor system. It aims to keep the CPU busy as much as possible while minimizing response time and waiting time for processes.

### Process States
- **NEW**: A process that has been created but not arrived yet
- **RDY**: A process that has arrived and moved to the ready queue
- **RUN**: A process being served by the CPU
- **BLK**: A process that has requested an I/O operation
- **TRM**: A process that has finished execution

### The Type of Processors and Their Algorithms
- **First Come First Serve (FCFS)**: Assigns the CPU to the process that requests it first
- **Shortest Job First (SJF)**: Selects the waiting process with the smallest remaining CPU time
- **Round Robin (RR)**: Assigns a fixed time slice to each process

### Operations on Processes
- **Process Migration**: Processes may migrate between processors based on certain conditions.
- **Work Stealing**: Processes from the shortest queue steal processes from the longest queue.
- **Killing a Process**: A process should be killed if it receives a kill signal.
- **Process Forking**: A process can fork another process.
- **Orphan Process**: Child processes of a terminated parent are considered orphaned.
- **Processor Overhead**: A processor may go out of service due to overhead.

### Statistics
The project calculates various statistics related to process scheduling, including arrival time, response time, CPU time, termination time, turnaround duration, waiting time, processor load, and processor utilization.

## Program Interface
- **Interactive Mode**: Displays output upon pressing the "Enter" key.
- **Step-By-Step Mode**: Waits one second before displaying output.
- **Silent Mode**: Produces an output file.

## Input File
The input file specifies parameters such as the number of processors, time slice for RR, and process details.

## How to Use the Program
1. Create the input file.
2. Run the program.
3. Select the desired mode.
4. Check the output.

## Pictures
Include screenshots here.

![image](https://github.com/yaraFarouk/Process_Scheduler/assets/142579909/5fbf9bd9-ead7-4833-900d-6f8970389dd4)

![image](https://github.com/yaraFarouk/Process_Scheduler/assets/142579909/8e5f3f80-fa41-4da9-9814-59834446a879)


