---
layout: post
title: "Smoothed Dilated Convolutions for Improved Dense Prediction"
date: 2018-08-27 17:13:38
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Prediction Detection
author: Zhengyang Wang, Shuiwang Ji
mathjax: true
---

* content
{:toc}

##### Abstract
Dilated convolutions, also known as atrous convolutions, have been widely explored in deep convolutional neural networks (DCNNs) for various tasks like semantic image segmentation, object detection, audio generation, video modeling, and machine translation. However, dilated convolutions suffer from the gridding artifacts, which hampers the performance of DCNNs with dilated convolutions. In this work, we propose two simple yet effective degridding methods by studying a decomposition of dilated convolutions. Unlike existing models, which explore solutions by focusing on a block of cascaded dilated convolutional layers, our methods address the gridding artifacts by smoothing the dilated convolution itself. By analyzing them in both the original operation and the decomposition views, we further point out that the two degridding approaches are intrinsically related and define separable and shared (SS) operations, which generalize the proposed methods. We evaluate our methods thoroughly on two datasets and visualize the smoothing effect through effective receptive field analysis. Experimental results show that our methods yield significant and consistent improvements on the performance of DCNNs with dilated convolutions, while adding negligible amounts of extra training parameters.

##### Abstract (translated by Google)
扩张卷积，也称为萎缩卷曲，已经在深度卷积神经网络（DCNN）中广泛探索用于各种任务，例如语义图像分割，对象检测，音频生成，视频建模和机器翻译。然而，扩张的卷曲受到网格伪影的影响，这妨碍了具有扩张卷积的DCNN的性能。在这项工作中，我们通过研究扩张卷积的分解提出了两种简单而有效的降级方法。与通过关注级联膨胀卷积层探索解决方案的现有模型不同，我们的方法通过平滑扩张卷积本身来解决网格伪像。通过在原始操作和分解视图中分析它们，我们进一步指出两种降级方法是内在相关的，并定义了可分离和共享（SS）操作，这些操作推广了所提出的方法。我们在两个数据集上彻底评估我们的方法，并通过有效的感受野分析可视化平滑效果。实验结果表明，我们的方法对扩散卷积的DCNN的性能产生了显着和一致的改进，同时增加了可忽略不计的额外训练参数。

##### URL
[http://arxiv.org/abs/1808.08931](http://arxiv.org/abs/1808.08931)

##### PDF
[http://arxiv.org/pdf/1808.08931](http://arxiv.org/pdf/1808.08931)

