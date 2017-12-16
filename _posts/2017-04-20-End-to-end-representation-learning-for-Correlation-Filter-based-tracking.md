---
layout: post
title: "End-to-end representation learning for Correlation Filter based tracking"
date: 2017-04-20 07:51:27
categories: arXiv_CV
tags: arXiv_CV Object_Detection Tracking Object_Tracking Represenation_Learning Detection Relation
author: Jack Valmadre, Luca Bertinetto, João F. Henriques, Andrea Vedaldi, Philip H. S. Torr
mathjax: true
---

* content
{:toc}

##### Abstract
The Correlation Filter is an algorithm that trains a linear template to discriminate between images and their translations. It is well suited to object tracking because its formulation in the Fourier domain provides a fast solution, enabling the detector to be re-trained once per frame. Previous works that use the Correlation Filter, however, have adopted features that were either manually designed or trained for a different task. This work is the first to overcome this limitation by interpreting the Correlation Filter learner, which has a closed-form solution, as a differentiable layer in a deep neural network. This enables learning deep features that are tightly coupled to the Correlation Filter. Experiments illustrate that our method has the important practical benefit of allowing lightweight architectures to achieve state-of-the-art performance at high framerates.

##### Abstract (translated by Google)
相关滤波器是训练线性模板以区分图像及其翻译的算法。它非常适合对象跟踪，因为它在傅里叶域中的表达提供了一个快速的解决方案，使检测器每帧重新训练一次。然而，之前使用相关滤波器的作品已经采用了手动设计或者针对不同任务进行训练的特征。这项工作是第一个克服了这个限制的解释，相关滤波器的学习者，它是一个封闭的解决方案，作为一个深层神经网络的可微分层。这样可以学习与关联过滤器紧密耦合的深层功能。实验表明，我们的方法具有重要的实际好处，即允许轻量级体系结构在高帧率下实现最先进的性能。

##### URL
[https://arxiv.org/abs/1704.06036](https://arxiv.org/abs/1704.06036)

##### PDF
[https://arxiv.org/pdf/1704.06036](https://arxiv.org/pdf/1704.06036)

