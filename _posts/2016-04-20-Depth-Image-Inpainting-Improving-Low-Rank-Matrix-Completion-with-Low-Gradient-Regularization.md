---
layout: post
title: "Depth Image Inpainting: Improving Low Rank Matrix Completion with Low Gradient Regularization"
date: 2016-04-20 04:56:06
categories: arXiv_CV
tags: arXiv_CV Regularization Sparse
author: Hongyang Xue, Shengming Zhang, Deng Cai
mathjax: true
---

* content
{:toc}

##### Abstract
We consider the case of inpainting single depth images. Without corresponding color images, previous or next frames, depth image inpainting is quite challenging. One natural solution is to regard the image as a matrix and adopt the low rank regularization just as inpainting color images. However, the low rank assumption does not make full use of the properties of depth images. A shallow observation may inspire us to penalize the non-zero gradients by sparse gradient regularization. However, statistics show that though most pixels have zero gradients, there is still a non-ignorable part of pixels whose gradients are equal to 1. Based on this specific property of depth images , we propose a low gradient regularization method in which we reduce the penalty for gradient 1 while penalizing the non-zero gradients to allow for gradual depth changes. The proposed low gradient regularization is integrated with the low rank regularization into the low rank low gradient approach for depth image inpainting. We compare our proposed low gradient regularization with sparse gradient regularization. The experimental results show the effectiveness of our proposed approach.

##### Abstract (translated by Google)
我们考虑修改单个深度图像的情况。没有相应的彩色图像，前一帧或下一帧，深度图像修复是相当具有挑战性的。一个自然的解决办法就是把图像看作一个矩阵，就像修改彩色图像一样采用低秩正则化。然而，低秩假设并没有充分利用深度图像的属性。浅层观察可能会激发我们通过稀疏梯度正则化惩罚非零梯度。但统计结果表明，虽然大部分像元的梯度都是零，但梯度等于1的像素仍有不可忽略的部分。基于深度图像的这种特殊性质，我们提出了一种低梯度正则化方法，惩罚梯度1，同时惩罚非零梯度以允许逐渐深度改变。提出的低梯度正则化与低秩正则化方法相结合，构成了低阶低梯度方法进行深度图像修复。我们比较我们提出的低梯度正则化与稀疏梯度正则化。实验结果表明了我们提出的方法的有效性。

##### URL
[https://arxiv.org/abs/1604.05817](https://arxiv.org/abs/1604.05817)

##### PDF
[https://arxiv.org/pdf/1604.05817](https://arxiv.org/pdf/1604.05817)

