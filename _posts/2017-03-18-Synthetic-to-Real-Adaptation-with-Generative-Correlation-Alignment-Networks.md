---
layout: post
title: "Synthetic to Real Adaptation with Generative Correlation Alignment Networks"
date: 2017-03-18 12:56:45
categories: arXiv_CV
tags: arXiv_CV CNN Relation Recognition
author: Xingchao Peng, Kate Saenko
mathjax: true
---

* content
{:toc}

##### Abstract
Synthetic images rendered from 3D CAD models are useful for augmenting training data for object recognition algorithms. However, the generated images are non-photorealistic and do not match real image statistics. This leads to a large domain discrepancy, causing models trained on synthetic data to perform poorly on real domains. Recent work has shown the great potential of deep convolutional neural networks to generate realistic images, but has not utilized generative models to address synthetic-to-real domain adaptation. In this work, we propose a Deep Generative Correlation Alignment Network (DGCAN) to synthesize images using a novel domain adaption algorithm. DGCAN leverages a shape preserving loss and a low level statistic matching loss to minimize the domain discrepancy between synthetic and real images in deep feature space. Experimentally, we show training off-the-shelf classifiers on the newly generated data can significantly boost performance when testing on the real image domains (PASCAL VOC 2007 benchmark and Office dataset), improving upon several existing methods.

##### Abstract (translated by Google)
从3D CAD模型渲染的合成图像对于增强对象识别算法的训练数据非常有用。然而，生成的图像是非真实的，并且不匹配真实图像统计。这导致了大的域差异，导致在合成数据上训练的模型在真实域上表现不佳。最近的研究表明深度卷积神经网络产生逼真图像的巨大潜力，但没有利用生成模型来解决合成到真实域的适应问题。在这项工作中，我们提出一个深生成相关对齐网络（DGCAN）合成图像使用一种新的领域自适应算法。 DGCAN利用形状保持损失和低水平统计匹配损失来最小化合成图像和真实图像之间在深度特征空间中的域差异。在实验中，我们展示了在新生成的数据上使用现成的分类器对实际图像域进行测试（PASCAL VOC 2007基准测试和Office数据集）时的显着提升性能，并改进了多种现有方法。

##### URL
[https://arxiv.org/abs/1701.05524](https://arxiv.org/abs/1701.05524)

##### PDF
[https://arxiv.org/pdf/1701.05524](https://arxiv.org/pdf/1701.05524)

