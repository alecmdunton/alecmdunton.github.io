---
permalink: /
title: "About Me"
excerpt: "Home"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate in the Department of Applied Mathematics at the University of Colorado Boulder expecting to finish this summer. I work with Dr. Alireza Doostan and am a member of the Uncertainty Quantification, Learning, and Estimation from Data (UQLED) Group. 

Prior to CU, I completed my undergraduate degree in mathematics at Harvey Mudd College in Claremont, California. I did my senior thesis with Dr. Andrew Bernoff, in which I developed methods using algebraic topology to identify persistent topological structures in dynamical systems.  

A common theme connecting my work back to my days at Mudd is identifying low-dimensional features in high-dimensional datasets. The applications of my work have varied from clustering and visualization to data compression. However, I have always been interested in using data-driven approaches to study physical systems, especially when doing so relies on rigorous mathematical theory. 

Research Interests 
======

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
