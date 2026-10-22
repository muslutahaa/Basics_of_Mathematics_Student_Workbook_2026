# Exercise 2: Addition and Scalar Multiplication

## 1. Problem Statement

For $`A=\begin{pmatrix}1&2\\-1&3\end{pmatrix}`$ and $`B=\begin{pmatrix}4&-2\\0&5\end{pmatrix}`$, compute $`A+B`$, $`A-B`$, and $`3A-2B`$. Explain the requirement for addition.

## 2. Theoretical Background and Concepts

Addition and subtraction are entrywise: $`(A\pm B)_{ij}=a_{ij}\pm b_{ij}`$. Scalar multiplication acts on every entry: $`(kA)_{ij}=ka_{ij}`$. Addition requires equal dimensions.

## 3. Detailed Step-by-Step Solution

Given $`A=\begin{pmatrix}1&2\\-1&3\end{pmatrix}`$ and $`B=\begin{pmatrix}4&-2\\0&5\end{pmatrix}`$.

Adding corresponding entries gives

```math
A+B=\begin{pmatrix}1+4&2-2\\-1+0&3+5\end{pmatrix}=\begin{pmatrix}5&0\\-1&8\end{pmatrix}.
```

Subtracting corresponding entries gives

```math
A-B=\begin{pmatrix}1-4&2-(-2)\\-1-0&3-5\end{pmatrix}=\begin{pmatrix}-3&4\\-1&-2\end{pmatrix}.
```

For scalar multiplication,

```math
3A=\begin{pmatrix}3&6\\-3&9\end{pmatrix},\qquad 2B=\begin{pmatrix}8&-4\\0&10\end{pmatrix}.
```

Therefore,

```math
3A-2B=\begin{pmatrix}-5&10\\-3&-1\end{pmatrix}.
```

**Explanation:** Addition and subtraction operate on corresponding entries, so matrices must have the same number of rows and columns.

## 4. Verification and Consistency Checks

$`(A+B)-B=\begin{pmatrix}5&0\\-1&8\end{pmatrix}-\begin{pmatrix}4&-2\\0&5\end{pmatrix}=A`$. Also $`(3A-2B)+2B=3A`$.
