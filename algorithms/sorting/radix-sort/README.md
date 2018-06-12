# Radix Sort

In computer science, radix sort is a non-comparative integer sorting algorithm that sorts data with integer keys by grouping keys by the individual digits which share the same significant position and value. A positional notation is required, but because integers can represent strings of characters (e.g., names or dates) and specially formatted floating point numbers, radix sort is not limited to integers. Radix sort dates back as far as 1887 to the work of Herman Hollerith on tabulating machines.

[Algorithm Visualization](https://www.cs.usfca.edu/~galles/visualization/RadixSort.html)

Time complexity

| Best   |  Average  | Worst  |
| ----   | --------  | ------ |
| Ω(nk)  |  Θ(nk)    | O(nk)  |

Space Complexity

|        Worst     |
|------------------|
|   O(n+k)         |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Radix_sort)
* [MIT - YouTube Video](https://youtu.be/Nz1KZXbghj8)

## Implementations

* [Implementation in JavaScript](https://github.com/trekhleb/javascript-algorithms/tree/master/src/algorithms/sorting/radix-sort)
* [Implementation in many languages](https://rosettacode.org/wiki/Sorting_algorithms/Radix_sort)
