# OS-LAB-ASSIGNMENT

Student and Submission Details

Name: Shami Ahmad
Roll Number: 2301010030
Course Code & Name: ENCS351 Operating System Lab
Program: B.Tech CSE (Sem-05)
Course Teacher: Mrs. Suman
Assignments Covered: Lab Assignment Sheet-1 & Sheet-2


Lab Assignments Overview

Lab Assignment Sheet-1: Process Creation and Management

Technologies Used: Python (os, subprocess) and Java (ProcessBuilder)

Tasks:

1. Process Creation: Creates N child processes using Python's os.fork() or Java's ProcessBuilder. Parent waits for all children.
2. Command Execution: Child processes execute system commands (Linux: ls, date; Windows: date /t, whoami) using Python's os.execvp() or Java's ProcessBuilder.
3. Zombie & Orphan Processes: Simulates Zombie (parent skips waiting) and Orphan (parent exits first) processes.
4. Inspecting /proc: Reads and prints process details (name, state, memory usage, executable path) from /proc filesystem in Python; conceptual approach in Java.
5. Prioritization: Creates CPU-intensive tasks and assigns different priority levels to observe scheduler impact.

Lab Assignment Sheet-2: System Startup and Process Simulation

Technologies Used: Python (multiprocessing, logging) and Java (Thread, Logger)

Objective: Simulates system boot-up, concurrent process creation, graceful shutdown, and lifecycle logging to process_log.txt.
