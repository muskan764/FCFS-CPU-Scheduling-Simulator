# 🖥️ FCFS CPU Scheduling Simulator

This project simulates **First-Come, First-Served (FCFS) CPU scheduling**, a basic but fundamental scheduling algorithm in operating systems. 

It calculates **waiting time** and **turnaround time** for each process based on their arrival and burst times, displaying the execution order and average times.

------------------------------------------------------------------------------------------------------------

## ⚙️ How It Works

1. Define a list of processes with:
   - **Process ID**  
   - **Arrival Time**  
   - **Burst Time**  

2. The program schedules processes **in the order they arrive** (first-come, first-served).  

3. Calculates:
   - **Waiting Time (WT)** for each process  
   - **Turnaround Time (TAT)** for each process  

4. Displays the process table and **average waiting and turnaround times**.

------------------------------------------------------------------------------------------------------------

## 🚀 Usage

1. Run the Python script:
```bash
python fcfs_scheduling.py
Example Input (in script):

processes = [1, 2, 3, 4]
arrival_time = [0, 1, 2, 3]
burst_time = [5, 3, 8, 6]
Sample Output:

Process  Arrival Time  Burst Time  Waiting Time  Turnaround Time
1        0             5           0             5
2        1             3           4             7
3        2             8           6             14
4        3             6           15            21
```

Average Waiting Time: 6.25
Average Turnaround Time: 11.75

------------------------------------------------------------------------------------------------------------

## ✨ Features

✅ Calculates waiting time and turnaround time for each process

✅ Implements FCFS CPU scheduling

✅ Computes average waiting and turnaround times

✅ Demonstrates how arrival order impacts scheduling efficiency
