---
layout: post
title: "Context Encoders: Feature Learning by Inpainting"
date: 2016-11-21 20:56:42
categories: arXiv_CV
tags: arXiv_CV Adversarial Segmentation CNN Classification Prediction Quantitative Detection
author: Deepak Pathak, Philipp Krahenbuhl, Jeff Donahue, Trevor Darrell, Alexei A. Efros
mathjax: true
---

* content
{:toc}

##### Abstract
We present an unsupervised visual feature learning algorithm driven by context-based pixel prediction. By analogy with auto-encoders, we propose Context Encoders -- a convolutional neural network trained to generate the contents of an arbitrary image region conditioned on its surroundings. In order to succeed at this task, context encoders need to both understand the content of the entire image, as well as produce a plausible hypothesis for the missing part(s). When training context encoders, we have experimented with both a standard pixel-wise reconstruction loss, as well as a reconstruction plus an adversarial loss. The latter produces much sharper results because it can better handle multiple modes in the output. We found that a context encoder learns a representation that captures not just appearance but also the semantics of visual structures. We quantitatively demonstrate the effectiveness of our learned features for CNN pre-training on classification, detection, and segmentation tasks. Furthermore, context encoders can be used for semantic inpainting tasks, either stand-alone or as initialization for non-parametric methods.

##### Abstract (translated by Google)
我们提出了一种基于上下文的像素预测驱动的无监督视觉特征学习算法。通过与自动编码器的类比，我们提出了上下文编码器（一种卷积神经网络，训练用来生成任意图像区域的内容）。为了在这个任务中取得成功，上下文编码器需要理解整个图像的内容，并且为缺失的部分提供合理的假设。当训练上下文编码器时，我们已经尝试了标准像素重建丢失，以及重建加上对抗损失。后者产生更清晰的结果，因为它可以更好地处理输出中的多种模式。我们发现上下文编码器学习一个表示，不仅捕获外观，而且捕获视觉结构的语义。我们在数量上证明了我们学习的CNN预分类，检测和分割任务的功能的有效性。此外，上下文编码器可以用于语义修补任务，可以是独立的，也可以作为非参数方法的初始化。

##### URL
[https://arxiv.org/abs/1604.07379](https://arxiv.org/abs/1604.07379)

##### PDF
[https://arxiv.org/pdf/1604.07379](https://arxiv.org/pdf/1604.07379)

