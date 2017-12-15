---
layout: post
title: "Neural Programmer: Inducing Latent Programs with Gradient Descent"
date: 2016-08-04 18:23:03
categories: arXiv_CL
tags: arXiv_CL Attention Speech_Recognition Classification Gradient_Descent Recognition
author: Arvind Neelakantan, Quoc V. Le, Ilya Sutskever
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural networks have achieved impressive supervised classification performance in many tasks including image recognition, speech recognition, and sequence to sequence learning. However, this success has not been translated to applications like question answering that may involve complex arithmetic and logic reasoning. A major limitation of these models is in their inability to learn even simple arithmetic and logic operations. For example, it has been shown that neural networks fail to learn to add two binary numbers reliably. In this work, we propose Neural Programmer, an end-to-end differentiable neural network augmented with a small set of basic arithmetic and logic operations. Neural Programmer can call these augmented operations over several steps, thereby inducing compositional programs that are more complex than the built-in operations. The model learns from a weak supervision signal which is the result of execution of the correct program, hence it does not require expensive annotation of the correct program itself. The decisions of what operations to call, and what data segments to apply to are inferred by Neural Programmer. Such decisions, during training, are done in a differentiable fashion so that the entire network can be trained jointly by gradient descent. We find that training the model is difficult, but it can be greatly improved by adding random noise to the gradient. On a fairly complex synthetic table-comprehension dataset, traditional recurrent networks and attentional models perform poorly while Neural Programmer typically obtains nearly perfect accuracy.

##### Abstract (translated by Google)
深度神经网络在包括图像识别，语音识别和顺序学习的许多任务中取得了令人印象深刻的监督分类性能。然而，这个成功还没有被翻译成可能涉及复杂算术和逻辑推理的问题回答。这些模型的一个主要局限在于它们甚至无法学习简单的算术和逻辑运算。例如，已经表明神经网络不能学会可靠地添加两个二进制数。在这项工作中，我们提出神经程序员，一个端到端的微分神经网络，增加了一套基本的算术和逻辑运算。神经程序员可以通过几个步骤调用这些增强的操作，从而诱发比内置操作更复杂的组合程序。该模型是从一个弱的监督信号中学习的，这个信号是执行正确的程序的结果，因此它不需要昂贵的正确程序本身的注释。神经程序员推断哪些操作需要调用哪些数据段，以及应用哪些数据段。训练期间的这种决策是以可区分的方式完成的，以便整个网络可以通过梯度下降来共同训练。我们发现，训练模型是困难的，但是可以通过向梯度添加随机噪声来大大改善。在一个相当复杂的合成表理解数据集上，传统的递归网络和注意模型表现不佳，而神经程序员通常获得接近完美的准确度。

##### URL
[https://arxiv.org/abs/1511.04834](https://arxiv.org/abs/1511.04834)

##### PDF
[https://arxiv.org/pdf/1511.04834](https://arxiv.org/pdf/1511.04834)

