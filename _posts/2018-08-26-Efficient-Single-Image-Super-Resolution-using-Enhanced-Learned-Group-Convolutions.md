---
layout: post
title: "Efficient Single Image Super Resolution using Enhanced Learned Group Convolutions"
date: 2018-08-26 06:16:29
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Vandit Jain, Prakhar Bansal, Abhinav Kumar Singh, Rajeev Srivastava
mathjax: true
---

* content
{:toc}

##### Abstract
Convolutional Neural Networks (CNNs) have demonstrated great results for the single-image super-resolution (SISR) problem. Currently, most CNN algorithms promote deep and computationally expensive models to solve SISR. However, we propose a novel SISR method that uses relatively less number of computations. On training, we get group convolutions that have unused connections removed. We have refined this system specifically for the task at hand by removing unnecessary modules from original CondenseNet. Further, a reconstruction network consisting of deconvolutional layers has been used in order to upscale to high resolution. All these steps significantly reduce the number of computations required at testing time. Along with this, bicubic upsampled input is added to the network output for easier learning. Our model is named SRCondenseNet. We evaluate the method using various benchmark datasets and show that it performs favourably against the state-of-the-art methods in terms of both accuracy and number of computations required.

##### Abstract (translated by Google)
卷积神经网络（CNN）已经证明了单图像超分辨率（SISR）问题的很好结果。目前，大多数CNN算法都在推广深度和计算上昂贵的模型来解决SISR问题。然而，我们提出了一种使用相对较少数量的计算的新型SISR方法。在培训时，我们会删除未使用连接的组卷积。我们通过从原始CondenseNet中删除不必要的模块，专门针对手头的任务改进了该系统。此外，已经使用由去卷积层组成的重建网络以便升级到高分辨率。所有这些步骤都显着减少了测试时所需的计算次数。与此同时，双向上采样输入被添加到网络输出中以便于学习。我们的模型名为SRCondenseNet。我们使用各种基准数据集评估该方法，并表明它在准确性和所需计算数量方面对最先进的方法表现出良好的效果。

##### URL
[http://arxiv.org/abs/1808.08509](http://arxiv.org/abs/1808.08509)

##### PDF
[http://arxiv.org/pdf/1808.08509](http://arxiv.org/pdf/1808.08509)

