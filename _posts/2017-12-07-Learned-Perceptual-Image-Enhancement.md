---
layout: post
title: "Learned Perceptual Image Enhancement"
date: 2017-12-07 21:23:12
categories: arXiv_CV
tags: arXiv_CV Image_Enhancement CNN Inference
author: Hossein Talebi, Peyman Milanfar
mathjax: true
---

* content
{:toc}

##### Abstract
Learning a typical image enhancement pipeline involves minimization of a loss function between enhanced and reference images. While L1 and L2 losses are perhaps the most widely used functions for this purpose, they do not necessarily lead to perceptually compelling results. In this paper, we show that adding a learned no-reference image quality metric to the loss can significantly improve enhancement operators. This metric is implemented using a CNN (convolutional neural network) trained on a large-scale dataset labelled with aesthetic preferences of human raters. This loss allows us to conveniently perform back-propagation in our learning framework to simultaneously optimize for similarity to a given ground truth reference and perceptual quality. This perceptual loss is only used to train parameters of image processing operators, and does not impose any extra complexity at inference time. Our experiments demonstrate that this loss can be effective for tuning a variety of operators such as local tone mapping and dehazing.

##### Abstract (translated by Google)
学习典型的图像增强流水线涉及增强图像和参考图像之间的损失函数的最小化。虽然L1和L2的损失也许是用于此目的最广泛使用的功能，但它们并不一定会导致令人信服的令人信服的结果。在本文中，我们表明，增加一个学习的无参考图像质量度量的损失可以显着改善增强算子。这个度量是通过使用一个CNN（卷积神经网络）来实现的，这个网络在一个大规模的数据集上进行训练，这个数据集标有人类评价者的审美偏好。这种损失使我们能够在我们的学习框架中方便地执行反向传播，以同时优化与给定的地面真实参考和感知质量的相似性。这种感知损失仅用于训练图像处理操作者的参数，并且在推理时不会增加额外的复杂度。我们的实验表明，这种损失可以有效地调整各种运营商，如本地色调映射和除雾。

##### URL
[http://arxiv.org/abs/1712.02864](http://arxiv.org/abs/1712.02864)

##### PDF
[http://arxiv.org/pdf/1712.02864](http://arxiv.org/pdf/1712.02864)

