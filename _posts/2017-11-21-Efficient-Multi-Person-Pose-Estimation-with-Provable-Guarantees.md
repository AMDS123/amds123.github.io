---
layout: post
title: "Efficient Multi-Person Pose Estimation with Provable Guarantees"
date: 2017-11-21 14:13:41
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Inference Detection
author: Shaofei Wang, Konrad Paul Kording, Julian Yarkony
mathjax: true
---

* content
{:toc}

##### Abstract
Multi-person pose estimation (MPPE) in natural images is key to the meaningful use of visual data in many fields including movement science, security, and rehabilitation. In this paper we tackle MPPE with a bottom-up approach, starting with candidate detections of body parts from a convolutional neural network (CNN) and grouping them into people. We formulate the grouping of body part detections into people as a minimum-weight set packing (MWSP) problem where the set of potential people is the power set of body part detections. We model the quality of a hypothesis of a person which is a set in the MWSP by an augmented tree-structured Markov random field where variables correspond to body-parts and their state-spaces correspond to the power set of the detections for that part. We describe a novel algorithm that combines efficiency with provable bounds on this MWSP problem. We employ an implicit column generation strategy where the pricing problem is formulated as a dynamic program. To efficiently solve this dynamic program we exploit the problem structure utilizing a nested Bender's decomposition (NBD) exact inference strategy which we speed up by recycling Bender's rows between calls to the pricing problem. We test our approach on the MPII-Multiperson dataset, showing that our approach obtains comparable results with the state-of-the-art algorithm for joint node labeling and grouping problems, and that NBD achieves considerable speed-ups relative to a naive dynamic programming approach. Typical algorithms that solve joint node labeling and grouping problems use heuristics and thus can not obtain proofs of optimality. Our approach, in contrast, proves that for over 99 percent of problem instances we find the globally optimal solution and otherwise provide upper/lower bounds.

##### Abstract (translated by Google)
在自然图像中的多人姿态估计（MPPE）是视觉数据在包括运动科学，安全性和康复在内的许多领域中有意义的使用的关键。在本文中，我们用自下而上的方法来处理MPPE，首先从卷积神经网络（CNN）的候选人身体部位检测并将其分组成人。我们将身体部位检测分为人群最小权重集合包装（MWSP）问题，其中潜在人员集合是身体部位检测的功率集合。我们通过扩展的树状结构马尔可夫随机场对MWSP中的一个人的假设的质量进行建模，其中变量对应于身体部分，并且他们的状态空间对应于该部分的检测的幂集。我们描述了一个新的算法，结合了MWSP问题的可证明的边界的效率。我们采用隐式列生成策略，定价问题被定义为动态程序。为了有效地解决这个动态程序，我们利用嵌套的Bender分解（NBD）精确推理策略来利用问题结构，通过在调用定价问题之间回收Bender行来加速这个策略。我们在MPII-Multiperson数据集上测试了我们的方法，表明我们的方法获得了与联合节点标记和分组问题的最新算法相当的结果，并且相对于天真的动态规划，NBD实现了相当快的速度做法。解决联合节点标记和分组问题的典型算法使用启发式，因此不能获得最优性的证明。相比之下，我们的方法证明，对于超过99％的问题实例，我们找到全局最优解，并提供上下限。

##### URL
[https://arxiv.org/abs/1711.07794](https://arxiv.org/abs/1711.07794)

##### PDF
[https://arxiv.org/pdf/1711.07794](https://arxiv.org/pdf/1711.07794)

