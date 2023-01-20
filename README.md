# Operating-Systems-course-project (Paging Simulator)

## Here is the report of the project , and below is the screens and description:

![image](https://user-images.githubusercontent.com/110572038/213672183-123f66ea-fa50-45f8-b024-09ba3c02f2b6.png)

![image](https://user-images.githubusercontent.com/110572038/213672343-29aff84b-a895-4f97-b886-dcc510868ded.png)

![image](https://user-images.githubusercontent.com/110572038/213672386-75ef1282-aa62-4760-a3e2-36e78a63158e.png)

![image](https://user-images.githubusercontent.com/110572038/213672458-82768bb3-9c99-45ff-845a-3523094ea414.png)

![image](https://user-images.githubusercontent.com/110572038/213672523-f3f58bdc-a035-4166-8534-4c045b38a589.png)


This project is a paging simulator that implements various page replacement algorithms such as Second Chance, Clock and FIFO, as well as a Round Robin CPU scheduling algorithm.

## Getting Started
These instructions will guide you through the process of running the simulator on your local machine.

## Prerequisites
* A C++ compiler (e.g. GCC)
* The input data files, which can be generated using a random number generator.
## Running the Simulator
* Compile the source code using your C++ compiler.
### Copy code
$ g++ -o simulator main.cpp
* Run the compiled executable file and provide the input data files as arguments.
### Copy code
$ ./simulator input1.txt input2.txt ...

## Page Replacement Algorithms
The simulator implements the following page replacement algorithms:

- FIFO: The basic algorithm which replaces the oldest page in memory.
- Second Chance: An improvement of the FIFO algorithm, where a page is given a "second chance" if its reference bit is set.
- Clock: Implemented as a circular queue, where a pointer advances until it finds a page with a false reference bit to replace.
## CPU Scheduling Algorithm
The simulator uses the Round Robin scheduling algorithm, which is a time-sharing algorithm that pre-empts a process after a certain time quantum, and places it at the end of the ready queue to be executed again.

## Virtual Memory Allocation
The simulator simulates the process of virtual memory allocation, which is the separation of user logical memory from physical memory. The benefits of virtual memory include efficient use of physical memory and the ability to share address spaces among processes.

## Input Data Files
The input data files are generated using a random number generator, and contain information such as the number of memory accesses for a job, which is proportional to its length, and the rate of page generation. The trace files are also generated using the random number generator, which produces random page numbers for each job.

## User Interface
The simulator has a simple and friendly user interface, which displays the simulation results in a clear and organized manner.

## Bonus
The scheduling part has been implemented as a bonus.

## Conclusion
This project provides a comprehensive simulation of the paging process, including the implementation of various page replacement algorithms, and a CPU scheduling algorithm, as well as the simulation of virtual memory allocation. The user interface is simple and easy to use, providing a clear and organized display of the simulation results. The project is a great tool for understanding the workings of virtual memory and page replacement algorithms.
