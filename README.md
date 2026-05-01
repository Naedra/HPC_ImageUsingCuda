*CUDA Image Processing*

Technology Used: C++, CUDA, GoogleColab, OpenCv

This project explores GPU performance using CUDA by reasearching, implementing and comparing sequential(CPU) and parallel(GPU) versions of 
three image processing operations.

*Implemented Operations*

- Grayscale conversion ( from RGB  to grayscale)
- Horizontal image flip
- Blur filter

Objetive:
The main purpose of this project was to analyze and compare the performance of sequential versus parallel implemnetations(using CUDA). 

The performance was evaluated by measuring  and comparing the execution time for both sequential and parallel implementations of each image processing operations.
The execution time was measured for Sequential using clock() and for parallel using cudaEvent_t
