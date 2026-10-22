# Exercise 10 — Columns of a Matrix Product

$$A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},\quad B=\begin{pmatrix}1&2\\-1&0\\3&1\end{pmatrix}.$$

The columns of $B$ are
$$b_1=\begin{pmatrix}1\\-1\\3\end{pmatrix},\qquad b_2=\begin{pmatrix}2\\0\\1\end{pmatrix}.$$

$$Ab_1=\begin{pmatrix}1(1)+2(-1)+0(3)\\0(1)+1(-1)+1(3)\end{pmatrix}=\begin{pmatrix}-1\\2\end{pmatrix}.$$

$$Ab_2=\begin{pmatrix}1(2)+2(0)+0(1)\\0(2)+1(0)+1(1)\end{pmatrix}=\begin{pmatrix}2\\1\end{pmatrix}.$$

Thus
$$AB=\begin{pmatrix}-1&2\\2&1\end{pmatrix}=\begin{pmatrix}\vert&\vert\\Ab_1&Ab_2\\\vert&\vert\end{pmatrix}.$$

**Explanation:** The $j$th column of $AB$ is $A$ multiplied by the $j$th column of $B$. The direct product confirms both columns.
