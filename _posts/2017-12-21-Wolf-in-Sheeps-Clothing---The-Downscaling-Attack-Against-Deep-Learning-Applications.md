---
layout: post
title: "Wolf in Sheep's Clothing - The Downscaling Attack Against Deep Learning Applications"
date: 2017-12-21 06:17:43
categories: arXiv_CV
tags: arXiv_CV Image_Classification Classification Deep_Learning
author: Qixue Xiao, Kang Li, Deyue Zhang, Yier Jin
mathjax: true
---

* content
{:toc}

##### Abstract
This paper considers security risks buried in the data processing pipeline in common deep learning applications. Deep learning models usually assume a fixed scale for their training and input data. To allow deep learning applications to handle a wide range of input data, popular frameworks, such as Caffe, TensorFlow, and Torch, all provide data scaling functions to resize input to the dimensions used by deep learning models. Image scaling algorithms are intended to preserve the visual features of an image after scaling. However, common image scaling algorithms are not designed to handle human crafted images. Attackers can make the scaling outputs look dramatically different from the corresponding input images. 
 This paper presents a downscaling attack that targets the data scaling process in deep learning applications. By carefully crafting input data that mismatches with the dimension used by deep learning models, attackers can create deceiving effects. A deep learning application effectively consumes data that are not the same as those presented to users. The visual inconsistency enables practical evasion and data poisoning attacks to deep learning applications. This paper presents proof-of-concept attack samples to popular deep-learning-based image classification applications. To address the downscaling attacks, the paper also suggests multiple potential mitigation strategies.

##### Abstract (translated by Google)
本文考虑了数据处理流程中隐藏的常见深度学习应用中的安全风险。深度学习模型通常假定他们的训练和输入数据是固定的。为了允许深度学习应用程序处理广泛的输入数据，流行的框架（如Caffe，TensorFlow和Torch）都提供了数据缩放功能，以将输入调整为深度学习模型使用的维度。图像缩放算法旨在在缩放后保留图像的视觉特征。但是，常见的图像缩放算法并不是用来处理人造图像的。攻击者可以使缩放输出与对应的输入图像显着不同。
 本文提出了一种针对深度学习应用中的数据缩放过程的缩减攻击。通过仔细制作与深度学习模型所使用的维度不匹配的输入数据，攻击者可以创造欺骗效果。深度学习应用程序有效地使用与提供给用户的数据不同的数据。视觉不一致性使实际逃避和数据中毒攻击深度学习应用程序。本文将概念证明攻击样本提供给流行的基于深度学习的图像分类应用。为了解决降尺度攻击，本文还提出了多种潜在的缓解策略。

##### URL
[http://arxiv.org/abs/1712.07805](http://arxiv.org/abs/1712.07805)

##### PDF
[http://arxiv.org/pdf/1712.07805](http://arxiv.org/pdf/1712.07805)

