---
layout: post
title: "A Deep Learning Based Fast Image Saliency Detection Algorithm"
date: 2016-02-01 16:14:57
categories: arXiv_CV
tags: arXiv_CV Salient CNN Deep_Learning Detection Gradient_Descent
author: Hengyue Pan, Hui Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose a fast deep learning method for object saliency detection using convolutional neural networks. In our approach, we use a gradient descent method to iteratively modify the input images based on the pixel-wise gradients to reduce a pre-defined cost function, which is defined to measure the class-specific objectness and clamp the class-irrelevant outputs to maintain image background. The pixel-wise gradients can be efficiently computed using the back-propagation algorithm. We further apply SLIC superpixels and LAB color based low level saliency features to smooth and refine the gradients. Our methods are quite computationally efficient, much faster than other deep learning based saliency methods. Experimental results on two benchmark tasks, namely Pascal VOC 2012 and MSRA10k, have shown that our proposed methods can generate high-quality salience maps, at least comparable with many slow and complicated deep learning methods. Comparing with the pure low-level methods, our approach excels in handling many difficult images, which contain complex background, highly-variable salient objects, multiple objects, and/or very small salient objects.

##### Abstract (translated by Google)
在本文中，我们提出了一种快速的深度学习方法用于卷积神经网络的物体显着性检测。在我们的方法中，我们使用梯度下降法来迭代地修改输入图像基于逐像素渐变，以减少预定义的成本函数，它被定义为测量类特定的对象和钳类不相关输出到保持图像背景。可以使用反向传播算法有效地计算逐像素梯度。我们进一步应用SLIC超像素和基于LAB颜色的低级显着特征来平滑和细化渐变。我们的方法计算效率相当高，比其他基于深度学习的显着性方法快得多。在两项基准任务（即Pascal VOC 2012和MSRA10k）上的实验结果表明，我们提出的方法可以生成高质量的显着图，至少可以与许多缓慢而复杂的深度学习方法相媲美。与纯粹的低级方法相比，我们的方法擅长处理复杂背景，高度变化的显着对象，多个对象，和/或非常小的显着对象。

##### URL
[https://arxiv.org/abs/1602.00577](https://arxiv.org/abs/1602.00577)

##### PDF
[https://arxiv.org/pdf/1602.00577](https://arxiv.org/pdf/1602.00577)

