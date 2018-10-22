---
layout: post
title: "Fast Graph-Cut Based Optimization for Practical Dense Deformable Registration of Volume Images"
date: 2018-10-19 10:09:54
categories: arXiv_CV
tags: arXiv_CV Segmentation Optimization
author: Simon Ekstr&#xf6;m, Filip Malmberg, H&#xe5;kan Ahlstr&#xf6;m, Joel Kullberg, Robin Strand
mathjax: true
---

* content
{:toc}

##### Abstract
Objective: Deformable image registration is a fundamental problem in medical image analysis, with applications such as longitudinal studies, population modeling, and atlas based image segmentation. Registration is often phrased as an optimization problem, i.e., finding a deformation field that is optimal according to a given objective function. Discrete, combinatorial, optimization techniques have successfully been employed to solve the resulting optimization problem. Specifically, optimization based on $\alpha$-expansion with minimal graph cuts has been proposed as a powerful tool for image registration. The high computational cost of the graph-cut based optimization approach, however, limits the utility of this approach for registration of large volume images. Methods: Here, we propose to accelerate graph-cut based deformable registration by dividing the image into overlapping sub-regions and restricting the $\alpha$-expansion moves to a single sub-region at a time. Results: We demonstrate empirically that this approach can achieve a large reduction in computation time -- from days to minutes -- with only a small penalty in terms of solution quality. Conclusion: The reduction in computation time provided by the proposed method makes graph cut based deformable registration viable for large volume images. Significance: Graph cut based image registration has previously been shown to produce excellent results, but the high computational cost has hindered the adoption of the method for registration of large medical volume images. Our proposed method lifts this restriction, requiring only a small fraction of the computational cost to produce results of comparable quality.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.08427](http://arxiv.org/abs/1810.08427)

##### PDF
[http://arxiv.org/pdf/1810.08427](http://arxiv.org/pdf/1810.08427)

