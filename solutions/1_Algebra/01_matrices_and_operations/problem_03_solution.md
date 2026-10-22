# Exercise 3 — When Can Matrices Be Multiplied?

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

**Verification:** For every valid product, the result's row count comes from the first matrix and its column count from the second matrix.
