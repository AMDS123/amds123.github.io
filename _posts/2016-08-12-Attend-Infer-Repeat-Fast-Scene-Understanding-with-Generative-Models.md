---
layout: post
title: "Attend, Infer, Repeat: Fast Scene Understanding with Generative Models"
date: 2016-08-12 16:05:08
categories: arXiv_CV
tags: arXiv_CV Inference
author: S. M. Ali Eslami, Nicolas Heess, Theophane Weber, Yuval Tassa, David Szepesvari, Koray Kavukcuoglu, Geoffrey E. Hinton
mathjax: true
---

* content
{:toc}

##### Abstract
We present a framework for efficient inference in structured image models that explicitly reason about objects. We achieve this by performing probabilistic inference using a recurrent neural network that attends to scene elements and processes them one at a time. Crucially, the model itself learns to choose the appropriate number of inference steps. We use this scheme to learn to perform inference in partially specified 2D models (variable-sized variational auto-encoders) and fully specified 3D models (probabilistic renderers). We show that such models learn to identify multiple objects - counting, locating and classifying the elements of a scene - without any supervision, e.g., decomposing 3D images with various numbers of objects in a single forward pass of a neural network. We further show that the networks produce accurate inferences when compared to supervised counterparts, and that their structure leads to improved generalization.

##### Abstract (translated by Google)
我们提出了一个结构化图像模型中的高效推理框架，明确推理对象。我们通过使用循环神经网络进行概率推理来实现这一点，该循环神经网络参与场景元素并逐个处理它们。至关重要的是，模型本身学习选择适当数量的推理步骤。我们使用这个方案学习在部分指定的二维模型（可变大小的变分自动编码器）和完全指定的三维模型（概率渲染器）中执行推理。我们表明，这样的模型学习识别多个对象 - 计数，定位和分类场景元素 - 没有任何监督，例如，在神经网络的单个正向通道中用不同数量的对象分解3D图像。我们进一步表明，网络产生准确的推论，与被监督的同行相比，他们的结构导致改进泛化。

##### URL
[https://arxiv.org/abs/1603.08575](https://arxiv.org/abs/1603.08575)

##### PDF
[https://arxiv.org/pdf/1603.08575](https://arxiv.org/pdf/1603.08575)

