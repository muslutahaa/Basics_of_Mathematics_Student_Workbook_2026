# Exercise 10: Columns of a Matrix Product

## 1. Problem Statement

For $`A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix}`$ and $`B=\begin{pmatrix}1&2\\-1&0\\3&1\end{pmatrix}`$, compute $`Ab_1,Ab_2,AB`$ and compare columns.

## 2. Theoretical Background and Concepts

For $`B=[b_1\ b_2]`$, matrix multiplication satisfies $`AB=[Ab_1\ Ab_2]`$. This follows from row-column multiplication.

## 3. Detailed Step-by-Step Solution

```math
A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},\quad B=\begin{pmatrix}1&2\\-1&0\\3&1\end{pmatrix}.
```

The columns of $`B`$ are

```math
b_1=\begin{pmatrix}1\\-1\\3\end{pmatrix},\qquad b_2=\begin{pmatrix}2\\0\\1\end{pmatrix}.
```

```math
Ab_1=\begin{pmatrix}1(1)+2(-1)+0(3)\\0(1)+1(-1)+1(3)\end{pmatrix}=\begin{pmatrix}-1\\2\end{pmatrix}.
```

```math
Ab_2=\begin{pmatrix}1(2)+2(0)+0(1)\\0(2)+1(0)+1(1)\end{pmatrix}=\begin{pmatrix}2\\1\end{pmatrix}.
```

Thus

```math
AB=\begin{pmatrix}-1&2\\2&1\end{pmatrix}=\begin{pmatrix}\vert&\vert\\Ab_1&Ab_2\\\vert&\vert\end{pmatrix}.
```

**Explanation:** The $`j`$th column of $`AB`$ is $`A`$ multiplied by the $`j`$th column of $`B`$. The direct product confirms both columns.

## 4. Verification and Consistency Checks

The first and second columns of the directly computed $`AB`$ are respectively $`(-1,2)^T`$ and $`(2,1)^T`$, exactly $`Ab_1`$ and $`Ab_2`$.
