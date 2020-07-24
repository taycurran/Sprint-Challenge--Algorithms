#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

A O(n^3) --- The While loop will run till A > n^3.
While n is small, this won't make a huge difference,
but it will get much worse as n grows.


B O(log n) --- Reason is that j doubles with each pass. This means that
j is growing faster than n and j is the "breaks" of the algorithm.


C O(n) --- Reason is that the recursion will loop n times.

## Exercise II

Recursive Binary Search

- Divide the building height in half.
- Drop egg at mid point.
- If egg breaks, find midpoint of bottom half and repeat.
- If egg does not break, find midpoint of top half and repeat.
- Base Case: Floor where Egg Breaks - Floor where egg does not break == 1

The run time complexity of this would be O(log n) because it is a 
AVL balanced tree
