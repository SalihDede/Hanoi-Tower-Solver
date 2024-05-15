This Java program solves the classic Tower of Hanoi problem efficiently using recursion. It prompts the user to input the number of disks they want to move, then demonstrates the optimal sequence of moves to solve the puzzle.

The program defines a recursive function moveDisks() that calculates and prints the sequence of moves needed to solve the Tower of Hanoi problem for a given number of disks. It adheres to the following rules:

Only one disk can be moved at a time.
Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack.
No disk may be placed on top of a smaller disk.


Eaample Output:
Enter number of disks: 3

The moves are:
Move disk 1 from A to C
Move disk 2 from A to B
Move disk 1 from C to B
Move disk 3 from A to C
Move disk 1 from B to A
Move disk 2 from B to C
Move disk 1 from A to C

The total number of moves is 7.
