---
layout: post
title: "Numerical Coordinate Regression with Convolutional Neural Networks"
date: 2018-01-23 02:18:04
categories: arXiv_CV
tags: arXiv_CV Pose_Estimation CNN Inference Deep_Learning Prediction
author: Aiden Nibali, Zhen He, Stuart Morgan, Luke Prendergast
mathjax: true
---

* content
{:toc}

##### Abstract
We study deep learning approaches to inferring numerical coordinates for points of interest in an input image. Existing convolutional neural network-based solutions to this problem either take a heatmap matching approach or regress to coordinates with a fully connected output layer. Neither of these approaches is ideal, since the former is not entirely differentiable, and the latter lacks inherent spatial generalization. We propose our differentiable spatial to numerical transform (DSNT) to fill this gap. The DSNT layer adds no trainable parameters, is fully differentiable, and exhibits good spatial generalization. Unlike heatmap matching, DSNT works well with low heatmap resolutions, so it can be dropped in as an output layer for a wide range of existing fully convolutional architectures. Consequently, DSNT offers a better trade-off between inference speed and prediction accuracy compared to existing techniques. When used to replace the popular heatmap matching approach used in almost all state-of-the-art methods for pose estimation, DSNT gives better prediction accuracy for all model architectures tested.

##### Abstract (translated by Google)
我们研究深度学习方法来推断输入图像中感兴趣点的数字坐标。现有的基于卷积神经网络的解决方案要么采取热图匹配的方法，要么退化为完全连接输出层的坐标。这两种方法都不是理想的，因为前者不是完全可区分的，后者缺乏内在的空间概括。我们提出了可微分空间数值转换（DSNT）来填补这个空白。 DSNT层不添加可训练参数，是完全可微的，并展现出良好的空间泛化。与热图匹配不同，DSNT在低热图分辨率下工作良好，因此可以作为输出图层用于各种现有的完全卷积体系结构。因此，与现有技术相比，DSNT在推断速度和预测精度之间提供了更好的平衡。当用于替代几乎所有用于姿态估计的现有技术方法中常用的热图匹配方法时，DSNT为所有测试的模型架构提供了更好的预测精度。

##### URL
[http://arxiv.org/abs/1801.07372](http://arxiv.org/abs/1801.07372)

##### PDF
[http://arxiv.org/pdf/1801.07372](http://arxiv.org/pdf/1801.07372)

