---
layout: post
title: "Multi-body Non-rigid Structure-from-Motion"
date: 2016-07-15 14:04:30
categories: arXiv_CV
tags: arXiv_CV Sparse Optimization
author: Suryansh Kumar, Yuchao Dai, Hongdong Li
mathjax: true
---

* content
{:toc}

##### Abstract
Conventional structure-from-motion (SFM) research is primarily concerned with the 3D reconstruction of a single, rigidly moving object seen by a static camera, or a static and rigid scene observed by a moving camera --in both cases there are only one relative rigid motion involved. Recent progress have extended SFM to the areas of {multi-body SFM} (where there are {multiple rigid} relative motions in the scene), as well as {non-rigid SFM} (where there is a single non-rigid, deformable object or scene). Along this line of thinking, there is apparently a missing gap of "multi-body non-rigid SFM", in which the task would be to jointly reconstruct and segment multiple 3D structures of the multiple, non-rigid objects or deformable scenes from images. Such a multi-body non-rigid scenario is common in reality (e.g. two persons shaking hands, multi-person social event), and how to solve it represents a natural {next-step} in SFM research. By leveraging recent results of subspace clustering, this paper proposes, for the first time, an effective framework for multi-body NRSFM, which simultaneously reconstructs and segments each 3D trajectory into their respective low-dimensional subspace. Under our formulation, 3D trajectories for each non-rigid structure can be well approximated with a sparse affine combination of other 3D trajectories from the same structure (self-expressiveness). We solve the resultant optimization with the alternating direction method of multipliers (ADMM). We demonstrate the efficacy of the proposed framework through extensive experiments on both synthetic and real data sequences. Our method clearly outperforms other alternative methods, such as first clustering the 2D feature tracks to groups and then doing non-rigid reconstruction in each group or first conducting 3D reconstruction by using single subspace assumption and then clustering the 3D trajectories into groups.

##### Abstract (translated by Google)
传统的运动结构（SFM）研究主要涉及静态摄像机看到的单个刚性移动物体的三维重建，或移动摄像机观察到的静态和刚性场景 - 在这两种情况下，只有一个涉及相对僵硬的运动。最近的进展已经将SFM延伸到{多体SFM}（在场景中存在{多个刚性}相对运动）以及{非刚性SFM}（其中存在单个非刚性可变形对象或场景）。沿着这一思路，显然有一个“多体非刚性SFM”的缺失，其中的任务是从图像中共同重建和分割多个非刚性物体或可变形场景的多个三维结构。这种多体非刚性的情景在现实中很常见（如两人握手，多人社交活动），如何解决这个问题代表了SFM研究中的一个自然的下一步。通过利用子空间聚类的最新成果，本文首次提出了多体NRSFM的有效框架，该框架同时将每个三维轨迹重构和分割成各自的低维子空间。根据我们的公式，每个非刚性结构的三维轨迹可以很好地用相同结构（自我表现）的其他三维轨迹的稀疏仿射组合来逼近。我们利用乘法器的交替方向法（ADMM）来求解最终的优化。我们通过对合成和实际数据序列进行广泛的实验来证明所提出的框架的功效。我们的方法明显优于其他替代方法，例如首先将2D特征轨道聚类到组，然后在每个组中进行非刚性重构，或者首先使用单子空间假设进行3D重建，然后将3D轨迹聚类为组。

##### URL
[https://arxiv.org/abs/1607.04515](https://arxiv.org/abs/1607.04515)

##### PDF
[https://arxiv.org/pdf/1607.04515](https://arxiv.org/pdf/1607.04515)

