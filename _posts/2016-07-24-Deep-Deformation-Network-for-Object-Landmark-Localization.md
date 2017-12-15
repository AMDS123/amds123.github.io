---
layout: post
title: "Deep Deformation Network for Object Landmark Localization"
date: 2016-07-24 06:46:58
categories: arXiv_CV
tags: arXiv_CV Regularization Pose_Estimation CNN Prediction
author: Xiang Yu, Feng Zhou, Manmohan Chandraker
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel cascaded framework, namely deep deformation network (DDN), for localizing landmarks in non-rigid objects. The hallmarks of DDN are its incorporation of geometric constraints within a convolutional neural network (CNN) framework, ease and efficiency of training, as well as generality of application. A novel shape basis network (SBN) forms the first stage of the cascade, whereby landmarks are initialized by combining the benefits of CNN features and a learned shape basis to reduce the complexity of the highly nonlinear pose manifold. In the second stage, a point transformer network (PTN) estimates local deformation parameterized as thin-plate spline transformation for a finer refinement. Our framework does not incorporate either handcrafted features or part connectivity, which enables an end-to-end shape prediction pipeline during both training and testing. In contrast to prior cascaded networks for landmark localization that learn a mapping from feature space to landmark locations, we demonstrate that the regularization induced through geometric priors in the DDN makes it easier to train, yet produces superior results. The efficacy and generality of the architecture is demonstrated through state-of-the-art performances on several benchmarks for multiple tasks such as facial landmark localization, human body pose estimation and bird part localization.

##### Abstract (translated by Google)
我们提出了一个新的级联框架，即深度变形网络（DDN），用于定位非刚性物体的标志。 DDN的特点是在卷积神经网络（CNN）框架内纳入了几何约束，训练的方便性和有效性，以及应用的一般性。一个新颖的形状基础网络（SBN）形成了级联的第一阶段，由此通过结合CNN特征的优点和学习形状基础来初始化地标，以降低高度非线性姿态流形的复杂性。在第二阶段，点变压器网络（PTN）估计局部变形被参数化为薄板样条变换以进行更精细的细化。我们的框架不包含手工功能或零件连接功能，从而在培训和测试期间实现端到端形状预测管道。与之前的用于地标定位的级联网络学习从特征空间到地标位置的映射相反，我们证明了通过DDN中的几何先验引发的正则化使得训练更容易，但是产生更好的结果。该架构的有效性和通用性通过在多个任务的若干基准上的最新性能表现来证明，所述多个任务例如面部标志定位，人体姿态估计和鸟类部分定位。

##### URL
[https://arxiv.org/abs/1605.01014](https://arxiv.org/abs/1605.01014)

##### PDF
[https://arxiv.org/pdf/1605.01014](https://arxiv.org/pdf/1605.01014)

