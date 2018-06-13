---
layout: post
title: "DeepASL: Kinetic Model Incorporated Loss for Denoising Arterial Spin Labeled MRI via Deep Residual Learning"
date: 2018-06-12 11:34:02
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning
author: Cagdas Ulas, Giles Tetteh, Stephan Kaczmarz, Christine Preibisch, Bjoern H. Menze
mathjax: true
---

* content
{:toc}

##### Abstract
Arterial spin labeling (ASL) allows to quantify the cerebral blood flow (CBF) by magnetic labeling of the arterial blood water. ASL is increasingly used in clinical studies due to its noninvasiveness, repeatability and benefits in quantification. However, ASL suffers from an inherently low-signal-to-noise ratio (SNR) requiring repeated measurements of control/spin-labeled (C/L) pairs to achieve a reasonable image quality, which in return increases motion sensitivity. This leads to clinically prolonged scanning times increasing the risk of motion artifacts. Thus, there is an immense need of advanced imaging and processing techniques in ASL. In this paper, we propose a novel deep learning based approach to improve the perfusion-weighted image quality obtained from a subset of all available pairwise C/L subtractions. Specifically, we train a deep fully convolutional network (FCN) to learn a mapping from noisy perfusion-weighted image and its subtraction (residual) from the clean image. Additionally, we incorporate the CBF estimation model in the loss function during training, which enables the network to produce high quality images while simultaneously enforcing the CBF estimates to be as close as reference CBF values. Extensive experiments on synthetic and clinical ASL datasets demonstrate the effectiveness of our method in terms of improved ASL image quality, accurate CBF parameter estimation and considerably small computation time during testing.

##### Abstract (translated by Google)
动脉自旋标记（ASL）允许通过磁性标记动脉血液水来量化脑血流量（CBF）。由于无创性，可重复性和量化优势，ASL越来越多地用于临床研究。然而，ASL具有固有的低信噪比（SNR），要求重复测量控制/自旋标记（C / L）对以实现合理的图像质量，这反过来又增加了运动灵敏度。这导致临床上延长的扫描时间增加运动伪影的风险。因此，ASL需要先进的成像和处理技术。在本文中，我们提出了一种新的基于深度学习的方法来改善从所有可用的成对C / L减法子集获得的灌注加权图像质量。具体来说，我们训练一个深度完全卷积网络（FCN）来学习噪声灌注加权图像和干净图像中的减法（残差）映射。此外，我们将CBF估计模型纳入训练期间的损失函数中，使网络能够产生高质量图像，同时强制CBF估计值与参考CBF值相近。在合成和临床ASL数据集上的大量实验证明了我们的方法在改善ASL图像质量，准确的CBF参数估计和测试期间相当小的计算时间方面的有效性。

##### URL
[http://arxiv.org/abs/1804.02755](http://arxiv.org/abs/1804.02755)

##### PDF
[http://arxiv.org/pdf/1804.02755](http://arxiv.org/pdf/1804.02755)

