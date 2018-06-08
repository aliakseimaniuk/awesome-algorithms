# Insertion Sort

Insertion sort iterates, consuming one input element each repetition, and growing a sorted output list. At each iteration, insertion sort removes one element from the input data, finds the location it belongs within the sorted list, and inserts it there. It repeats until no input elements remain.

Sorting is typically done in-place, by iterating up the array, growing the sorted list behind it. At each array-position, it checks the value there against the largest value in the sorted list (which happens to be next to it, in the previous array-position checked). If larger, it leaves the element in place and moves to the next. If smaller, it finds the correct position within the sorted list, shifts all the larger values up to make a space, and inserts into that correct position.

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/4/42/Insertion_sort.gif)

Time complexity

| Best |  Average | Worst  |
| ---- | -------- | ------ |
| Ω(n) |  Θ(n^2)  | O(n^2) |

Space Complexity

|        Worst        |
|---------------------|
|        O(1)         |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Insertion_sort)
* [CS50 YouTube Video](https://youtu.be/kU9M51eKSX8)
* [MIT YouTube Video](https://youtu.be/Kg4bqzAqRBM)

## Books

* **Introduction to Algorithms** by Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Clifford Stein
* **Algorithms in Java, Parts 1-4** by Robert Sedgewick

## Articles

* [Inching Towards Insertion Sort](https://medium.com/basecs/inching-towards-insertion-sort-9799274430da)

## Implementations

* [Implementation in JavaScript](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/insertion-sort)
* [Implementation in Go](https://github.com/aliakseimaniuk/go-algorithms/blob/master/insertionSort.go)
* [Implementation in C++](https://www.geeksforgeeks.org/insertion-sort/)
* [Implementation in Java](https://www.geeksforgeeks.org/insertion-sort/)
* [Implementation in Python](https://www.geeksforgeeks.org/insertion-sort/)
