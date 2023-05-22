
The Algorithm for deadlock detection is here bellow and the source code and the screenshot for input and output
 is found in the folder that included this file.

C program for deadlock detection - Operating Systems
ALGORITHM:

1. Mark each process that has a row in the Allocation matrix of all zeros.
2. Initialize a temporary vectorW to equal the Available vector.
3. Find an indexi such that processi is currently unmarked and thei th row ofQ
is less than or equal to W . That is,Q ik … Wk, for 1 … k … m . If no such row is
found, terminate the algorithm.
4. If such a row is found, mark processi and add the corresponding row of the
allocation matrix to W . That is, setWk = Wk + Aik, for 1 … k … m . Return
to step 3.


