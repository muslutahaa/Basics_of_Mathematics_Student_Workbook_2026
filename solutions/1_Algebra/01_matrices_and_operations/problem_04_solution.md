# Exercise 4 — Matrix Multiplication and Noncommutativity

$$A=\begin{pmatrix}1&2\\0&1\end{pmatrix},\qquad B=\begin{pmatrix}2&0\\3&1\end{pmatrix}.$$

Using row-by-column multiplication,
$$AB=\begin{pmatrix}1(2)+2(3)&1(0)+2(1)\\0(2)+1(3)&0(0)+1(1)\end{pmatrix}=\begin{pmatrix}8&2\\3&1\end{pmatrix}.$$

$$BA=\begin{pmatrix}2(1)+0(0)&2(2)+0(1)\\3(1)+1(0)&3(2)+1(1)\end{pmatrix}=\begin{pmatrix}2&4\\3&7\end{pmatrix}.$$

**Conclusion:** $AB\ne BA$ because, for example, their top-left entries are $8$ and $2$. Matrix multiplication is generally **noncommutative**: changing the order of the factors can change the result.
