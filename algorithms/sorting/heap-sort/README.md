# Heap Sort

In computer science, heapsort is a comparison-based sorting algorithm. Heapsort can be thought of as an improved selection sort: like that algorithm, it divides its input into a sorted and an unsorted region, and it iteratively shrinks the unsorted region by extracting the largest element and moving that to the sorted region. The improvement consists of the use of a heap data structure rather than a linear-time search to find the maximum.

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/1/1b/Sorting_heapsort_anim.gif)

[Algorithm Visualization](https://www.cs.usfca.edu/~galles/visualization/HeapSort.html)

Time complexity

| Best        |  Average     | Worst       |
| --------    | --------     | ------      |
| Ω(n log(n)) |  Θ(n log(n)) | O(n log(n)) |

Space Complexity

|    Worst   |
| ---------- |
|    Θ(1)    |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Heapsort)
* [Heaps and Heap Sort - MIT Video](https://youtu.be/B7hVxCmfPtM)

## Implementations

* [Implementation in many languages](https://rosettacode.org/wiki/Sorting_algorithms/Heapsort)
* [Implementation in JavaScript](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/heap-sort)
