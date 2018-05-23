---
layout: post
title: "Autofocus Layer for Semantic Segmentation"
date: 2018-05-22 05:35:20
categories: arXiv_CV
tags: arXiv_CV Segmentation Attention GAN CNN Semantic_Segmentation
author: Yao Qin, Konstantinos Kamnitsas, Siddarth Ancha, Jay Nanavati, Garrison Cottrell, Antonio Criminisi, Aditya Nori
mathjax: true
---

* content
{:toc}

##### Abstract
We propose the autofocus convolutional layer for semantic segmentation with the objective of enhancing the capabilities of neural networks for multi-scale processing. Autofocus layers adaptively change the size of the effective receptive field based on the processed context to generate more powerful features. This is achieved by parallelising multiple convolutional layers with different dilation rates, combined by an attention mechanism that learns to focus on the optimal scales driven by context. By sharing the weights of the parallel convolutions we introduce only a small number of trainable parameters. The proposed autofocus layer can be easily integrated into existing networks to cope with biological variability among tasks. We evaluate our models on the challenging tasks of multi-organ segmentation in pelvic CT and brain tumor segmentation in MRI and achieve very promising performance.

##### Abstract (translated by Google)
我们提出了用于语义分割的自动对焦卷积层，目的是提高神经网络在多尺度处理中的能力。自动对焦图层根据处理的上下文自适应地更改有效接受区域的大小，以生成更强大的功能。这是通过并行化具有不同膨胀率的多个卷积层，并结合注意机制来学习以关注由上下文驱动的最佳尺度。通过共享平行卷积的权重，我们只引入少量的可训练参数。建议的自动对焦层可以很容易地集成到现有的网络，以应付任务间的生物变异。我们评估我们的模型，对骨盆CT中的多器官分割和MRI中的脑肿瘤分割的具有挑战性的任务进行评估，并获得非常有前途的表现。

##### URL
[https://arxiv.org/abs/1805.08403](https://arxiv.org/abs/1805.08403)

##### PDF
[https://arxiv.org/pdf/1805.08403](https://arxiv.org/pdf/1805.08403)

