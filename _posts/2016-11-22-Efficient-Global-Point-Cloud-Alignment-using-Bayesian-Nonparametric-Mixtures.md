---
layout: post
title: "Efficient Global Point Cloud Alignment using Bayesian Nonparametric Mixtures"
date: 2016-11-22 03:46:37
categories: arXiv_CV
tags: arXiv_CV Face Optimization Recognition
author: Julian Straub, Trevor Campbell, Jonathan P. How, John W. Fisher III
mathjax: true
---

* content
{:toc}

##### Abstract
Point cloud alignment is a common problem in computer vision and robotics, with applications ranging from 3D object recognition to reconstruction. We propose a novel approach to the alignment problem that utilizes Bayesian nonparametrics to describe the point cloud and surface normal densities, and branch and bound (BB) optimization to recover the relative transformation. BB uses a novel, refinable, near-uniform tessellation of rotation space using 4D tetrahedra, leading to more efficient optimization compared to the common axis-angle tessellation. We provide objective function bounds for pruning given the proposed tessellation, and prove that BB converges to the optimum of the cost function along with providing its computational complexity. Finally, we empirically demonstrate the efficiency of the proposed approach as well as its robustness to real-world conditions such as missing data and partial overlap.

##### Abstract (translated by Google)
点云对准是计算机视觉和机器人技术中的一个常见问题，其应用范围从三维物体识别到重建。我们提出了一种利用贝叶斯非参数来描述点云和表面正常密度以及分支和边界（BB）优化来恢复相对变换的对齐问题的新方法。 BB使用四维四面体进行旋转空间的新颖，可细化，接近均匀的细分，从而导致与常见的轴角镶嵌相比更高效的优化。给出了所提出的细化算法，给出了修剪的目标函数界，并证明了BB收敛于代价函数的最优值，并提供了计算复杂度。最后，我们凭经验论证了所提出的方法的有效性以及其对实际情况的稳健性，如缺失数据和部分重叠。

##### URL
[https://arxiv.org/abs/1603.04868](https://arxiv.org/abs/1603.04868)

##### PDF
[https://arxiv.org/pdf/1603.04868](https://arxiv.org/pdf/1603.04868)

