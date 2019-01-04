Implementation of the 2D Fast Fourier transform using MPI.

This program computes the forward and reverse Fast Fourier transform of the given input 2D matrix.

Assumption: All input files will be square, same width and height and will be a power of 2

Execution-

Forward DFT
./p32 forward [INPUTFILE] [OUTPUTFILE]
Reverse DFT
./p32 reverse [INPUTFILE] [OUTPUTFILE]

EXAMPLE-

Forward DFT
./p32 forward Tower256.txt Output256.txt
Reverse DFT
./p32 reverse Tower256.txt Output256.txt

