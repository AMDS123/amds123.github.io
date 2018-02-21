---
layout: post
title: "Stroke Controllable Fast Style Transfer with Adaptive Receptive Fields"
date: 2018-02-20 13:21:53
categories: arXiv_CV
tags: arXiv_CV Style_Transfer
author: Yongcheng Jing, Yang Liu, Yezhou Yang, Zunlei Feng, Yizhou Yu, Mingli Song
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, in the community of Neural Style Transfer, several algorithms are proposed to transfer an artistic style in real-time, which is known as Fast Style Transfer. However, controlling the stroke size in stylized results still remains an open challenge. To achieve controllable stroke sizes, several attempts were made including training multiple models and resizing the input image in a variety of scales, respectively. However, their results are not promising regarding the efficiency and quality. In this paper, we present a stroke controllable style transfer network that incorporates different stroke sizes into one single model. Firstly, by analyzing the factors that influence the stroke size, we adopt the idea that both the receptive field and the style image scale should be taken into consideration for most cases. Then we propose a StrokePyramid module to endow the network with adaptive receptive fields, and two training strategies to achieve faster convergence and augment new stroke sizes upon a trained model respectively. Finally, by combining the proposed runtime control techniques, our network can produce distinct stroke sizes in different output images or different spatial regions within the same output image. The experimental results demonstrate that with almost the same number of parameters as the previous Fast Style Transfer algorithm, our network can transfer an artistic style in a stroke controllable manner.

##### Abstract (translated by Google)
最近，在Neural Style Transfer社区中，提出了几种实时传输艺术风格的算法，即Fast Style Transfer。然而，在程式化结果中控制笔画大小仍然是一个公开挑战。为了实现可控的笔画大小，分别进行了多次尝试，包括训练多个模型并以各种比例调整输入图像的大小。然而，他们的结果在效率和质量方面并不乐观。在这篇文章中，我们提出了一个笔画可控的风格转移网络，将不同的笔画大小合并到一个模型中。首先通过分析影响中风大小的因素，认为大多数情况下都应考虑感受野和风格图像尺度。然后，我们提出了一个StrokePyramid模块来赋予网络自适应接受领域，并且两种训练策略分别实现更快的收敛和增加新的笔画大小。最后，通过结合所提出的运行时控制技术，我们的网络可以在不同的输出图像或相同输出图像内的不同空间区域中产生不同的笔划大小。实验结果表明，与之前的Fast Style Transfer算法具有几乎相同的参数数量，我们的网络可以以笔画可控的方式传输艺术风格。

##### URL
[http://arxiv.org/abs/1802.07101](http://arxiv.org/abs/1802.07101)

##### PDF
[http://arxiv.org/pdf/1802.07101](http://arxiv.org/pdf/1802.07101)

