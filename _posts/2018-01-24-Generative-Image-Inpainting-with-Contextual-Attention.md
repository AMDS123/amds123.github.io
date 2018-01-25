---
layout: post
title: "Generative Image Inpainting with Contextual Attention"
date: 2018-01-24 08:04:55
categories: arXiv_CV
tags: arXiv_CV Attention Face CNN Deep_Learning Prediction
author: Jiahui Yu, Zhe Lin, Jimei Yang, Xiaohui Shen, Xin Lu, Thomas S. Huang
mathjax: true
---

* content
{:toc}

##### Abstract
Recent deep learning based approaches have shown promising results on image inpainting for the challenging task of filling in large missing regions in an image. These methods can generate visually plausible image structures and textures, but often create distorted structures or blurry textures inconsistent with surrounding areas. This is mainly due to ineffectiveness of convolutional neural networks in explicitly borrowing or copying information from distant spatial locations. On the other hand, traditional texture and patch synthesis approaches are particularly suitable when it needs to borrow textures from the surrounding regions. Motivated by these observations, we propose a new deep generative model-based approach which can not only synthesize novel image structures but also explicitly utilize surrounding image features as references during network training to make better predictions. The model is a feed-forward, fully convolutional neural network which can process images with multiple holes at arbitrary locations and with variable sizes during the test time. Experiments on multiple datasets including faces, textures and natural images demonstrate that the proposed approach generates higher-quality inpainting results than existing ones. Code and trained models will be released.

##### Abstract (translated by Google)
最近的基于深度学习的方法已经在图像修复上显示出有希望的结果，用于填充图像中的大缺失区域的具有挑战性的任务。这些方法可以产生视觉上合理的图像结构和纹理，但是通常会产生与周围区域不一致的扭曲结构或模糊纹理。这主要是由于卷积神经网络在从远处空间位置明确地借用或复制信息方面是无效的。另一方面，当需要从周围地区借用纹理时，传统的纹理和贴片合成方法是特别合适的。在这些观察的启发下，我们提出了一种新的基于深度生成模型的方法，不仅可以合成新的图像结构，还可以在网络训练过程中明确地利用周围的图像特征作为参考，做出更好的预测。该模型是一个前馈完全卷积神经网络，它可以在测试时间内在任意位置以不同大小处理具有多个孔的图像。在包括人脸，纹理和自然图像的多个数据集上的实验表明，所提出的方法产生比现有方法更高质量的修复结果。代码和训练有素的模型将被发布。

##### URL
[http://arxiv.org/abs/1801.07892](http://arxiv.org/abs/1801.07892)

##### PDF
[http://arxiv.org/pdf/1801.07892](http://arxiv.org/pdf/1801.07892)

