# Cycle Sort

Cycle sort is an in-place, unstable sorting algorithm, a comparison sort that is theoretically optimal in terms of the total number of writes to the original array, unlike any other in-place sorting algorithm. It is based on the idea that the permutation to be sorted can be factored into cycles, which can individually be rotated to give a sorted result.

[Algorithm Visualization](https://youtu.be/ZSJGf5Ngw18)

Time complexity

| Best       |  Average      | Worst       |
| --------   | --------      | ------      |
| Ω(n^2)     |  Θ(n^2)       | O(n^2)      |

Space Complexity

|        Worst                             |
| ---------------------                    |
|        Θ(n) total, Θ(1) auxiliary        |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Cubesort)
* [YouTube](https://youtu.be/0eFq2YSueeA)

## Implementations

* [Implementation of cycle sort in many languages](https://rosettacode.org/wiki/Sorting_algorithms/Cycle_sort)
