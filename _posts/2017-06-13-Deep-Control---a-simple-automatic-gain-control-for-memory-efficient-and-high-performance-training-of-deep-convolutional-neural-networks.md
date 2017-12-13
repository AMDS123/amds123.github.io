---
layout: post
title: "Deep Control - a simple automatic gain control for memory efficient and high performance training of deep convolutional neural networks"
date: 2017-06-13 05:29:05
categories: arXiv_CV
tags: arXiv_CV CNN Inference Gradient_Descent
author: Brendan Ruff
mathjax: true
---

* content
{:toc}

##### Abstract
Training a deep convolutional neural net typically starts with a random initialisation of all filters in all layers which severely reduces the forward signal and back-propagated error and leads to slow and sub-optimal training. Techniques that counter that focus on either increasing the signal or increasing the gradients adaptively but the model behaves very differently at the beginning of training compared to later when stable pathways through the net have been established. To compound this problem the effective minibatch size varies greatly between layers at different depths and between individual filters as activation sparsity typically increases with depth leading to a reduction in effective learning rate since gradients may superpose rather than add and this further compounds the covariate shift problem as deeper neurons are less able to adapt to upstream shift. Proposed here is a method of automatic gain control of the signal built into each convolutional neuron that achieves equivalent or superior performance than batch normalisation and is compatible with single sample or minibatch gradient descent. The same model is used both for training and inference. The technique comprises a scaled per sample map mean subtraction from the raw convolutional filter output followed by scaling of the difference.

##### Abstract (translated by Google)
训练深度卷积神经网络通常始于对所有层中的所有滤波器进行随机初始化，这严重降低了前向信号和后向传播误差，并导致缓慢和次优的训练。技术，反对重点要么增加信号或增加梯度自适应，但模型行为非常不同，在培训开始时，相比较后，当稳定的路径通过网络已经建立。为了解决这个问题，有效的小批量大小在不同深度和各个滤波器之间的层之间变化很大，因为激活稀疏度通常随着深度而增加，导致有效学习率降低，因为梯度可能叠加而不是相加，这进一步将协变量移位问题更深的神经元不能适应上游的转变。这里提出的是一种对每个卷积神经元中内置的信号进行自动增益控制的方法，其实现与批量归一化相当或更好的性能，并且与单个样本或小批次梯度下降兼容。相同的模型同时用于训练和推理。该技术包括从原始卷积滤波器输出缩放的每样本映射平均相减，随后缩放该差值。

##### URL
[https://arxiv.org/abs/1706.03907](https://arxiv.org/abs/1706.03907)

##### PDF
[https://arxiv.org/pdf/1706.03907](https://arxiv.org/pdf/1706.03907)

