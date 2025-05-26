# CPU-Scheduling-Simulator

A Software Engineering project that simulates various CPU scheduling algorithms — an essential concept in Operating Systems. Users can choose from different scheduling techniques such as FCFS, SJF, Priority, and more, input custom data, and visualize how each algorithm processes tasks along with calculating average Waiting Time, Turnaround Time, Burst Time, etc.




## Overview

This repository contains a Java-based simulator for CPU scheduling algorithms. CPU scheduling is a fundamental aspect of operating systems, where the CPU decides the order in which processes are executed. This simulator allows users to visualize and analyze different scheduling algorithms such as First-Come, First-Served (FCFS), Shortest Job Next (SJN), Round Robin (RR), and more. 

## Problem Statement
Different CPU scheduling algorithms have unique properties, and choosing the right one for a particular situation depends on various criteria used to compare their performance. These criteria are referred to as CPU scheduling criteria. For instance, in some cases, maximizing response time may be prioritized over throughput, while in others, minimizing average waiting time might be more important, even if it means sacrificing response time. Sometimes, a balance between multiple criteria is required. The challenge lies in determining which scheduling algorithm is best suited for a given situation. This project aims to address that challenge. The CPU Scheduling Simulator provides an environment where users can experimentally test and compare the performance of different scheduling algorithms through simulation. At the start, users can select any CPU scheduling algorithm they wish to evaluate. They then input the number of processes and relevant details for each process, such as CPU burst time, process ID, priority (if a priority scheduling policy is chosen), arrival time, and more. The simulator visually demonstrates the execution of processes, showing the remaining wait and burst times, as well as the processes waiting in the ready queue. One of the key features of this project is its Graphical User Interface, making it user-friendly and easy to operate.

## Features

- **Multiple Scheduling Algorithms**: Simulates various CPU scheduling algorithms such as FCFS, SJN, RR, and more.
- **User Interface**: Provides a graphical user interface (GUI) for easy interaction and visualization.
- **Detailed Output**: Displays the order of process execution, waiting time, turnaround time, and other performance metrics.
- **Custom Data Structures**: Tailored data structures for managing processes and scheduling tasks.


## Files and Directories
- `sources/`: Directory for additional source files.
- `src/main/`: Main source code directory where the implementation of CPU scheduling algorithms resides.
- `target/`: Directory for compiled classes and build artifacts.
- `pom.xml`: Maven project file for managing dependencies and build configurations.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) 8 or higher.
- Apache Maven (optional, for building the project).
- A Java IDE (e.g., IntelliJ IDEA, Eclipse) or any text editor with Java support.



### Usage

1. **Compile the project**: Ensure all `.java` files are compiled. Most IDEs handle this automatically.
2. **Run the Simulator**:
   - Execute the main class in `src/main/` to launch the simulator's user interface.
   - Choose the desired CPU scheduling algorithm and input the process data.
3. **View Results**:
   - The simulator will display the sequence of process execution and calculate important metrics like waiting time, turnaround time, and CPU utilization.

▶️ Usage
1. Run the application.
2. Choose the scheduling algorithm you want to simulate.
3. Input:
   a. Number of processes
   b. Arrival time
   c. Burst time
   d. Priority (if applicable)
4. Click on Start.
5. View the execution order and computed results.

### Example

- **Simulating Round Robin Scheduling**:
  1. Open the simulator.
  2. Select "Round Robin" from the list of algorithms.
  3. Input the number of process.
  4. Click "Start" to see the order of execution and performance metrics.

**Team Members**
Piyush Kumar 
Kartik Kapri
Mayank Singh
Kumkum Pandey

