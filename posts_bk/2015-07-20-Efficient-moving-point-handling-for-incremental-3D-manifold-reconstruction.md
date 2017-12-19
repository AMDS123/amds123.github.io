---
layout: post
title: "Efficient moving point handling for incremental 3D manifold reconstruction"
date: 2015-07-20 13:38:02
categories: arXiv_CV
tags: arXiv_CV Sparse
author: Andrea Romanoni, Matteo Matteucci
mathjax: true
---

* content
{:toc}

##### Abstract
As incremental Structure from Motion algorithms become effective, a good sparse point cloud representing the map of the scene becomes available frame-by-frame. From the 3D Delaunay triangulation of these points, state-of-the-art algorithms build a manifold rough model of the scene. These algorithms integrate incrementally new points to the 3D reconstruction only if their position estimate does not change. Indeed, whenever a point moves in a 3D Delaunay triangulation, for instance because its estimation gets refined, a set of tetrahedra have to be removed and replaced with new ones to maintain the Delaunay property; the management of the manifold reconstruction becomes thus complex and it entails a potentially big overhead. In this paper we investigate different approaches and we propose an efficient policy to deal with moving points in the manifold estimation process. We tested our approach with four sequences of the KITTI dataset and we show the effectiveness of our proposal in comparison with state-of-the-art approaches.

##### Abstract (translated by Google)
随着来自运动算法的增量结构变得有效，代表场景映射的良好稀疏点云逐渐变为可用。从这些点的三维Delaunay三角剖分中，最先进的算法构建了一个场景的流形粗糙模型。这些算法只有在位置估计值没有变化的情况下，才会逐渐将新的点集成到三维重建中。事实上，每当一个点在三维Delaunay三角测量中移动，例如因为它的估计得到了改进，一组四面体不得不被移除，并用新的三角面体代替以保持Delaunay性质;歧管重建的管理变得如此复杂，并且带来潜在的巨大开销。在本文中，我们研究不同的方法，我们提出一个有效的策略来处理流形估计过程中的移动点。我们用KITTI数据集的四个序列测试了我们的方法，并且与最先进的方法相比，我们展示了我们提议的有效性。

##### URL
[https://arxiv.org/abs/1507.05489](https://arxiv.org/abs/1507.05489)

##### PDF
[https://arxiv.org/pdf/1507.05489](https://arxiv.org/pdf/1507.05489)

