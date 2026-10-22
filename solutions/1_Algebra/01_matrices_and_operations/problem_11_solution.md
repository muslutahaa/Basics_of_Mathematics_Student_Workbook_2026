# Exercise 11 — When Do Matrices Commute?

$$A=\begin{pmatrix}1&1\\0&1\end{pmatrix},\qquad B=\begin{pmatrix}a&b\\c&d\end{pmatrix}.$$

$$AB=\begin{pmatrix}a+c&b+d\\c&d\end{pmatrix},\qquad BA=\begin{pmatrix}a&a+b\\c&c+d\end{pmatrix}.$$

For $AB=BA$, comparing entries gives $a+c=a$, $b+d=a+b$, and $d=c+d$. Thus $c=0$ and $d=a$; there is no restriction on $b$.

Therefore all commuting matrices have the form
$$\boxed{B=\begin{pmatrix}a&b\\0&a\end{pmatrix}},\qquad a,b\in\mathbb R.$$

**Verification:** For this form, both $AB$ and $BA$ equal $\begin{pmatrix}a&a+b\\0&a\end{pmatrix}$.
