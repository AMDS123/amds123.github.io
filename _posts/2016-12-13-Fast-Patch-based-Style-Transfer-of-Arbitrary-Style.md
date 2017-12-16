---
layout: post
title: "Fast Patch-based Style Transfer of Arbitrary Style"
date: 2016-12-13 20:05:37
categories: arXiv_CV
tags: arXiv_CV Style_Transfer CNN Optimization
author: Tian Qi Chen, Mark Schmidt
mathjax: true
---

* content
{:toc}

##### Abstract
Artistic style transfer is an image synthesis problem where the content of an image is reproduced with the style of another. Recent works show that a visually appealing style transfer can be achieved by using the hidden activations of a pretrained convolutional neural network. However, existing methods either apply (i) an optimization procedure that works for any style image but is very expensive, or (ii) an efficient feedforward network that only allows a limited number of trained styles. In this work we propose a simpler optimization objective based on local matching that combines the content structure and style textures in a single layer of the pretrained network. We show that our objective has desirable properties such as a simpler optimization landscape, intuitive parameter tuning, and consistent frame-by-frame performance on video. Furthermore, we use 80,000 natural images and 80,000 paintings to train an inverse network that approximates the result of the optimization. This results in a procedure for artistic style transfer that is efficient but also allows arbitrary content and style images.

##### Abstract (translated by Google)
艺术风格转移是一种图像合成问题，其中图像的内容是以另一种风格再现的。最近的研究表明，通过使用预训练的卷积神经网络的隐藏激活，可以实现视觉上吸引人的风格转移。然而，现有的方法要么应用（i）适用于任何样式图像但是非常昂贵的优化过程，或者（ii）仅允许有限数量的训练样式的高效的前馈网络。在这项工作中，我们提出了一个基于局部匹配的简单的优化目标，它将内容结构和样式纹理结合在一个预训练网络的单层中。我们展示了我们的目标具有理想的特性，例如更简单的优化格局，直观的参数调整以及视频上一致的逐帧性能。此外，我们使用8万幅自然图像和8万幅绘画来训练近似优化结果的逆网络。这导致了艺术风格转换的程序是高效的，但也允许任意的内容和风格的图像。

##### URL
[https://arxiv.org/abs/1612.04337](https://arxiv.org/abs/1612.04337)

##### PDF
[https://arxiv.org/pdf/1612.04337](https://arxiv.org/pdf/1612.04337)

