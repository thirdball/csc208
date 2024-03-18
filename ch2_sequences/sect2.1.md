## 1. Find the closed formula for each of the following sequences by relating them to a well known sequence. Assume the first term given is a1.
>(a) 2, 5, 10, 17, 26, . . .

The sequence above consists of all numbers that are 1 more than a perfect square (1, 4, 9, 16, 25). With that, the formula would be $a_n = n^2 +1$

>(b) 0,2,5,9,14,20,...

This looks like triangular numbers (1, 3, 6,...), but is just subtracting one. We can just subtract one from the triangular number formula which gives us $a_n = \left(\frac{n(n+1)}{2}\right) - 1$
> (c) 8,12,17,23,30,...

This pattern also uses triangular numbers, but later in the pattern . This will give us the equation $ a_n = \frac{(n+2)(n+3)}{2} + 2 $
>(d) 1,5,23,119,719,...

This pattern uses factorials, but starts with the second term and subtracts one from each number. This gives us $ a_n = (n+1)! - 1 $

## 17. Consider bit strings with length l and weight k (so strings of l 0’s and 1’s, including k 1’s). We know how to count the number of these for a fixed l and k. Now, we will count the number of strings for which the sum of the length and the weight is fixed. For example, let’s count all the bit strings for which l + k  11.

### Find examples of these strings of different lengths. What is the longest string possible? What is the shortest? 

The longest string is $l = 11, k = 0$. The shortest is $l = 6, k = 5$.

### (b) How many strings are there of each of these lengths. Use this to
count the total number of strings (with sum 11).

There ${11 \choose 0}$ and ${6 \choose 5}$ of these, respectively. So we just fill in the blanks and get the sum by doing:
	$${11 \choose 0}+{10 \choose 1}+{9 \choose 2}+{8 \choose 3}+{7 \choose 4}+{6 \choose 5} = 134$$

### (c) The other approach: Let n  l + k vary. How many strings have sum n  1? How many have sum n  2? And so on. Find and explain a recurrence relation for the sequence (an) which gives the number of strings with sum n.

Well making this into a sequence, the first few terms, starting at $a_1$, are $$ 1, 2, 3, 5, 8, 13, 21$$ i see the pattern. A recursive formula is difficult to find here but I think it's $a_{n+1}$ = $a_n - a_{n-1}$ with $a_1 = 1, a_2 = 2$

### (d) Describe what you have found above in terms of Pascal’s Triangle. What pattern have you discovered?

 $a_n$ in this case follows the same rule as pascal's triangle  where two numbers in the same row add up to the number below them. Here, $a_1 + a_2 = a_3$, $a_3 + a_4 = a_5$, and so on. This pattern happens indefinitely. 
    
![pattern](https://github.com/thirdball/csc208/blob/main/ch2_sequences/17d.png)