---
layout: post
title: "A Data and Model-Parallel, Distributed and Scalable Framework for Training of Deep Networks in Apache Spark"
date: 2017-08-19 13:17:58
categories: arXiv_CV
tags: arXiv_CV CNN RNN
author: Disha Shrivastava, Santanu Chaudhury, Dr. Jayadeva
mathjax: true
---

* content
{:toc}

##### Abstract
Training deep networks is expensive and time-consuming with the training period increasing with data size and growth in model parameters. In this paper, we provide a framework for distributed training of deep networks over a cluster of CPUs in Apache Spark. The framework implements both Data Parallelism and Model Parallelism making it suitable to use for deep networks which require huge training data and model parameters which are too big to fit into the memory of a single machine. It can be scaled easily over a cluster of cheap commodity hardware to attain significant speedup and obtain better results making it quite economical as compared to farm of GPUs and supercomputers. We have proposed a new algorithm for training of deep networks for the case when the network is partitioned across the machines (Model Parallelism) along with detailed cost analysis and proof of convergence of the same. We have developed implementations for Fully-Connected Feedforward Networks, Convolutional Neural Networks, Recurrent Neural Networks and Long Short-Term Memory architectures. We present the results of extensive simulations demonstrating the speedup and accuracy obtained by our framework for different sizes of the data and model parameters with variation in the number of worker cores/partitions; thereby showing that our proposed framework can achieve significant speedup (upto 11X for CNN) and is also quite scalable.

##### Abstract (translated by Google)
培训深度网络是昂贵和费时的，随着培训时间的增加，数据量和模型参数的增长。在本文中，我们提供了一个在Apache Spark中通过CPU集群进行深度网络分布式培训的框架。该框架实现了数据并行和模型并行，使其适用于需要大量训练数据和模型参数的深度网络，这些网络太大而不适合单个机器的内存。它可以轻松地在一个廉价的商品硬件集群上进行缩放，以获得显着的加速并获得更好的结果，与GPU和超级计算机的农场相比，它非常经济。我们提出了一种新的深度网络训练算法，用于网络划分机器的情况（模型并行性）以及详细的成本分析和收敛性证明。我们已经开发了全连接前馈网络，卷积神经网络，递归神经网络和长期短期存储器体系结构的实现。我们给出了广泛仿真的结果，展示了我们的框架针对不同大小的数据和模型参数获得的加速和准确性，以及工作者内核/分区数量的变化;从而表明我们提出的框架可以实现显着的加速（CNN高达11X），并且还具有相当的可扩展性。

##### URL
[https://arxiv.org/abs/1708.05840](https://arxiv.org/abs/1708.05840)

##### PDF
[https://arxiv.org/pdf/1708.05840](https://arxiv.org/pdf/1708.05840)

