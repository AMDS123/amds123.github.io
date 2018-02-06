---
layout: post
title: "Efficient Video Object Segmentation via Network Modulation"
date: 2018-02-04 23:53:58
categories: arXiv_CV
tags: arXiv_CV Segmentation Deep_Learning Gradient_Descent
author: Linjie Yang, Yanran Wang, Xuehan Xiong, Jianchao Yang, Aggelos K. Katsaggelos
mathjax: true
---

* content
{:toc}

##### Abstract
Video object segmentation targets at segmenting a specific object throughout a video sequence, given only an annotated first frame. Recent deep learning based approaches find it effective by fine-tuning a general-purpose segmentation model on the annotated frame using hundreds of iterations of gradient descent. Despite the high accuracy these methods achieve, the fine-tuning process is inefficient and fail to meet the requirements of real world applications. We propose a novel approach that uses a single forward pass to adapt the segmentation model to the appearance of a specific object. Specifically, a second meta neural network named modulator is learned to manipulate the intermediate layers of the segmentation network given limited visual and spatial information of the target object. The experiments show that our approach is 70times faster than fine-tuning approaches while achieving similar accuracy.

##### Abstract (translated by Google)
视频对象分割目标是在整个视频序列中对特定对象进行分段，只给予注释的第一帧。最近的基于深度学习的方法通过使用数百次梯度下降迭代在标注帧上微调通用分割模型而发现其有效。尽管这些方法具有很高的准确性，但微调过程效率低下，无法满足现实应用的要求。我们提出了一种新颖的方法，使用单个正向通道来使分割模型适应特定对象的外观。具体来说，第二个称为调制器的元神经网络被学习来在给定目标对象的有限视觉和空间信息的情况下操纵分割网络的中间层。实验表明，我们的方法比微调方法快70倍，同时达到相似的精度。

##### URL
[http://arxiv.org/abs/1802.01218](http://arxiv.org/abs/1802.01218)

##### PDF
[http://arxiv.org/pdf/1802.01218](http://arxiv.org/pdf/1802.01218)

