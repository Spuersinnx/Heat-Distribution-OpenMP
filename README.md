# Heat-Distribution-OpenMP

##About This Program
The following program calculates heat dissipation in a room space using the static heat equation. This program is parallelizable and uses OpenMP for that purpose.
This program is similar to the Heat-Distribution code found in another repo

##How It Works
1. The program will prompt the user for the size of the room N x N (matrix)
2. The program will then prompt the user for the number of iterations to be taken into account, as the program calculates heat dissipation within the room
3. The program will then calculate the temperatures
4. The program will then output the initial and then the final temperatures within the room
5. The program contains built-in error checking to determine if both calculations are identical for parallel and sequential calculations
6. The program will output execution time for both sequential execution and parallel execution
7. Speedup factor is displayed and outputted as well
