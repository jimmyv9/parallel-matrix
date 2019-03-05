# parallel-matrix
Implementation of parallelized matrix multiplication in C using OpenMP. It calculates the average runtime of multiplying NxN matrices in any P amount of processors available. Code was written for a Parallel Systems class.

# How to compile
gcc -fopenmp -lm -O3 -o executableName lab2.c

# How to run it
./executableName sizeofMatrix numberofProcessors
