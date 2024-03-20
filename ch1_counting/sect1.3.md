# 1.3 Exercises

## 1.
*A pizza parlor offers 10 toppings.*
### (a)
"How many 3-topping pizzas could they put on their menu? Assume double toppings are not allowed."

The order doesn't matter here cause it's a combination.  $\binom{10}{3} = 120$ pizzas.
### (b)
"How many total pizzas are possible, with between zero and ten toppings (but not double toppings) allowed?"

There are 10 toppings you can either choose or leave out, so there are  $2^{10} = 1024$ possible pizzas.
### (c)
"The pizza parlor will list the 10 toppings in two equal-sized columns on their menu. How many ways can they arrange the toppings in the left column?"

This is a permutation because order matters. Here, there are 10 options and 5 spaces so the equation would be $P(10,5) = \frac{10!}{(10-5)!} = 3628800 /120 = 30240$

## 2. A combination lock consists of a dial with 40 numbers on it. To open the lock, you turn the dial to the right until you reach a first number, then to the left until you get to second number, then to the right again to the third number. The numbers must be distinct. How many different combinations are possible?

Here, you have to subtract 1 from the total for each turn to get 3 distinct numbers. The equation would be $40 \times 39 \times 38 = 59280$
