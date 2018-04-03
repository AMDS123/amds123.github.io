---
layout: post
title: "Semantic Adversarial Examples"
date: 2018-03-16 18:02:14
categories: arXiv_AI
tags: arXiv_AI Adversarial Optimization Prediction
author: Hossein Hosseini, Radha Poovendran
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks are known to be vulnerable to adversarial examples, i.e., images that are maliciously perturbed to fool the model. Generating adversarial examples has been mostly limited to finding small perturbations that maximize the model prediction error. Such images, however, contain artificial perturbations that make them somewhat distinguishable from natural images. This property is used by several defense methods to counter adversarial examples by applying denoising filters or training the model to be robust to small perturbations. 
 In this paper, we introduce a new class of adversarial examples, namely "Semantic Adversarial Examples," as images that are arbitrarily perturbed to fool the model, but in such a way that the modified image semantically represents the same object as the original image. We formulate the problem of generating such images as a constrained optimization problem and develop an adversarial transformation based on the shape bias property of human cognitive system. In our method, we generate adversarial images by first converting the RGB image into the HSV (Hue, Saturation and Value) color space and then randomly shifting the Hue and Saturation components, while keeping the Value component the same. Our experimental results on CIFAR10 dataset show that the accuracy of VGG16 network on adversarial color-shifted images is 5.7%.

##### Abstract (translated by Google)
已知深度神经网络容易受到敌对性例子的影响，即恶意扰乱的图像来欺骗模型。生成敌对的例子大多局限于寻找最大化模型预测误差的小扰动。然而，这样的图像包含人造干扰，使它们与自然图像有些区别。这种性质被几种防御方法用来抵消敌对性的例子，通过应用去噪滤波器或训练模型对小扰动具有鲁棒性。
 在本文中，我们引入了一类新的对抗性例子，即“语义敌对性例子”，它们是被任意扰动以欺骗模型的图像，但是这样一种方式是修改后的图像在语义上表示与原始图像相同的对象。我们将这些图像生成为一个约束优化问题，并根据人类认知系统的形状偏差性质进行对抗性转换。在我们的方法中，我们首先将RGB图像转换为HSV（色调，饱和度和色彩）色彩空间，然后随机地移动色相和饱和度分量，同时保持Value分量相同，从而生成敌对图像。我们在CIFAR10数据集上的实验结果表明，VGG16网络在对抗色移图像上的准确率为5.7％。

##### URL
[http://arxiv.org/abs/1804.00499](http://arxiv.org/abs/1804.00499)

##### PDF
[http://arxiv.org/pdf/1804.00499](http://arxiv.org/pdf/1804.00499)

