# Exercise 9: Composing Transformations

## 1. Problem Statement

With $`S=\begin{pmatrix}2&0\\0&1\end{pmatrix}`$, $`R=\begin{pmatrix}0&-1\\1&0\end{pmatrix}`$, $`x=\begin{pmatrix}1\\2\end{pmatrix}`$, compute $`RSx`$ and $`SRx`$ and interpret.

## 2. Theoretical Background and Concepts

Matrix products compose transformations from right to left. $`S`$ scales the horizontal coordinate by 2; $`R`$ rotates counterclockwise by $`90^\circ`$.

## 3. Detailed Step-by-Step Solution

```math
S=\begin{pmatrix}2&0\\0&1\end{pmatrix},\quad R=\begin{pmatrix}0&-1\\1&0\end{pmatrix},\quad x=\begin{pmatrix}1\\2\end{pmatrix}.
```

First scale, then rotate:

```math
Sx=\begin{pmatrix}2\\2\end{pmatrix},\qquad RSx=R(Sx)=\begin{pmatrix}-2\\2\end{pmatrix}.
```

First rotate, then scale:

```math
Rx=\begin{pmatrix}-2\\1\end{pmatrix},\qquad SRx=S(Rx)=\begin{pmatrix}-4\\1\end{pmatrix}.
```

**Explanation:** $`S`$ doubles the horizontal coordinate, while $`R`$ rotates vectors $`90^\circ`$ counterclockwise. After rotation, the direction to which the horizontal scaling applies changes. Therefore $`RSx\ne SRx`$.

## 4. Verification and Consistency Checks

Direct products give $`RS=\begin{pmatrix}0&-1\\2&0\end{pmatrix}`$ and $`SR=\begin{pmatrix}0&-2\\1&0\end{pmatrix}`$. Applying these to $`x`$ reproduces the two answers.
