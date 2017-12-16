---
layout: post
title: "Few-shot Autoregressive Density Estimation: Towards Learning to Learn Distributions"
date: 2017-11-22 19:42:35
categories: arXiv_CV
tags: arXiv_CV Attention
author: Scott Reed, Yutian Chen, Thomas Paine, Aäron van den Oord, S. M. Ali Eslami, Danilo Rezende, Oriol Vinyals, Nando de Freitas
mathjax: true
---

* content
{:toc}

##### Abstract
Deep autoregressive models have shown state-of-the-art performance in density estimation for natural images on large-scale datasets such as ImageNet. However, such models require many thousands of gradient-based weight updates and unique image examples for training. Ideally, the models would rapidly learn visual concepts from only a handful of examples, similar to the manner in which humans learns across many vision tasks. In this paper, we show how 1) neural attention and 2) meta learning techniques can be used in combination with autoregressive models to enable effective few-shot density estimation. Our proposed modifications to PixelCNN result in state-of-the art few-shot density estimation on the Omniglot dataset. Furthermore, we visualize the learned attention policy and find that it learns intuitive algorithms for simple tasks such as image mirroring on ImageNet and handwriting on Omniglot without supervision. Finally, we extend the model to natural images and demonstrate few-shot image generation on the Stanford Online Products dataset.

##### Abstract (translated by Google)
深度自回归模型显示了大规模数据集（如ImageNet）上自然图像密度估计的最新性能。然而，这样的模型需要成千上万的基于梯度的重量更新和独特的训练图像例子。理想情况下，这些模型只能从少数几个例子中快速学习视觉概念，类似于人类在许多视觉任务中学习的方式。在本文中，我们展示了如何1）神经注意力和2）元学习技术可以结合自回归模型使用，使有效的几率密度估计。我们对PixelCNN的修改提出了Omniglot数据集中最先进的少光密度估计。此外，我们将所学习的关注策略可视化，并发现它为简单任务学习了直观的算法，例如ImageNet上的图像镜像和Omniglot上的手写，而无需监督。最后，我们将模型扩展到自然图像，并在斯坦福在线产品数据集上演示少量图像生成。

##### URL
[https://arxiv.org/abs/1710.10304](https://arxiv.org/abs/1710.10304)

##### PDF
[https://arxiv.org/pdf/1710.10304](https://arxiv.org/pdf/1710.10304)

