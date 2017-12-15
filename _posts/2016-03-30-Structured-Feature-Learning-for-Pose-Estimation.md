---
layout: post
title: "Structured Feature Learning for Pose Estimation"
date: 2016-03-30 07:52:22
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation Relation
author: Xiao Chu, Wanli Ouyang, Hongsheng Li, Xiaogang Wang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a structured feature learning framework to reason the correlations among body joints at the feature level in human pose estimation. Different from existing approaches of modelling structures on score maps or predicted labels, feature maps preserve substantially richer descriptions of body joints. The relationships between feature maps of joints are captured with the introduced geometrical transform kernels, which can be easily implemented with a convolution layer. Features and their relationships are jointly learned in an end-to-end learning system. A bi-directional tree structured model is proposed, so that the feature channels at a body joint can well receive information from other joints. The proposed framework improves feature learning substantially. With very simple post processing, it reaches the best mean PCP on the LSP and FLIC datasets. Compared with the baseline of learning features at each joint separately with ConvNet, the mean PCP has been improved by 18% on FLIC. The code is released to the public.

##### Abstract (translated by Google)
在本文中，我们提出了一个结构化的特征学习框架来推断人体姿态估计中特征层面身体关节之间的相关性。与在分数图或预测标签上建模结构的现有方法不同，特征图保存了关于身体关节的更丰富的描述。引入的几何变换核捕获关节特征图之间的关系，可以很容易地实现一个卷积层。在一个端到端的学习系统中共同学习功能及其关系。提出了一种双向树结构模型，使得身体关节处的特征通道能很好地接收来自其他关节的信息。所提出的框架大大改进了特征学习。通过非常简单的后处理，在LSP和FLIC数据集上达到最佳平均PCP。与ConvNet分别关联学习特征的基线相比，FLIC平均PCP提高了18％。该代码发布给公众。

##### URL
[https://arxiv.org/abs/1603.09065](https://arxiv.org/abs/1603.09065)

##### PDF
[https://arxiv.org/pdf/1603.09065](https://arxiv.org/pdf/1603.09065)

