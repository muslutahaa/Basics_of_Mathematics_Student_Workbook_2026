# Exercise 3: When Can Matrices Be Multiplied?

## 1. Problem Statement

Given dimensions $A:2\times3$, $B:3\times4$, $C:4\times2$, $D:2\times2$, determine whether $AB,BA,BC,CB,AC,CA,AD,DA$ exist and give their dimensions.

## 2. Theoretical Background and Concepts

A product of an $m\times n$ matrix and a $p\times q$ matrix exists only if $n=p$. The result is $m\times q$.

## 3. Detailed Step-by-Step Solution

The dimensions are $A:2\times3$, $B:3\times4$, $C:4\times2$, and $D:2\times2$.

The product $(m\times n)(p\times q)$ is defined exactly when $n=p$, and then has size $m\times q$.

| Product | Inner dimensions | Defined? | Result size |
|---|---|---|---|
| $AB$ | $3=3$ | Yes | $2\times4$ |
| $BA$ | $4\ne2$ | No | — |
| $BC$ | $4=4$ | Yes | $3\times2$ |
| $CB$ | $2\ne3$ | No | — |
| $AC$ | $3\ne4$ | No | — |
| $CA$ | $2=2$ | Yes | $4\times3$ |
| $AD$ | $3\ne2$ | No | — |
| $DA$ | $2=2$ | Yes | $2\times3$ |

Each row of the table applies the same inner-dimension rule; a mismatch makes the product undefined.

## 4. Verification and Consistency Checks

For each valid product, the output row count equals the left factor’s row count and the output column count equals the right factor’s column count. Invalid products have unequal inner dimensions.
