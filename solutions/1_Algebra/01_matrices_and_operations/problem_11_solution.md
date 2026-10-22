# Exercise 11: When Do Matrices Commute?

## 1. Problem Statement

For $A=\begin{pmatrix}1&1\\0&1\end{pmatrix}$ and $B=\begin{pmatrix}a&b\\c&d\end{pmatrix}$, find all $B$ satisfying $AB=BA$.

## 2. Theoretical Background and Concepts

Two matrices commute when $AB=BA$. Equating corresponding entries gives conditions on unknown matrix entries.

## 3. Detailed Step-by-Step Solution

$$A=\begin{pmatrix}1&1\\0&1\end{pmatrix},\qquad B=\begin{pmatrix}a&b\\c&d\end{pmatrix}.$$

$$AB=\begin{pmatrix}a+c&b+d\\c&d\end{pmatrix},\qquad BA=\begin{pmatrix}a&a+b\\c&c+d\end{pmatrix}.$$

For $AB=BA$, comparing entries gives $a+c=a$, $b+d=a+b$, and $d=c+d$. Thus $c=0$ and $d=a$; there is no restriction on $b$.

Therefore all commuting matrices have the form
$$\boxed{B=\begin{pmatrix}a&b\\0&a\end{pmatrix}},\qquad a,b\in\mathbb R.$$

The equality in the upper-right entry gives $d=a$, and the upper-left entry gives $c=0$; $b$ remains arbitrary.

## 4. Verification and Consistency Checks

Substituting $B=\begin{pmatrix}a&b\\0&a\end{pmatrix}$ into both products yields $AB=BA=\begin{pmatrix}a&a+b\\0&a\end{pmatrix}$.
