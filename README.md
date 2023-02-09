# Garbage-collector
Implement four of the known algorithms used in Garbage Collectors.
## Description
In this Project, We will implement four of the known algorithms used in Garbage Collectors:
 1- Mark & Sweep GC.
 2- Mark & Compact GC.
 3- Copy GC.
 
## How to run:
Program is executed by jar file which takes four arguments:
 * The first three arguments are the absolute paths of heap.csv, roots.txt, and pointers.csv.
 * The last argument is the absolute path in which the new-heap.csv file will be saved to.

### The input files:
 * File heap.csv : it represents the information about a single allocated object. This object may be used or not used.
    * object-identifier: a unique 6 digits identifier of the allocated objects.
    * memory-start: the index of the first byte in heap memory representing this object
    * memory-end: the index of the last byte in heap memory representing this object

