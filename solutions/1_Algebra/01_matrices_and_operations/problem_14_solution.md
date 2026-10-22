# Exercise 14 — Rotation Matrices

$$R(\theta)=\begin{pmatrix}\cos\theta&-\sin\theta\\\sin\theta&\cos\theta\end{pmatrix}.$$

Multiplying gives
$$R(\alpha)R(\beta)=\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta&-\cos\alpha\sin\beta-\sin\alpha\cos\beta\\
\sin\alpha\cos\beta+\cos\alpha\sin\beta&-\sin\alpha\sin\beta+\cos\alpha\cos\beta
\end{pmatrix}.$$

Using
$$\cos(\alpha+\beta)=\cos\alpha\cos\beta-\sin\alpha\sin\beta$$
and
$$\sin(\alpha+\beta)=\sin\alpha\cos\beta+\cos\alpha\sin\beta,$$
we obtain
$$\boxed{R(\alpha)R(\beta)=\begin{pmatrix}\cos(\alpha+\beta)&-\sin(\alpha+\beta)\\\sin(\alpha+\beta)&\cos(\alpha+\beta)\end{pmatrix}=R(\alpha+\beta)}.$$

**Geometric explanation:** Applying a rotation by $\beta$ and then one by $\alpha$ rotates the plane by their total angle $\alpha+\beta$.

**Verification:** For $\alpha=\beta=90^\circ$, two quarter-turns yield $R(180^\circ)=-I$.
