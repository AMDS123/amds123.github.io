---
layout: post
title: "Robust Visual Tracking via Hierarchical Convolutional Features"
date: 2017-07-12 17:54:21
categories: arXiv_CV
tags: arXiv_CV Tracking CNN Detection Relation Recognition
author: Chao Ma, Jia-Bin Huang, Xiaokang Yang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Visual tracking is challenging as target objects often undergo significant appearance changes caused by deformation, abrupt motion, background clutter and occlusion. In this paper, we propose to exploit the rich hierarchical features of deep convolutional neural networks to improve the accuracy and robustness of visual tracking. Deep neural networks trained on object recognition datasets consist of multiple convolutional layers. These layers encode target appearance with different levels of abstraction. For example, the outputs of the last convolutional layers encode the semantic information of targets and such representations are invariant to significant appearance variations. However, their spatial resolutions are too coarse to precisely localize the target. In contrast, features from earlier convolutional layers provide more precise localization but are less invariant to appearance changes. We interpret the hierarchical features of convolutional layers as a nonlinear counterpart of an image pyramid representation and explicitly exploit these multiple levels of abstraction to represent target objects. Specifically, we learn adaptive correlation filters on the outputs from each convolutional layer to encode the target appearance. We infer the maximum response of each layer to locate targets in a coarse-to-fine manner. To further handle the issues with scale estimation and target re-detection from tracking failures caused by heavy occlusion or moving out of the view, we conservatively learn another correlation filter that maintains a long-term memory of target appearance as a discriminative classifier. Extensive experimental results on large-scale benchmark datasets show that the proposed algorithm performs favorably against the state-of-the-art tracking methods.

##### Abstract (translated by Google)
视觉跟踪是具有挑战性的，因为目标物体经常经历由变形，突然运动，背景杂波和遮挡引起的显着的外观变化。本文提出利用深度卷积神经网络丰富的层次特征来提高视觉跟踪的准确性和鲁棒性。在对象识别数据集上训练的深度神经网络由多个卷积层组成。这些图层用不同的抽象级别来编码目标外观。例如，最后的卷积层的输出对目标的语义信息进行编码，并且这种表示对于显着的外观变化是不变的。然而，他们的空间分辨率太粗糙，不能精确定位目标。相比之下，来自较早卷积层的特征提供更精确的定位，但对外观变化的影响更小。我们将卷积层的层次特征解释为图像金字塔表示的非线性对应物，并明确地利用这些多层次的抽象来表示目标对象。具体来说，我们在每个卷积层的输出上学习自适应相关滤波器来编码目标外观。我们推断每层的最大响应以从粗到细的方式定位目标。为了进一步处理尺度估计和目标重新检测的问题，从追踪由重度遮挡引起的失效或移出视野，我们保守地学习另一个相关滤波器，以保持对目标外观的长期记忆作为判别分类器。在大规模基准数据集上的广泛的实验结果表明，所提出的算法对于最先进的跟踪方法有利。

##### URL
[https://arxiv.org/abs/1707.03816](https://arxiv.org/abs/1707.03816)

##### PDF
[https://arxiv.org/pdf/1707.03816](https://arxiv.org/pdf/1707.03816)

