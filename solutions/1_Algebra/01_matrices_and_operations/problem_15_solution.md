# Exercise 15 — Associativity of Multiplication and Different Calculation Paths

$$A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},\quad B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix},\quad C=\begin{pmatrix}2&1\\0&-1\end{pmatrix}.$$

**Path 1: $(AB)C$.** First,
$$AB=\begin{pmatrix}1+4&0+2\\2-1&1+3\end{pmatrix}=\begin{pmatrix}5&2\\1&4\end{pmatrix}.$$
Then
$$(AB)C=\begin{pmatrix}5&2\\1&4\end{pmatrix}\begin{pmatrix}2&1\\0&-1\end{pmatrix}=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.$$

**Path 2: $A(BC)$.** First,
$$BC=\begin{pmatrix}2&1\\4&1\\-2&-4\end{pmatrix}.$$
Then
$$A(BC)=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix}\begin{pmatrix}2&1\\4&1\\-2&-4\end{pmatrix}=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.$$

**Verification:** Both paths produce the same $2\times2$ matrix. This illustrates associativity: $(AB)C=A(BC)$, even though the intermediate matrices differ.

**Operation count:** Counting scalar multiplications by the standard row-by-column method, $AB$ needs $2\cdot3\cdot2=12$ and $(AB)C$ needs $2\cdot2\cdot2=8$, totaling **20**. Computing $BC$ needs $3\cdot2\cdot2=12$ and $A(BC)$ needs $2\cdot3\cdot2=12$, totaling **24**. Thus the first path uses fewer scalar multiplications for these dimensions.
