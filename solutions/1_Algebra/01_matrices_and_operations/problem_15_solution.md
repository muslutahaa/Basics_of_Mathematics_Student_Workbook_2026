# Exercise 15: Associativity of Multiplication and Different Calculation Paths

## 1. Problem Statement

For $A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix}$, $B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix}$, and $C=\begin{pmatrix}2&1\\0&-1\end{pmatrix}$, compare $(AB)C$ and $A(BC)$ including operation counts.

## 2. Theoretical Background and Concepts

Associativity says $(AB)C=A(BC)$ for compatible matrices. Parenthesization can change the cost: multiplying an $m\times n$ by an $n\times p$ matrix requires $mnp$ scalar multiplications using the standard method.

## 3. Detailed Step-by-Step Solution

$$A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},\quad B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix},\quad C=\begin{pmatrix}2&1\\0&-1\end{pmatrix}.$$

**Path 1: $(AB)C$.** First,
$$AB=\begin{pmatrix}1+4&0+2\\2-1&1+3\end{pmatrix}=\begin{pmatrix}5&2\\1&4\end{pmatrix}.$$
Then
$$(AB)C=\begin{pmatrix}5&2\\1&4\end{pmatrix}\begin{pmatrix}2&1\\0&-1\end{pmatrix}=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.$$

**Path 2: $A(BC)$.** First,
$$BC=\begin{pmatrix}2&1\\4&1\\-2&-4\end{pmatrix}.$$
Then
$$A(BC)=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix}\begin{pmatrix}2&1\\4&1\\-2&-4\end{pmatrix}=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.$$

## 4. Verification and Consistency Checks

Both multiplication orders yield $\begin{pmatrix}10&3\\2&-3\end{pmatrix}$. The standard scalar multiplication counts are 20 for $(AB)C$ and 24 for $A(BC)$.
