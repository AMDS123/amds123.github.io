---
layout: post
title: "Fast Distributed Deep Learning via Worker-adaptive Batch Sizing"
date: 2018-06-07 04:15:58
categories: arXiv_AI
tags: arXiv_AI Deep_Learning Prediction
author: Chen Chen, Qizhen Weng, Wei Wang, Baochun Li, Bo Li
mathjax: true
---

* content
{:toc}

##### Abstract
Deep neural network models are usually trained in cluster environments, where the model parameters are iteratively refined by multiple worker machines in parallel. One key challenge in this regard is the presence of stragglers, which significantly degrades the learning performance. In this paper, we propose to eliminate stragglers by adapting each worker's training load to its processing capability; that is, slower workers receive a smaller batch of data to process. 
 Following this idea, we develop a new synchronization scheme called LB-BSP (Load-balanced BSP). It works by coordinately setting the batch size of each worker so that they can finish batch processing at around the same time. A prerequisite for deciding the workers' batch sizes is to know their processing speeds before each iteration starts. For the best prediction accuracy, we adopt NARX, an extended recurrent neural network that accounts for both the historical speeds and the driving factors such as CPU and memory in prediction. We have implemented LB-BSP for both TensorFlow and MXNet. EC2 experiments against popular benchmarks show that LB-BSP can effectively accelerate the training of deep models, with up to 2x speedup.

##### Abstract (translated by Google)
深度神经网络模型通常在集群环境中进行训练，其中模型参数由多个并行的工作机器迭代地改进。在这方面的一个关键挑战是散兵队的存在，这会显着降低学习成绩。在本文中，我们建议通过调整每个员工的训练负荷来处理他们的处理能力，也就是说，较慢的工作人员会收到一小批要处理的数据。
 遵循这个想法，我们开发了一种名为LB-BSP（负载均衡BSP）的新同步方案。它通过协调设置每个工人的批量大小来工作，以便他们可以在大约同一时间完成批处理。确定工人批量大小的先决条件是在每次迭代开始前了解他们的处理速度。为了获得最好的预测精度，我们采用了NARX，这是一个扩展的循环神经网络，它可以预测历史速度和预测中CPU和内存等驱动因素。我们已经为TensorFlow和MXNet实施了LB-BSP。根据流行的基准进行的EC2实验表明，LB-BSP可以有效加速深层模型的训练，最多可提升2x的速度。

##### URL
[http://arxiv.org/abs/1806.02508](http://arxiv.org/abs/1806.02508)

##### PDF
[http://arxiv.org/pdf/1806.02508](http://arxiv.org/pdf/1806.02508)

