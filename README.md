# Operating-System-practical




Q1. Implement SRTF. Compute waiting time, turnaround time.

SRTF Scheduling:
According to the SRTF scheduling, among all the processes CPU is assigned to process having the smallest burst time.

The main benefit of SRTF scheduling is that it gives minimum waiting time.

It cannot be implemented practically since it has many drawbacks:

-burst time of a process cannot be known in advance
-priorities cannot be set for processes.
-processes having larger burst times have poor response times.


![q1 output](https://user-images.githubusercontent.com/77840734/145349282-0be51815-4893-4c3e-a13b-b22dedda0a57.png)


Q2. Write a program to demonstrate fork where parent and child run same codes and child 
process should run first.

In this example, child process runs and terminates before parent process

![q2 output](https://user-images.githubusercontent.com/77840734/145349446-fba916a6-cec6-4448-9937-4bb01cae9b50.png)
