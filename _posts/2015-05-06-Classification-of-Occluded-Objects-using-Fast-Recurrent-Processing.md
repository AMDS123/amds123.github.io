---
layout: post
title: "Classification of Occluded Objects using Fast Recurrent Processing"
date: 2015-05-06 12:58:58
categories: arXiv_CV
tags: arXiv_CV RNN Classification
author: Ozgur Yilmaz
mathjax: true
---

* content
{:toc}

##### Abstract
Recurrent neural networks are powerful tools for handling incomplete data problems in computer vision, thanks to their significant generative capabilities. However, the computational demand for these algorithms is too high to work in real time, without specialized hardware or software solutions. In this paper, we propose a framework for augmenting recurrent processing capabilities into a feedforward network without sacrificing much from computational efficiency. We assume a mixture model and generate samples of the last hidden layer according to the class decisions of the output layer, modify the hidden layer activity using the samples, and propagate to lower layers. For visual occlusion problem, the iterative procedure emulates feedforward-feedback loop, filling-in the missing hidden layer activity with meaningful representations. The proposed algorithm is tested on a widely used dataset, and shown to achieve 2$\times$ improvement in classification accuracy for occluded objects. When compared to Restricted Boltzmann Machines, our algorithm shows superior performance for occluded object classification.

##### Abstract (translated by Google)
递归神经网络是处理计算机视觉中的不完整数据问题的强大工具，这归功于其显着的生成能力。但是，如果没有专门的硬件或软件解决方案，这些算法的计算需求太高，无法实时工作。在本文中，我们提出了一个框架，用于在不牺牲计算效率的前提下将循环处理能力扩展到前馈网络。我们假设一个混合模型，并根据输出层的类决策生成最后一个隐藏层的样本，使用样本修改隐藏层活动，并传播到较低层。对于视觉遮挡问题，迭代过程模拟前馈反馈循环，用有意义的表示填补缺失的隐藏层活动。所提出的算法在广泛使用的数据集上进行测试，并且显示在被遮挡的对象的分类准确性方面实现了2倍的改进。与限制玻尔兹曼机器相比，我们的算法显示出优越的性能，用于遮挡物体分类。

##### URL
[https://arxiv.org/abs/1505.01350](https://arxiv.org/abs/1505.01350)

##### PDF
[https://arxiv.org/pdf/1505.01350](https://arxiv.org/pdf/1505.01350)

