---
layout: post
title: "Fast, Simple Calcium Imaging Segmentation with Fully Convolutional Networks"
date: 2017-07-19 22:27:29
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Deep_Learning Prediction
author: Aleksander Klibisz, Derek Rose, Matthew Eicholtz, Jay Blundon, Stanislav Zakharenko
mathjax: true
---

* content
{:toc}

##### Abstract
Calcium imaging is a technique for observing neuron activity as a series of images showing indicator fluorescence over time. Manually segmenting neurons is time-consuming, leading to research on automated calcium imaging segmentation (ACIS). We evaluated several deep learning models for ACIS on the Neurofinder competition datasets and report our best model: U-Net2DS, a fully convolutional network that operates on 2D mean summary images. U-Net2DS requires minimal domain-specific pre/post-processing and parameter adjustment, and predictions are made on full $512\times512$ images at $\approx$9K images per minute. It ranks third in the Neurofinder competition ($F_1=0.569$) and is the best model to exclusively use deep learning. We also demonstrate useful segmentations on data from outside the competition. The model's simplicity, speed, and quality results make it a practical choice for ACIS and a strong baseline for more complex models in the future.

##### Abstract (translated by Google)
钙成像是一种观察神经元活动的技术，作为显示随时间推移的荧光指示剂的一系列图像。手动分割神经元是耗时的，导致对自动钙成像分割（ACIS）的研究。我们在Neurofinder竞争数据集上评估了ACIS的几种深度学习模型，并报告了我们的最佳模型：U-Net2DS，一种完全卷积网络，在二维平均汇总图像上运行。 U-Net2DS需要最小的特定于领域的前/后处理和参数调整，并且预测以每分钟$¥大约9K图像的全部$ 512 \ times512 $图像进行。它在Neurofinder竞赛中排名第三（$ F_1 = 0.569 $），是专门用于深度学习的最佳模式。我们还展示了来自竞争对手之外的有用数据。该模型的简单性，速度和质量结果使其成为ACIS的一个实际选择，并成为未来更复杂模型的强大基准。

##### URL
[https://arxiv.org/abs/1707.06314](https://arxiv.org/abs/1707.06314)

##### PDF
[https://arxiv.org/pdf/1707.06314](https://arxiv.org/pdf/1707.06314)

