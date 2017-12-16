---
layout: post
title: "Pixel Objectness"
date: 2017-04-12 07:36:44
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Segmentation CNN Prediction
author: Suyog Dutt Jain, Bo Xiong, Kristen Grauman
mathjax: true
---

* content
{:toc}

##### Abstract
We propose an end-to-end learning framework for generating foreground object segmentations. Given a single novel image, our approach produces pixel-level masks for all "object-like" regions---even for object categories never seen during training. We formulate the task as a structured prediction problem of assigning foreground/background labels to all pixels, implemented using a deep fully convolutional network. Key to our idea is training with a mix of image-level object category examples together with relatively few images with boundary-level annotations. Our method substantially improves the state-of-the-art on foreground segmentation for ImageNet and MIT Object Discovery datasets. Furthermore, on over 1 million images, we show that it generalizes well to segment object categories unseen in the foreground maps used for training. Finally, we demonstrate how our approach benefits image retrieval and image retargeting, both of which flourish when given our high-quality foreground maps.

##### Abstract (translated by Google)
我们提出了一个端到端的学习框架来生成前景对象分割。给定一个新颖的图像，我们的方法为所有“类似物体”的区域生成像素级的蒙版 - 即使是在训练期间从未见过的物体类别。我们把这个任务作为一个结构化的预测问题，把前景/背景标签分配给所有的像素，用深度完全卷积网络来实现。我们想法的关键是将图像级别的对象类别示例与相对较少的带有边界级别注释的图像混合在一起进行训练。我们的方法大大改善了ImageNet和MIT Object Discovery数据集的前景分割技术。此外，在超过100万的图像上，我们展示了它很好地概括了在用于训练的前景地图中看不见的对象类别。最后，我们演示了我们的方法如何有益于图像检索和图像重定向，在给定高质量的前景地图时，这两种方法都会蓬勃发展。

##### URL
[https://arxiv.org/abs/1701.05349](https://arxiv.org/abs/1701.05349)

##### PDF
[https://arxiv.org/pdf/1701.05349](https://arxiv.org/pdf/1701.05349)

