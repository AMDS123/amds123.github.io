---
layout: post
title: "Detail Preserving Depth Estimation from a Single Image Using Attention Guided Networks"
date: 2018-09-03 16:33:30
categories: arXiv_CV
tags: arXiv_CV Attention CNN Classification Prediction Quantitative
author: Zhixiang Hao, Yu Li, Shaodi You, Feng Lu
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks have demonstrated superior performance on single image depth estimation in recent years. These works usually use stacked spatial pooling or strided convolution to get high-level information which are common practices in classification task. However, depth estimation is a dense prediction problem and low-resolution feature maps usually generate blurred depth map which is undesirable in application. In order to produce high quality depth map, say clean and accurate, we propose a network consists of a Dense Feature Extractor (DFE) and a Depth Map Generator (DMG). The DFE combines ResNet and dilated convolutions. It extracts multi-scale information from input image while keeping the feature maps dense. As for DMG, we use attention mechanism to fuse multi-scale features produced in DFE. Our Network is trained end-to-end and does not need any post-processing. Hence, it runs fast and can predict depth map in about 15 fps. Experiment results show that our method is competitive with the state-of-the-art in quantitative evaluation, but can preserve better structural details of the scene depth.

##### Abstract (translated by Google)
卷积神经网络近年来在单幅图像深度估计方面表现出优越的性能。这些工作通常使用堆叠空间池或跨步卷积来获得高级信息，这是分类任务中的常见做法。然而，深度估计是密集预测问题，并且低分辨率特征图通常生成模糊深度图，这在应用中是不期望的。为了生成高质量的深度图，比如干净准确，我们提出了一个由密集特征提取器（DFE）和深度图生成器（DMG）组成的网络。 DFE结合了ResNet和扩张的卷积。它从输入图像中提取多尺度信息，同时保持特征图密集。对于DMG，我们使用注意机制来融合DFE中产生的多尺度特征。我们的网络端到端培训，不需要任何后期处理。因此，它运行速度快，可以预测大约15 fps的深度图。实验结果表明，我们的方法与定量评估中的最新技术竞争，但可以保留更好的场景深度结构细节。

##### URL
[http://arxiv.org/abs/1809.00646](http://arxiv.org/abs/1809.00646)

##### PDF
[http://arxiv.org/pdf/1809.00646](http://arxiv.org/pdf/1809.00646)

