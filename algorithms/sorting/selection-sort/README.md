# Selection Sort

In computer science, selection sort is a sorting algorithm, specifically an in-place comparison sort. It has O(n^2) time complexity, making it inefficient on large lists, and generally performs worse than the similar insertion sort. Selection sort is noted for its simplicity, and it has performance advantages over more complicated algorithms in certain situations, particularly where auxiliary memory is limited.

The algorithm divides the input list into two parts: the sub-list of items already sorted, which is built up from left to right at the front (left) of the list, and the sub-list of items remaining to be sorted that occupy the rest of the list. Initially, the sorted sub-list is empty and the unsorted sub-list is the entire input list. The algorithm proceeds by finding the smallest (or largest, depending on sorting order) element in the unsorted sub-list, exchanging (swapping) it with the leftmost unsorted element (putting it in sorted order), and moving the sub-list boundaries one element to the right.

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/thumb/b/b0/Selection_sort_animation.gif/250px-Selection_sort_animation.gif)

[Algorithm Visualization](https://www.cs.usfca.edu/~galles/visualization/ComparisonSort.html)

Time complexity

| Best    |  Average   | Worst   |
| ----    | --------   | ------  |
| Ω(n^2)  |  Θ(n^2)    | O(n^2)  |

Space Complexity

|        Worst   |
|----------------|
|   O(1)         |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Selection_sort)
* [CS50 - YouTube Video](https://youtu.be/3hH8kTHFw2A)

## Implementations

* [Implementation in JavaScript](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/selection-sort)
* [Implementation in many languages](https://rosettacode.org/wiki/Sorting_algorithms/Selection_sort)
