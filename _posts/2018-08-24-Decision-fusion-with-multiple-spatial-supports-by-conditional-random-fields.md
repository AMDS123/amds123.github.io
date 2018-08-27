---
layout: post
title: "Decision fusion with multiple spatial supports by conditional random fields"
date: 2018-08-24 06:52:50
categories: arXiv_CV
tags: arXiv_CV Regularization Classification Prediction
author: Devis Tuia, Michele Volpi, Gabriele Moser
mathjax: true
---

* content
{:toc}

##### Abstract
Classification of remotely sensed images into land cover or land use is highly dependent on geographical information at least at two levels. First, land cover classes are observed in a spatially smooth domain separated by sharp region boundaries. Second, land classes and observation scale are also tightly intertwined: they tend to be consistent within areas of homogeneous appearance, or regions, in the sense that all pixels within a roof should be classified as roof, independently on the spatial support used for the classification. In this paper, we follow these two observations and encode them as priors in an energy minimization framework based on conditional random fields (CRFs), where classification results obtained at pixel and region levels are probabilistically fused. The aim is to enforce the final maps to be consistent not only in their own spatial supports (pixel and region) but also across supports, i.e., by getting the predictions on the pixel lattice and on the set of regions to agree. To this end, we define an energy function with three terms: 1) a data term for the individual elements in each support (support-specific nodes); 2) spatial regularization terms in a neighborhood for each of the supports (support-specific edges); and 3) a regularization term between individual pixels and the region containing each of them (intersupports edges). We utilize these priors in a unified energy minimization problem that can be optimized by standard solvers. The proposed 2LCRF model consists of a CRF defined over a bipartite graph, i.e., two interconnected layers within a single graph accounting for interlattice connections.

##### Abstract (translated by Google)
将遥感图像分类为土地覆盖或土地利用在很大程度上取决于地理信息，至少在两个层面。首先，在由尖锐区域边界分隔的空间平滑区域中观察到土地覆盖类别。其次，土地类别和观察尺度也紧密相连：它们倾向于在均匀外观或区域范围内保持一致，即屋顶内的所有像素都应归类为屋顶，独立于用于分类的空间支撑。在本文中，我们遵循这两个观察，并在基于条件随机场（CRF）的能量最小化框架中将它们编码为先验，其中在像素和区域水平获得的分类结果是概率融合的。目的是强制最终的地图不仅在它们自己的空间支持（像素和区域）中而且在支持物之间是一致的，即，通过使像素点阵上的预测和区域集合达成一致。为此，我们用三个术语定义能量函数：1）每个支持中的各个元素的数据项（支持特定节点）; 2）每个支持的邻域中的空间正则化项（支持特定边）; 3）各个像素和包含它们中的每个像素的区域之间的正则化项（间隔边缘）。我们将这些先验用于统一的能量最小化问题，可以通过标准求解器进行优化。所提出的2LCRF模型由在二分图上定义的CRF组成，即，在单个图中的两个互连层，用于解释层间连接。

##### URL
[http://arxiv.org/abs/1808.08024](http://arxiv.org/abs/1808.08024)

##### PDF
[http://arxiv.org/pdf/1808.08024](http://arxiv.org/pdf/1808.08024)

