---
layout: post
title: "Real-time CPU-based large-scale 3D mesh reconstruction"
date: 2018-01-16 12:49:04
categories: arXiv_RO
tags: arXiv_RO Sparse SLAM
author: Enrico Piazza, Andrea Romanoni, Matteo Matteucci
mathjax: true
---

* content
{:toc}

##### Abstract
In Robotics, especially in this era of autonomous driving, mapping is one key ability of a robot to be able to navigate through an environment, localize on it and analyze its traversability. To allow for real-time execution on constrained hardware, the map usually estimated by feature-based or semi-dense SLAM algorithms is a sparse point cloud; a richer and more complete representation of the environment is desirable. Existing dense mapping algorithms require extensive use of GPU computing and they hardly scale to large environments; incremental algorithms from sparse points still represent an effective solution when light computational effort is needed and big sequences have to be processed in real-time. In this paper we improved and extended the state of the art incremental manifold mesh algorithm proposed in [1] and extended in [2]. While these algorithms do not achieve real-time and they embed points from SLAM or Structure from Motion only when their position is fixed, in this paper we propose the first incremental algorithm able to reconstruct a manifold mesh in real-time through single core CPU processing which is also able to modify the mesh according to 3D points updates from the underlying SLAM algorithm. We tested our algorithm against two state of the art incremental mesh mapping systems on the KITTI dataset, and we showed that, while accuracy is comparable, our approach is able to reach real-time performances thanks to an order of magnitude speed-up.

##### Abstract (translated by Google)
在机器人领域，特别是在这个自主驾驶的时代，绘图是机器人能够在环境中导航，定位并分析其穿越能力的关键能力之一。为了允许在受限硬件上实时执行，通常由基于特征或半密集SLAM算法估计的映射是稀疏点云;一个更丰富和更完整的环境代表是可取的。现有的密集映射算法需要广泛使用GPU计算，并且难以扩展到大的环境;当需要轻量计算时，来自稀疏点的增量算法仍然是一个有效的解决方案，并且需要实时处理大的序列。在本文中，我们对[1]中提出并在[2]中进行了扩展的现有技术增量流形网格算法进行了改进和扩展。虽然这些算法并没有实时实现，但是只有当它们的位置是固定的，它们才从SLAM或Structure from Motion中嵌入点，本文中我们提出了第一种能够通过单核CPU处理来实时重构流形网格的增量算法也可以根据底层SLAM算法的三维点更新修改网格。我们使用KITTI数据集上的两个最先进的增量网格映射系统测试了我们的算法，并且我们证明，虽然精度是可比的，但是我们的方法能够实现实时性能，这要归功于数量级的加速。

##### URL
[http://arxiv.org/abs/1801.05230](http://arxiv.org/abs/1801.05230)

##### PDF
[http://arxiv.org/pdf/1801.05230](http://arxiv.org/pdf/1801.05230)

