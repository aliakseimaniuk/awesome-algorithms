# Bogosort

Bogosort simply shuffles a collection randomly until it is sorted. Bogosort is a perversely inefficient algorithm only used as an in-joke.

Its average run-time is **O(n!)** because the chance that any given shuffle of a set will end up in sorted order is about one in n factorial, and the worst case is infinite since there's no guarantee that a random shuffling will ever produce a sorted sequence. Its best case is **O(n)** since a single pass through the elements may suffice to order them.

## References

* [Wikipedia](https://en.wikipedia.org/wiki/Bogosort)

## Implementations

* [Implementation in many languages](https://rosettacode.org/wiki/Sorting_algorithms/Bogosort)
