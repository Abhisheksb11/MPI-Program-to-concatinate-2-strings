# MPI-Program-to-concatinate-2-strings
MPI Program to read two strings S1 and S2 of same length in the root process. Using N process including the root (string length is evenly divisible by N), produce the concatenated resultant string as shown below. Display the resultant string in the root process.


Steps to execute:-
1. mpicc code.c
2. mpiexec -n 2 ./a.out code.c
Enter 2 strings :- string length
THE RESULTANT STRING WILL BE : slternigntgh
