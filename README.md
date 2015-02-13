# Computing Pi in CUDA
This project is based around the computation of the mathematical constant Pi. The computation can be very intensive and take an incredibly long time to calculate accurate to millions of decimal places. 

The goal here was not to set a new record for the number of decimal places or computational time involved, but rather to demonstrate the benefits of GPU computing, by using CUDA(http://en.wikipedia.org/wiki/CUDA) to parallelize a traditional serial algorithm used to estimate Pi. The algorithm I chose uses numerical integration in order to compute an estimation of Pi. This algorithm can almost entirely be parallelised, which should result in huge performance gains and speedup when implemented using a parallel framework like CUDA. 

To run you must have an NVIDIA GPU capable of compiling and running CUDA.
