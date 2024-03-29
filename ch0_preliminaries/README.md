# Chapter 0 Notes

## Implications (Part 1)

An implication is basically an "if...then" statement.

Let p and q be propositions. The proposition "p implies q" denoted by p -> q is called implication. It is false when p is true and q is false and is true otherwise. In p -> q, p is called the hypothesis and q is called the conclusion.

Examples: 

 **P -> Q**: If statement P is true, then statement Q must also be true.

**Inverse**: The inverse of P -> Q is -P -> -Q. If P is false, then Q must be false.

**Biconditional**: P if and only if Q, denoted as P <-> Q. Both P -> Q and Q -> P are true.


#### Sources
* https://www.javatpoint.com/implication-in-discrete-mathematics 

* https://math.libretexts.org/Bookshelves/Combinatorics_and_Discrete_Mathematics/A_Spiral_Workbook_for_Discrete_Mathematics_(Kwong)/02%3A_Logic/2.03%3A_Implications

## Mathimatical Statements - Implications Part 2 (by Caleb)

### Converse and Contrapositives
$$P\to Q$$
$$Q\to P$$

Converse: If P then Q and if Q then P.

Converses are two independent statements. It is very common for a statements converse to not be true. 

e.x. If it snows then traffic moves slowly ($P \to Q$). If traffic moves slowy then it snows ($Q \to P$).

| $P$ | $Q$ | $P \to Q$| $Q \to P$ |
|-----|-----|----------|-----------|
|True |True| True| True |
|True |False| False| True |
|False |True| True| False |
|False |False| True| True |

Contrapositive: If not P then not Q and if not Q the not P.

Same truth table as above, but inverted.

If it snows then traffic moves slowly ($P \to Q$). If it does not snow then traffic moves quickly ($\neg P \to \neg Q$).

### If and Only If

$P \leftrightarrow Q$ means the same as $(P \to Q) \wedge (Q \to P)$\
$P \to Q$ is the `if` part and $Q \to P$ is the `only if` part.

If and only if statements are built of a statement and its converse.

### Necessary and Sufficient

$Q \to P$ - $P$ is neccesary for $Q$\
$P \to Q$ - $P$ is sufficient for $Q$\
$P \leftrightarrow Q$ - $P$ is neccessary and sufficient for $Q$

```
Thinking about the necessity and sufficiency of conditions can also help when writing proofs and
justifying conclusions. If you want to establish some mathematical fact, it is helpful to think what 
other facts would be enough (be sufficient) to prove your fact. If you have an assumption, think 
about what must also be necessary if that hypothesis is true. (Page 14)
``` 

### Practice 
Suppose I tell John that if he gets a 68% on his final, then he will fail the class. Assuming that what I said is true, what can you conclude in the following cases:
1. John gets a 68% on her final.
2. John gets fails the class.
3. John does not get a 68% on his final.
4. John does not fail the class.
5. None of the above.


## Atomic and Molecular Statements (by Parker)
---
### Logical Connectives
* simple statements can be combined into more complex ones using logical connectives.
    * Telephone numbers in the USA have 10 digits and 42 is a perfect square.

This sentence combines the statements "Telephone numbers in the USA have 10 digits" and "42 is a perfect square."

|        |P⋀Q        |P⋁Q        |P→Q|P↔Q|¬P|
|-       |-          |-          |-|-|-|
|read |P and Q    |P or Q     |if P then Q|P if and only if Q|not P|
|called|conjunction|disjunction|implication or conditional|biconditional|negation|

||P⋀Q|P⋁Q|P→Q|P↔Q|¬P|
|-|-|-|-|-|-|
|P is true, Q is true|true|true|true|true|false|
|P is true, Q is false|false|true|false|false|false|
|P is false, Q is true|false|true|true|false|true|
|P is false, Q is false|false|false|true|true|true|

### Exercises

|        |P⋀Q        |P⋁Q        |P→Q|P↔Q|¬P|
|-       |-          |-          |-|-|-|
|read |P and Q    |P or Q     |if P then Q|P if and only if Q|not P|
|called|conjunction|disjunction|implication or conditional|biconditional|negation|

1. Suppose P and Q are the statements: 
	- P: Jack passed math.
	
	- Q: Jill passed math.
		- Translate "Jack and Jill both passed math" to symbols.<sub>1</sub>
		
		- Translate "If Jack passed math, then Jill did not" to symbols.<sub>2</sub>
		- Translate "P⋁Q" to English.<sub>3</sub>
		- Translate "¬(P⋀Q)→Q" to English."<sub>4</sub>
		- Suppose you know that if Jack passed math, then so did Jill. What can you conclude if you know that:
			- Jill passed math?<sub>5</sub>
			
			- Jill did not pass math?<sub>6</sub>
### Answers

 1. P⋀Q.

 2. P→¬Q.
 3. Jack passed math (inclusive or) Jill passed math.
 4. If Jack and Jill both did not pass math, then Jill did.
 5. Nothing more.
 6. Jack also did not pass.

##### Sources
 - [Wikipedia - Converse](https://en.wikipedia.org/wiki/Converse_(logic))
 - [University of Pittsburgh - Discrete Mathematics](https://people.cs.pitt.edu/~milos/courses/cs441/lectures/Class1.pdf)
 - [Caleb's git repo](https://github.com/CalebNeal07/csc208/blob/main/presentations/0.2-Implications.md)
- [Wikipedia](https://en.wikipedia.org/wiki/Logical_conjunction)
- [Lander.edu](https://philosophy.lander.edu/logic/conjunct.html)
- [Parker's git repo](https://github.com/PB22-School/csc208/blob/main/ch0/atomic-molecular.md)