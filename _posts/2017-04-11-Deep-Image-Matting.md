---
layout: post
title: "Deep Image Matting"
date: 2017-04-11 00:57:05
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Prediction
author: Ning Xu, Brian Price, Scott Cohen, Thomas Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Image matting is a fundamental computer vision problem and has many applications. Previous algorithms have poor performance when an image has similar foreground and background colors or complicated textures. The main reasons are prior methods 1) only use low-level features and 2) lack high-level context. In this paper, we propose a novel deep learning based algorithm that can tackle both these problems. Our deep model has two parts. The first part is a deep convolutional encoder-decoder network that takes an image and the corresponding trimap as inputs and predict the alpha matte of the image. The second part is a small convolutional network that refines the alpha matte predictions of the first network to have more accurate alpha values and sharper edges. In addition, we also create a large-scale image matting dataset including 49300 training images and 1000 testing images. We evaluate our algorithm on the image matting benchmark, our testing set, and a wide variety of real images. Experimental results clearly demonstrate the superiority of our algorithm over previous methods.

##### Abstract (translated by Google)
图像抠像是一个基本的计算机视觉问题，有很多应用。当图像具有相似的前景和背景颜色或复杂的纹理时，以前的算法性能较差。主要原因是以前的方法1）只使用低级特征2）缺少高级上下文。在本文中，我们提出了一种新的深度学习算法，可以解决这两个问题。我们的深层模型有两个部分。第一部分是深度卷积编码器 - 解码器网络，它将图像和相应的trimap作为输入，并预测图像的alpha遮罩。第二部分是一个小的卷积网络，它改进了第一个网络的alpha遮罩预测，以获得更准确的alpha值和更锐利的边缘。此外，我们还创建了一个大规模的图像数据集，包括49300个训练图像和1000个测试图像。我们评估我们的算法在图像抠像基准测试，我们的测试集和各种各样的真实图像。实验结果清楚地证明了我们的算法优于以前的方法。

##### URL
[https://arxiv.org/abs/1703.03872](https://arxiv.org/abs/1703.03872)

##### PDF
[https://arxiv.org/pdf/1703.03872](https://arxiv.org/pdf/1703.03872)

