---
layout: post
title: "Inferring and Executing Programs for Visual Reasoning"
date: 2017-05-10 07:08:23
categories: arXiv_CL
tags: arXiv_CL
author: Justin Johnson, Bharath Hariharan, Laurens van der Maaten, Judy Hoffman, Li Fei-Fei, C. Lawrence Zitnick, Ross Girshick
mathjax: true
---

* content
{:toc}

##### Abstract
Existing methods for visual reasoning attempt to directly map inputs to outputs using black-box architectures without explicitly modeling the underlying reasoning processes. As a result, these black-box models often learn to exploit biases in the data rather than learning to perform visual reasoning. Inspired by module networks, this paper proposes a model for visual reasoning that consists of a program generator that constructs an explicit representation of the reasoning process to be performed, and an execution engine that executes the resulting program to produce an answer. Both the program generator and the execution engine are implemented by neural networks, and are trained using a combination of backpropagation and REINFORCE. Using the CLEVR benchmark for visual reasoning, we show that our model significantly outperforms strong baselines and generalizes better in a variety of settings.

##### Abstract (translated by Google)
视觉推理的现有方法尝试使用黑盒体系结构直接将输入映射到输出，而不明确建模底层推理过程。因此，这些黑盒模型经常学习利用数据中的偏见，而不是学习进行视觉推理。受到模块网络的启发，本文提出了一个视觉推理模型，该模型由一个程序生成器和一个执行引擎组成，该程序生成器构造了要执行的推理过程的显式表示，并执行结果程序以产生答案。程序生成器和执行引擎都是通过神经网络来实现的，并且使用反向传播和增强（REINFORCE）的组合来训练。使用CLEVR基准进行视觉推理，我们发现我们的模型明显优于强基线，并在各种设置中得到更好的推广。

##### URL
[https://arxiv.org/abs/1705.03633](https://arxiv.org/abs/1705.03633)

##### PDF
[https://arxiv.org/pdf/1705.03633](https://arxiv.org/pdf/1705.03633)

