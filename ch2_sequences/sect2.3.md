# 2.3 Exercises

1. Use polynomial fitting to find the formula for the nth term of the sequence $(a_n)_{n≥0}$ which starts,
$$ 0, 2, 6, 12, 20 $$

Differences between each term are 2, 4, 6,... increasing by 2 for each term. This is a constant second diffrence, so we know were looking for a quadratic. Since $a_n = 0$, $c=0$. Plugging in $n=1$ & $n=2$ gives us the equations:
$$ 2=a+b $$
$$ 6 = 4a+2b $$
Solving shows that a = 1 and b = 1, so the the formula is $a_n = n^2 + n $.
___
2. Use polynomial fitting to find the formula for the nth term of the sequence $(a_n)_{n≥0}$ which starts,
$$ 1,2,4,8,15,26 $$


The first differences are $1, 2, 4, 7, 11$, the second are $1, 2, 3, 4$, and the third are $1, 1, 1$, meaning its a trinomial ($\triangle^3-constant$). $a_n = 1/6(n^3+5n+6)$