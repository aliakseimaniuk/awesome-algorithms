# Shell Sort aka Shell's method

Shellsort, also known as Shell sort or Shell's method, is an in-place comparison sort. It can be seen as either a generalization of sorting by exchange (bubble sort) or sorting by insertion (insertion sort). The method starts by sorting pairs of elements far apart from each other, then progressively reducing the gap between elements to be compared. Starting with far apart elements, it can move some out-of-place elements into position faster than a simple nearest neighbor exchange. Donald Shell published the first version of this sort in 1959. The running time of Shellsort is heavily dependent on the gap sequence it uses. For many practical variants, determining their time complexity remains an open problem.

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/d/d8/Sorting_shellsort_anim.gif)

[Algorithm Visualization](https://www.cs.usfca.edu/~galles/visualization/ComparisonSort.html)

Time complexity

| Best | Average | Worst |
| ---- | ------- | ----- |
| Ω(n log(n)) |  Θ(n(log(n))^2) | O(n(log(n))^2) |

Space Complexity

|  Worst   |
| -------- |
|   O(1)   |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Shellsort)
* [YouTube Video](https://youtu.be/ddeLSDsYVp8)

## Implementations

* [Implementation in JavaScript](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/shell-sort)
* [Implementation in many languages](https://rosettacode.org/wiki/Sorting_algorithms/Shell_sort)
