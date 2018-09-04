README
======

Assignment: 
	The objective of this assignment is a simple refresher on memory allocations and deallocations using C.

Driver The driver module is responsible for:
1. Invoking functions in the MemoryManager.
2. Setting upper bounds for memory consumption.

MemoryManager The memory management module is responsible for:
It is responsible for:
	1. Allocating and de-allocating data structures
	2. Populating elements in the data structure
	3. Computing the median element within the data structure
	4. Checking to see if the median number is divisible by 13
	5. Maintaining a running count of median elements that were divisible by 13.
Your functionality will be go inside the function get_running_count() in the MemoryManager.c file.



This package includes the following files.

|-- Driver.c [This is the driver program which will be used to invoke the MemoryManager.]
|-- MemoryManager.c [MemoryManager is implemented here.]
|-- MemoryManager.h [Header file declaring the function exposed from MemoryManager]
|-- README.txt [This file]

To compile:
    gcc *.c

To run:
    ./a.out <seed>

For example;
    ./a.out 1234

