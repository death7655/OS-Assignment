# SJF CPU Scheduling Implementation

This repository contains a C implementation of the Shortest Job First (SJF) non-preemptive scheduling algorithm. The program calculates Completion Time, Turnaround Time, and Waiting Time for a given set of processes based on their arrival and burst times.

---

## Features
* SJF Logic: Always selects the available process with the shortest burst time.
* Idle Time Management: Correctly handles gaps where no processes are ready.
* Formatted Output: Displays individual process metrics and system-wide averages.
* Interactive Input: Prompts for process names, arrival times, and burst times.

---

## Execution Result
Below is a screenshot of the program execution and output:

<img width="487" height="452" alt="image" src="https://github.com/user-attachments/assets/6fc3587b-c465-46d8-afdd-e96fc5a44c49" />


---

## Sample Data Test
The program was tested with the following parameters:

| Process | Arrival Time | Burst Time | Waiting Time | Turnaround Time |
| :--- | :---: | :---: | :---: | :---: |
| P1 | 0 | 6 | 0 | 6 |
| P2 | 1 | 8 | 15 | 23 |
| P3 | 2 | 7 | 7 | 14 |
| P4 | 3 | 3 | 3 | 6 |

**Performance Metrics:**
* Average Waiting Time: 6.25
* Average Turnaround Time: 12.25
---
Author
Robinson George Arysseril VML24AD095

OS Assignment 1

March 17th, 2026
Would you like me to help you format the final source code one last time to ensure it
