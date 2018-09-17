---
layout: post
title: "Style Augmentation: Data Augmentation via Style Randomization"
date: 2018-09-14 12:34:36
categories: arXiv_CV
tags: arXiv_CV Style_Transfer Embedding CNN Classification
author: Philip T. Jackson, Amir Atapour-Abarghouei, Stephen Bonner, Toby Breckon, Boguslaw Obara
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce style augmentation, a new form of data augmentation based on random style transfer, for improving the robustness of convolutional neural networks (CNN) over both classification and regression based tasks. During training, our style augmentation randomizes texture, contrast and color, while preserving shape and semantic content. This is accomplished by adapting an arbitrary style transfer network to perform style randomization, by sampling input style embeddings from a multivariate normal distribution instead of inferring them from a style image. In addition to standard classification experiments, we investigate the effect of style augmentation (and data augmentation generally) on domain transfer tasks. We find that data augmentation significantly improves robustness to domain shift, and can be used as a simple, domain agnostic alternative to domain adaptation. Comparing style augmentation against a mix of seven traditional augmentation techniques, we find that it can be readily combined with them to improve network performance. We validate the efficacy of our technique with domain transfer experiments in classification and monocular depth estimation, illustrating consistent improvements in generalization.

##### Abstract (translated by Google)
我们引入了样式增强，一种基于随机样式传递的新形式的数据增强，用于提高卷积神经网络（CNN）在分类和基于回归的任务上的鲁棒性。在训练过程中，我们的风格增强使纹理，对比度和颜色随机化，同时保留形状和语义内容。这是通过调整任意样式传输网络来执行样式随机化，通过从多元正态分布中采样输入样式嵌入而不是从样式图像推断它们来实现的。除了标准分类实验，我们还研究了样式扩充（以及通常的数据扩充）对域转移任务的影响。我们发现数据增强显着提高了对域移位的鲁棒性，并且可以用作域自适应的简单，域不可知替代方案。将样式增强与七种传统增强技术的混合进行比较，我们发现它可以很容易地与它们结合以提高网络性能。我们在分类和单眼深度估计中验证了我们的技术与域转移实验的功效，说明了泛化的一致性改进。

##### URL
[http://arxiv.org/abs/1809.05375](http://arxiv.org/abs/1809.05375)

##### PDF
[http://arxiv.org/pdf/1809.05375](http://arxiv.org/pdf/1809.05375)

