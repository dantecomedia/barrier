# barrier
Barrier Synchronization

In parallel computing, a barrier is a type of synchronization method. A barrier for a group of threads or processes in the source code means any thread/process must stop at this point and cannot proceed until all other threads/processes reach this barrier.

Many collective routines and directive-based parallel languages impose implicit barriers. For example, a parallel do loop in Fortran with OpenMP will not be allowed to continue on any thread until the last iteration is completed. This is in case the program relies on the result of the loop immediately after its completion. In message passing, any global communication (such as reduction or scatter) may imply a barrier.

https://en.wikipedia.org/wiki/Barrier_(computer_science)
