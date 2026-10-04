# RR_CPU_Scheduler:Round Robin CPU Scheduling Simulator

Round Robin (RR) is one of the simplest and most widely used CPU scheduling algorithms, especially in time‑sharing and interactive systems. It ensures that all processes receive equal CPU time in a cyclic manner. 

Key Characteristics
Preemptive: A timer interrupt stops a process when its quantum expires.
Fair: Every process gets an equal time slice.
FIFO Ready Queue: Processes are scheduled in arrival order.
Starvation-free: No process is indefinitely delayed.
Ideal for time‑sharing systems: Ensures responsiveness.
======================Collect this information from  Wikipedia

How Round Robin Works
All ready processes enter a FIFO queue.
The scheduler assigns the CPU to the process at the front for one time quantum.
If the process:
Finishes early: It leaves the system.
Does not finish: It is preempted and moved to the back of the queue.
The next process in the queue receives the CPU.
This cycle continues until all processes complete.
======================================================
Important Terms
Burst Time (BT): CPU time required by a process.
Arrival Time (AT): When a process enters the ready queue.
Completion Time (CT): When a process finishes.
Turnaround Time (TAT): CT − AT
Waiting Time (WT): TAT − BT

----------------------------------
Applications:
Operating systems: CPU scheduling in Linux, Windows, and time‑sharing systems.
Network scheduling: Fair packet distribution.
Sports tournaments: Ensures each team plays all others.
