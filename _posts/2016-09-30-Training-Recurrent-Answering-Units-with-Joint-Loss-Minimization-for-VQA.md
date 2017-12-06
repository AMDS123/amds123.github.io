---
layout: post
title: "Training Recurrent Answering Units with Joint Loss Minimization for VQA"
date: 2016-09-30 03:31:53
categories: arXiv_CV
tags: arXiv_CV VQA
author: Hyeonwoo Noh, Bohyung Han
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel algorithm for visual question answering based on a recurrent deep neural network, where every module in the network corresponds to a complete answering unit with attention mechanism by itself. The network is optimized by minimizing loss aggregated from all the units, which share model parameters while receiving different information to compute attention probability. For training, our model attends to a region within image feature map, updates its memory based on the question and attended image feature, and answers the question based on its memory state. This procedure is performed to compute loss in each step. The motivation of this approach is our observation that multi-step inferences are often required to answer questions while each problem may have a unique desirable number of steps, which is difficult to identify in practice. Hence, we always make the first unit in the network solve problems, but allow it to learn the knowledge from the rest of units by backpropagation unless it degrades the model. To implement this idea, we early-stop training each unit as soon as it starts to overfit. Note that, since more complex models tend to overfit on easier questions quickly, the last answering unit in the unfolded recurrent neural network is typically killed first while the first one remains last. We make a single-step prediction for a new question using the shared model. This strategy works better than the other options within our framework since the selected model is trained effectively from all units without overfitting. The proposed algorithm outperforms other multi-step attention based approaches using a single step prediction in VQA dataset.

##### Abstract (translated by Google)
我们提出了一种基于循环深度神经网络的视觉问题解答的新算法，其中网络中的每个模块都对应一个完整的具有关注机制的应答单元。通过最小化所有单元聚集的损失来优化网络，所述单元共享模型参数，同时接收不同的信息以计算注意概率。对于训练，我们的模型参与图像特征映射中的一个区域，基于该问题更新其内存和出席图像特征，并且基于其内存状态来回答该问题。执行此过程以计算每个步骤中的损失。这种方法的动机是我们的观察，经常需要多步推理来回答问题，而每个问题可能有独特的理想的步骤数量，这在实践中很难识别。因此，我们总是使网络中的第一个单元解决问题，但是让它通过反向传播学习其余单元的知识，除非它降低了模型。为了实现这个想法，我们尽快开始训练每个单元。需要注意的是，由于更复杂的模型往往会过分简化问题，所以展开的循环神经网络中的最后一个应答单元通常会首先被杀死，而第一个则保持最后一个。我们使用共享模型对新问题进行单步预测。这个策略比我们的框架中的其他选项更好，因为所选择的模型是从所有单元有效地训练而不过度拟合的。所提出的算法在VQA数据集中使用单步预测的性能优于其他基于多步骤注意的方法。

##### URL
[https://arxiv.org/abs/1606.03647](https://arxiv.org/abs/1606.03647)

