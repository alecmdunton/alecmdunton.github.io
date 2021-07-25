---
permalink: /
title: "About Me"
excerpt: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an incoming postdoctoral researcher in the Center for Applied Scientific Computing at Lawrence Livermore National Laboratory. I recently completed my PhD in applied mathematics at CU Boulder, where I worked with Prof. Alireza Doostan and studied matrix methods for dimensionality reduction of large datasets.  

Prior to CU, I completed my undergraduate degree in mathematics at Harvey Mudd College in Claremont, California. I did my senior thesis with Prof. Andrew Bernoff, under whose mentorship I developed methods using algebraic topology to identify persistent topological structures in dynamical systems.  

A common theme connecting my work back to my days at Mudd is using data-driven approaches to study physical systems, especially when doing so relies on rigorous mathematical theory. I have always been particularly interested in identifying low-dimensional features in high-dimensional datasets. The applications of my work vary from clustering and visualization to data compression.

Current Research Interests 
======

The following topics encapsulate most of the work I've done as a PhD student at CU and my two summer internships at Lawrence Livermore National Laboratory.

Nonlinear Dimensionality Reduction 
------

My current research can be found under the buzzword umbrella of scientific machine learning (SciML) and is centered on using nonlinear approaches such as Kernel Principal Component Analysis (Kernel PCA) and a class of neural networks called autoencoders for data compression in large-scale scientific applications. These techniques possess significant advantages over analogous linear approaches like PCA and matrix interpolative decomposition (ID) when the problem of concern features sharp nonlinearities, e.g., shock solutions obtained in the modeling of hypersonics.

Linear Dimensionality Reduction 
------

A lot of the work I did earlier on in my PhD was concerned with developing linear low-rank matrix approximation methods for compression of scientific data. I've built memory- and pass-efficient algorithms for computing the singular value decomposition (SVD) and ID of matrices arising in the simulation of turbulent flows. 

Online Algorithms 
------

Across my projects, whether the goal is compressing data or identifying clusters in large-scale graphs, I am interested in building algorithms that achieve performant results having seen their input once, i.e., online algorithms. When the data we have to process exceeds available RAM -- or even disk memory -- we want to minimize the number of passes we make over our input and the associated costs of memory movement. Online approaches help us address this concern.

Matrix Sketching
------

Matrix sketching has played a central role in almost all of my research as a PhD student. Matrix sketching is a linear dimensionality reduction technique wherein a large-scale data matrix is embedded in a lower dimension via application of a linear operator. If this linear operator is constructed properly, the resulting sketch matrix will preserve important geometric properties of the input matrix in a significantly lower dimensional space. 

Applications
======

The research I have conducted as a graduate student has myriad applications, two of which I address directly in my publications: data compression and graph clustering. 

Data Compression
------

Linear and nonlinear dimensionality reduction methods can be used to embed large data matrices in low-dimensional spaces. In the linear case, this takes the form of, e.g., a low-rank approximation; in the nonlinear setting, generalized coordinates corresponding to the low-dimensional manifold on which the data lives. The embedded data, along with the approximate reconstruction mapping, constitute a compressed format of the input data. For more information on this, please see the following [paper](http://alecmdunton.github.io/files/pass_efficient.pdf).

Community Detection in Networks
------

Matrix sketching, coupled with nonlinear dimensionality reduction methods like Uniform Manifold Approximation and Projection (UMAP), enables online clustering of large-scale graphs stored in distributed memory. The linear-nonlinear hybrid approach takes advantages of the efficiency of linear matrix sketches and nonlinear structures identified by manifold learning methods like UMAP. For more information on this, please see the following paper:


