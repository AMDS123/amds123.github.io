---
layout: post
title: "Doubly Nested Network for Resource-Efficient Inference"
date: 2018-06-20 06:11:35
categories: arXiv_CV
tags: arXiv_CV Knowledge Inference Prediction
author: Jaehong Kim, Sungeun Hong, Yongseok Choi, Jiwon Kim
mathjax: true
---

* content
{:toc}

##### Abstract
We propose doubly nested network(DNNet) where all neurons represent their own sub-models that solve the same task. Every sub-model is nested both layer-wise and channel-wise. While nesting sub-models layer-wise is straight-forward with deep-supervision as proposed in \cite{xie2015holistically}, channel-wise nesting has not been explored in the literature to our best knowledge. Channel-wise nesting is non-trivial as neurons between consecutive layers are all connected to each other. In this work, we introduce a technique to solve this problem by sorting channels topologically and connecting neurons accordingly. For the purpose, channel-causal convolutions are used. Slicing doubly nested network gives a working sub-network. The most notable application of our proposed network structure with slicing operation is resource-efficient inference. At test time, computing resources such as time and memory available for running the prediction algorithm can significantly vary across devices and applications. Given a budget constraint, we can slice the network accordingly and use a sub-model for inference within budget, requiring no additional computation such as training or fine-tuning after deployment. We demonstrate the effectiveness of our approach in several practical scenarios of utilizing available resource efficiently.

##### Abstract (translated by Google)
我们提出双重嵌套网络（DNNet），其中所有神经元代表它们自己的解决相同任务的子模型。每个子模型都嵌套在层面和通道上。虽然按照\ cite {xie2015holistic}中提出的深层监督方式，将子模型分层嵌套是直截了当的，但在文献中还没有探索过通道嵌套方法，以我们的最佳知识。通道嵌套是不平凡的，因为连续层之间的神经元全部彼此连接。在这项工作中，我们引入了一种技术来解决这个问题，通过拓扑排序通道并相应地连接神经元。为此目的，使用通道因果卷积。切片双重嵌套网络提供了一个工作子网络。我们提出的带切片操作的网络结构最显着的应用是资源高效推断。在测试时间内，可用于运行预测算法的计算资源（如时间和内存）可能会因设备和应用程序而显着不同。鉴于预算约束，我们可以相应地对网络进行分割，并在预算范围内使用子模型进行推理，无需额外的计算，例如部署后的训练或微调。我们在几个有效利用可用资源的实际场景中展示了我们方法的有效性。

##### URL
[http://arxiv.org/abs/1806.07568](http://arxiv.org/abs/1806.07568)

##### PDF
[http://arxiv.org/pdf/1806.07568](http://arxiv.org/pdf/1806.07568)

