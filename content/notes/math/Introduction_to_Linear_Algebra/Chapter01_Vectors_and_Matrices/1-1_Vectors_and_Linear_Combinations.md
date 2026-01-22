---
title: "1-1 Vectors and Linear Combinations"
date: 2026-01-22
weight: 1
summary: ""
math: true
---


### Linear Combinations
If $w$ and $v$ are non-collinear, the linear combinations $c\vec{v} + d\vec{w}$ **fill the plane**.

### Solving Two Equations 
If $\vec{v}$, $\vec{w}$ are not on the same line. They are **linearly independent**.

### Can Elimination Fail?
If $\vec{v}$ and $\vec{w}$ lie on the same line. They are **linearly dependent**.  

$$
\mathbf{v} = \begin{bmatrix}
2 \\
3 \\
1
\end{bmatrix}, \quad
\mathbf{w} = \begin{bmatrix}
1 \\
1 \\
0
\end{bmatrix}
$$

The combinations of $\mathbf{v}, \mathbf{w}$ **only fill a plane in 3D space**

- **idintity Matrix $I$**: matrix analog of the number 1, becase $I\mathbf{v} = \mathbf{v}$


### How Do We Know It Is a Plane?

Consider $\vec{u}, \vec{v}, \vec{w}$ if $\vec{w} = c\vec{u} + d\vec{v}$ then they are **a plane**.


Consider $\vec{u}, \vec{v}, \vec{w}$ if $\vec{w} \neq c\vec{u} + d\vec{v}$ then they are **a 3D space**.

### Challenge Problems

24. How many corners $(\pm1, \pm1, \pm1, \pm1)$ does a cube of side 2 have in 4 dimensions? What is its volume? How many 3D faces? How many edges? Find one edge.
    1. $\mathbf{2 \times 2 \times 2 \times 2}$
    2. $\mathbf{2 \times 2 \times 2 \times 2}$
    3. 3D faces have three freedom dimensions. There are $\mathbf{2 \times 4}$
    4. Lines have one freedom dimension. There are $\mathbf{8 \times 4}$
    5. e.g. $\mathbf{(-1, 1, 1, 1) \  to \ (1, 1, 1, 1)}$





