# Exercise 8 — Row Operations and Their Reversibility

Start with
$$A=\begin{pmatrix}1&2&-1\\2&4&1\\-1&1&3\end{pmatrix}.$$

**Step 1:** $R_2\leftarrow R_2-2R_1$. The new second row is $(0,0,3)$:
$$\begin{pmatrix}1&2&-1\\0&0&3\\-1&1&3\end{pmatrix}.$$
Reverse: $R_2\leftarrow R_2+2R_1$.

**Step 2:** $R_3\leftarrow R_3+R_1$. The new third row is $(0,3,2)$:
$$\begin{pmatrix}1&2&-1\\0&0&3\\0&3&2\end{pmatrix}.$$
Reverse: $R_3\leftarrow R_3-R_1$.

**Step 3:** Interchange $R_2$ and $R_3$:
$$\begin{pmatrix}1&2&-1\\0&3&2\\0&0&3\end{pmatrix}.$$
Reverse: interchange $R_2$ and $R_3$ again.

**Verification:** Applying the inverse operations in reverse order (swap, subtract $R_1$ from $R_3$, then add $2R_1$ to $R_2$) recovers the original $A$.
