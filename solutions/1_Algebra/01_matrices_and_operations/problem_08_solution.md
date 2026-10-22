# Exercise 8: Row Operations and Their Reversibility

## 1. Problem Statement

For $A=\begin{pmatrix}1&2&-1\\2&4&1\\-1&1&3\end{pmatrix}$, perform $R_2\leftarrow R_2-2R_1$, $R_3\leftarrow R_3+R_1$, then swap rows 2 and 3. Give inverses.

## 2. Theoretical Background and Concepts

Elementary row operations include adding a multiple of another row and swapping rows. They are reversible by subtracting the multiple or swapping again.

## 3. Detailed Step-by-Step Solution

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

## 4. Verification and Consistency Checks

Undo the operations in reverse order: swap rows 2 and 3, replace $R_3$ by $R_3-R_1$, and replace $R_2$ by $R_2+2R_1$. This returns the original matrix.
