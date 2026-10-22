# Exercise 12: Formula for a Matrix Power

## 1. Problem Statement

For $`A=\begin{pmatrix}1&1\\0&1\end{pmatrix}`$, calculate $`A^2,A^3,A^4`$, conjecture $`A^n`$, and prove by induction.

## 2. Theoretical Background and Concepts

Mathematical induction proves a formula for all nonnegative integers by verifying a base case and deriving case $`n+1`$ from case $`n`$.

## 3. Detailed Step-by-Step Solution

```math
A=\begin{pmatrix}1&1\\0&1\end{pmatrix}.
```

Direct multiplication gives

```math
A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix},\quad A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix},\quad A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix}.
```

The pattern suggests

```math
\boxed{A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}}\quad(n\ge0).
```

**Proof by induction:** For $`n=0`$, $`A^0=I=\begin{pmatrix}1&0\\0&1\end{pmatrix}`$. Assume $`A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}`$. Then

```math
A^{n+1}=A^nA=\begin{pmatrix}1&n\\0&1\end{pmatrix}\begin{pmatrix}1&1\\0&1\end{pmatrix}=\begin{pmatrix}1&n+1\\0&1\end{pmatrix}.
```

This is exactly the formula with $`n`$ replaced by $`n+1`$, proving the conjecture for all nonnegative integers.

## 4. Verification and Consistency Checks

The base case $`n=0`$ gives $`A^0=I`$. Multiplying the assumed $`A^n`$ by $`A`$ gives the same expression with $`n`$ replaced by $`n+1`$.
