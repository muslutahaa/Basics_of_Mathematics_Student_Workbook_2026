# Exercise 6: Transpose

## 1. Problem Statement

For $A=\begin{pmatrix}1&2&3\\4&5&6\end{pmatrix}$ and $B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix}$, calculate $A^T,B^T,AB$ and check $(AB)^T=B^TA^T$.

## 2. Theoretical Background and Concepts

The transpose exchanges rows and columns: $(A^T)_{ij}=A_{ji}$. For compatible matrices, transposition reverses multiplication order: $(AB)^T=B^TA^T$.

## 3. Detailed Step-by-Step Solution

$$A=\begin{pmatrix}1&2&3\\4&5&6\end{pmatrix},\qquad B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix}.$$

Transposition interchanges rows and columns:
$$A^T=\begin{pmatrix}1&4\\2&5\\3&6\end{pmatrix},\qquad B^T=\begin{pmatrix}1&2&-1\\0&1&3\end{pmatrix}.$$

Multiplication gives
$$AB=\begin{pmatrix}1+4-3&0+2+9\\4+10-6&0+5+18\end{pmatrix}=\begin{pmatrix}2&11\\8&23\end{pmatrix}.$$

Hence
$$(AB)^T=\begin{pmatrix}2&8\\11&23\end{pmatrix}.$$

Checking the reversed product:
$$B^TA^T=\begin{pmatrix}1&2&-1\\0&1&3\end{pmatrix}\begin{pmatrix}1&4\\2&5\\3&6\end{pmatrix}=\begin{pmatrix}2&8\\11&23\end{pmatrix}.$$

## 4. Verification and Consistency Checks

Both $(AB)^T$ and $B^TA^T$ equal $\begin{pmatrix}2&8\\11&23\end{pmatrix}$, verifying the identity.
