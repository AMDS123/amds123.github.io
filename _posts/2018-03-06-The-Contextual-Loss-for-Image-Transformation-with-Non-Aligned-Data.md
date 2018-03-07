---
layout: post
title: "The Contextual Loss for Image Transformation with Non-Aligned Data"
date: 2018-03-06 09:43:25
categories: arXiv_CV
tags: arXiv_CV Face
author: Roey Mechrez, Itamar Talmi, Lihi Zelnik-Manor
mathjax: true
---

* content
{:toc}

##### Abstract
Feed-forward CNNs trained for image transformation problems rely on loss functions that measure the similarity between the generated image and a target image. Most of the common loss functions assume that these images are spatially aligned and compare pixels at corresponding locations. However, for many tasks, aligned training pairs of images will not be available. We present an alternative loss function that does not require alignment, thus providing an effective and simple solution for a new space of problems. Our loss is based on both context and semantics -- it compares regions with similar semantic meaning, while considering the context of the entire image. Hence, for example, when transferring the style of one face to another, it will translate eyes-to-eyes and mouth-to-mouth.

##### Abstract (translated by Google)
针对图像转换问题训练的前馈CNN依赖于损失函数，该函数测量生成的图像与目标图像之间的相似性。大多数常见损失函数都假设这些图像在空间上是对齐的，并比较相应位置的像素。但是，对于许多任务来说，对齐的训练对图像将不可用。我们提出了一种不需要对齐的替代损失函数，从而为新的问题空间提供了有效且简单的解决方案。我们的损失是基于上下文和语义 - 它会比较具有相似语义含义的区域，同时考虑整个图像的上下文。因此，例如，当将一个脸部的风格转移到另一个脸部时，它将转换成眼睛和嘴对嘴。

##### URL
[http://arxiv.org/abs/1803.02077](http://arxiv.org/abs/1803.02077)

##### PDF
[http://arxiv.org/pdf/1803.02077](http://arxiv.org/pdf/1803.02077)

