---
layout: post
title: "Realtime Hierarchical Clustering based on Boundary and Surface Statistics"
date: 2016-09-22 10:17:30
categories: arXiv_CV
tags: arXiv_CV Face RNN Recognition
author: Dominik Alexander Klein, Dirk Schulz, Armin Bernd Cremers
mathjax: true
---

* content
{:toc}

##### Abstract
Visual grouping is a key mechanism in human scene perception. There, it belongs to the subconscious, early processing and is key prerequisite for other high level tasks such as recognition. In this paper, we introduce an efficient, realtime capable algorithm which likewise agglomerates a valuable hierarchical clustering of a scene, while using purely local appearance statistics. To speed up the processing, first we subdivide the image into meaningful, atomic segments using a fast Watershed transform. Starting from there, our rapid, agglomerative clustering algorithm prunes and maintains the connectivity graph between clusters to contain only such pairs, which directly touch in the image domain and are reciprocal nearest neighbors (RNN) wrt. a distance metric. The core of this approach is our novel cluster distance: it combines boundary and surface statistics both in terms of appearance as well as spatial linkage. This yields state-of-the-art performance, as we demonstrate in conclusive experiments conducted on BSDS500 and Pascal-Context datasets.

##### Abstract (translated by Google)
视觉分组是人类视觉感知的关键机制。在那里，它属于潜意识，早期处理，是识别等其他高级任务的关键先决条件。在本文中，我们引入了一个高效的，实时的算法，它同样聚集了一个有价值的场景层次聚类，同时使用纯粹的局部外观统计。为了加速处理，首先使用快速分水岭变换将图像细分为有意义的原子段。从那里开始，我们的快速凝聚聚类算法修剪和维护聚类之间的连通图，只包含这些对，它们直接在图像域中接触，是互逆最近邻（RNN）。距离度量。这种方法的核心是我们的新颖的聚类距离：它在外观和空间联系方面结合了边界和表面统计。这产生了最先进的性能，正如我们在BSDS500和Pascal-Context数据集上进行的最终实验中所证明的那样。

##### URL
[https://arxiv.org/abs/1609.06896](https://arxiv.org/abs/1609.06896)

##### PDF
[https://arxiv.org/pdf/1609.06896](https://arxiv.org/pdf/1609.06896)

