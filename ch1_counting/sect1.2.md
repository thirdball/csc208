# Chapter 1.2 Notes

## Problem I was supposed to present:
### 7. How many subsets of {0, 1, . . . , 9} have cardinality 6 or more?
___________________________________________
The total number of subsets of {0, 1, ..., 9} of cardinality less than 6 is 1 + 10 + 45 + 120 + 210 + 252 = 638. Therefore, the number of subsets of {0, 1, ..., 9} of cardinality 6 or more is 1024 - 638 = 386.

You can also add the combinations in desmos scientific calculator:
![equation](https://github.com/thirdball/csc208/blob/main/ch1_counting/equation.png)

### Counting Subsets
Suppose we look at the set A  {1, 2, 3, 4, 5}. How many subsets of A contain xactly 3 elements?

Together there are 20
of these subsets, so 10 each.

Finding how many subsets of A exist of cardinality x reveals a symmetrical pattern.

| Number of elements | Number of subsets|
| -------------------|------------------|
|0                   |1                 |
|1                   |5                 |
|2                   |10                |
|3                   |10                |
|4                   |5                 |
|5                   |1                 |
### Bit Strings
Bit is short for binary digit, so a bit string is just a string of binary digits from 0 to 1.
Examples:
101010   0   1111111

- An n-bit string is a bit string of length n. It contains n symbols, which each are a bit of either 1 or 0.
- The weight of a bit string is the number of 1's in it.

### Lattice Paths
The integer lattice is the set of all points in the Cartesian plane for which both the x and y coordinates are integers.

A lattice path is one of the shortest paths connecting two points on a lattice.

For example, a lattice path connecting the coordinates (0,0) and (3,2) would have to have only 5 steps. Some lattice paths would be (U meaning up and R meaning right) UUURR and RURUR.

### Binomial Coefficients

Binomial Coefficients are read as "n choose k". This costruct is the number of subsets of a set of size n with a cardinality of k.
This can be written as $|B_k^n|$.
