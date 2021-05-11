---
title: "Deterministic matrix sketches for low-rank compression of high-dimensional simulation data"
collection: publications
permalink: /publications/2021-05-11-deterministic-sketches
excerpt: ''
date: 2021-05-11
venue: 'arXiv'
paperurl: 'http://alecmdunton.github.io/files/2105.01271.pdf'
---

Matrices arising in scientific applications frequently admit linear low-rank approximations due to smoothness in the physical and/or temporal domain of the problem. In large-scale problems, computing an optimal low-rank approximation can be prohibitively expensive. Matrix sketching addresses this by reducing the input matrix to a smaller, but representative matrix via a low-dimensional linear embedding. If the sketch matrix produced by the embedding sufficiently captures the geometric properties of the original matrix, then a near-optimal approximation may be obtained. Much of the work done in matrix sketching has centered on random projection. Alternatively, in this work, deterministic matrix sketches which generate coarse representations – compatible with the corresponding PDE solve – are considered in the computation of the singular value decomposition and matrix interpolative decomposition. The deterministic sketching approaches in this work have many advantages over randomized sketches. Broadly, randomized sketches are data-agnostic, whereas the proposed sketching methods exploit structures within data generated in complex PDE systems. These deterministic sketches are often faster, require access to a small fraction of the input matrix, and do not need to be explicitly constructed. A novel single-pass, i.e., requiring one read over the input, power iteration algorithm is also presented. The power iteration method is particularly effective in improving low-rank approximations when the singular value decay of data is slow. Finally, theoretical error bounds and estimates, as well as numerical results across three application problems, are provided.

[Download paper here](http://alecmdunton.github.io/files/2105.01271.pdf)
