---
layout: post
title: "PSDF Fusion: Probabilistic Signed Distance Function for On-the-fly 3D Data Fusion and Scene Reconstruction"
date: 2018-07-29 10:10:12
categories: arXiv_CV
tags: arXiv_CV Face
author: Wei Dong, Qiuyuan Wang, Xin Wang, Hongbin Zha
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel 3D spatial representation for data fusion and scene reconstruction. Probabilistic Signed Distance Function (Probabilistic SDF, PSDF) is proposed to depict uncertainties in the 3D space. It is modeled by a joint distribution describing SDF value and its inlier probability, reflecting input data quality and surface geometry. A hybrid data structure involving voxel, surfel, and mesh is designed to fully exploit the advantages of various prevalent 3D representations. Connected by PSDF, these components reasonably cooperate in a consistent frame- work. Given sequential depth measurements, PSDF can be incrementally refined with less ad hoc parametric Bayesian updating. Supported by PSDF and the efficient 3D data representation, high-quality surfaces can be extracted on-the-fly, and in return contribute to reliable data fu- sion using the geometry information. Experiments demonstrate that our system reconstructs scenes with higher model quality and lower redundancy, and runs faster than existing online mesh generation systems.

##### Abstract (translated by Google)
我们提出了一种用于数据融合和场景重建的新型3D空间表示。提出概率符号距离函数（概率SDF，PSDF）来描述3D空间中的不确定性。它由描述SDF值及其内部概率的联合分布建模，反映输入数据质量和表面几何。涉及体素，表面和网格的混合数据结构被设计为充分利用各种流行的3D表示的优点。通过PSDF连接，这些组件在一致的框架中合理地协作。给定顺序深度测量，可以使用较少的自组织参数贝叶斯更新来逐步细化PSDF。在PSDF和高效的3D数据表示的支持下，可以即时提取高质量的表面，并使用几何信息提供可靠的数据融合。实验表明，我们的系统可以重建具有更高模型质量和更低冗余度的场景，并且比现有的在线网格生成系统运行得更快。

##### URL
[http://arxiv.org/abs/1807.11034](http://arxiv.org/abs/1807.11034)

##### PDF
[http://arxiv.org/pdf/1807.11034](http://arxiv.org/pdf/1807.11034)

