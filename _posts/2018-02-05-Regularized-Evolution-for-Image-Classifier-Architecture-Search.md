---
layout: post
title: "Regularized Evolution for Image Classifier Architecture Search"
date: 2018-02-05 18:20:52
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning
author: Esteban Real, Alok Aggarwal, Yanping Huang, Quoc V Le
mathjax: true
---

* content
{:toc}

##### Abstract
The effort devoted to hand-crafting image classifiers has motivated the use of architecture search to discover them automatically. Reinforcement learning and evolution have both shown promise for this purpose. This study introduces a regularized version of a popular asynchronous evolutionary algorithm. We rigorously compare it to the non-regularized form and to a highly-successful reinforcement learning baseline. Using the same hardware, compute effort and neural network training code, we conduct repeated experiments side-by-side, exploring different datasets, search spaces and scales. We show regularized evolution consistently produces models with similar or higher accuracy, across a variety of contexts without need for re-tuning parameters. In addition, regularized evolution exhibits considerably better performance than reinforcement learning at early search stages, suggesting it may be the better choice when fewer compute resources are available. This constitutes the first controlled comparison of the two search algorithms in this context. Finally, we present new architectures discovered with regularized evolution that we nickname AmoebaNets. These models set a new state of the art for CIFAR-10 (mean test error = 2.13%) and mobile-size ImageNet (top-5 accuracy = 92.1% with 5.06M parameters), and reach the current state of the art for ImageNet (top-5 accuracy = 96.2%).

##### Abstract (translated by Google)
致力于手工制作图像分类器的努力已经促使使用架构搜索来自动发现它们。为了这个目的，强化学习和进化已经显示出前景。本研究介绍了一种流行的异步进化算法的正则化版本。我们严格地将其与非正规化形式和高度成功的强化学习基线进行比较。使用相同的硬件，计算工作量和神经网络训练代码，我们并排重复实验，探索不同的数据集，搜索空间和尺度。我们展示正规化的进化一贯产生具有相似或更高准确性的模型，跨越各种情况而不需要重新调整参数。另外，在早期搜索阶段，正则化进化比强化学习表现出更好的性能，这表明当更少的计算资源可用时，它可能是更好的选择。这构成了在这种情况下两种搜索算法的第一个受控比较。最后，我们展示了我们称之为AmoebaNets的正规化进化所发现的新架构。这些模型为CIFAR-10（平均测试误差= 2.13％）和移动大小的ImageNet（前5精度= 92.1％，5.06M参数）设置了最新的技术水平，并且达到了ImageNet的最新技术水平（前5精度= 96.2％）。

##### URL
[http://arxiv.org/abs/1802.01548](http://arxiv.org/abs/1802.01548)

##### PDF
[http://arxiv.org/pdf/1802.01548](http://arxiv.org/pdf/1802.01548)

