# Insertion-Checkpoint-Project
The insertion algorithm works as follows:

EXPLANATION
Declared the variable as follows : key as current element j as sorted counter and i as unsorted counter

Transverse the first element of the array. This element is considered the sorted sequence. . Pick the next unsorted element (arr[i]) and insert it into the sorted sequence (the elements from 0 to i-1).

Two counters were used: i for iterating through the unsorted elements and j for iterating through the sorted sequence.

The current element (key) with the elements in the sorted sequence (j) and move larger elements to the right to make space for the new element.

steps 2-4 were repeated for all remaining unsorted elements in the array.

After processing all elements, the entire array is sorted
