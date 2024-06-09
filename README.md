Objective:
The primary objective of this project is to compare the performance of
sorting algorithms when implemented as processes versus threads.
Specifically, we aim to achieve the following:

1. Implement five sorting algorithms (Bubble Sort, Selection Sort,
Insertion Sort, Merge Sort, and Quick Sort) as processes and
threads.

2. Measure and analyze the execution time of each sorting algorithm
when implemented as processes and threads.

3. Compare the execution time and efficiency of process-based versus
thread-based implementations for each sorting algorithm.
4. Present the results through graphical representations for better
visualization and understanding.

Project Description:
In modern computing, parallelism plays a crucial role in enhancing the
performance of various algorithms and tasks. Processes and threads are
two fundamental units of parallel execution in operating systems.
Processes represent independent, isolated units of execution, each with its
own memory space, while threads are lighter-weight units that share the
same memory space within a process.
In this project, we implemented five well-known sorting algorithms: Bubble
Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort. Each
algorithm was implemented both as processes and as threads using
POSIX threading (pthread library). We used large datasets consisting of
random numbers to test the performance of these algorithms. The datasets
were provided through files. Datasets included 1000, 10000, 10000,
100000, and 200000 random numbers generated between 1 to 100.
The implementation involved creating functions for each sorting algorithm,
as well as additional functions for thread creation (separate functions were
created for 2 threaded processes and 4 threaded processes). We carefully
designed the code to ensure that the sorting algorithms functioned correctly
in both process and thread environments.
After implementing the algorithms, we conducted experiments to measure
the execution time of each algorithm when implemented as processes and
threads. The execution time was measured using the clock() function from
the C++ standard library.

