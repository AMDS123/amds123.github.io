---
layout: post
title: "When Image Denoising Meets High-Level Vision Tasks: A Deep Learning Approach"
date: 2017-09-05 03:30:51
categories: arXiv_CV
tags: arXiv_CV Knowledge Segmentation CNN Image_Classification Semantic_Segmentation Optimization Classification Deep_Learning
author: Ding Liu, Bihan Wen, Xianming Liu, Thomas S. Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Conventionally, image denoising and high-level vision tasks are handled separately in computer vision, and their connection is fragile. In this paper, we cope with the two jointly and explore the mutual influence between them with the focus on two questions, namely (1) how image denoising can help solving high-level vision problems, and (2) how the semantic information from high-level vision tasks can be used to guide image denoising. First we propose a deep convolutional neural network for image denoising which is able to outperform the state-of-the-art. Second we propose a deep neural network solution that cascades two modules for image denoising and various high-level tasks, respectively, and propose the use of joint loss for updating only the denoising network to allow the semantic information flowing into the optimization of the denoising network via back-propagation. Our experimental results demonstrate that on one hand, the proposed architecture is able to overcome the performance degradation of different high-level vision tasks, e.g., image classification and semantic segmentation, due to image noise or artifacts caused by conventional denoising approaches such as over-smoothing. On the other hand, with the guidance of high-level vision information, the denoising network can further preserve more fine details and generate more visually appealing results. To the best of our knowledge, this is the first work to systematically investigate the benefit of using high-level vision semantics for image denoising via deep learning.

##### Abstract (translated by Google)
传统上，图像去噪和高级视觉任务在计算机视觉中是分开处理的，它们之间的联系是脆弱的。在本文中，我们共同探讨两者之间的相互影响，重点研究两个问题，即（1）图像去噪如何能够帮助解决高层次的视觉问题;（2）来自高层的语义信息水平视觉任务可以用来指导图像去噪。首先，我们提出一个深度卷积神经网络的图像去噪，它能够超越最先进的技术。其次，我们提出了一种深度神经网络解决方案，分别将图像去噪和各种高层任务级联成两个模块，并提出使用联合损失来仅更新去噪网络，使语义信息流入去噪网络的优化通过反向传播。我们的实验结果表明，一方面，由于图像噪声或传统的去噪方法造成的人为噪声，例如过度的噪声，所提出的体系结构能够克服不同高级别视觉任务（例如，图像分类和语义分割）平滑。另一方面，在高层视觉信息的引导下，去噪网络可以进一步保留更多细节，产生更具视觉吸引力的效果。据我们所知，这是第一个系统地研究通过深度学习使用高级视觉语义来进行图像去噪的好处的工作。

##### URL
[https://arxiv.org/abs/1706.04284](https://arxiv.org/abs/1706.04284)

##### PDF
[https://arxiv.org/pdf/1706.04284](https://arxiv.org/pdf/1706.04284)

