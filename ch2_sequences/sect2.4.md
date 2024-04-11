# 2.4 Exercises

1. Find the next two terms in $(a_n)_{n \ge 0}$ beginning
$3, 5, 11, 21, 43, 85,...$ Then give a recursive definition for the sequence.
Finally, use the characteristic root technique to find a closed formula for the
sequence.

 $11 = 2 \times 3 + 5$ 
 
 $21 = 2 \times 5 + 11$
 
 $43 = 2 \times 11 + 21$

 $85 = 2 \times 21 + 43$ 
 
 This gives the recursive formula: $a_n = 2a_{n-2} + a_{n-1}$

The next terms are 171 and 341. 

 $a_n - a_{n-1} - 2a_{n-2} = 0$
 
 Characteristic formula: $x^2 + -x + -2$ 
 
 Characteristic equation: $x^2 + -x + -2 = 0$.
 
 Factoring gives $(x + 1)(x - 2) = 0$
 
$r_1 = -1$ and $r_2 = 2$.

 $a_n = a \times(-1)^n + b \times 2^n$
 
 Using the first two values of the sequence as the intial conditions, we
 can solve for $a$ and $b$. $3 = a + b$ and $5 = -a + 2b$. $b = \frac{8}{3}$
 and $a = \frac{1}{3}$, and the closed formula for this sequence is:
$$
a_n = \frac{8 \times (-1)^n + 2^n}{3}
$$