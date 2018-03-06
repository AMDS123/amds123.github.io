---
layout: post
title: "Elastic LiDAR Fusion: Dense Map-Centric Continuous-Time SLAM"
date: 2018-03-05 04:45:33
categories: arXiv_RO
tags: arXiv_RO Face Optimization SLAM
author: Chanoh Park, Peyman Moghadam, Soohwan Kim, Alberto Elfes, Clinton Fookes, Sridha Sridharan
mathjax: true
---

* content
{:toc}

##### Abstract
The concept of continuous-time trajectory representation has brought increased accuracy and efficiency to multi-modal sensor fusion in modern SLAM. However, regardless of these advantages, its offline property caused by the requirement of global batch optimization is critically hindering its relevance for real-time and life-long applications. In this paper, we present a dense map-centric SLAM method based on a continuous-time trajectory to cope with this problem. The proposed system locally functions in a similar fashion to conventional Continuous-Time SLAM (CT-SLAM). However, it removes the need for global trajectory optimization by introducing map deformation. The computational complexity of the proposed approach for loop closure does not depend on the operation time, but only on the size of the space it explored before the loop closure. It is therefore more suitable for long term operation compared to the conventional CT-SLAM. Furthermore, the proposed method reduces uncertainty in the reconstructed dense map by using probabilistic surface element (surfel) fusion. We demonstrate that the proposed method produces globally consistent maps without global batch trajectory optimization, and effectively reduces LiDAR noise by surfel fusion.

##### Abstract (translated by Google)
连续时间轨迹表示的概念为现代SLAM中的多模态传感器融合带来了更高的精度和效率。但是，无论这些优势如何，其全球批量优化要求所导致的离线属性严重阻碍了其与实时和终身应用程序的相关性。在本文中，我们提出了一个基于连续时间轨迹的密集的以地图为中心的SLAM方法来解决这个问题。所提出的系统在本地以与常规连续时间SLAM（CT-SLAM）相似的方式运行。但是，它通过引入地图变形消除了对全球轨迹优化的需求。所提出的闭环方法的计算复杂性不取决于操作时间，而仅取决于在闭环之前探测的空间的大小。因此，与传统的CT-SLAM相比，它更适合于长期操作。此外，所提出的方法通过使用概率表面元素（surfel）融合来减少重构密集图中的不确定性。我们证明了所提出的方法在没有全局批量轨迹优化的情况下产生全局一致的地图，并且通过surfel融合有效地减少了LiDAR噪声。

##### URL
[http://arxiv.org/abs/1711.01691](http://arxiv.org/abs/1711.01691)

##### PDF
[http://arxiv.org/pdf/1711.01691](http://arxiv.org/pdf/1711.01691)

