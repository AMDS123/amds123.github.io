---
layout: post
title: "On-the-fly Network Pruning for Object Detection"
date: 2016-05-11 15:27:43
categories: arXiv_CV
tags: arXiv_CV Object_Detection Detection
author: Marc Masana, Joost van de Weijer, Andrew D. Bagdanov
mathjax: true
---

* content
{:toc}

##### Abstract
Object detection with deep neural networks is often performed by passing a few thousand candidate bounding boxes through a deep neural network for each image. These bounding boxes are highly correlated since they originate from the same image. In this paper we investigate how to exploit feature occurrence at the image scale to prune the neural network which is subsequently applied to all bounding boxes. We show that removing units which have near-zero activation in the image allows us to significantly reduce the number of parameters in the network. Results on the PASCAL 2007 Object Detection Challenge demonstrate that up to 40% of units in some fully-connected layers can be entirely eliminated with little change in the detection result.

##### Abstract (translated by Google)
深度神经网络的目标检测通常通过将每个图像的数千个候选包围盒通过深度神经网络来执行。这些边界框由于来源于相同的图像而高度相关。在本文中，我们研究如何利用图像尺度上的特征出现来修剪随后应用于所有边界框的神经网络。我们显示，去除图像中具有接近零激活的单元，可以显着减少网络中的参数数量。 PASCAL 2007对象检测挑战的结果表明，一些完全连接层中高达40％的单元可以完全消除，检测结果几乎没有变化。

##### URL
[https://arxiv.org/abs/1605.03477](https://arxiv.org/abs/1605.03477)

##### PDF
[https://arxiv.org/pdf/1605.03477](https://arxiv.org/pdf/1605.03477)

