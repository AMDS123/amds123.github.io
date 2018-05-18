---
layout: post
title: "QuaterNet: A Quaternion-based Recurrent Model for Human Motion"
date: 2018-05-16 18:38:37
categories: arXiv_CV
tags: arXiv_CV Deep_Learning Prediction Quantitative
author: Dario Pavllo, David Grangier, Michael Auli
mathjax: true
---

* content
{:toc}

##### Abstract
Deep learning for predicting or generating 3D human pose sequences is an active research area. Previous work regresses either joint rotations or joint positions. The former strategy is prone to error accumulation along the kinematic chain, as well as discontinuities when using Euler angle or exponential map parameterizations. The latter requires re-projection onto skeleton constraints to avoid bone stretching and invalid configurations. This work addresses both limitations. Our recurrent network, QuaterNet, represents rotations with quaternions and our loss function performs forward kinematics on a skeleton to penalize absolute position errors instead of angle errors. On short-term predictions, QuaterNet improves the state-of-the-art quantitatively. For long-term generation, our approach is qualitatively judged as realistic as recent neural strategies from the graphics literature.

##### Abstract (translated by Google)
用于预测或生成3D人体姿势序列的深度学习是一个活跃的研究领域。以前的工作要么是联合轮换，要么是联合职位。前一种策略很容易在运动链中产生误差累积，以及在使用欧拉角或指数图参数化时容易产生不连续性。后者需要重新投影到骨架约束上以避免骨骼伸展和无效配置。这项工作解决了两个限制。我们的经常性网络QuaterNet表示四元数的旋转，而我们的损失函数在骨架上执行正向运动以惩罚绝对位置误差而不是角度误差。在短期预测方面，QuaterNet可以定量地改进现有技术。对于长期生成，我们的方法在图形文献中被定性地判断为最新的神经策略。

##### URL
[http://arxiv.org/abs/1805.06485](http://arxiv.org/abs/1805.06485)

##### PDF
[http://arxiv.org/pdf/1805.06485](http://arxiv.org/pdf/1805.06485)

