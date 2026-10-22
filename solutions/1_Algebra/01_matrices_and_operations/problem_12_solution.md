# Exercise 12 — Formula for a Matrix Power

$$A=\begin{pmatrix}1&1\\0&1\end{pmatrix}.$$

Direct multiplication gives
$$A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix},\quad A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix},\quad A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix}.$$

The pattern suggests
$$\boxed{A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}}\quad(n\ge0).$$

**Proof by induction:** For $n=0$, $A^0=I=\begin{pmatrix}1&0\\0&1\end{pmatrix}$. Assume $A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}$. Then
$$A^{n+1}=A^nA=\begin{pmatrix}1&n\\0&1\end{pmatrix}\begin{pmatrix}1&1\\0&1\end{pmatrix}=\begin{pmatrix}1&n+1\\0&1\end{pmatrix}.$$
This is exactly the formula with $n$ replaced by $n+1$, proving the conjecture for all nonnegative integers.
