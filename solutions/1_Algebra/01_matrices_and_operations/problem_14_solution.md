# Exercise 14: Rotation Matrices

## 1. Problem Statement

For $`R(\theta)=\begin{pmatrix}\cos\theta&-\sin\theta\\\sin\theta&\cos\theta\end{pmatrix}`$, show $`R(\alpha)R(\beta)=R(\alpha+\beta)`$ algebraically and geometrically.

## 2. Theoretical Background and Concepts

Rotation matrices describe counterclockwise rotations. The trigonometric angle-addition formulas combine sine and cosine terms of two rotations.

## 3. Detailed Step-by-Step Solution

```math
R(\theta)=\begin{pmatrix}\cos\theta&-\sin\theta\\\sin\theta&\cos\theta\end{pmatrix}.
```

Multiplying gives

```math
R(\alpha)R(\beta)=\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta&-\cos\alpha\sin\beta-\sin\alpha\cos\beta\\
\sin\alpha\cos\beta+\cos\alpha\sin\beta&-\sin\alpha\sin\beta+\cos\alpha\cos\beta
\end{pmatrix}.
```

Using

```math
\cos(\alpha+\beta)=\cos\alpha\cos\beta-\sin\alpha\sin\beta
```

and

```math
\sin(\alpha+\beta)=\sin\alpha\cos\beta+\cos\alpha\sin\beta,
```

we obtain

```math
\boxed{R(\alpha)R(\beta)=\begin{pmatrix}\cos(\alpha+\beta)&-\sin(\alpha+\beta)\\\sin(\alpha+\beta)&\cos(\alpha+\beta)\end{pmatrix}=R(\alpha+\beta)}.
```

**Geometric explanation:** Applying a rotation by $`\beta`$ and then one by $`\alpha`$ rotates the plane by their total angle $`\alpha+\beta`$.

## 4. Verification and Consistency Checks

For $`\alpha=\beta=90^\circ`$, the composition gives $`R(180^\circ)=-I`$, agreeing with two quarter-turns.
