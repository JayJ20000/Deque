-Project Overview
--This project implementes a double-ended queue in C++. With using a block-based memory fortmat, it supportes insertions and deletions from both ends and handles memory expansion.

-Features
-- Block-based memory management
-- Access and modifications at both ends
-- Memory cleanup

-Files
-- deque.h: Header file declaring the Deque class
-- deque.cpp: Implementation of all class methods
-- main.cpp: Shows usage of the deque by pushing, popping, and printing values

-Main operations
-- void pushFront(): Inserts a value at the front
-- void pushBack(): Inserts a value at the back.
-- void popFront(): Removes a value from the front
-- void popBack(): Removes a value from the back.
-- int getFront(): Returns the value at the front
-- int getBack(): Returns the value at the back
-- bool isEmpty(): Returns true if the deque has no elements.
-- int getSize(): Returns the number of elements currently in the deque.
-- int& operator[](): Returns a reference to the element at the specified index.
-- void print(): Outputs all elements in the deque.

-How to Run
-- With the makefile, run "make" in the terminal and run the program with ./deque
