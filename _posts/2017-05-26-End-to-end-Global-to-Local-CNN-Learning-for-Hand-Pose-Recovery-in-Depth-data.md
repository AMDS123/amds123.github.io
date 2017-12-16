---
layout: post
title: "End-to-end Global to Local CNN Learning for Hand Pose Recovery in Depth data"
date: 2017-05-26 14:55:44
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Relation
author: Meysam Madadi, Sergio Escalera, Xavier Baro, Jordi Gonzalez
mathjax: true
---

* content
{:toc}

##### Abstract
Despite recent advances in 3D pose estimation of human hands, especially thanks to the advent of CNNs and depth cameras, this task is still far from being solved. This is mainly due to the highly non-linear dynamics of fingers, which makes hand model training a challenging task. In this paper, we exploit a novel hierarchical tree-like structured CNN, in which branches are trained to become specialized in predefined subsets of hand joints, called local poses. We further fuse local pose features, extracted from hierarchical CNN branches, to learn higher order dependencies among joints in the final pose by end-to-end training. Lastly, the loss function used is also defined to incorporate appearance and physical constraints about doable hand motion and deformation. Experimental results suggest that feeding a tree-shaped CNN, specialized in local poses, into a fusion network for modeling joints correlations, helps to increase the precision of final estimations, outperforming state-of-the-art results on NYU and MSRA datasets.

##### Abstract (translated by Google)
尽管人类手部三维姿态估计的最新进展，尤其是感谢CNN和深度相机的出现，但这项任务还远远没有得到解决。这主要是由于手指的高度非线性动力学，这使得手模型训练成为具有挑战性的任务。在本文中，我们利用一种新型的分层树状结构化CNN，其中分支被训练成专用于手关节的预定义子集，称为本地姿势。我们进一步融合从层次CNN分支中提取的局部姿态特征，以通过端到端训练来学习最终姿态中关节之间的高阶依赖性。最后，所使用的损失函数也被定义为包含关于可行的手部运动和变形的外观和物理限制。实验结果表明，将一个专门用于局部姿势的树状CNN融合到融合网络中以建立关节相关性，有助于提高最终估计的精确度，优于纽约大学和MSRA数据集的最新成果。

##### URL
[https://arxiv.org/abs/1705.09606](https://arxiv.org/abs/1705.09606)

##### PDF
[https://arxiv.org/pdf/1705.09606](https://arxiv.org/pdf/1705.09606)

