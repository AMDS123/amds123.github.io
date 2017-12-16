---
layout: post
title: "A Greedy Part Assignment Algorithm for Real-time Multi-person 2D Pose Estimation"
date: 2017-08-30 09:13:38
categories: arXiv_CV
tags: arXiv_CV Sparse Pose_Estimation Detection Relation
author: Srenivas Varadarajan, Parual Datta, Omesh Tickoo
mathjax: true
---

* content
{:toc}

##### Abstract
Human pose-estimation in a multi-person image involves detection of various body parts and grouping them into individual person clusters. While the former task is challenging due to mutual occlusions, the combinatorial complexity of the latter task is very high. We propose a greedy part assignment algorithm that exploits the inherent structure of the human body to achieve a lower complexity, compared to any of the prior published works. This is accomplished by (i) reducing the number of part-candidates using the estimated number of people in the image, (ii) doing a greedy sequential assignment of part-classes, following the kinematic chain from head to ankle (iii) doing a greedy assignment of parts in each part-class set, to person-clusters (iv) limiting the candidate person clusters to the most proximal clusters using human anthropometric data and (v) using only a specific subset of pre-assigned parts for establishing pairwise structural constraints. We show that, these steps result in a sparse body parts relationship graph and reduces the complexity. We also propose methods for improving the accuracy of pose-estimation by (i) spawning person-clusters from any unassigned significant body part and (ii) suppressing hallucinated parts. On the MPII multi-person pose database, pose-estimation using the proposed method takes only 0.14 seconds per image. We show that, our proposed algorithm, by using a large spatial and structural context, achieves the state-of-the-art accuracy on both MPII and WAF multi-person pose datasets, demonstrating the robustness of our approach.

##### Abstract (translated by Google)
多人图像中的人体姿态估计涉及各种身体部位的检测并将其分组为个人人群。虽然前面的任务由于相互遮挡而具有挑战性，但后一任务的组合复杂性非常高。我们提出了一个贪婪的部分分配算法，利用人体内在的结构来实现一个较低的复杂性，相比任何以前发表的作品。这是通过以下方式实现的：（i）使用图像中估计的人数减少部分候选人的数量，（ii）遵循从头部到脚踝的运动链，进行部分类别的贪婪连续分配（iii） （iv）使用人体测量数据将候选人群限制到最近的群，以及（v）仅使用预先指定的部分的特定子集来建立成对结构限制。我们表明，这些步骤导致稀疏的身体部位关系图，并降低了复杂性。我们还提出了通过（i）从任何未分配的重要身体部分产生人群和（ii）抑制幻觉部分来提高姿态估计的准确度的方法。在MPII多人姿势数据库中，使用所提出的方法的姿态估计每个图像仅需0.14秒。我们表明，我们提出的算法，通过使用一个大的空间和结构上下文，实现了MPII和WAF多人姿势数据集的最先进的准确性，展示了我们的方法的鲁棒性。

##### URL
[https://arxiv.org/abs/1708.09182](https://arxiv.org/abs/1708.09182)

##### PDF
[https://arxiv.org/pdf/1708.09182](https://arxiv.org/pdf/1708.09182)

