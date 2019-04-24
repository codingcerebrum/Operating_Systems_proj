# Operating_Systems_proj
program for multilevel queue scheduling algorithm

Ques:
Write a program for multilevel queue scheduling algorithm. There must be three queues generated. There must be specific range of priority associated with every queue. Now prompt the user to enter number of processes along with their priority and burst time. Each process must occupy the respective queue with specific priority range according to its priority. Apply Round robin algorithm with quantum time 4 on queue with highest priority range. Apply priority scheduling algorithm on the queue with medium range of priority and First come first serve algorithm on the queue with lowest range of priority. Each and every queue should get a quantum time of 10 seconds. Cpu will keep on shifting between queues after every 10 seconds
i.e. to apply round robin algorithm OF 10 seconds on over all structure.
Calculate Waiting time and turnaround time for every process. The input for number of processes should be given by the user.

# Multilevel Queue Scheduling
Multi Level Queue Scheduling Algorithm in Operating System


**Quantum Time: 4s**

**Queue Shift Time: 10s**

## Algorithms Used

|Queue|Priority Range|Algorithm|
|---------|--------------|---------|
|1|1-3|First Come First Serve|
|2|4-6|Priority Scheduling|
|3|>6|Round Robin|
