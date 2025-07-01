# Operating-System-Project
🖥️ Dynamic Multi-Functional Operating System Simulation
This project is a comprehensive simulation of core operating system functionalities, built using modern C++ standards. It models process management, resource allocation, and system communication in a streamlined mini-OS environment.
🚀 Key Features
- Hybrid CPU Scheduler: Switches dynamically between Priority Scheduling and Round Robin based on system load to optimize fairness and responsiveness.
- Deadlock Handling: Detects deadlocks using a Wait-For Graph, and avoids them proactively with Banker's Algorithm.
- Inter-Process Communication (IPC): Simulates secure message passing via C++ queues, incorporating mutual exclusion to prevent race conditions.
- Memory Management: Implements paging with a FIFO page replacement strategy to manage memory under constrained capacity.
- Performance Metrics: Calculates waiting time, turnaround time, and throughput to evaluate system behavior.
📊 Modules Breakdown
| Module | Functionality | 
| Hybrid Scheduler | Prioritizes tasks based on system state and time slices | 
| Deadlock Detection | Identifies cyclic waits among processes | 
| Banker's Algorithm | Verifies safe resource allocation before granting requests | 
| IPC via Queue | Enables message-based communication between simulated processes | 
| Paging Simulation | Mimics memory frame replacement using FIFO | 


🧠 Project Goal
To provide a hands-on simulation of OS behaviors that reinforces theoretical concepts such as scheduling algorithms, deadlock detection, and memory management—ideal for students exploring system-level programming.

Team Members:
             Muhammad Sannan Azmat
             Shaheer Ahmed
