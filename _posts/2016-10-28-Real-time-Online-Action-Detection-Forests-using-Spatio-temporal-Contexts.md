---
layout: post
title: "Real-time Online Action Detection Forests using Spatio-temporal Contexts"
date: 2016-10-28 18:15:31
categories: arXiv_CV
tags: arXiv_CV CNN Classification Detection Relation
author: Seungryul Baek, Kwang In Kim, Tae-Kyun Kim
mathjax: true
---

* content
{:toc}

##### Abstract
Online action detection (OAD) is challenging since 1) robust yet computationally expensive features cannot be straightforwardly used due to the real-time processing requirements and 2) the localization and classification of actions have to be performed even before they are fully observed. We propose a new random forest (RF)-based online action detection framework that addresses these challenges. Our algorithm uses computationally efficient skeletal joint features. High accuracy is achieved by using robust convolutional neural network (CNN)-based features which are extracted from the raw RGBD images, plus the temporal relationships between the current frame of interest, and the past and future frames. While these high-quality features are not available in real-time testing scenario, we demonstrate that they can be effectively exploited in training RF classifiers: We use these spatio-temporal contexts to craft RF's new split functions improving RFs' leaf node statistics. Experiments with challenging MSRAction3D, G3D, and OAD datasets demonstrate that our algorithm significantly improves the accuracy over the state-of-the-art online action detection algorithms while achieving the real-time efficiency of existing skeleton-based RF classifiers.

##### Abstract (translated by Google)
在线行为检测（OAD）是具有挑战性的，因为1）由于实时处理要求，不能直接使用强大而计算上昂贵的特征，2）即使在完全观察之前，行为的定位和分类也必须被执行。我们提出了一个新的基于随机森林（RF）的在线行动检测框架，以应对这些挑战。我们的算法使用计算有效的骨架关节特征。通过使用从原始RGBD图像提取的鲁棒卷积神经网络（CNN）的特征加上当前感兴趣帧与过去和未来帧之间的时间关系，实现了高精度。虽然这些高质量的功能在实时测试场景中不可用，但是我们证明它们可以有效地用于训练射频分类器：我们使用这些时空上下文来制作射频的新分裂函数，以改善射频的叶节点统计信息。对具有挑战性的MSRAction3D，G3D和OAD数据集的实验表明，我们的算法显着提高了最先进的在线动作检测算法的精度，同时实现了现有基于骨架的RF分类器的实时效率。

##### URL
[https://arxiv.org/abs/1610.09334](https://arxiv.org/abs/1610.09334)

##### PDF
[https://arxiv.org/pdf/1610.09334](https://arxiv.org/pdf/1610.09334)

