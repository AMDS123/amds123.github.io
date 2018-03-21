---
layout: post
title: "Fast End-to-End Trainable Guided Filter"
date: 2018-03-15 07:31:24
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Prediction
author: Huikai Wu, Shuai Zheng, Junge Zhang, Kaiqi Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Image processing and pixel-wise dense prediction have been advanced by harnessing the capabilities of deep learning. One central issue of deep learning is the limited capacity to handle joint upsampling. We present a deep learning building block for joint upsampling, namely guided filtering layer. This layer aims at efficiently generating the high-resolution output given the corresponding low-resolution one and a high-resolution guidance map. The proposed layer is composed of a guided filter, which is reformulated as a fully differentiable block. To this end, we show that a guided filter can be expressed as a group of spatial varying linear transformation matrices. This layer could be integrated with the convolutional neural networks (CNNs) and jointly optimized through end-to-end training. To further take advantage of end-to-end training, we plug in a trainable transformation function that generates task-specific guidance maps. By integrating the CNNs and the proposed layer, we form deep guided filtering networks. The proposed networks are evaluated on five advanced image processing tasks. Experiments on MIT-Adobe FiveK Dataset demonstrate that the proposed approach runs 10-100 times faster and achieves the state-of-the-art performance. We also show that the proposed guided filtering layer helps to improve the performance of multiple pixel-wise dense prediction tasks. The code is available at this https URL

##### Abstract (translated by Google)
通过利用深度学习的功能，图像处理和像素密集预测得到了进一步发展。深度学习的一个中心问题是处理联合升频的能力有限。我们为联合上采样提供了一个深度学习构建模块，即引导滤波层。该层旨在高效地生成高分辨率输出，并给出相应的低分辨率输出和高分辨率制导图。所提出的层由导向滤波器组成，该滤波器被重新配置为完全可微分块。为此，我们证明了一个引导滤波器可以表示为一组空间变化的线性变换矩阵。该层可以与卷积神经网络（CNN）集成并通过端到端的训练进行联合优化。为了进一步利用端到端培训，我们插入了一个可训练的转换函数，可以生成特定于任务的指导图。通过整合CNN和提出的层，我们形成深度导向滤波网络。拟议的网络在五个高级图像处理任务上进行评估。 MIT-Adobe FiveK数据集上的实验表明，所提出的方法运行速度提高了10-100倍，并达到了最先进的性能。我们还表明，提出的引导过滤层有助于提高多个像素密集预测任务的性能。该代码可在此https URL中找到

##### URL
[https://arxiv.org/abs/1803.05619](https://arxiv.org/abs/1803.05619)

##### PDF
[https://arxiv.org/pdf/1803.05619](https://arxiv.org/pdf/1803.05619)

