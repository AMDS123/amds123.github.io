---
layout: post
title: "Optimizing the F-measure for Threshold-free Salient Object Detection"
date: 2018-05-19 10:54:43
categories: arXiv_CV
tags: arXiv_CV Salient Object_Detection Optimization Prediction Detection
author: Kai Zhao, Shanghua Gao, Qibin Hou, Dan-Dan Li, Ming-Ming Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Current CNN-based solutions to salient object detection (SOD) mainly rely on the optimization of cross-entropy loss (CELoss). Then the quality of detected saliency maps is often evaluated in terms of F-measure. In this paper, we investigate an interesting issue: can we consistently use the F-measure formulation in both training and evaluation for SOD? By reformulating the standard F-measure we propose the relaxed F-measure which is differentiable w.r.t the posterior and can be easily appended to the back of CNNs as the loss function. Compared to the conventional cross-entropy loss of which the gradients decrease dramatically in the saturated area, our loss function, named FLoss, holds considerable gradients even when the activation approaches the target. Consequently, the FLoss can continuously force the network to produce polarized activations. Comprehensive benchmarks on several popular datasets show that FLoss outperforms the state- of-the-arts with a considerable margin. More specifically, due to the polarized predictions, our method is able to obtain high quality saliency maps without carefully tuning the optimal threshold, showing significant advantages in real world applications.

##### Abstract (translated by Google)
目前基于CNN的显着物体检测（SOD）解决方案主要依赖于交叉熵损失（CELoss）的优化。然后，检测到的显着图的质量通常用F-measure来评估。在本文中，我们调查了一个有趣的问题：我们是否可以在训练和评估SOD过程中始终如一地使用F-measure制剂？通过重新制定标准的F-度量，我们提出了松弛的F-度量，它在后验上是可微的，并且可以很容易地作为损失函数附加到CNN的后面。与饱和区域中梯度急剧减小的传统交叉熵损耗相比，即使激活接近目标，我们的损耗函数FLoss也具有相当大的梯度。因此，FLoss可以不断强制网络产生极化激活。几个流行数据集的综合基准数据表明，FLoss的性能优于现有技术，并有相当大的余量。更具体地说，由于极化预测，我们的方法能够在不仔细调整最佳阈值的情况下获得高质量显着图，显示出在现实世界应用中的显着优点。

##### URL
[https://arxiv.org/abs/1805.07567](https://arxiv.org/abs/1805.07567)

##### PDF
[https://arxiv.org/pdf/1805.07567](https://arxiv.org/pdf/1805.07567)

