---
layout: post
title: "Insights on representational similarity in neural networks with canonical correlation"
date: 2018-06-14 22:34:11
categories: arXiv_AI
tags: arXiv_AI RNN Relation
author: Ari S. Morcos, Maithra Raghu, Samy Bengio
mathjax: true
---

* content
{:toc}

##### Abstract
Comparing different neural network representations and determining how representations evolve over time remain challenging open questions in our understanding of the function of neural networks. Comparing representations in neural networks is fundamentally difficult as the structure of representations varies greatly, even across groups of networks trained on identical tasks, and over the course of training. Here, we develop projection weighted CCA (Canonical Correlation Analysis) as a tool for understanding neural networks, building off of SVCCA, a recently proposed method. We first improve the core method, showing how to differentiate between signal and noise, and then apply this technique to compare across a group of CNNs, demonstrating that networks which generalize converge to more similar representations than networks which memorize, that wider networks converge to more similar solutions than narrow networks, and that trained networks with identical topology but different learning rates converge to distinct clusters with diverse representations. We also investigate the representational dynamics of RNNs, across both training and sequential timesteps, finding that RNNs converge in a bottom-up pattern over the course of training and that the hidden state is highly variable over the course of a sequence, even when accounting for linear transforms. Together, these results provide new insights into the function of CNNs and RNNs, and demonstrate the utility of using CCA to understand representations.

##### Abstract (translated by Google)
比较不同的神经网络表征并确定表征随着时间的推移如何演化仍然对我们理解神经网络功能的开放性问题提出了挑战。比较神经网络中的表示是非常困难的，因为表示的结构变化很大，甚至在训练相同任务的网络组之间以及在训练过程中变化很大。在这里，我们开发投影加权CCA（典型相关分析）作为理解神经网络的工具，构建了最近提出的SVCCA方法。我们首先对核心方法进行了改进，展示了如何区分信号和噪声，然后应用这种技术对一组CNN进行比较，表明广义网络比记忆的网络更接近于更类似的表示，更广泛的网络汇聚到更多类似于窄网络的解决方案，并且具有相同拓扑但具有不同学习速率的训练网络汇聚成具有不同表示的不同集群。我们还调查RNN的代表动态，包括训练和连续时间步，发现RNN在训练过程中以自下而上的模式收敛，并且隐藏状态在一个序列过程中是高度可变的，即使考虑到线性变换。总之，这些结果为CNN和RNN的功能提供了新的见解，并展示了使用CCA理解表示的效用。

##### URL
[http://arxiv.org/abs/1806.05759](http://arxiv.org/abs/1806.05759)

##### PDF
[http://arxiv.org/pdf/1806.05759](http://arxiv.org/pdf/1806.05759)

