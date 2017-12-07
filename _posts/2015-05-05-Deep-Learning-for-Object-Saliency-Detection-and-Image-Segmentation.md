---
layout: post
title: "Deep Learning for Object Saliency Detection and Image Segmentation"
date: 2015-05-05 20:03:07
categories: arXiv_CV
tags: arXiv_CV Salient Segmentation CNN Deep_Learning Detection Gradient_Descent
author: Hengyue Pan, Bo Wang, Hui Jiang
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we propose several novel deep learning methods for object saliency detection based on the powerful convolutional neural networks. In our approach, we use a gradient descent method to iteratively modify an input image based on the pixel-wise gradients to reduce a cost function measuring the class-specific objectness of the image. The pixel-wise gradients can be efficiently computed using the back-propagation algorithm. The discrepancy between the modified image and the original one may be used as a saliency map for the image. Moreover, we have further proposed several new training methods to learn saliency-specific convolutional nets for object saliency detection, in order to leverage the available pixel-wise segmentation information. Our methods are extremely computationally efficient (processing 20-40 images per second in one GPU). In this work, we use the computed saliency maps for image segmentation. Experimental results on two benchmark tasks, namely Microsoft COCO and Pascal VOC 2012, have shown that our proposed methods can generate high-quality salience maps, clearly outperforming many existing methods. In particular, our approaches excel in handling many difficult images, which contain complex background, highly-variable salient objects, multiple objects, and/or very small salient objects.

##### Abstract (translated by Google)
在本文中，我们提出了几种基于强大的卷积神经网络的对象显着性检测的深度学习方法。在我们的方法中，我们使用梯度下降法来迭代地修改基于逐像素梯度的输入图像，以减少测量图像的类特定对象的成本函数。可以使用反向传播算法有效地计算逐像素梯度。修改后的图像与原始图像之间的差异可以用作图像的显着图。此外，我们进一步提出了一些新的训练方法来学习针对显着性的卷积网络来进行对象显着性检测，以利用可用的像素分割信息。我们的方法计算效率极高（在一个GPU中每秒处理20-40个图像）。在这项工作中，我们使用计算的显着性地图进行图像分割。在两项基准任务（即Microsoft COCO和Pascal VOC 2012）上的实验结果表明，我们提出的方法可以生成高质量的显着图，明显优于许多现有的方法。特别是，我们的方法擅长处理许多复杂的背景，高度变化的显着对象，多个对象，和/或非常小的显着对象。

##### URL
[https://arxiv.org/abs/1505.01173](https://arxiv.org/abs/1505.01173)

##### PDF
[https://arxiv.org/pdf/1505.01173](https://arxiv.org/pdf/1505.01173)

