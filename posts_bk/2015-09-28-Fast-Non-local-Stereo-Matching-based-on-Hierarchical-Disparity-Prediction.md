---
layout: post
title: "Fast Non-local Stereo Matching based on Hierarchical Disparity Prediction"
date: 2015-09-28 05:00:01
categories: arXiv_CV
tags: arXiv_CV Prediction
author: Xuan Luo, Xuejiao Bai, Shuo Li, Hongtao Lu, Sei-ichiro Kamata
mathjax: true
---

* content
{:toc}

##### Abstract
Stereo matching is the key step in estimating depth from two or more images. Recently, some tree-based non-local stereo matching methods have been proposed, which achieved state-of-the-art performance. The algorithms employed some tree structures to aggregate cost and thus improved the performance and reduced the coputation load of the stereo matching. However, the computational complexity of these tree-based algorithms is still high because they search over the entire disparity range. In addition, the extreme greediness of the minimum spanning tree (MST) causes the poor performance in large areas with similar colors but varying disparities. In this paper, we propose an efficient stereo matching method using a hierarchical disparity prediction (HDP) framework to dramatically reduce the disparity search range so as to speed up the tree-based non-local stereo methods. Our disparity prediction scheme works on a graph pyramid derived from an image whose disparity to be estimated. We utilize the disparity of a upper graph to predict a small disparity range for the lower graph. Some independent disparity trees (DT) are generated to form a disparity prediction forest (HDPF) over which the cost aggregation is made. When combined with the state-of-the-art tree-based methods, our scheme not only dramatically speeds up the original methods but also improves their performance by alleviating the second drawback of the tree-based methods. This is partially because our DTs overcome the extreme greediness of the MST. Extensive experimental results on some benchmark datasets demonstrate the effectiveness and efficiency of our framework. For example, the segment-tree based stereo matching becomes about 25.57 times faster and 2.2% more accurate over the Middlebury 2006 full-size dataset.

##### Abstract (translated by Google)
立体匹配是估计来自两个或更多图像的深度的关键步骤。近来，已经提出了一些基于树的非局部立体匹配方法，其实现了最新的性能。该算法采用了一些树型结构来聚合成本，从而提高了性能，减少了立体匹配的交叉负担。然而，这些基于树的算法的计算复杂度仍然很高，因为它们搜索整个视差范围。另外，最小生成树（MST）的极端贪婪性导致在具有相似颜色但差异性不同的大区域中性能差。在本文中，我们提出了一种高效的立体匹配方法，使用层次视差预测（HDP）框架来显着降低视差搜索范围，从而加速基于树的非局部立体方法。我们的视差预测方案在从要估计视差的图像导出的图金字塔上工作。我们利用上图的差异来预测下图的小差异范围。生成一些独立的视差树（DT）以形成在其上进行成本聚集的视差预测森林（HDPF）。结合最先进的基于树的方法，我们的方案不仅大大加快了原有的方法，而且通过缓解基于树的方法的第二个缺点，提高了它们的性能。这部分是因为我们的DT克服了MST的极度贪婪。一些基准数据集的广泛的实验结果证明了我们框架的有效性和有效性。例如，基于分段树的立体匹配比Middlebury 2006全尺寸数据集快25.57倍，精度提高2.2％。

##### URL
[https://arxiv.org/abs/1509.08197](https://arxiv.org/abs/1509.08197)

##### PDF
[https://arxiv.org/pdf/1509.08197](https://arxiv.org/pdf/1509.08197)

