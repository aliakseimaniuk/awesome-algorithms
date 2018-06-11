# Odd–even Sort aka Brick Sort

In computing, an odd–even sort or odd–even transposition sort (also known as brick sort[self-published source]) is a relatively simple sorting algorithm, developed originally for use on parallel processors with local interconnections. It is a comparison sort related to bubble sort, with which it shares many characteristics. It functions by comparing all odd/even indexed pairs of adjacent elements in the list and, if a pair is in the wrong order (the first is larger than the second) the elements are switched. The next step repeats this for even/odd indexed pairs (of adjacent elements). Then it alternates between odd/even and even/odd steps until the list is sorted.

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/1/1b/Odd_even_sort_animation.gif)

Time complexity

| Best  |  Average     | Worst  |
| ----  | --------     | ------ |
| Ω(n)  |  Θ(n^2)      | O(n^2) |

Space Complexity

|        Worst        |
|---------------------|
|        O(1)         |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Odd–even_sort)

## Implementations

* [Implementation in C++, Java, Python, C#](https://www.geeksforgeeks.org/odd-even-sort-brick-sort/)
