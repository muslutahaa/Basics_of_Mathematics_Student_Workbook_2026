# Exercise 9 — Composing Transformations

$$S=\begin{pmatrix}2&0\\0&1\end{pmatrix},\quad R=\begin{pmatrix}0&-1\\1&0\end{pmatrix},\quad x=\begin{pmatrix}1\\2\end{pmatrix}.$$

First scale, then rotate:
$$Sx=\begin{pmatrix}2\\2\end{pmatrix},\qquad RSx=R(Sx)=\begin{pmatrix}-2\\2\end{pmatrix}.$$

First rotate, then scale:
$$Rx=\begin{pmatrix}-2\\1\end{pmatrix},\qquad SRx=S(Rx)=\begin{pmatrix}-4\\1\end{pmatrix}.$$

**Explanation:** $S$ doubles the horizontal coordinate, while $R$ rotates vectors $90^\circ$ counterclockwise. After rotation, the direction to which the horizontal scaling applies changes. Therefore $RSx\ne SRx$.

**Verification:** $RS=\begin{pmatrix}0&-1\\2&0\end{pmatrix}$ and $SR=\begin{pmatrix}0&-2\\1&0\end{pmatrix}$; multiplying each by $x$ gives the same results as above.
