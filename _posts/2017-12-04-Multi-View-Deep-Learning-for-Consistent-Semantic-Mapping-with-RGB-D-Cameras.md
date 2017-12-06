---
layout: post
title: 'Multi-View Deep Learning for Consistent Semantic Mapping with RGB-D Cameras'
date: 2017-12-04 19:01:11
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Deep_Learning
author: Lingni Ma, J&#xf6;rg St&#xfc;ckler, Christian Kerl, Daniel Cremers
---

* content
{:toc}

##### Abstract
Visual scene understanding is an important capability that enables robots to purposefully act in their environment. In this paper, we propose a novel approach to object-class segmentation from multiple RGB-D views using deep learning. We train a deep neural network to predict object-class semantics that is consistent from several view points in a semi-supervised way. At test time, the semantics predictions of our network can be fused more consistently in semantic keyframe maps than predictions of a network trained on individual views. We base our network architecture on a recent single-view deep learning approach to RGB and depth fusion for semantic object-class segmentation and enhance it with multi-scale loss minimization. We obtain the camera trajectory using RGB-D SLAM and warp the predictions of RGB-D images into ground-truth annotated frames in order to enforce multi-view consistency during training. At test time, predictions from multiple views are fused into keyframes. We propose and analyze several methods for enforcing multi-view consistency during training and testing. We evaluate the benefit of multi-view consistency training and demonstrate that pooling of deep features and fusion over multiple views outperforms single-view baselines on the NYUDv2 benchmark for semantic segmentation. Our end-to-end trained network achieves state-of-the-art performance on the NYUDv2 dataset in single-view segmentation as well as multi-view semantic fusion.

##### Abstract (translated by Google)
视觉场景理解是使机器人有目的地在自己的环境中行动的重要能力。在本文中，我们提出了一种新的方法来从多个RGB-D视图使用深度学习对象类分割。我们训练一个深度神经网络，以半监督的方式从几个观点来预测对象类语义。在测试时间，我们的网络的语义预测可以在语义关键帧映射中比在单个视图上训练的网络的预测更一致地融合。我们将我们的网络架构建立在最近的RGB单视图深度学习方法和深度融合的语义对象类分割上，并通过多尺度损失最小化来加强它。我们使用RGB-D SLAM获得摄像机轨迹，并将RGB-D图像的预测转换为地面真实标注帧，以便在训练期间实施多视图一致性。在测试时间，来自多个视图的预测被融合到关键帧中。我们提出并分析了在训练和测试期间执行多视图一致性的几种方法。我们评估了多视图一致性训练的好处，并且证明了将多个视图的深度特征和融合汇集在一起​​，胜过了对于语义分割的NYUDv2基准的单视图基线。我们的端到端训练网络在单视图分割和多视图语义融合的NYUDv2数据集上实现了最先进的性能。

##### URL
[http://arxiv.org/abs/1703.08866](http://arxiv.org/abs/1703.08866)

