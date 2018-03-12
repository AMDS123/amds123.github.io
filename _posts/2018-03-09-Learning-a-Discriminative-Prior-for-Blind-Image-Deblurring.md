---
layout: post
title: "Learning a Discriminative Prior for Blind Image Deblurring"
date: 2018-03-09 02:48:10
categories: arXiv_CV
tags: arXiv_CV Face CNN Quantitative
author: Lerenhan Li, Jinshan Pan, Wei-Sheng Lai, Changxin Gao, Nong Sang, Ming-Hsuan Yang
mathjax: true
---

* content
{:toc}

##### Abstract
We present an effective blind image deblurring method based on a data-driven discriminative prior.Our work is motivated by the fact that a good image prior should favor clear images over blurred images.In this work, we formulate the image prior as a binary classifier which can be achieved by a deep convolutional neural network (CNN).The learned prior is able to distinguish whether an input image is clear or not.Embedded into the maximum a posterior (MAP) framework, it helps blind deblurring in various scenarios, including natural, face, text, and low-illumination images.However, it is difficult to optimize the deblurring method with the learned image prior as it involves a non-linear CNN.Therefore, we develop an efficient numerical approach based on the half-quadratic splitting method and gradient decent algorithm to solve the proposed model.Furthermore, the proposed model can be easily extended to non-uniform deblurring.Both qualitative and quantitative experimental results show that our method performs favorably against state-of-the-art algorithms as well as domain-specific image deblurring approaches.

##### Abstract (translated by Google)
我们提出了一种基于数据驱动的判别式先验的有效的盲图像去模糊方法。我们的工作受到以下事实的启发：先验好的图像应该对模糊图像有利于清晰的图像。在本文中，我们将图像先作为二元分类器这可以通过深度卷积神经网络（CNN）来实现。学习的先验能够区分输入图像是否清晰。嵌入最大后验（MAP）框架，它有助于在各种场景下的盲目去模糊，包括自然，人脸，文本和低照度图像。但是，由于涉及到非线性CNN，因此很难优化带有学习图像的去模糊方法。因此，我们开发了一种基于半二次分裂方法和梯度下降算法对该模型进行求解。此外，该模型易于推广到非均匀去模糊化。定性和定量实验结果表明，我们的方法对最先进的算法以及特定领域的图像去模糊方法表现优异。

##### URL
[http://arxiv.org/abs/1803.03363](http://arxiv.org/abs/1803.03363)

##### PDF
[http://arxiv.org/pdf/1803.03363](http://arxiv.org/pdf/1803.03363)

