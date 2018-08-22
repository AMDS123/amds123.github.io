---
layout: post
title: "Deep Learned Full-3D Object Completion from Single View"
date: 2018-08-21 11:07:08
categories: arXiv_CV
tags: arXiv_CV CNN
author: Dario Rethage, Federico Tombari, Felix Achilles, Nassir Navab
mathjax: true
---

* content
{:toc}

##### Abstract
3D geometry is a very informative cue when interacting with and navigating an environment. This writing proposes a new approach to 3D reconstruction and scene understanding, which implicitly learns 3D geometry from depth maps pairing a deep convolutional neural network architecture with an auto-encoder. A data set of synthetic depth views and voxelized 3D representations is built based on ModelNet, a large-scale collection of CAD models, to train networks. The proposed method offers a significant advantage over current, explicit reconstruction methods in that it learns key geometric features offline and makes use of those to predict the most probable reconstruction of an unseen object. The relatively small network, consisting of roughly 4 million weights, achieves a 92.9% reconstruction accuracy at a 30x30x30 resolution through the use of a pre-trained decompression layer. This is roughly 1/4 the weights of the current leading network. The fast execution time of the model makes it suitable for real-time applications.

##### Abstract (translated by Google)
在与环境交互和导航时，3D几何是一个非常有用的提示。本文提出了一种新的三维重建和场景理解方法，它从深度卷积神经网络架构与自动编码器的深度图中隐式学习三维几何。基于ModelNet（用于训练网络的大规模CAD模型集）构建合成深度视图和体素化3D表示的数据集。所提出的方法提供了优于当前的显式重建方法的显着优点，因为它离线学习关键几何特征并利用这些特征来预测未见对象的最可能的重建。相对较小的网络由大约400万个权重组成，通过使用预先训练的减压层，在30x30x30分辨率下实现了92.9％的重建精度。这大约是当前领先网络权重的1/4。该模型的快速执行时间使其适用于实时应用程序。

##### URL
[http://arxiv.org/abs/1808.06843](http://arxiv.org/abs/1808.06843)

##### PDF
[http://arxiv.org/pdf/1808.06843](http://arxiv.org/pdf/1808.06843)

