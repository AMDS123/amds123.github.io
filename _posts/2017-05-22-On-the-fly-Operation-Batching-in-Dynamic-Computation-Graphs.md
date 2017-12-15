---
layout: post
title: "On-the-fly Operation Batching in Dynamic Computation Graphs"
date: 2017-05-22 17:04:56
categories: arXiv_CL
tags: arXiv_CL GAN
author: Graham Neubig, Yoav Goldberg, Chris Dyer
mathjax: true
---

* content
{:toc}

##### Abstract
Dynamic neural network toolkits such as PyTorch, DyNet, and Chainer offer more flexibility for implementing models that cope with data of varying dimensions and structure, relative to toolkits that operate on statically declared computations (e.g., TensorFlow, CNTK, and Theano). However, existing toolkits - both static and dynamic - require that the developer organize the computations into the batches necessary for exploiting high-performance algorithms and hardware. This batching task is generally difficult, but it becomes a major hurdle as architectures become complex. In this paper, we present an algorithm, and its implementation in the DyNet toolkit, for automatically batching operations. Developers simply write minibatch computations as aggregations of single instance computations, and the batching algorithm seamlessly executes them, on the fly, using computationally efficient batched operations. On a variety of tasks, we obtain throughput similar to that obtained with manual batches, as well as comparable speedups over single-instance learning on architectures that are impractical to batch manually.

##### Abstract (translated by Google)
动态神经网络工具包（如PyTorch，DyNet和Chainer）相对于静态声明计算的工具包（例如TensorFlow，CNTK和Theano）提供了更大的灵活性来实现处理不同维度和结构的数据的模型。但是，现有的工具包（无论是静态的还是动态的）都要求开发人员将计算组织成开发高性能算法和硬件所需的批次。这个配料任务通常是困难的，但是随着架构变得复杂，这成为一个主要障碍。在本文中，我们提出了一个算法及其在DyNet工具包中的实现，用于自动批处理操作。开发人员只需将小批量计算写成单实例计算的集合，批处理算法就可以使用计算高效的批处理操作实时执行它们。在各种任务中，我们获得与手动批处理类似的吞吐量，以及在架构上进行单实例学习的可比较的加速，这些加速对于手动批处理来说是不切实际的。

##### URL
[https://arxiv.org/abs/1705.07860](https://arxiv.org/abs/1705.07860)

##### PDF
[https://arxiv.org/pdf/1705.07860](https://arxiv.org/pdf/1705.07860)

