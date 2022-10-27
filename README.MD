# Requirements

1. Answer Part 1 questions here in this file
2. Answer Part 2 questions in the source files
3. Submit this file and the two source files on to the Gradescope

# Part1: Short Answer Questions

### 1. How to add custom search path for header files and libraries file for gcc compiling (10 Points)

**Answer**: 

Header File: gcc -I\<Header File Directory Path\>

Library File: gcc -L\<Library File Directory Path\>

### 2. How to create a int array of length 100 using heap memory (10 Points)

**Answer**: int *array = malloc(100 * sizeof(int));

### 3. Give each an example of dangling pointer and wild pointer (10 Points)

**Answer**: 

Dangling Pointer: A pointer pointing to a memory location that has been deleted | Ex: free(ptr);

Wild Pointer: A pointer that has not been initialized to anything | Ex: int *ptr[3];

### 4. What are the four different segments of a C program runtime memory layout and what are they used of? (10 Points)

**Answer**: 

Text: Machine Instructions (Operators)

Data: Constants and Static Variables (Constant Literals)

Heap: Dynamically Allocated Space (Malloc’d Data)

Stack: Runtime Call Stack (Local Variables, Return Address, and Returned Values)

# Part2: Coding  (60 Points)

Read the question in the README file and then complete the [solution] function
in the Source Code file for submission.

Coding 1: [README](coding_1.MD) and [Source Code](coding_1.c)

Coding 2: [README](coding_2.MD) and [Source Code](coding_2.c)
