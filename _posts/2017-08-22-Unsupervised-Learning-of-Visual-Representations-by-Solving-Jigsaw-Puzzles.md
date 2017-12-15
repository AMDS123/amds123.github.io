---
layout: post
title: "Unsupervised Learning of Visual Representations by Solving Jigsaw Puzzles"
date: 2017-08-22 17:32:19
categories: arXiv_CV
tags: arXiv_CV Image_Caption CNN Transfer_Learning Represenation_Learning Classification Detection
author: Mehdi Noroozi, Paolo Favaro
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper we study the problem of image representation learning without human annotation. By following the principles of self-supervision, we build a convolutional neural network (CNN) that can be trained to solve Jigsaw puzzles as a pretext task, which requires no manual labeling, and then later repurposed to solve object classification and detection. To maintain the compatibility across tasks we introduce the context-free network (CFN), a siamese-ennead CNN. The CFN takes image tiles as input and explicitly limits the receptive field (or context) of its early processing units to one tile at a time. We show that the CFN includes fewer parameters than AlexNet while preserving the same semantic learning capabilities. By training the CFN to solve Jigsaw puzzles, we learn both a feature mapping of object parts as well as their correct spatial arrangement. Our experimental evaluations show that the learned features capture semantically relevant content. Our proposed method for learning visual representations outperforms state of the art methods in several transfer learning benchmarks.

##### Abstract (translated by Google)
本文研究了无人注释的图像表示学习问题。通过遵循自我监督的原则，我们构建了一个卷积神经网络（CNN），可以训练解决拼图谜题作为一个借口任务，不需要手动标记，然后再用于解决对象分类和检测。为了保持跨任务的兼容性，我们引入了上下文无关网络（CFN），即一个连接到CNN的连接。 CFN将图像切片作为输入，并将其早期处理单元的接受范围（或上下文）显式限制为一次一个切片。我们证明CFN包含的参数比AlexNet少，同时保留了相同的语义学习能力。通过训练CFN来解决拼图游戏，我们学习了对象部分的特征映射以及它们的正确的空间排列。我们的实验评估表明，学习的功能捕捉语义相关的内容。我们提出的用于学习视觉表示的方法在几个传输学习基准中优于现有技术方法。

##### URL
[https://arxiv.org/abs/1603.09246](https://arxiv.org/abs/1603.09246)

##### PDF
[https://arxiv.org/pdf/1603.09246](https://arxiv.org/pdf/1603.09246)

