# Timsort

Timsort is a hybrid stable sorting algorithm, derived from merge sort and insertion sort, designed to perform well on many kinds of real-world data. It uses techniques from Peter McIlroy's "Optimistic Sorting and Information Theoretic Complexity", in Proceedings of the Fourth Annual ACM-SIAM Symposium on Discrete Algorithms, pp. 467–474, January 1993. It was implemented by Tim Peters in 2002 for use in the Python programming language. The algorithm finds subsequences of the data that are already ordered, and uses that knowledge to sort the remainder more efficiently. This is done by merging an identified subsequence, called a run, with existing runs until certain criteria are fulfilled. Timsort has been Python's standard sorting algorithm since version 2.3. It is also used to sort arrays of non-primitive type in Java SE 7, on the Android platform, and in GNU Octave.

[Algorithm Visualization - YouTube Video](https://youtu.be/NVIjHj-lrT4)

Time complexity

| Best | Average | Worst |
| ---- | ------- | ----- |
| Ω(n) | Θ(n log n) | O(n log n) |

Space Complexity

|  Worst   |
| -------- |
| O(n)     |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Timsort)

## Implementations

* [Implementation in C++](https://www.geeksforgeeks.org/timsort/)
