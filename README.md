THIS IS THE CODE EXPLANATION VIDEO : https://drive.google.com/file/d/1_TZF0a-aw5BUmd3t1aql6UVssjx3kBQc/view?usp=sharing
THIS IS THE PRESENTATION : https://drive.google.com/file/d/19_kzF86byy07qht4dDIXafipV5WYbT60/view?usp=sharing

Overview

WAS (Weighted Average Scheduling) is a CPU scheduling algorithm where each process is assigned a weight, and the CPU chooses the next process based on the highest weighted priority.

This scheduling approach ensures that important or time-critical tasks receive more CPU time than others.

🎯 Objectives of WAS
Give preference to high-priority processes
Reduce waiting time for critical tasks
Efficient CPU utilization
Good for systems where tasks have different importance levels

⚙️ How WAS Works
Each process has:
Burst Time (BT)
Priority Weight (W)
Arrival Time (optional)

The CPU calculates:
Weighted Score = Weight / Burst Time

The highest Weighted Score process gets scheduled first.

📌 Key Features
✔ Fairer than normal priority scheduling
✔ Prevents long processes from starving
✔ Handles different importance levels efficiently
✔ Works well in real-time systems and multi-tasking environments

Process	   Burst Time   	Weight	 Weighted Score
P1	           10	          3	       0.30
P2             	5         	5	       1.00
P3	            8          	2	       0.25

GANTT CHART 
|   P2   |        P1        |      P3     |
0        5                 15            23



