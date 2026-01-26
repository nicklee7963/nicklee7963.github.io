---
title: "1-3 Matrices and Their Column Spaces"
dates: 2026-01-26
math: true
summary: ""
weight: 2
---

$
A = \begin{bmatrix}
1 & 2 \\
3 & 4 \\
5 & 6 
\end{bmatrix}
$
is a **3 by 2 matrix** (3 rows 2 columns)


- The **row picture** of Ax will come from **dot products** of x with rows of A.

$A\mathbf{x} = \begin{bmatrix} 
-1 & 1 & 0 & 0 \\
0 & -1 & 1 & 0 \\
0 & 0 & -1 & 1
\end{bmatrix}
\begin{bmatrix}
x1 \\ 
x2 \\
x3 \\
x4
\end{bmatrix}
=\begin{bmatrix} 
row 1 \cdot \mathbf{x} \\
row 2 \cdot \mathbf{x} \\
row 3 \cdot \mathbf{x}
\end{bmatrix}$

- The **column picture** will come from **linear combinations** of the columns of A.

$A\mathbf{x} = x_1\begin{bmatrix}
-1 \\
0 \\
0\end{bmatrix}
+x_2\begin{bmatrix}
1 \\
-1 \\
0
\end{bmatrix}
+x_3\begin{bmatrix}
0 \\
1 \\
-1 
\end{bmatrix}
+x_4\begin{bmatrix}
0 \\
0 \\
1
\end{bmatrix}
$

##### Indpendent columns
$$ 
A_1 = \begin{bmatrix}
1 & 0 & 0 \\
2 & 4 & 0 \\
3 & 5 & 6
\end{bmatrix}
$$
*Each column gives a new direction.* Their combinations fill 3D space $R^3$

##### Dependent columns
$$ 
A_1 = \begin{bmatrix}
1 & 2 & 3 \\
1 & 4 & 5 \\
6 & 0 & 6
\end{bmatrix}
$$
**Column 1 + Column 2 = Column3. Their combinations don't fill 3D space**

**Column space: All combinations of the columns.**


### Thinking About the Column Space of $A$
**Span**: describes all the linear combinations of a set of vectors.

1. **Rank**: the number of independent columns in A
2. **Basis**: The first $\gamma$ independent columns


