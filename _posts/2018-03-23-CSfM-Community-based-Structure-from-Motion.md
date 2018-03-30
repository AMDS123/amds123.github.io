---
layout: post
title: "CSfM: Community-based Structure from Motion"
date: 2018-03-23 10:27:01
categories: arXiv_CV
tags: arXiv_CV Optimization
author: Hainan Cui, Shuhan Shen, Xiang Gao, Zhanyi Hu
mathjax: true
---

* content
{:toc}

##### Abstract
Structure-from-Motion approaches could be broadly divided into two classes: incremental and global. While incremental manner is robust to outliers, it suffers from error accumulation and heavy computation load. The global manner has the advantage of simultaneously estimating all camera poses, but it is usually sensitive to epipolar geometry outliers. In this paper, we propose an adaptive community-based SfM (CSfM) method which takes both robustness and efficiency into consideration. First, the epipolar geometry graph is partitioned into separate communities. Then, the reconstruction problem is solved for each community in parallel. Finally, the reconstruction results are merged by a novel global similarity averaging method, which solves three convex $L1$ optimization problems. Experimental results show that our method performs better than many of the state-of-the-art global SfM approaches in terms of computational efficiency, while achieves similar or better reconstruction accuracy and robustness than many of the state-of-the-art incremental SfM approaches.

##### Abstract (translated by Google)
动态结构方法大致可以分为两类：增量式和全局式。虽然增量式方法对异常值具有鲁棒性，但会受到误差累积和大量计算负担的影响。全局方式具有同时估计所有相机姿态的优点，但它通常对极外几何异常值很敏感。在本文中，我们提出了一个基于自适应社区的SfM（CSfM）方法，该方法既考虑到鲁棒性又考虑效率。首先，极线几何图形被划分为不同的社区。然后，并行解决每个社区的重建问题。最后，重建结果由一种新颖的全局相似性平均方法合并，该方法解决了三个凸$ L1 $优化问题。实验结果表明，我们的方法在计算效率方面比许多先进的全球SfM方法执行得更好，同时获得了与许多现有技术增量SfM相似或更好的重构精度和鲁棒性方法。

##### URL
[https://arxiv.org/abs/1803.08716](https://arxiv.org/abs/1803.08716)

##### PDF
[https://arxiv.org/pdf/1803.08716](https://arxiv.org/pdf/1803.08716)

