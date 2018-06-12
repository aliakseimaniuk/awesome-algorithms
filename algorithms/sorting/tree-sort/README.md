# Tree Sort

A tree sort is a sort algorithm that builds a binary search tree from the elements to be sorted, and then traverses the tree (in-order) so that the elements come out in sorted order. Its typical use is sorting elements online: after each insertion, the set of elements seen so far is available in sorted order.

Time complexity

| Best | Average | Worst |
| ---- | ------- | ----- |
| Ω(n log(n)) | Θ(n log n) | O(n^2) |

Space Complexity

|  Worst   |
| -------- |
| O(n)     |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Tree_sort)
* [YouTube Video](https://youtu.be/n2MLjGeK7qA)

## Implementations

* [Implementation in C++](https://www.geeksforgeeks.org/tree-sort/)
