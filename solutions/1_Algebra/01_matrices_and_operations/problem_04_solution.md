# Exercise 4: Matrix Multiplication and Noncommutativity

## 1. Problem Statement

Compute $AB$ and $BA$ for $A=\begin{pmatrix}1&2\\0&1\end{pmatrix}$ and $B=\begin{pmatrix}2&0\\3&1\end{pmatrix}$, and discuss commutativity.

## 2. Theoretical Background and Concepts

Matrix multiplication uses row-column dot products: $(AB)_{ij}=\sum_k a_{ik}b_{kj}$. In general, changing factor order changes the product.

## 3. Detailed Step-by-Step Solution

$$A=\begin{pmatrix}1&2\\0&1\end{pmatrix},\qquad B=\begin{pmatrix}2&0\\3&1\end{pmatrix}.$$

Using row-by-column multiplication,
$$AB=\begin{pmatrix}1(2)+2(3)&1(0)+2(1)\\0(2)+1(3)&0(0)+1(1)\end{pmatrix}=\begin{pmatrix}8&2\\3&1\end{pmatrix}.$$

$$BA=\begin{pmatrix}2(1)+0(0)&2(2)+0(1)\\3(1)+1(0)&3(2)+1(1)\end{pmatrix}=\begin{pmatrix}2&4\\3&7\end{pmatrix}.$$

The computed products differ, so the order of multiplication matters.

## 4. Verification and Consistency Checks

The $(1,1)$ entries are $(AB)_{11}=8$ and $(BA)_{11}=2$. Since these differ, $AB\ne BA$.
