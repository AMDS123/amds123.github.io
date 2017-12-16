---
layout: post
title: "Examining the Impact of Blur on Recognition by Convolutional Networks"
date: 2017-05-30 13:56:22
categories: arXiv_CV
tags: arXiv_CV CNN Recognition
author: Igor Vasiljevic, Ayan Chakrabarti, Gregory Shakhnarovich
mathjax: true
---

* content
{:toc}

##### Abstract
State-of-the-art algorithms for many semantic visual tasks are based on the use of convolutional neural networks. These networks are commonly trained, and evaluated, on large annotated datasets of artifact-free high-quality images. In this paper, we investigate the effect of one such artifact that is quite common in natural capture settings: optical blur. We show that standard network models, trained only on high-quality images, suffer a significant degradation in performance when applied to those degraded by blur due to defocus, or subject or camera motion. We investigate the extent to which this degradation is due to the mismatch between training and input image statistics. Specifically, we find that fine-tuning a pre-trained model with blurred images added to the training set allows it to regain much of the lost accuracy. We also show that there is a fair amount of generalization between different degrees and types of blur, which implies that a single network model can be used robustly for recognition when the nature of the blur in the input is unknown. We find that this robustness arises as a result of these models learning to generate blur invariant representations in their hidden layers. Our findings provide useful insights towards developing vision systems that can perform reliably on real world images affected by blur.

##### Abstract (translated by Google)
用于许多语义视觉任务的最先进的算法是基于卷积神经网络的使用。这些网络通常经过大规模的无伪影高质量图像的注释数据集的训练和评估。在这篇文章中，我们研究了一个在自然捕获设置中很常见的这种伪像的影响：光学模糊。我们展示了仅在高质量图像上训练的标准网络模型在应用于因散焦或主体或相机运动而导致的模糊退化时，性能显着降低。我们调查这种退化的程度是由于训练和输入图像统计之间的不匹配造成的。具体而言，我们发现对训练集中添加模糊图像的预训练模型进行微调可以使其重新获得大部分精度。我们还表明，在不同程度和类型的模糊之间存在相当数量的泛化，这意味着当输入中的模糊的性质未知时，单个网络模型可以被鲁棒地用于识别。我们发现这种鲁棒性是由于这些模型学习在其隐藏层中生成模糊不变表示而产生的。我们的发现为开发视觉系统提供了有用的见解，可以在模糊影响的真实世界的图像上可靠地执行。

##### URL
[https://arxiv.org/abs/1611.05760](https://arxiv.org/abs/1611.05760)

##### PDF
[https://arxiv.org/pdf/1611.05760](https://arxiv.org/pdf/1611.05760)

