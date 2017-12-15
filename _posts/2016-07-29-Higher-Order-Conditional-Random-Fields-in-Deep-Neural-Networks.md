---
layout: post
title: "Higher Order Conditional Random Fields in Deep Neural Networks"
date: 2016-07-29 18:16:18
categories: arXiv_CV
tags: arXiv_CV Object_Detection Segmentation CNN Semantic_Segmentation Inference Deep_Learning Detection
author: Anurag Arnab, Sadeep Jayasumana, Shuai Zheng, Philip Torr
mathjax: true
---

* content
{:toc}

##### Abstract
We address the problem of semantic segmentation using deep learning. Most segmentation systems include a Conditional Random Field (CRF) to produce a structured output that is consistent with the image's visual features. Recent deep learning approaches have incorporated CRFs into Convolutional Neural Networks (CNNs), with some even training the CRF end-to-end with the rest of the network. However, these approaches have not employed higher order potentials, which have previously been shown to significantly improve segmentation performance. In this paper, we demonstrate that two types of higher order potential, based on object detections and superpixels, can be included in a CRF embedded within a deep network. We design these higher order potentials to allow inference with the differentiable mean field algorithm. As a result, all the parameters of our richer CRF model can be learned end-to-end with our pixelwise CNN classifier. We achieve state-of-the-art segmentation performance on the PASCAL VOC benchmark with these trainable higher order potentials.

##### Abstract (translated by Google)
我们用深度学习来解决语义分割的问题。大多数分割系统包括一个条件随机场（CRF）来产生一个与图像视觉特征一致的结构化输出。最近的深度学习方法已经将CRF引入了卷积神经网络（CNN），有些甚至将CRF与网络的其他部分进行端到端的训练。然而，这些方法并没有采用更高阶的潜力，以前已被证明显着改善分割性能。在本文中，我们证明了基于对象检测和超像素的两种类型的高阶潜能可以包含在嵌入深度网络中的CRF中。我们设计这些更高阶的电位，以允许推断可微平均场算法。因此，我们更丰富的CRF模型的所有参数都可以通过我们的像素CNN分类器端对端地学习。我们利用这些可训练的高阶潜能，在PASCAL VOC基准上实现了最先进的细分表现。

##### URL
[https://arxiv.org/abs/1511.08119](https://arxiv.org/abs/1511.08119)

##### PDF
[https://arxiv.org/pdf/1511.08119](https://arxiv.org/pdf/1511.08119)

