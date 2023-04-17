# lab3_paralela

## ejer 1
gcc -g -Wall -o vector_add vector_add.c -fopenmp
./vector_add

## ejer 1 mpi Windows
mpicc mpi_vector_add.c -o mpi_vector_add
mpiexec -n 4 ./mpi_vector_add