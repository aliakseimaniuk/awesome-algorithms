# Counting Sort

In computer science, counting sort is an algorithm for sorting a collection of objects according to keys that are small integers; that is, it is an integer sorting algorithm. It operates by counting the number of objects that have each distinct key value, and using arithmetic on those counts to determine the positions of each key value in the output sequence. Its running time is linear in the number of items and the difference between the maximum and minimum key values, so it is only suitable for direct use in situations where the variation in keys is not significantly greater than the number of items. However, it is often used as a subroutine in another sorting algorithm, radix sort, that can handle larger keys more efficiently.

[Algorithm Visualization](https://www.cs.usfca.edu/~galles/visualization/CountingSort.html)

Time complexity

| Best     |  Average   | Worst    |
| -------- | --------   | ------   |
| Ω(n + k) |  Θ(n + k)  | O(n + k) |

Space Complexity

|        Worst        |
|---------------------|
|        O(k)         |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Counting_sort)
* [YouTube](https://youtu.be/TTnvXY82dtM)
* [MIT YouTube Video](https://youtu.be/Nz1KZXbghj8)

## Books

* **Introduction to Algorithms** by Thomas H. Cormen, Charles E. Leiserson, Ronald L. Rivest, Clifford Stein

## Articles

* [Counting Linearly With Counting Sort](https://medium.com/basecs/counting-linearly-with-counting-sort-cd8516ae09b3)

## Implementations

* [Implementation in C++](https://www.geeksforgeeks.org/counting-sort/)
* [Implementation in Java](https://www.geeksforgeeks.org/counting-sort/)
* [Implementation in Python](https://www.geeksforgeeks.org/counting-sort/)
* [Implementation in C#](https://www.geeksforgeeks.org/counting-sort/)
