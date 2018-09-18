---
layout: post
title: "Beyond saliency: understanding convolutional neural networks from saliency prediction on layer-wise relevance propagation"
date: 2018-09-15 01:12:58
categories: arXiv_CV
tags: arXiv_CV Salient Attention Face CNN Prediction Recognition
author: Heyi Li, Yunke Tian, Klaus Mueller, Xin Chen
mathjax: true
---

* content
{:toc}

##### Abstract
Despite the tremendous achievements of deep convolutional neural networks (CNNs) in many computer vision tasks, understanding how they actually work remains a significant challenge. In this paper, we propose a novel two-step understanding method, namely Salient Relevance (SR) map, which aims to shed light on how deep CNNs recognize images and learn features from areas, referred to as attention areas, therein. Our proposed method starts out with a layer-wise relevance propagation (LRP) step which estimates a pixel-wise relevance map over the input image. Following, we construct a context-aware saliency map, SR map, from the LRP-generated map which predicts areas close to the foci of attention instead of isolated pixels that LRP reveals. In human visual system, information of regions is more important than of pixels in recognition. Consequently, our proposed approach closely simulates human recognition. Experimental results using the ILSVRC2012 validation dataset in conjunction with two well-established deep CNN models, AlexNet and VGG-16, clearly demonstrate that our proposed approach concisely identifies not only key pixels but also attention areas that contribute to the underlying neural network's comprehension of the given images. As such, our proposed SR map constitutes a convenient visual interface which unveils the visual attention of the network and reveals which type of objects the model has learned to recognize after training. The source code is available at https://github.com/Hey1Li/Salient-Relevance-Propagation.

##### Abstract (translated by Google)
尽管深度卷积神经网络（CNN）在许多计算机视觉任务中取得了巨大成就，但了解它们实际工作的方式仍然是一项重大挑战。在本文中，我们提出了一种新颖的两步理解方法，即显着相关（SR）图，旨在揭示CNN识别图像的深度以及从其中被称为关注区域的区域学习特征。我们提出的方法从分层相关传播（LRP）步骤开始，该步骤估计输入图像上的像素相关性映射。接下来，我们从LRP生成的地图构建一个上下文感知显着图SR图，该图预测接近注意力焦点的区域而不是LRP显示的孤立像素。在人类视觉系统中，区域信息比识别中的像素更重要。因此，我们提出的方法非常模拟人类的认知。使用ILSVRC2012验证数据集结合两个成熟的深度CNN模型AlexNet和VGG-16的实验结果清楚地表明，我们提出的方法不仅简明地识别关键像素，而且还有助于识别潜在神经网络的关注区域。给出的图像。因此，我们提出的SR地图构成了一个方便的视觉界面，它揭示了网络的视觉注意力，并揭示了模型在训练后学会识别的对象类型。源代码可在https://github.com/Hey1Li/Salient-Relevance-Propagation获得。

##### URL
[http://arxiv.org/abs/1712.08268](http://arxiv.org/abs/1712.08268)

##### PDF
[http://arxiv.org/pdf/1712.08268](http://arxiv.org/pdf/1712.08268)

