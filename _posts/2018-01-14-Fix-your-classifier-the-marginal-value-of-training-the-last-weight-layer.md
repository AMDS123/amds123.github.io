---
layout: post
title: "Fix your classifier: the marginal value of training the last weight layer"
date: 2018-01-14 12:00:43
categories: arXiv_CV
tags: arXiv_CV Inference Classification
author: Elad Hoffer, Itay Hubara, Daniel Soudry
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are commonly used as models for classification for a wide variety of tasks. Typically, a learned affine transformation is placed at the end of such models, yielding a per-class value used for classification. This classifier can have a vast number of parameters, which grows linearly with the number of possible classes, thus requiring increasingly more resources. In this work we argue that this classifier can be fixed, up to a global scale constant, with little or no loss of accuracy for most tasks, allowing memory and computational benefits. Moreover, we show that by initializing the classifier with a Hadamard matrix we can speed up inference as well. We discuss the implications for current understanding of neural network models.

##### Abstract (translated by Google)
神经网络通常被用作各种任务分类的模型。典型地，学习仿射变换放置在这样的模型的末尾，产生用于分类的每类值。这个分类器可以有大量的参数，它随着可能的类的数量而线性增长，因此需要越来越多的资源。在这项工作中，我们认为这个分类器可以被固定，达到一个全球范围常数，对于大多数任务来说，精度损失很小或没有损失，从而允许记忆和计算的好处。此外，我们表明，通过用哈达玛矩阵初始化分类器，我们也可以加速推理。我们讨论目前对神经网络模型理解的含义。

##### URL
[https://arxiv.org/abs/1801.04540](https://arxiv.org/abs/1801.04540)

##### PDF
[https://arxiv.org/pdf/1801.04540](https://arxiv.org/pdf/1801.04540)

