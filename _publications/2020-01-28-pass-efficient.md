---
title: "Pass-efficient methods for compression of high dimensional turbulent flow data"
collection: publications
permalink: /publications/2020-01-28-pass-efficient
excerpt: 'The future of high-performance computing, specifically on future Exascale computers, will presumably seememory capacity and bandwidth fail to keep pace with data generated, for instance, from massively parallelpartial differential equation (PDE) systems.  Current strategies proposed to address this bottleneck entailthe  omission  of  large  fractions  of  data,  as  well  as  the  incorporation  ofin situcompression  algorithms  toavoid overuse of memory.  To ensure that post-processing operations are successful,  this must be done ina way that a sufficiently accurate representation of the solution is stored.  Moreover,  in situations wherethe input/output system becomes a bottleneck in analysis, visualization, etc., or the execution of the PDEsolver  is  expensive,  the  the  number  of passes  made  over the  data  must  be  minimized.   In the  interest  ofaddressing this problem,  this work focuses on the utility of pass-efficient,  parallelizable, low-rank,  matrixdecomposition methods in compressing high-dimensional simulation data from turbulent flows.  A particularemphasis is placed on using coarse representation of the data – compatible with the PDE discretization grid –to accelerate the construction of the low-rank factorization.  This includes the presentation of a novel single-pass matrix decomposition algorithm for computing the so-called interpolative decomposition.  The methodsare described extensively and numerical experiments on two turbulent channel flow data are performed.  Inthe  first  (unladen)  channel  flow  case,  compression  factors  exceeding  400  are  achieved  while  maintainingaccuracy  with  respect  to  first-  and  second-order  flow  statistics.   In  the  particle-laden  case,  compressionfactors of 100 are achieved and the compressed data is used to recover particle velocities.  These results showthat these compression methods can enable efficient computation of various quantities of interest in boththe carrier and disperse phases.'
date: 2020-01-28
venue: 'Journal of Computational Physics'
paperurl: 'http://alecmdunton.github.io/files/pass_efficient.pdf'
---


[Download paper here](http://alecmdunton.github.io/files/pass_efficient.pdf)
