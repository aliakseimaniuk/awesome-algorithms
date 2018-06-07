# Block Sort aka Block Merge Sort

A sorting algorithm combining at least two merge operations with an insertion sort to arrive at O(n log n) in-place stable sorting. It gets its name from the observation that merging two sorted lists, A and B, is equivalent to breaking A into evenly sized blocks, inserting each A block into B under special rules, and merging AB pairs.

One practical algorithm for O(log n) in place merging was proposed by Pok-Son Kim and Arne Kutzner in 2008.

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/9/9f/Block_sort_with_numbers_1_to_16_%28thumb%29.gif)

Time complexity

| Best |  Average     | Worst      |
| ---- | ------------ | ---------- |
| Ω(n) |  Θ(n log n)  | O(n log n) |

Space Complexity

|        Worst        |
|---------------------|
|        O(1)         |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Block_sort)
