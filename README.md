# TCES_420_Project2
Thien: I upload what i have done, but have not test it. It works in size 2 array for sure. 

Thank you, I will test it.

## Version 0.1 Speed Results of Matrix size 500
* 1 Thread: time = 29.783972s
* 2 Thread: time = 29.796831s
* 4 Thread: time = 29.090250s
* 8 Thread: time = 30.226021s
* 16 Thread: time = 29.473454s

No performance increase (on raspberry pi)

In the mythread function computation for loop each thread goes from 0 to SIZE 
instead it each thread should start at a different indice and calculate the indices
each thread is responsible for

## Version 0.2 (Davids thread) Speed Results of Matrix size 800 (Latest version is matrixmult)
* 1 Thread: time = 22s
* 2 Thread: time = 11s
* 4 Thread: time = 5s
* 8 Thread: time = 6s
* 16 Thread: time = 6s

## Version 0.2 (Davids thread) Speed Results of Matrix size 2000 (Latest version is matrixmult)
* 1 Thread: time = 334.577752s
* 2 Thread: time = 167.481944s (about 2x speed up)
* 4 Thread: time = 94.933584s  (about 3.5x speed up)
* 8 Thread: time = 112.481346s (about 3x speed up)
* 16 Thread: time = 120.071180s (about 2.8x speed up)
