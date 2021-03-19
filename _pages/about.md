---
permalink: /
title: "Bio"
excerpt: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a 5th year graduate student in the Department of Applied Mathematics at the University of Colorado Boulder. I work with Dr. Alireza Doostan and am a member of the Uncertainty Quantification, Learning, and Estimation from Data (UQLED) Group.

Research Interests 
======

Nonlinear Dimensionality Reduction 
------

My current research can be found under the buzzword umbrella of scientific machine learning (SciML) and is centered on using nonlinear approaches such as Kernel Principal Component Analysis (Kernel PCA) and a type of neural network called an autoencoder for data compression in scientific applications. These techniques possess significant advantages over analogous linear approaches like PCA and matrix interpolative decomposition (ID) when the problem of concern features sharp nonlinearities, e.g., shock solutions obtained in the modeling of hypersonics.

Linear Dimensionality Reduction 
------

A lot of the work I did earlier on in my PhD was concerned with using linear low-rank matrix approximation methods for compression of scientific data. I've developed memory- and pass-efficient algorithms for computing the singular value decomposition (SVD) and ID of matrices arising in the simulation of turbulent flows. 

Online Algorithms 
------

Across my projects, whether the goal is compressing data or identifying clusters in large-scale graphs, I am interested in building algorithms that achieve performant results having seen their input once, i.e, online algorithms. When the data we have to process exceeds available RAM -- or even disk memory -- we want to minimize the number of passes we make over our input and the associated costs of memory movement. Online approaches help us address this concern.



Matrix Sketching
------

Matrix sketching is a linear dimensionality reduction technique wherein a large-scale data matrix is embedded in a lower dimension via application of a linear operator. If this linear operator is constructed properly, the resulting sketch matrix will preserve important geometric properties of the input matrix in a significantly lower dimensional space. 
