---
title: "Understanding SVD (Singular Value Decomposition)"
date: 2026-01-21
math: true
tags: ["Math", "Linear Algebra", "Machine Learning"]
summary: "My notes on SVD and its application in image compression."
---

In my journey learning Computer Vision, I realized that **Linear Algebra** is the engine behind everything. Here is my breakdown of SVD.

### The Concept
Every matrix $A$ can be decomposed into three matrices:

$$A = U \Sigma V^T$$

Where:
* $U$: Left singular vectors (Orthonormal)
* $\Sigma$: Singular values (Diagonal scaling matrix)
* $V^T$: Right singular vectors

### Application in Image Processing
In my recent experiment, I used SVD to compress an image by keeping only the top $k$ singular values. This significantly reduced the file size while maintaining visual structure.
