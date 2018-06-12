# Sleep Sort

In general, sleep sort works by starting a separate task for each item to be sorted, where each task sleeps for an interval corresponding to the item's sort key, then emits the item. Items are then collected sequentially in time.

Task: Write a program that implements sleep sort. Have it accept non-negative integers on the command line and print the integers in sorted order. If this is not idomatic in your language or environment, input and output may be done differently. Enhancements for optimization, generalization, practicality, robustness, and so on are not required.

Sleep sort was presented anonymously on 4chan and has been discussed on Hacker News.

## References

* [GeeksForGeeks](https://www.geeksforgeeks.org/sleep-sort-king-laziness-sorting-sleeping/)

## Implementations

* [Implementation in many languages](https://rosettacode.org/wiki/Sorting_algorithms/Sleep_sort)
