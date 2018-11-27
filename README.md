# cabrera-cristian-hw4
## Developers
- Marcial Cabrera -- mcabr122@fiu.edu
- Cristian Cepeda -- ccepe014@fiu.edu
## Compile
```
> make -f Makefile.LibDisk
> make -f Makefile.LibFS
> make
```
## Run 
```
./main.exe disk
./simple-test.exe disk
```
## README provided by professor 
This directory contains a partial implementation of the simple file
system for homework assignment 5. The partial implementation is in
LibFS.c; it's heavily commented code so hopefully the implementation
is self-explanatory. The places marked as YOUR CODE are to be filled
in by your implementation.

NOTE THAT THE IMPLEMENTATION PROVIDED HERE IS PURELY DESIGNED TO HELP
YOU COMPLETE THE TASK. YOU DO NOT HAVE TO FOLLOW THE IMPLEMENTATION.
BUT IF YOU DO, PAY ATTENTION TO THE DETAILS. THERE IS NOT GUARANTEE
THAT THE PROVIDED PARTIAL IMPLEMENTATION IS BUG-FREE CODE OR CONSIDERS
ALL POSSIBLE SCENARIOS.

The directory also contains a number of test applications implmement
file system commands, including ls, mkdir, cat, rm, rmdir. The touch
command is to create an empty file. The import and export commands
used for copying a unix file into and out from our simple file system.

Enjoy coding!