# Comb Sort

The basic idea is to eliminate turtles, or small values near the end of the list, since in a bubble sort these slow the sorting down tremendously. Rabbits, large values around the beginning of the list, do not pose a problem in bubble sort.

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/4/46/Comb_sort_demo.gif)

Time complexity

| Best        |  Average                                              | Worst  |
| --------    | --------                                              | ------ |
| Ω(n log(n)) |  Θ(n^2 / 2^p), where p is the number of increments    | O(n^2) |

Space Complexity

|        Worst        |
|---------------------|
|        O(1)         |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Comb_sort)
* [YouTube](https://youtu.be/X5DKBwDL0kU)

## Articles

* [Sorting Algorithms: The Comb Sort](http://buffered.io/posts/sorting-algorithms-the-comb-sort/)

## Implementations

* [Implementation in C++](https://www.geeksforgeeks.org/comb-sort/)
* [Implementation in Java](https://www.geeksforgeeks.org/comb-sort/)
* [Implementation in Python](https://www.geeksforgeeks.org/comb-sort/)
* [Implementation in C#](https://www.geeksforgeeks.org/comb-sort/)
* [Implementation in Go](http://www.golangprograms.com/golang-program-for-implementation-of-combsort.html)
* [Implementation of comb sort in many languages](https://rosettacode.org/wiki/Sorting_algorithms/Comb_sort)
