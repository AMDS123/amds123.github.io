---
layout: post
title: "DEEP-CARVING: Discovering Visual Attributes by Carving Deep Neural Nets"
date: 2015-04-19 18:56:52
categories: arXiv_CV
tags: arXiv_CV Salient Weakly_Supervised CNN Prediction
author: Sukrit Shankar, Vikas K. Garg, Roberto Cipolla
mathjax: true
---

* content
{:toc}

##### Abstract
Most of the approaches for discovering visual attributes in images demand significant supervision, which is cumbersome to obtain. In this paper, we aim to discover visual attributes in a weakly supervised setting that is commonly encountered with contemporary image search engines. Deep Convolutional Neural Networks (CNNs) have enjoyed remarkable success in vision applications recently. However, in a weakly supervised scenario, widely used CNN training procedures do not learn a robust model for predicting multiple attribute labels simultaneously. The primary reason is that the attributes highly co-occur within the training data. To ameliorate this limitation, we propose Deep-Carving, a novel training procedure with CNNs, that helps the net efficiently carve itself for the task of multiple attribute prediction. During training, the responses of the feature maps are exploited in an ingenious way to provide the net with multiple pseudo-labels (for training images) for subsequent iterations. The process is repeated periodically after a fixed number of iterations, and enables the net carve itself iteratively for efficiently disentangling features. Additionally, we contribute a noun-adjective pairing inspired Natural Scenes Attributes Dataset to the research community, CAMIT - NSAD, containing a number of co-occurring attributes within a noun category. We describe, in detail, salient aspects of this dataset. Our experiments on CAMIT-NSAD and the SUN Attributes Dataset, with weak supervision, clearly demonstrate that the Deep-Carved CNNs consistently achieve considerable improvement in the precision of attribute prediction over popular baseline methods.

##### Abstract (translated by Google)
发现图像中的视觉属性的大多数方法需要重要的监督，这是非常麻烦的。在本文中，我们的目标是发现当前图像搜索引擎经常遇到的弱监督环境下的视觉属性。深度卷积神经网络（CNN）近来在视觉应用方面取得了显着的成功。然而，在弱监督的情况下，广泛使用的CNN训练程序不能学习同时预测多个属性标签的鲁棒模型。主要原因是这些属性在训练数据中高度共同发生。为了改善这一局限性，我们提出了深度雕刻（Deep-Carving），这是一种新颖的CNN训练过程，帮助网络高效地完成多个属性预测任务。在训练过程中，特征映射的反应被巧妙地利用来为网络提供多个伪标签（用于训练图像）用于随后的迭代。该过程在固定数量的迭代之后被周期性地重复，并且使网络自身迭代地有效地解开特征。此外，我们提供了一个名词形容词配对启发自然场景属性数据集的研究社区，CAMIT  -  NSAD，包含一些名词类共同发生的属性。我们详细描述了这个数据集的显着方面。我们在CAMIT-NSAD和SUN属性数据集上进行的实验表明，深度刻画的CNN在流行的基线方法上的属性预测精度一直在大大提高。

##### URL
[https://arxiv.org/abs/1504.04871](https://arxiv.org/abs/1504.04871)

##### PDF
[https://arxiv.org/pdf/1504.04871](https://arxiv.org/pdf/1504.04871)

