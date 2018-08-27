---
layout: post
title: "Recalibrating Fully Convolutional Networks with Spatial and Channel 'Squeeze & Excitation' Blocks"
date: 2018-08-23 13:45:03
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN Image_Classification Semantic_Segmentation Classification
author: Abhijit Guha Roy, Nassir Navab, Christian Wachinger
mathjax: true
---

* content
{:toc}

##### Abstract
In a wide range of semantic segmentation tasks, fully convolutional neural networks (F-CNNs) have been successfully leveraged to achieve state-of-the-art performance. Architectural innovations of F-CNNs have mainly been on improving spatial encoding or network connectivity to aid gradient flow. In this article, we aim towards an alternate direction of recalibrating the learned feature maps adaptively; boosting meaningful features while suppressing weak ones. The recalibration is achieved by simple computational blocks that can be easily integrated in F-CNNs architectures. We draw our inspiration from the recently proposed 'squeeze &amp; excitation' (SE) modules for channel recalibration for image classification. Towards this end, we introduce three variants of SE modules for segmentation, (i) squeezing spatially and exciting channel-wise, (ii) squeezing channel-wise and exciting spatially and (iii) joint spatial and channel 'squeeze &amp; excitation'. We effectively incorporate the proposed SE blocks in three state-of-the-art F-CNNs and demonstrate a consistent improvement of segmentation accuracy on three challenging benchmark datasets. Importantly, SE blocks only lead to a minimal increase in model complexity of about 1.5%, while the Dice score increases by 4-9% in the case of U-Net. Hence, we believe that SE blocks can be an integral part of future F-CNN architectures.

##### Abstract (translated by Google)
在广泛的语义分割任务中，已经成功地利用完全卷积神经网络（F-CNN）来实现最先进的性能。 F-CNN的架构创新主要是改进空间编码或网络连接以帮助梯度流。在本文中，我们的目标是自适应地重新校准学习的特征图;在抑制弱势特征的同时提升有意义的特征。通过简单的计算模块实现重新校准，这些模块可以轻松集成到F-CNN架构中。我们从最近提出的'挤压＆amp; amp;用于图像分类的通道重新校准的激发'（SE）模块。为此，我们引入了用于分割的SE模块的三种变体，（i）在空间上挤压并且在通道方向上激励，（ii）在空间上挤压通道并且在空间上激励，以及（iii）关节空间和通道'挤压＆amp;励磁'。我们有效地将所提出的SE模块整合到三个最先进的F-CNN中，并展示了在三个具有挑战性的基准数据集上的分割准确性的持续改进。重要的是，SE块仅导致模型复杂度的最小增加约1.5％，而在U-Net的情况下，Dice得分增加4-9％。因此，我们认为SE模块可以成为未来F-CNN架构的组成部分。

##### URL
[http://arxiv.org/abs/1808.08127](http://arxiv.org/abs/1808.08127)

##### PDF
[http://arxiv.org/pdf/1808.08127](http://arxiv.org/pdf/1808.08127)

