# Smoothsort

In computer science, smoothsort is a comparison-based sorting algorithm. A variant of heapsort, it was invented and published by Edsger Dijkstra in 1981. Like heapsort, smoothsort is an in-place algorithm with an upper bound of O(n log n), but it is not a stable sort. The advantage of smoothsort is that it comes closer to O(n) time if the input is already sorted to some degree, whereas heapsort averages O(n log n) regardless of the initial sorted state.

![Algorithm Visualization](https://upload.wikimedia.org/wikipedia/commons/a/a5/Smoothsort.gif)

[Algorithm Visualization - YouTube Video](https://youtu.be/Xu5ia5x2Vsw)

Time complexity

| Best | Average | Worst |
| ---- | ------- | ----- |
| Ω(n) | Θ(n log n) | O(n log n) |

Space Complexity

|  Worst   |
| -------- |
| O(n) total, O(1) auxiliary |

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Smoothsort)
* [Smoothsort Demystified](http://www.keithschwarz.com/smoothsort/)
* [Smoothsort, an alternative for sorting in situ by Edsger W. Dijkstra](https://www.cs.utexas.edu/users/EWD/transcriptions/EWD07xx/EWD796a.html)

## Implementations

* [Implementation in C++](https://github.com/gregreen/smoothsort)
* [Implementation in Ruby](https://github.com/chuckremes/smooth-sort/blob/master/sort.rb)
