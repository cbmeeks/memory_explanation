## Memory Explanation
General information on different memory types for the JVM.


## Eden Space (heap)
The pool from which memory is initially allocated for most objects.

## Survivor Space (heap)
The pool containing objects that have survived the garbage collection of the Eden space.

## Tenured Generation (heap)
The pool containing objects that have existed for some time in the survivor space.

## Permanent Generation (non-heap)
The pool containing all the reflective data of the virtual machine itself, such as **class** and **method** objects. 
With Java VMs that use class data sharing, this generation is divided into read-only and read-write areas.

## Code Cache (non-heap)
The HotSpot Java VM also includes a code cache, containing memory that is used for compilation and storage of native code.
