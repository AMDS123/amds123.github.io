---
layout: post
title: "Visual Coreference Resolution in Visual Dialog using Neural Module Networks"
date: 2018-09-06 04:36:22
categories: arXiv_AI
tags: arXiv_AI QA VQA
author: Satwik Kottur, Jos&#xe9; M. F. Moura, Devi Parikh, Dhruv Batra, Marcus Rohrbach
mathjax: true
---

* content
{:toc}

##### Abstract
Visual dialog entails answering a series of questions grounded in an image, using dialog history as context. In addition to the challenges found in visual question answering (VQA), which can be seen as one-round dialog, visual dialog encompasses several more. We focus on one such problem called visual coreference resolution that involves determining which words, typically noun phrases and pronouns, co-refer to the same entity/object instance in an image. This is crucial, especially for pronouns (e.g., `it'), as the dialog agent must first link it to a previous coreference (e.g., `boat'), and only then can rely on the visual grounding of the coreference `boat' to reason about the pronoun `it'. Prior work (in visual dialog) models visual coreference resolution either (a) implicitly via a memory network over history, or (b) at a coarse level for the entire question; and not explicitly at a phrase level of granularity. In this work, we propose a neural module network architecture for visual dialog by introducing two novel modules - Refer and Exclude - that perform explicit, grounded, coreference resolution at a finer word level. We demonstrate the effectiveness of our model on MNIST Dialog, a visually simple yet coreference-wise complex dataset, by achieving near perfect accuracy, and on VisDial, a large and challenging visual dialog dataset on real images, where our model outperforms other approaches, and is more interpretable, grounded, and consistent qualitatively.

##### Abstract (translated by Google)
视觉对话需要使用对话历史作为上下文来回答基于图像的一系列问题。除了视觉问答（VQA）中可以看作一轮对话的挑战外，视觉对话还包含其他几个。我们关注一个称为视觉共指消解的问题，该问题涉及确定哪些单词（通常是名词短语和代词）共同引用图像中的相同实体/对象实例。这是至关重要的，特别是对于代词（例如，“它”），因为对话代理必须首先将它链接到先前的共同参考（例如，“船”），然后才能依赖于共同参与“船”的视觉基础。推断代词“它”。先前的工作（在视觉对话中）模拟视觉共参考解决方案（a）通过历史记录的内存网络隐式地，或（b）整个问题的粗略级别;而不是明确地在词组级别的粒度。在这项工作中，我们提出了一个用于视觉对话的神经模块网络架构，引入了两个新颖的模块 - 参考和排除 - 在更精细的单词级别执行显式的，基础的共参考分辨率。我们通过实现接近完美的精度，以及在真实图像上的大型且具有挑战性的视觉对话数据集VisDial上展示了我们模型在MNIST Dialog上的有效性，这是一个视觉上简单但依赖于共参数的复杂数据集，其中我们的模型优于其他方法，并且更具有解释性，扎根性和定性性。

##### URL
[http://arxiv.org/abs/1809.01816](http://arxiv.org/abs/1809.01816)

##### PDF
[http://arxiv.org/pdf/1809.01816](http://arxiv.org/pdf/1809.01816)

