---
layout: post
title: "Neural Mesh: Introducing a Notion of Space and Conservation of Energy to Neural Networks"
date: 2018-07-29 23:14:21
categories: arXiv_AI
tags: arXiv_AI RNN
author: Jacob Beck, Zoe Papakipos
mathjax: true
---

* content
{:toc}

##### Abstract
Neural networks are based on a simplified model of the brain. In this project, we wanted to relax the simplifying assumptions of a traditional neural network by making a model that more closely emulates the low level interactions of neurons. Like in an RNN, our model has a state that persists between time steps, so that the energies of neurons persist. However, unlike an RNN, our state consists of a 2 dimensional matrix, rather than a 1 dimensional vector, thereby introducing a concept of distance to other neurons within the state. In our model, neurons can only fire to adjacent neurons, as in the brain. Like in the brain, we only allow neurons to fire in a time step if they contain enough energy, or excitement. We also enforce a notion of conservation of energy, so that a neuron cannot excite its neighbors more than the excitement it already contained at that time step. Taken together, these two features allow signals in the form of activations to flow around in our network over time, making our neural mesh more closely model signals traveling through the brain the brain. Although our main goal is to design an architecture to more closely emulate the brain in the hope of having a correct internal representation of information by the time we know how to properly train a general intelligence, we did benchmark our neural mash on a specific task. We found that by increasing the runtime of the mesh, we were able to increase its accuracy without increasing the number of parameters.

##### Abstract (translated by Google)
神经网络基于简化的大脑模型。在这个项目中，我们希望通过建立一个更接近模拟神经元低水平相互作用的模型来放松传统神经网络的简化假设。就像在RNN中一样，我们的模型具有在时间步长之间持续存在的状态，因此神经元的能量持续存在。然而，与RNN不同，我们的状态由2维矩阵而不是1维向量组成，从而引入了与状态内其他神经元的距离概念。在我们的模型中，神经元只能射向相邻的神经元，就像在大脑中一样。就像在大脑中一样，如果它们包含足够的能量或兴奋，我们只允许神经元在一个时间步骤中发射。我们还强制执行能量守恒的概念，这样神经元就不能激发它的邻居，而不是它在那个时间步骤已经包含的兴奋。总之，这两个特征允许激活形式的信号随着时间的推移在我们的网络中流动，使我们的神经网格更紧密地模拟通过大脑的大脑传播的信号。虽然我们的主要目标是设计一个更接近模拟大脑的架构，希望在我们知道如何正确训练一般情报的时候拥有正确的信息内部表示，但我们确实在特定任务上对神经混搭进行了基准测试。我们发现通过增加网格的运行时间，我们能够在不增加参数数量的情况下提高其准确性。

##### URL
[http://arxiv.org/abs/1807.11121](http://arxiv.org/abs/1807.11121)

##### PDF
[http://arxiv.org/pdf/1807.11121](http://arxiv.org/pdf/1807.11121)

