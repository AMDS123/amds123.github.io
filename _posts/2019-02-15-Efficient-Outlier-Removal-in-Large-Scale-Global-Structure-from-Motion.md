---
layout: post
title: "Efficient Outlier Removal in Large Scale Global Structure-from-Motion"
date: 2019-02-15 08:03:37
categories: arXiv_CV
tags: arXiv_CV
author: Fei Wen, Danping Zou, Rendong Ying, Peilin Liu
mathjax: true
---

* content
{:toc}

##### Abstract
This work addresses the outlier removal problem in large-scale global structure-from-motion. In such applications, global outlier removal is very useful to mitigate the deterioration caused by mismatches in the feature point matching step. Unlike existing outlier removal methods, we exploit the structure in multiview geometry problems to propose a dimension reduced formulation, based on which two methods have been developed. The first method considers a convex relaxed $\ell_1$ minimization and is solved by a single linear programming (LP), whilst the second one approximately solves the ideal $\ell_0$ minimization by an iteratively reweighted method. The dimension reduction results in a significant speedup of the new algorithms. Further, the iteratively reweighted method can significantly reduce the possibility of removing true inliers. Realistic multiview reconstruction experiments demonstrated that, compared with state-of-the-art algorithms, the new algorithms are much more efficient and meanwhile can give improved solution. Matlab code for reproducing the results is available at \textit{https://github.com/FWen/OUTLR.git}.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1808.03041](http://arxiv.org/abs/1808.03041)

##### PDF
[http://arxiv.org/pdf/1808.03041](http://arxiv.org/pdf/1808.03041)

