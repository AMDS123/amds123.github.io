---
layout: post
title: "Clearing the Skies: A deep network architecture for single-image rain removal"
date: 2017-02-06 19:53:29
categories: arXiv_CV
tags: arXiv_CV Knowledge Image_Enhancement CNN Relation
author: Xueyang Fu, Jiabin Huang, Xinghao Ding, Yinghao Liao, John Paisley
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce a deep network architecture called DerainNet for removing rain streaks from an image. Based on the deep convolutional neural network (CNN), we directly learn the mapping relationship between rainy and clean image detail layers from data. Because we do not possess the ground truth corresponding to real-world rainy images, we synthesize images with rain for training. In contrast to other common strategies that increase depth or breadth of the network, we use image processing domain knowledge to modify the objective function and improve deraining with a modestly-sized CNN. Specifically, we train our DerainNet on the detail (high-pass) layer rather than in the image domain. Though DerainNet is trained on synthetic data, we find that the learned network translates very effectively to real-world images for testing. Moreover, we augment the CNN framework with image enhancement to improve the visual results. Compared with state-of-the-art single image de-raining methods, our method has improved rain removal and much faster computation time after network training.

##### Abstract (translated by Google)
我们引入了一个名为DerainNet的深层网络体系结构，用于从图像中去除雨点。在深度卷积神经网络（CNN）的基础上，直接从数据中学习雨雪清晰图像细节层的映射关系。因为我们不具备与现实世界中的多雨图像相对应的基本事实，所以我们合成图像与雨水进行训练。与其他增加网络深度或广度的常用策略相比，我们使用图像处理领域知识来修改目标函数，并通过适度大小的CNN来改善排序。具体来说，我们在细节（高通）层上而不是在图像域上训练DerainNet。尽管DerainNet训练了合成数据，但我们发现，学习网络可以非常有效地转换为真实世界的图像进行测试。此外，我们通过增强图像增强的CNN框架来提高视觉效果。与先进的单幅图像降噪方法相比，本方法在网络训练后有较好的降雨效果和较快的计算时间。

##### URL
[https://arxiv.org/abs/1609.02087](https://arxiv.org/abs/1609.02087)

##### PDF
[https://arxiv.org/pdf/1609.02087](https://arxiv.org/pdf/1609.02087)

