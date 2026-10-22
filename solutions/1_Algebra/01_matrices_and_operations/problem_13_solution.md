# Exercise 13: A Recurrence Written in Matrix Form

## 1. Problem Statement

For $F=\begin{pmatrix}1&1\\1&0\end{pmatrix}$, compute $F^2$ through $F^5$, connect them to Fibonacci numbers, and explain $F(a,b)^T$.

## 2. Theoretical Background and Concepts

The Fibonacci recurrence is $f_{n+1}=f_n+f_{n-1}$. Multiplication by $F$ updates the state vector $(f_n,f_{n-1})^T$ to $(f_{n+1},f_n)^T$.

## 3. Detailed Step-by-Step Solution

$$F=\begin{pmatrix}1&1\\1&0\end{pmatrix}.$$

Successive products give
$$F^2=\begin{pmatrix}2&1\\1&1\end{pmatrix},\quad F^3=\begin{pmatrix}3&2\\2&1\end{pmatrix},$$
$$F^4=\begin{pmatrix}5&3\\3&2\end{pmatrix},\quad F^5=\begin{pmatrix}8&5\\5&3\end{pmatrix}.$$

These entries are Fibonacci numbers from $0,1,1,2,3,5,8,\ldots$. If $f_0=0$, $f_1=1$, and $f_{n+1}=f_n+f_{n-1}$, then
$$F^n=\begin{pmatrix}f_{n+1}&f_n\\f_n&f_{n-1}\end{pmatrix}\quad(n\ge1).$$

For arbitrary $a,b$,
$$F\begin{pmatrix}a\\b\end{pmatrix}=\begin{pmatrix}a+b\\a\end{pmatrix}.$$

**Explanation:** If $a,b$ are consecutive terms (newer first), the multiplication creates their sum and retains the previous newer term. This performs one Fibonacci recurrence step.

## 4. Verification and Consistency Checks

Multiplying $F^4$ by $F$ yields $F^5=\begin{pmatrix}8&5\\5&3\end{pmatrix}$, consistent with Fibonacci recurrence.
