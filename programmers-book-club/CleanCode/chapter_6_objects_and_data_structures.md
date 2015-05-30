# Chapter 6 - Objects and Data Structures

Abstraction is the process of decoupling the core process from changing details.
Decoupling gives us the ability to change implementation.

Hiding implementation is not about simply adding layers. Hiding implementation details is about abstraction. 

Creating a bunch of private variables and then adding getters and setters isn't abstraction. It's just extra work that doesn't abstract anything. It doesn't extract the heart of the matter. 

Abstraction is about shedding non-critical details in order to expose and enforce working through the prefered interface.

## Compare these two interfaces:
** What differences do you notice immediately? **

** Write down the differences that you notice **

### Vehicle Example 1
     interface Vehicle {
        public function getFuelTankCapacityInGallons();
        public function getGallonsOfGasoline();
    } 

### Vehicle Example 2
    interface Vehicle {
        public function getPerfentFuelRemaining();
    } 

* Based on the differences you notice, which interface is actually abtracting an abstraction?
* Which interface makes you feel safer across different measurement systems?
* Which interface would you prefer for selling the vehicle to international markets?



## Data/Object Anti-Symmetry

** "Objects hide their data behind abstractions and expose functions that operate on that data" **

** "Data structures expose their data and have no meaningful functions" **

"Procedural code (code using only data structures) makes it easy to add new functions without changing the existing data structures. Object Oriented code, on the other hand, makes it easy to add new classes without changing existing functions."

Also,
"Procedural code makes it hard to add new data structures because all the functions must change. OO cod emakes it hard to add new functions because all the classes must change."

