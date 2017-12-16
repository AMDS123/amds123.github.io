---
layout: post
title: "Recurrent Inference Machines for Solving Inverse Problems"
date: 2017-06-13 11:24:41
categories: arXiv_CV
tags: arXiv_CV Super_Resolution Knowledge Inference RNN
author: Patrick Putzky, Max Welling
mathjax: true
---

* content
{:toc}

##### Abstract
Much of the recent research on solving iterative inference problems focuses on moving away from hand-chosen inference algorithms and towards learned inference. In the latter, the inference process is unrolled in time and interpreted as a recurrent neural network (RNN) which allows for joint learning of model and inference parameters with back-propagation through time. In this framework, the RNN architecture is directly derived from a hand-chosen inference algorithm, effectively limiting its capabilities. We propose a learning framework, called Recurrent Inference Machines (RIM), in which we turn algorithm construction the other way round: Given data and a task, train an RNN to learn an inference algorithm. Because RNNs are Turing complete [1, 2] they are capable to implement any inference algorithm. The framework allows for an abstraction which removes the need for domain knowledge. We demonstrate in several image restoration experiments that this abstraction is effective, allowing us to achieve state-of-the-art performance on image denoising and super-resolution tasks and superior across-task generalization.

##### Abstract (translated by Google)
最近在解决迭代推理问题方面的许多研究集中在从手选推理算法转向学习推理。在后者中，推理过程在时间上被展开，并被解释为循环神经网络（RNN），其允许联合学习模型和随时间推移反向传播的推理参数。在这个框架中，RNN体系结构直接来源于手选推理算法，有效地限制了它的能力。我们提出了一个学习框架，称为循环推理机（RIM），其中我们反过来算法建设：给定数据和任务，训练一个RNN学习推理算法。由于RNNs是图灵完备的[1，2]，他们能够实现任何推理算法。该框架允许抽象，消除对领域知识的需要。我们在几个图像恢复实验中证明，这种抽象是有效的，使我们能够在图像去噪和超分辨率任务以及卓越的跨任务泛化方面实现最先进的性能。

##### URL
[https://arxiv.org/abs/1706.04008](https://arxiv.org/abs/1706.04008)

##### PDF
[https://arxiv.org/pdf/1706.04008](https://arxiv.org/pdf/1706.04008)

