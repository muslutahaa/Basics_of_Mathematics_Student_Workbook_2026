# Exercise 5 — Matrix Times Vector

$$A=\begin{pmatrix}2&-1\\1&3\end{pmatrix},\qquad x=\begin{pmatrix}4\\2\end{pmatrix}.$$

$$Ax=\begin{pmatrix}2(4)+(-1)(2)\\1(4)+3(2)\end{pmatrix}=\begin{pmatrix}6\\10\end{pmatrix}.$$

The columns of $A$ are $a_1=(2,1)^T$ and $a_2=(-1,3)^T$. Thus
$$Ax=4a_1+2a_2=4\begin{pmatrix}2\\1\end{pmatrix}+2\begin{pmatrix}-1\\3\end{pmatrix}=\begin{pmatrix}8\\4\end{pmatrix}+\begin{pmatrix}-2\\6\end{pmatrix}=\begin{pmatrix}6\\10\end{pmatrix}.$$

**Verification:** Both the row-by-column method and the column linear combination give the same vector.
