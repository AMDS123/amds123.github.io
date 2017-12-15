---
layout: post
title: "Log-Linear RNNs: Towards Recurrent Neural Networks with Flexible Prior Knowledge"
date: 2016-12-16 10:56:22
categories: arXiv_CL
tags: arXiv_CL Knowledge Represenation_Learning RNN Language_Model
author: Marc Dymetman, Chunyang Xiao
mathjax: true
---

* content
{:toc}

##### Abstract
We introduce LL-RNNs (Log-Linear RNNs), an extension of Recurrent Neural Networks that replaces the softmax output layer by a log-linear output layer, of which the softmax is a special case. This conceptually simple move has two main advantages. First, it allows the learner to combat training data sparsity by allowing it to model words (or more generally, output symbols) as complex combinations of attributes without requiring that each combination is directly observed in the training data (as the softmax does). Second, it permits the inclusion of flexible prior knowledge in the form of a priori specified modular features, where the neural network component learns to dynamically control the weights of a log-linear distribution exploiting these features. We conduct experiments in the domain of language modelling of French, that exploit morphological prior knowledge and show an important decrease in perplexity relative to a baseline RNN. We provide other motivating iillustrations, and finally argue that the log-linear and the neural-network components contribute complementary strengths to the LL-RNN: the LL aspect allows the model to incorporate rich prior knowledge, while the NN aspect, according to the "representation learning" paradigm, allows the model to discover novel combination of characteristics.

##### Abstract (translated by Google)
我们引入LL-RNN（对数线性RNN），递归神经网络的扩展，用对数线性输出层代替softmax输出层，其中softmax是一种特殊情况。这个概念上简单的举动有两个主要的优点。首先，它允许学习者通过允许它将单词（或者更一般地说，输出符号）建模为属性的复杂组合，而不需要在训练数据中直接观察到每个组合（如softmax所做的那样）来对付训练数据稀疏性。其次，它允许以先验指定模块化特征的形式包含灵活的先验知识，其中神经网络组件学习动态地控制利用这些特征的对数线性分布的权重。我们在法语的语言建模领域进行实验，利用形态学的先验知识，相对于基线RNN，困惑度显着下降。我们提供了其他激励性的图解，最后认为对数线性和神经网络组件为LL-RNN提供了互补的优势：LL方面允许模型融合丰富的先验知识，而NN方面则根据“表征学习“范式，使模型发现新颖的组合特征。

##### URL
[https://arxiv.org/abs/1607.02467](https://arxiv.org/abs/1607.02467)

##### PDF
[https://arxiv.org/pdf/1607.02467](https://arxiv.org/pdf/1607.02467)

