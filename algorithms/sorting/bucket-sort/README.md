# Bucket sort

A sorting algorithm that works by distributing the elements of an array into a number of buckets. Each bucket is then sorted individually, either using a different sorting algorithm, or by recursively applying the bucket sorting algorithm. It is a distribution sort, a generalization of pigeonhole sort, and is a cousin of radix sort in the most-to-least significant digit flavor. Bucket sort can be implemented with comparisons and therefore can also be considered a comparison sort algorithm. The computational complexity estimates involve the number of buckets.

Bucket sort works as follows:

1. Set up an array of initially empty "buckets".
1. Scatter: Go over the original array, putting each object in its bucket.
1. Sort each non-empty bucket.
1. Gather: Visit the buckets in order and put all elements back into the original array.

Time complexity

| Best     |  Average   | Worst  |
| -------- | --------   | ------ |
| Ω(n + k) |  Θ(n + k)  | O(n^2) |

Space Complexity

|        Worst        |
|---------------------|
|        O(n*k)       |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Bucket_sort)
* [YouTube](https://youtu.be/geVyIsFpxUs)

## Books

* **Introduction to Algorithms** by Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Clifford Stein

## Implementations

* [Implementation in C](https://users.dcc.uchile.cl/~rbaeza/handbook/algs/4/423.sort.c.html)
