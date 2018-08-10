---
layout: post
title: "Efficient Outlier Removal for Large Scale Global Structure-from-Motion"
date: 2018-08-09 07:05:18
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
这项工作解决了大规模全局动态结构中的异常值去除问题。在这样的应用中，全局异常值去除对于减轻由特征点匹配步骤中的不匹配引起的恶化非常有用。与现有的异常值去除方法不同，我们利用多视图几何问题中的结构来提出尺寸减小的公式，基于此已经开发了两种方法。第一种方法考虑凸松弛$ \ ell_1 $最小化并通过单个线性规划（LP）求解，而第二种方法通过迭代重加权方法近似解决理想的$ \ ell_0 $最小化。降维导致新算法的显着加速。此外，迭代重加权方法可以显着降低去除真实内点的可能性。逼真的多视图重建实验表明，与最先进的算法相比，新算法效率更高，同时可以提供更好的解决方案。用于复制结果的Matlab代码可在\ textit {https://github.com/FWen/OUTLR.git}获得。

##### URL
[http://arxiv.org/abs/1808.03041](http://arxiv.org/abs/1808.03041)

##### PDF
[http://arxiv.org/pdf/1808.03041](http://arxiv.org/pdf/1808.03041)

