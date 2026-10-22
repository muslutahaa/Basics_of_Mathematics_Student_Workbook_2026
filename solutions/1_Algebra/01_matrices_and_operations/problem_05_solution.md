# Exercise 5: Matrix Times Vector

## 1. Problem Statement

For $A=\begin{pmatrix}2&-1\\1&3\end{pmatrix}$ and $x=\begin{pmatrix}4\\2\end{pmatrix}$, compute $Ax$ and express it as a linear combination of columns of $A$.

## 2. Theoretical Background and Concepts

If $A=[a_1\ a_2]$ and $x=(x_1,x_2)^T$, then $Ax=x_1a_1+x_2a_2$. Each output entry is a dot product of a row of $A$ with $x$.

## 3. Detailed Step-by-Step Solution

$$A=\begin{pmatrix}2&-1\\1&3\end{pmatrix},\qquad x=\begin{pmatrix}4\\2\end{pmatrix}.$$

$$Ax=\begin{pmatrix}2(4)+(-1)(2)\\1(4)+3(2)\end{pmatrix}=\begin{pmatrix}6\\10\end{pmatrix}.$$

The columns of $A$ are $a_1=(2,1)^T$ and $a_2=(-1,3)^T$. Thus
$$Ax=4a_1+2a_2=4\begin{pmatrix}2\\1\end{pmatrix}+2\begin{pmatrix}-1\\3\end{pmatrix}=\begin{pmatrix}8\\4\end{pmatrix}+\begin{pmatrix}-2\\6\end{pmatrix}=\begin{pmatrix}6\\10\end{pmatrix}.$$

## 4. Verification and Consistency Checks

Direct row-dot-vector multiplication gives $(6,10)^T$; the weighted-column method also gives $(6,10)^T$.
