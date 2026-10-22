# Exercise 7 — Identity Matrix, Zero Matrix, and Powers

$$A=\begin{pmatrix}2&1\\0&2\end{pmatrix},\quad I=\begin{pmatrix}1&0\\0&1\end{pmatrix},\quad 0=\begin{pmatrix}0&0\\0&0\end{pmatrix}.$$

$$AI=IA=A=\begin{pmatrix}2&1\\0&2\end{pmatrix},\qquad A+0=A.$$

$$A^2=A\cdot A=\begin{pmatrix}4&4\\0&4\end{pmatrix}.$$

$$A^3=A^2A=\begin{pmatrix}8&12\\0&8\end{pmatrix}.$$

**Explanation:** $I$ is the multiplicative identity, while $0$ is the additive identity. The diagonal entries of $A^n$ are $2^n$; the upper-right entry follows $n2^{n-1}$, giving
$$A^n=\begin{pmatrix}2^n&n2^{n-1}\\0&2^n\end{pmatrix}\quad(n\ge1).$$

**Verification:** At $n=2$ and $n=3$, this formula reproduces the matrices calculated above.
