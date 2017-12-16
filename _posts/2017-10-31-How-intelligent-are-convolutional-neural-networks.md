---
layout: post
title: "How intelligent are convolutional neural networks?"
date: 2017-10-31 20:29:12
categories: arXiv_CV
tags: arXiv_CV CNN Deep_Learning Quantitative
author: Zhennan Yan, Xiang Sean Zhou
mathjax: true
---

* content
{:toc}

##### Abstract
Motivated by the Gestalt pattern theory, and the Winograd Challenge for language understanding, we design synthetic experiments to investigate a deep learning algorithm's ability to infer simple (at least for human) visual concepts, such as symmetry, from examples. A visual concept is represented by randomly generated, positive as well as negative, example images. We then test the ability and speed of algorithms (and humans) to learn the concept from these images. The training and testing are performed progressively in multiple rounds, with each subsequent round deliberately designed to be more complex and confusing than the previous round(s), especially if the concept was not grasped by the learner. However, if the concept was understood, all the deliberate tests would become trivially easy. Our experiments show that humans can often infer a semantic concept quickly after looking at only a very small number of examples (this is often referred to as an "aha moment": a moment of sudden realization), and performs perfectly during all testing rounds (except for careless mistakes). On the contrary, deep convolutional neural networks (DCNN) could approximate some concepts statistically, but only after seeing many (x10^4) more examples. And it will still make obvious mistakes, especially during deliberate testing rounds or on samples outside the training distributions. This signals a lack of true "understanding", or a failure to reach the right "formula" for the semantics. We did find that some concepts are easier for DCNN than others. For example, simple "counting" is more learnable than "symmetry", while "uniformity" or "conformance" are much more difficult for DCNN to learn. To conclude, we propose an "Aha Challenge" for visual perception, calling for focused and quantitative research on Gestalt-style machine intelligence using limited training examples.

##### Abstract (translated by Google)
受格式塔模式理论和Winograd对语言理解的挑战的启发，我们设计合成实验来研究深度学习算法从例子中推断简单（至少对于人类）视觉概念（如对称性）的能力。视觉概念由随机生成的正面和负面示例图像表示。然后我们测试算法（和人类）从这些图像学习概念的能力和速度。训练和测试是在多轮循环中逐步进行的，每一轮随后的一轮都被刻意设计得比前一轮更加复杂和混乱，特别是如果这个概念不被学习者掌握的话。但是，如果这个概念被理解了，那么所有的故意测试都将变得非常简单。我们的实验表明，人类往往只能看到非常少的例子（这通常被称为“aha时刻”：突然实现的一刻）之后很快推断出一个语义概念，并且在所有的测试轮次除了粗心的错误）。相反，深度卷积神经网络（DCNN）可以在统计上逼近一些概念，但只有在看到许多（×10 ^ 4）个例子之后。而且还会出现明显的错误，特别是在故意测试或者训练分布之外的样本中。这表示缺乏真正的“理解”，或者没有达到语义的正确“公式”。我们确实发现一些概念比DCNN更容易。例如，简单的“计数”比“对称性”更容易学习，而“一致性”或“一致性”对于DCNN来说学习起来要困难得多。总之，我们提出了一个视觉感知的“阿哈挑战”，要求使用有限的训练实例对格式塔式机器智能进行重点和定量的研究。

##### URL
[https://arxiv.org/abs/1709.06126](https://arxiv.org/abs/1709.06126)

##### PDF
[https://arxiv.org/pdf/1709.06126](https://arxiv.org/pdf/1709.06126)

